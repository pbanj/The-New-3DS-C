<p align="center"><img width="500" height="300"  alt="oshw" src="https://github.com/user-attachments/assets/1b70982f-cb5f-427d-8318-703a105bf2a8" /></p>  

# The "New" 3DS-C  

### [License](https://github.com/pbanj/The-New-3DS-C#but-pb-where-is-the-license)  


## What is this?
It's a an open source USB-C board for the 3/2DS family of handheld systems. 

## Why is this?
That is a long story..... 
The short story is giltesa is a little whiny bitch who seems to think they made something substantial that isn’t just a trimmed down basic trigger board.   
The long story is at the bottomish.  
There is no Schematic as there is 0 use for one. Why you may ask. Because it's literally Just the USb-C standard to trigger 5v3a(pd). All I did was add a diode between it and the device on the voltage rail.


## Features

- Data pads so it can be used for capture carts, nand mods , or any other use a user can think of. This was a request of [@fox8091](https://github.com/fox8091), but I might take advantage of it with an upcoming thing I’m working on.  
- A Schottky diode to bring the voltage the system gets close to what it expects for voltage. Why? With the amount of 3ds systems I've seen that have dying parts(ram, emmc, etc...), I figured I'd try to help prevent any extra stress even if it's such a small diff in voltage. It wants 4.6v but will take 5v seemingly fine. This will get it closer to 4.7v.  
- It retains support for the dock on both "Old" and "New" lines. The dock bypasses the diode as it’ll be sending the correct voltage to begin with.  
- 2 5.1kΩ resistors on the CC lines so it will trigger USB-PD at 5v. AKA it works with C to C cables, not just A to C.  
- The Dock parts shouldn’t require any plastic support as they are soldered to the PCB.  
- The holes around the port legs are designed to make installation on the "Old" line easier as they use surface mount and not through hole. They should also make better contact with the existing front holes on the "New" line. I did this by over-sizing the width of the holes so solder can flow more freely.
- Unless you're giltesa, you can pretty much do whatever you want with these. That includes selling them for profit.  


## Change log  

- V1 the initial public release of design files.   
    - I forgot to order the diodes, so finished pics will have to wait. But all the alignments are done. 
	- I also need to make a spacer or have someone who isn't a douche design it  
	- I don't have a use for a centring tool, but anyone who isn’t giltesa is free to make one for it if they want  



# Hi mobile users, [click here for releases](https://github.com/pbanj/The-New-3DS-C/releases)  


## Pictures  

### Top  

<p align="center"><img width="881" height="439"  alt="2D Top" src="https://github.com/pbanj/The-New-3DS-C/blob/main/Pictures/Top.png" /></p>  


### Bottom

<p align="center"><img width="881" height="439"  alt="2D Bottom" src="https://github.com/pbanj/The-New-3DS-C/blob/main/Pictures/Bottom.png" /></p>  


### Prototype  

<p align="center"><img width="500" height="667"  alt="2D Bottom" src="https://github.com/pbanj/The-New-3DS-C/blob/main/Pictures/Prototype.webp" /></p>  


### 3D Render  

<p align="center"><img width="773" height="495"  alt="2D Bottom" src="https://github.com/pbanj/The-New-3DS-C/blob/main/Pictures/3Drender.png" /></p>  









## The long

A while back I had a bunch of the boards he designed made. It allowed me to keep install prices down for people. Well, I started getting asked to sell them to people as giltesa was out of stock and all the tariff bullshit going on. Well the license for the boards doesn’t allow for commercial use. Now per the license I would’ve been able to sell them on my shop anyways as I wasn’t selling them for profit. But I didn't want to just list them on there and upset him, so for a while it was just over dm on discord. That became annoying and so as a gesture of good faith I figured I would ask giltesa if it’d be ok if I listed them on my shop. I also explained the situation about why I wanted to and that I was charging $10, that was it. No extra for shipping,  was the board I paid for and assembled and the 3d printed bits(I would toss a few in as they were shit) I was even including some solder, wick and flux in the box to make sure they would have a good install. It isn't about the money; it's about making sure systems are modded properly. After he was a condescending asshole in the GitHub issue(*). I told him that if he was going to act like that, that I would just sell a $10 box on my site and it includes the board free as that is technically within the license as I’m not selling it(I didn’t do this). Well, that must have really chapped his ass as he not only closed the GitHub issue, he deleted it completely. Then he went on to delete the sources for all his boards and overwrote the GitHub history to remove all traces. So, I went ahead and made my own with ~~black jack and hookers~~ Schottky diode and data pads.




\* He deleted the issue like a coward. Probably because he realized how much of an asshole, he made himself look like. The thing is though...... discord remembers.  

<img width="665" height="422" alt="image" src="https://github.com/user-attachments/assets/1fc25723-bfa6-4eda-938c-d899aeeef14d" />  


He put this on his repos.  

<img width="1584" height="429" alt="image" src="https://github.com/user-attachments/assets/a10a6017-a2aa-4683-ae82-8c1c90c1eed5" />  
  
He tried to tell me to buy them from him and then sell them to people. Now at the time he was charging like 15-20$ I can’t remember, when I reiterated that I wasn’t trying to make any money off them or take any credit. He also tried to tell me to go and design my own and I would feel a sense of accomplishment or some dumb shit. I pointed out to him that not only do I make pcbs(especially usb-c ones) and whatever I came up with was just going to pretty much be what he made because of how basic it was and this way he would at least get the credit for the board and what not. He even agreed that the design was simple and that it probably would be the same because as I had said at the time "there's only so many ways to skin a cat". 

Half assed price breakdown  
<img width="846" height="155" alt="image" src="https://github.com/user-attachments/assets/81052a8a-d43d-49df-a8e1-6c326f687c62" />  
<img width="876" height="136" alt="image" src="https://github.com/user-attachments/assets/fe347349-2b5a-4a55-b500-4d13abf16d33" />  
As stated that didn’t include the cost of the parts, I was too lazy to check. 















## But pb where is the license?  

Right here.
- It comes as is with no warranty or guarantees at all.  
- I'm not responsible for any harm/damage that may come from using it.  
- Unless you're [giltesa](https://github.com/giltesa/), You're free to Make them, Sell them, and make changes to the source code. Under the conditions that: 
    - Follow and retain this license.  
    - Provide your source.  
    - Give credit, link back to the repo.  
    - Don't use them for evil.
    - If you promise not to sue us, you can shove one up your nose 😉

If you’re [giltesa](https://github.com/giltesa/), you’re not allowed to do anything with it. You can't make them, sell them, or make any changes to the source. Figure it out yourself, you'll feel a sense of accomplishment.


## Disclaimer  

- This is for educational purposes only.  
- Neither I nor the contributors are responsible for any misuse or damage caused by this project.  
- Use at your own risk and only on systems you own or have explicit permission to test/work on.  
- If it wasn't clear, fuck glitesa. Am I being petty? 🤏
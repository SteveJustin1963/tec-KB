## Welcom to the TEC-1's keypad family

The appealing patina of dirt, fading and cracking, now in Kleong. 

![](https://github.com/SteveJustin1963/tec-KB/blob/master/pics/kb-fun2.png) 

The first gen's used the SPST momentary PCB Mounted tactile switch; a small circular dome of coloured plastic, with that vintage wobbly click clack feel. Labels were hand drawn with black markers then nail varnished to seal it on. Now 40 year on, new keys can still be had from Altronics. Or like a new set of mags we now have coloured square keys with clear plastic covers. 

In issue 15; "The LCD will be supported further in issue 16 and if all goes well, we will have a cheap, full alpha-numeric keyboard with supporting software". Follwing this up with Colin Mitchell (2019) he said, "I can't remember what they were going to use, 15 years ago. You can buy a keyboard for $12.00". He is right, using a modern KB is cheaper than a DIY one, but not as fun! I dont like using usb on the tec1, and ps2 type kb is better but still needs decoding.  

### How about a small Blackberry Q10 keyboard 
- get a bbq10kbd_breakout pcb

![](https://github.com/SteveJustin1963/tec-KB/blob/master/pics/120093001_2804585019774865_2639766788032736065_n2.jpg)

![](https://github.com/SteveJustin1963/tec-KB/blob/master/pics/9_11_29a2.png)



### Review
- review current tec-1 kb design, code and operation
- review FB group chats, eg changed code reflect new key positions 

### Iterate
- https://github.com/SteveJustin1963/tec-TOUCH
- expand current kb system with a few additional parts on the 74c928 
- https://easyeda.com/editor#id=f7c6e0caf9ca4567a0e26ea7a1748cf3
- can another kb project be ported to the tec-1? eg RS2014 
- can the mini qwerty layout be used such as the Blackberry Q10 ?
- what if no more 74c923 chips? 74C923 alternatives ? 
  - scan io port across xy, "Just scan them with an 8 bit input and 8 bit output latch. You are already scanning the 7seg display. there is the output scan already done for you. You will notice there is a header at the bottom of the 1E labeled Scan 7-0. That is there for this exact reason." (Ken Stone 2019)
  - Soutern Cross KB system

- parallel ascii kb
- ps2 kb with asci decoder
- usb kb port
- measure and graph a force-map for different key types and comment on its tactile feel
- 74C923 as a serial port https://github.com/SteveJustin1963/tec-BIT-BANG
- Craig Hearts "74c923 based on a Leostick". https://github.com/tec1group/Arduino74c923
 







### Ref
- http://www.keyboard-layout-editor.com/
- https://forum.digikey.com/t/ps-2-keyboard-to-ascii-converter-vhdl/12616
- https://www.tindie.com/products/arturo182/bb-q10-keyboard-pmod/?fbclid=IwAR1t-W0DrUagAI4YKQwu2w6RRxsA_6cYkzKNg-HH21vqRzOpqBbhDFmOmjw
- https://blog.tindie.com/2018/08/blackberry-q10-kb-prototyping-breadboard/
- https://kitspace.org/boards/github.com/arturo182/bbq10kbd_breakout/
- https://github.com/arturo182/BBQ10KBD
- https://hackaday.com/2019/04/23/reaction-video-build-your-own-custom-fortnite-controller-for-a-raspberry-pi/
- https://www.instructables.com/id/Make-a-Mini-Wireless-Keyboard-From-Your-TV-Remote/
- https://www.aliexpress.com/wholesale?catId=0&initiative_id=SB_20200901162929&SearchText=Blackberry+Q10+Keyboard
- https://blog.adafruit.com/2019/01/14/interfacing-a-blackberry-q10-keyboard-into-your-microcontroller-project-blackberry-arduino-microcontroller/
- https://hackaday.com/2018/03/08/regrowing-a-blackberry-from-the-keyboard-out/
- https://kitspace.org/boards/github.com/arturo182/bbq10kbd_breakout/
- http://www.zx81keyboardadventure.com/2019/05/zx-key-external-keyboard-for-zx81s-and.html?fbclid=IwAR2rAczJfns30fEFsxtXb796U0RyCowCzWCHT9iPAPgo3lfXKYyy38EsmuM
- 









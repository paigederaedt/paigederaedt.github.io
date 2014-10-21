---
layout: post
title:  "Binary Numbers"
date:   2014-10-02 21:43:47
categories: daily post
---
Today we started learning about binary numbers with Zach. Starting with the basics. I had learned a little bit of binary numbers in university but didn't have a good foundation, so this was a great refresher. We learned about the most significant vs the least significant digits. We looked at a visualization that took your webcam picture (in black and white) and visualized it based on each bit: what this means is that the color of each pixel was determined by bit 'n' (1 --> 8). We were able to see how the least significant digit holds the least information about the image, as the image created by choosing the pixel color from the least significant digit provided the most ambiguous image. Zan explained it in this way and it really made it click for me, so thank you Zan! 

We finished up the day by designing a game/process to teach an 8/80 year old binary numbers. I worked with Zach and Rachel to think about Zach's idea of using legs to act as on/off switches. We ended up designing a game that required 8 people, 1 to act as each bit in the byte. There were two rules in the game: 1. You can only move forwards and backwards (only alternating --> you can't move forward twice) 2. you have to make a move when the person to the right steps back. The idea is that the least significant digit is always moving back and forth, and the rest of the places/people follow suit based on the rules. The game is meant to help show how to count up in binary and also to understand how significant each digit is. An alternative to this is to have the people start moving, and then randomly call stop. When stopped, they must say what binary number they are at (but in base 10). 

![Binary Numbers Dance](http://paigederaedt.github.io/_assets/binaryGame_1.jpeg)

We also supplemented this with a game that helps you create a binary number that is equivalent to a base 10 number. it consisted of a line of 'switches' labeled with their 2^n = # starting at 128 and ending at 1. the idea was to take the number given, and start at the left (128) and ask if your number was lower, if yes, then flip the switch on, if no, go on. Each time you flip a switch, you subtract the number on the switch from your number and keep a running total until you get to zero. Once at zero, you are done, and you can see your binary number based on which switches are flipped.

![Base 2 from Base 10](https://github.com/paigederaedt/paigederaedt.github.io/blob/master/_assets/2014-10-02\ 2014.58.26.jpg)

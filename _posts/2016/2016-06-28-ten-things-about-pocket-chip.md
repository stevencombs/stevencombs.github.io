---
layout: post
title: '10 things to know about your new Pocket C.H.I.P.'
date: 'June 28, 2016'
comments: 'yes'
categories:
  - chip
---
  
I've had some fun playing with the Pocket C.H.I.P. over the past week and while I do plan to write a full review, in the short term I have ten items to share immediately that might be of interest to new or future owners of the the geekiest gadget of I have ever owned.

![Pocket C.H.I.P.](http://www.stevencombs.com/images/posts/pocket_chip.jpg)

1. The Pocket C.H.I.P. has a built in browser called `surf`. **Try this:** in the *Terminal* type: `surf google.com` and the Google search page will load. You will most likely have to scroll up/down and left/right to see the page. This is a very rudimentary browser, but can be used in a pinch.
2. Download a *Terminal* text-based browser to provide quick access to information (sans graphics). A couple of my favorites include `w3m`, `lynx` and `elinks`. **Try this:** Install `elinks` using the following *Terminal* commands, `sudo apt-get update` followed by `sudo apt-get install elinks`. When the installation is complete, **Try this:** `elinks stevencombs.com` and see this site in all its text-based glory. Use the tab and arrow keys to navigate.
3. There is an excellent online bulletin board system (BBS) full of users and Next Computing staff to provide assistance and support. It is located at <https://bbs.nextthing.co/>. The community is active and answers come quickly. Be sure to search the BBS before you post a question. You will most likely find your answer immediately. Before heading to the BBS though, you may just want to review the documentation at: <http://docs.getchip.com/pocketchip.html>
4. No need to hit that home button to get back to other apps or the *Terminal*. A task switcher, using ctrl + tab, allows you to quickly cycle through running applications.
5. Not all software will display properly on the small LCD screen and you may not be able to access all UI elements. There is no pinch and zoom currently. Keeping my fingers crossed that this will be addressed by someone soon.
6. If your resistive touch screen (not capacitance like those found on tablets and phones) is giving you fits, you can calibrate it using these instructions: <http://www.chip-community.org/index.php/Troubleshooting#Calibrating_Touchscreen_on_PocketChip>
7. Pico 8 is a fabulous app that not only let's you play retro style games, but also teach basic programming skills using the Lua programming language. Check out these excellent resources to get started: <https://github.com/felipebueno/awesome-PICO-8>
8. Use the included Python programming language as a built in calculator. **Try This:** in the *Terminal* type: `python` and the python prompt will appear. Type `2+2` followed by the return (↩) key. Python will display the sum. Type ctrl + `z` to exit the Python interpreter. Check out this resource for additional calculator functions: <https://docs.python.org/3/tutorial/introduction.html>
9. The [Logitech K400 keyboard](http://amzn.to/29loNc3) is an awesome external keyboard not only for a Raspberry Pi, but also the Pocket C.H.I.P. Plug the dongle into the USB port to make Pico 8 programming and use much more computer like, but with a tiny little screen.
10. Don't want to purchase an external keyboard? Control your Pocket C.H.I.P. using your computer keyboard and trackpad/mouse. Follow my [Raspberry Pi `x11vnc` instructions](http://www.stevencombs.com/raspberrypi/2016/03/24/mirror-raspi-monitor-on-mac.html). They work just as well on the C.H.I.P.

![Controlling the Pocket C.H.I.P. via x11vnc](https://lh3.googleusercontent.com/mLeA1bFTLZkzlWfV-QaG3OB5-438GbNNd2GiNcYbj6DvGYhMATZbbUvL0A2jCKR5_Ab02fagGrgeRPh2naC2qPx-y9WSEo2q3G-iJd5_by_TZDs7NmLTvX6iqqorpxT1PLXh0tGk1ITUNRvPLGCiR0Bull1EL14Mfq3P-w0hBf4wRsU2ANgOK9kkeex11xm1dwSsNAInMZFSckKgZ2Bmyhf-f-v_z6CNzqRo5NiqWs57FGPQRHNeMdPCsbBWlfhG6p7tB0pu-1R-G2cbsvJEMwY2E39CipwHp5_q9xtODNm1GxxRDSoAzr3pauRTRoQ-VT7IkJIpfkGTMil8nyOR2y16GpfVIsDIP3apTQYR-FHxXaTLaYJYjtLQaXh4KxrObBvT46J0y3mKghW8L12mn8iidv1R5vNwDbwUOGog7k_dDuwbr90-JHu3b9HkT8YenAp2yZv_efN0D4Nh6vuuMMdEI5dij7MxndbkuTIrBDzv6W4TndySD5zOVxvFmX10uFW5V-D4TsG8YvCiUhYdGbFdgJ8xzmRDl84HpAT-pQhJcavPwp5VsX2cvfXVw0-q8hdMqLQEOJB3uOJf5U_dGfsNUUeutR-f=w960-h680-no)

**BONUS FUN:** Watch the original Star Wars story unfold on your Pocket C.H.I.P. **Try this:** in the Terminal type: `sudo apt-get update`, followed by `sudo apt-get install telnet` followed by `telnet towel.blinkenlights.nl`. Use ctrl + j to close the telnet session and ctrl + l to clear the *Terminal*.

![Star Wars on the C.H.I.P.](https://lh3.googleusercontent.com/cFUGmmQh0EzBBCwFvnsbrvE22fWpOfyMehtge99keeoKHBLP0PmV-X0DHPhiAm8E718KGb2Z4asueGfxzRWYvroox1xig1cJe5Wozb3JkiESyg5j5jAenuP0ViCgvt97X2kXUs75UXuqk0wX3RrprDdnIfLlqIjCy-eov_WHbLTm4F-z0qH4mPrD8EY9ZaMpQifP0MdZzx5ulPb4ihQ9yt1q32oIimhdzEPog-v_CVizlZycYhBp05IpWzyZrcoM4-EPIcV3qaAHnLDt_wxnde_pNuxG5857fm761Ldkp7mpy1lnySJh0QcoZWkuklYuQLbGz5K2OI1_qFGNoMoSetDUMWEuGGh4ymPiVh7ZRVCruJfFHL8jUvGAHOVck9NSQpReGybTfLSSi3P4EicbQowmGEQcZPgMREUnfRpNihysiP03CCq6i64MrKRlqBjhDW2h_nxPO0s_OTVEhuNW0EZbFckxsnzG0ny34M5KXr8wBQemmXqViDwjUZuaIzdt9wXvL0TqOv39g8xAkGIM1rEa5lWugm9jHZcBsHRyQtc9wmyLpsV048WPYqmmsEhNRu-fOhUeJBCoqEeEmXGatY1qJyAaJyaV=w960-h545-no)

Have something else I should add to the list that other Pocket C.H.I.P. owners should know? Drop in the comments below. I would love to read your suggestions.
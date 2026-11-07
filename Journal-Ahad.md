# 6th November 2026

I started the research process and was able to find many things such as the raspberry pi zero but found out that it was a full devboard and had every feature that we had planed to add to our project. Then we decided which mcu to use which was sooooooooo long. And finally we decided to use the rp2350a but found out it was not compatible with the camera we were using which was the 
<a class="text-color-blue-600" href="https://robu.in/product/waveshare-ov5640-camera-board-c-5-megapixel-2592x1944-auto-focusing-onboard-flash/">OV5640</a>
then we found that the esp32-s3 was compatible with the ov5640, after sometime my teammate told me to use the esp32-s3-wroom-1 :hs: after so much work.

# 7th November 2026  

## Session 1

I started working with the wroom module and had to also add a battery charging circuit to it which was to be decide which ic to use we found out that the TI's bq series are one of the best single cell batter charging ics unlike the trash tp4056 modules.i am working on the wrooms io pins connections right now so im busy and will do the bqxxxxx ic after the io pins are done

## Session 2

I started the payout part of the pcb which was fun at first but i found out that the cameras traces were taking all of the pcb so i had to make the size bigger. Then after routing everything up and length matching the camera traces, i found out that i had forgot to route 1 trace of the camera and it turns out that was the longest trace of the camera so i deleted everything and have started the layout again.

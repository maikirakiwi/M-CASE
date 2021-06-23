# AM v0.0.1
* 1_Processed_SunnyDay.mp3 - (Jay Chou - Sunny Day/周杰伦 - 晴天) | 0.5aq, 0.01as, -1dB Auto Limiter, 320K MP3 Encoder

## How to read everything after | 
- aq = Quality but actually a combination of Mix/Dry-Wet Value/Filter Bandwidth (1.0 being the highest and 0.01 being the lowest)
- as = Smoothing but introduces proper interpolation to reduce pre-ringing artifacts (yes it's a Linear Phase processor)
- Auto Limiter doesn't need much explanation, just your standard Brickwall is all. The encoded result doesn't even get that hot so this is just a safety measure.
- 320K MP3 is encoded by the latest FFmpeg lib. The quality of 320kbps should suffice for these types of critical listening when the result is meant to be enjoyed under a lossy format.

## Description
A very primitive implementation of the concept.
Pretty much a rough EQ match to fixate the overall mastering style without taking in account of the context around it.
This will be attempted with a better algorithm & methodology in v0.0.2 (hopefully coming soon)

The current version (v0.0.1) has the algorithm defined as a class of multiple modern songs of the identical artist/overall structure combined and it attempts to do a rough EQ match with the input.

Really mixed results.

## Extended Description
To save me and you some brain cells.
Here are materials for you to read if you want to know why the processing/EQ Match **should** be in LP/Linear Phase.

https://dsp.stackexchange.com/questions/31726/why-is-a-linear-phase-important

![image](https://user-images.githubusercontent.com/74925636/123018727-ec166800-d383-11eb-84a6-9b45a3bd5cd1.png)

----------

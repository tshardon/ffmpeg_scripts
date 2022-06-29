# ffmpeg_scripts
Time Saving Scripts to get the most of out ffmpeg

On my freetime I make short videos. I found myself with two issues. 1. I was compressing the videos with Panda on my Android to keep Zuckerberg from distorting my carefully crafted videos, and 2. I was constantly having to offload from my phone using an amazing syncing software called SyncTrazor which I highly recommend. https://github.com/canton7/SyncTrayzor

After a short search I stumbled upon ffmpeg https://ffmpeg.org/  https://git.ffmpeg.org/ffmpeg.git. I didnt find the software very easy to understand, nor did I find a lot quality scripts. So one day I sat at my desk and did a 7 day crunch of learning, crafting, testing, and figuring out how to properly use the software. Currently I use the four main scripts that I have posted. I put the videos in a folder with these scripts and move them either back to the SyncTrayzor to sync back to my phone, or to their final destination. I am currently working on way to make the scripts go through my library recuresively and detect the size and compression ratio to see if they should be compressed and to organize my library for me. 

One could say that is a lot of work for a library of videos. But using the command dir *.mp4 /s to count the files I come up with 11,000+ vidoes. 95% of those videos are recordings I have made myself and 75% of them are recordings I have made in the past year and a half. And I am pretty sure other people that exercise Google's Takout could use the effort in helping themselves as well. 

There are currently 5 files in my compression folder. 

		ffmpeg.exe
					Not all compiled versions of this program are the same and I haven't gotten around to compiling my own version of it. But you better believe it will be 
					purpose built and lightning fast. :D The version I am using comes from a software package by BtbN https://github.com/BtbN/FFmpeg-Builds/releases. And of 	
					today he just released new version of the compiled program. Kudos to him for staying on top it. <3 Be sure to downlod one of the master builds.
		
		CompressVideo_HD_Final.cmd
				
				This script is run on videos that I have edited and want to save in the highest quality possible while making the video as small as possible. It names the 
				final compressed file as "OriginalName (HD)(Final).mp4" This does not resize the video.

		CompressVideosHD_in_CameraFolder.cmd
				This scripts if run on videos that are in their original state. I want to compress these videos but not so much that it distorts when I finally do edit those
				videos.  This does not resize the video.
		
		CompressVideo_msgr_portrait (16^9).cmd
				This script is for videos that I will send through messenger, snap chat, telegram etc in 16:9 format and at a resolution of 960x540. The resulting file 
				will be named "originalname (Compressed).mp4"

		CompressVideo_msgr_portrait (20^1).cmd
				This script is for videos that I will send through messenger, snap chat, telegram etc in 20:1 format and at a resolution of 960x432. The resulting file 
				will be named "originalname (Compressed).mp4"


		


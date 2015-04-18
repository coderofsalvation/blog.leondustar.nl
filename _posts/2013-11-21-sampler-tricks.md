---
layout: post
title: sampler tricks
---
Ok since Im a sucker for [oldschool hardware samplers](/blog/archive/limitations-ftw\" "\"\"") and limitations, here are some tips which will work on the electribe esx sampler, but probably as well on other samplers.


Some of the tips here are borrowed from forums, youtube etc.  

  


**Stay away from the computer**

**  
**


<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">Try to minimize your computerusage, especially internet and plugins can trigger your monkeybrains. If you want to create music walk to your sampler, accept the limitations and trigger your creative mind.



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">If you want to create samples walk to your computer.



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">  



**Use multishots**

**  
**


<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">instead of going for the traditional 1 sample per sampleslot, go for x samples per sampleslot using [this linux tool](https://github.com/coderofsalvation/sample-multi-shotifier\" "\"\""). This will open a whole new world of sequencing-possibilities.



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">  



**Save samplespace by pitching up**

  



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">Pitch up sounds to save samplespace, and pitch them down on your sampler for normal playback. There are up/downsides to this approach. For every sample you create on your laptop, always create 2 versions when preparing samples (the original and the uppitched sample). 



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">  




<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">credit: [carillonaudio](http://carillonaudio.wordpress.com/2012/04/16/korg-esx-electribe-sampler-tips/\" "\"\"")


  


**Use proper tools**

**  
**


<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">Some samplers only work with particular wav-files. Use sox-utilities to easily convert them to the proper bitrate/mono etc settings.



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">Wavosaur is also a nice sampleprecise editor. See the [electribrary](http://electribrary.2webapp.com/search?tags=tool\" "\"\"") for nice sampler tools.



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">  



**Rely on children math**

**  
**


<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">Dont blame your sampler if your loops are not tight. Suppose you are (re)sampling a four-to-the-floor beat of 120bpm at 44100hz (so 4 beats). In case of problems cut the length of your loop to 88200 samples or 2000 ms (2sec). Why? There's simple math for this what you can remember:



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">  




<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">
<u>length of loop in samples
</u>



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">=  

<span font-style:="" inherit="" line-height:="" style="\"font-family:">( (60/bpm) * beats ) * samplerate



<span arial="" font-size:="" font-style:="" line-height:="" ms="" normal="" style="\"font-family:" tahoma="">  




<span arial="" font-size:="" font-style:="" line-height:="" ms="" normal="" style="\"font-family:" tahoma=""> 

<span arial="" font-size:="" line-height:="" ms="" style="\"font-family:" tahoma="">*     so*



<span arial="" font-size:="" ms="" style="\"font-family:" tahoma="">*  ( (60/120) * 4 ) * 44100 = 88200 samples*


  



<u>bpm to millseconds
</u>

= ( 60000/bpm ) * 4

  



<div arial="" font-family:="" font-size:="" ms="" normal="" style="\"font-style:" tahoma="">
<span arial="" font-family:="" line-height:="" ms="" style="\"font-size:" tahoma="">* so*


<div arial="" font-family:="" font-size:="" ms="" normal="" style="\"font-style:" tahoma="">
<span arial="" font-family:="" ms="" style="\"font-size:" tahoma="">*  ( 60000/120 ) * 4 = 2000 ms*




<span arial="" font-family:="" ms="" style="\"font-size:" tahoma="">*  
*



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">[precalculated table here]({{ site.baseurl }}/public//Downloads/bpm.txt\" "\"\"")


  


all credits go to: [carillonaudio](http://carillonaudio.wordpress.com/2013/01/24/sampler-cheat-sheet/\" "\"\"")


<span arial="" font-family:="" ms="" style="\"font-size:" tahoma="">*  
*


**Automate your media-management**

**  
**


<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">Samplers are to keep your head of filemanagement. Therefore, somehow automate this stuff. I have a folder 'write-to-smartmediacard' on my laptop. When I put new wavfiles in there, and I connect my smartmediacardreader, it automatically copies them. Put in card laptop, pull out, put in sampler, done. For linux use [udev-autorun](https://github.com/coderofsalvation/udev-autorun\" "\"\""), for windows use [autorun.inf](http://en.wikipedia.org/wiki/Autorun.inf\" "\"\""), for apple use applescript or something.



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">  




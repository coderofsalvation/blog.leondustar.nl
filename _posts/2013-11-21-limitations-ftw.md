---
layout: post
title: limitations ftw
---
Ok since Im a sucker for [oldschool hardware samplers]({{ site.baseurl }}/blog/archive/limitations-ftw\" "\"\"") and limitations, here are some tips which will work on the electribe esx sampler, but probably as well on other samplers.


Some of the tips here are borrowed from forums, youtube etc.  

  


**Stay away from the computer**

  


If you really wanna push yourself into creativity mode: try to stay away from the computer/internet as much as possible. All its possibilities will trigger your monkeybrain. This is a unobvious trap which I often get sucked into.

  


**Use multishots**

**  
**


<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">instead of going for the traditional 1 sample per sampleslot, go for x samples per sampleslot using [this linux tool](https://github.com/coderofsalvation/sample-multi-shotifier\" "\"\""). This will open a whole new world of sequencing-possibilities.



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">  




<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">**Resample, tight loops**



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">**  
**



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">If your sampler doesnt allow you to make tight loops, correct it by using children math:



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">  




<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">milliseconds per beat = 



<span arial="" font-size:="" ms="" style="\"font-family:" tahoma="">*  6000/bpm *



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">  




<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">length of loop in sample =



<span arial="" font-size:="" ms="" style="\"font-family:" tahoma="">*  ((60/bpm)*samplerate) * beats*



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">  




<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">so if you are resampling a 4-to-the-floor loop of 125 bpm with , you know that it should be chopped to a length of  ((60/125)*44100)*4= 84672 samples. Or in your waveeditor cut it to (60000/125)*4 = 1920 milliseconds.



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">This is not rocketscience, just print out a cheatsheet of precalculated numbers..problem solved. (credit: [carillonaudio](http://carillonaudio.wordpress.com/2013/01/24/sampler-cheat-sheet\" "\"\"") )


  


**Save samplespace by pitching up**

  



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">Pitch up sounds to save samplespace, and pitch them down on your sampler for normal playback. There are up/downsides to this approach. For every sample you create on your laptop, always create 2 versions when preparing samples (the original and the uppitched sample). (credits: [carrilonaudio](http://carillonaudio.wordpress.com/2012/04/16/korg-esx-electribe-sampler-tips/\" "\"\""))


  


**Use the right tools**

**  
**


<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">Some samplers only work with particular wav-files. Use sox-utilities to easily convert them to the proper bitrate/mono etc settings. Also use wavosaur, a great sampleeditor (see [electribrary tools](http://electribrary.2webapp.com/search?tags=tool\" "\"\"") )



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">  




<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">  



**Automate your media-management**

**  
**


<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">Samplers are to keep your head of filemanagement. Therefore, somehow automate this stuff. I have a folder 'write-to-smartmediacard' on my laptop. When I put new wavfiles in there, and I connect my smartmediacardreader, it automatically copies them. Put in card laptop, pull out, put in sampler, done. For linux use [udev-autorun](https://github.com/coderofsalvation/udev-autorun\" "\"\""), for windows use [autorun.inf](http://en.wikipedia.org/wiki/Autorun.inf\" "\"\""), for apple use applescript or something.



<span arial="" font-size:="" font-style:="" ms="" normal="" style="\"font-family:" tahoma="">  




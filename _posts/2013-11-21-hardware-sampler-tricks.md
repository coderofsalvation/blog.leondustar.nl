---
layout: post
title: hardware sampler tricks
---
Ok since Im a sucker for [oldschool hardware samplers]({{ site.baseurl}}/2013/11/21/limitations-ftw) and limitations, here are some tips which will work on the electribe esx sampler, but probably as well on other samplers.

Some of the tips here are borrowed from forums, youtube etc.  

Stay away from the computer
---------------------------

Try to minimize your computerusage, especially internet and plugins can trigger your monkeybrains. If you want to create music walk to your sampler, accept the limitations and trigger your creative mind.

If you want to create samples walk to your computer.


Use multishots
--------------
Instead of going for the traditional 1 sample per sampleslot, go for x samples per sampleslot.
Suppose you have a nice beat playing which use 4 samples (kick/snare/closed hihat/open hihat):

* Resample your loop to a new sample 
* sequence that sample using different sample offsets 
* free up the other 4 samples

If you get the hang of it, you could go crazy using [this linux tool](https://github.com/coderofsalvation/sample-multi-shotifier).
This will open a whole new world of sequencing-possibilities.

Save samplespace by pitching up
-------------------------------
Pitch up sounds to save samplespace, and pitch them down on your sampler for normal playback. There are up/downsides to this approach. For every sample you create on your laptop, always create 2 versions when preparing samples (the original and the uppitched sample). 

> credit: [carillonaudio](http://carillonaudio.wordpress.com/2012/04/16/korg-esx-electribe-sampler-tips)

Use proper tools
----------------

Instead of covering commercial tools, I will only free tools which I think are suitable for audio production. 

Some samplers only work with particular wav-files. Use [sox-utilities](http://sox.sourceforge.net) (windows/linux) to easily convert them to the proper bitrate/mono etc settings.
A tool like [Audacity](http://audacity.sourceforge.net) can also do this in a more visual way.

Wavosaur is also a nice sampleprecise editor, especially for embedding looppoints in .wav files. See the [electribrary](http://electribrary.2webapp.com/search?tags=tool) for nice sampler tools.

Cut tight sounds by downpitching 
--------------------------------
Pitch down the sound before you attempt to truncate your start- of endpoint of your sample. It will allow you to hear the transients much easier.
Just trigger the sample and adjust the position until you really hear the transient playing `exactly` when you trigger the button.

Automate your media-management
------------------------------
This might be easier or mac and linux.
Samplers were designed to keep you away from tradition computer filemanagement. 
Therefore, it can be handy to automate any kind of filemanagement actions.

Example: I have a folder 'write-to-smartmediacard' on my laptop. When I put new wavfiles in there, and I connect my smartmediacardreader, it automatically copies them. Put in card laptop, pull out, put in sampler, done. For linux use [udev-autorun](https://github.com/coderofsalvation/udev-autorun), for windows use [autorun.inf](http://en.wikipedia.org/wiki/Autorun.inf), for apple use applescript or something.

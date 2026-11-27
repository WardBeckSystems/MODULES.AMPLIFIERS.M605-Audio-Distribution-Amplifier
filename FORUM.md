# M605 — Audio Distribution Amplifier: on the WBSps forum

What owners, technicians and Ward-Beck people said about the M605 on the WBSps.ca forum (Simple Machines), 2008|41 to 2013|46: 4 topics, oldest first. Quoted as posted (contact details taken out). Made by tools/forum_quotes.py from the forum's database backups.

## WTB: Blue connectors for W625B power supply

_WBS PARTS NEEDED · Nov 8, 2008|41_

> those connectors he linked to are wrong. Those are for the edge connectors of the audio modules not the power supplies.
>
> I think Amphenol Made them... I'll check on that later today
>
> Check out
> http://cgi.ebay.com/WBS-Audio-Distribution-Amp-Chassis-w-10x-M605-Modules_W0QQitemZ360102676452QQihZ023QQcategoryZ23787QQssPageNameZWDVWQQrdZ1QQcmdZViewItem
>
> This tray has 10 connectors for you to scam, $85 is probably cheaper than the $30/connector you would pay for new ones. I'll split this thing with you if you're interested.

— **kuzub**, Nov 9, 2008|41

## Convert M605A or M8205 DA into a mic splitter??

_WBS TECHNICAL SUPPORT · Dec 11, 2009|42_

> I thought I'd add my own little rant here... I apologize, because I'm on Pint #3. =)
>
> All my information here is based on the available M605 manual.
>
> I'd like to point out page 16;
> "On some units u2 will be a TL071CP......"
> I knew they were great and cheap little opamps!
> ^_^!!!
>
> Onto the main topic though:
> Phantom power can-not be easily applied; There are diodes on the input protecting the input...
> Anything above or below +32.7 and -32.7 volts will be drained away from the amp....
> (CR 1, 2, 3 and 4.)
> Remove these diodes, and applying phantom power as normal should work.
> (Through 6.8K resistors.)
>
> I'm lost as-to why the DA calls for a source impedance of 600 ohms... It has a higher-impedance input! (above 30K!)
> Somewhat irrelevant, but never-the-less misleading.
>
> You can hook a microphone right up to it, and buffer/split the mic signal... sure.... it'll work!
> But your noise will be retardantly high!
> (I made that word up... but you get my point!)
>
> If you configure your M605's to have a gain of 1, or unity, it's Signal-to-Noise ratio should be close too 
> "85dB below +8dB."(Page 5)
> +8 minus 85 = -77 dB.
>
> This means that with nothing connected to the input, you will have -77 dB of noise... hiss, buzz, hum, klunk-klunk, meows or tsssst's... doesn't matter... its noise.
>
> Let's say for assumption purposes, that your microphone has an output of -40 dB.
> Sending it through the M605 configured for unity gain will give you your -40dB of microphone signal;
> and it will give you -77dB of noise.
>
> When you send the split signal through a Preamp, and amplify it by let's say 40dB; your microphone level will now be 0dB... but your noise will be at -37dB.
>
> Open up your favorite audio software; and generate a sine-wave, or pink or white noise, with a volume of -37 dB. Play it, and determine how loud it is for yourself.
>
> In my technical opinion, this is a very noisy way to split a microphone signal....
> It will work, but it will be noisy!
> Any preamp you connect this signal to will have a limited Signal-To-Noise ratio of 37 dB.
> Both the M470 and M460 claim to have a ratio of 125 dB!
> That is a HUGE difference!
>
> Your best solution, would be to send your microphone through one Preamp.
> And then send this preamp-output into the M605's.
> If you really want several Mic-Level outputs, you can send the outputs of the M605 through 30-60 dB PADS.
> This will do the best to keep your noise level down.
>
> Other than that, they look like great little units!
> Very basic, but I think they just look so cute! all small, and narrow and such... Makes me want a rack of them!
> I don't have anything to trade you, but let me know what you'd be looking for in the way of cash... and I might consider getting a rack. =)

— **Tristan.Miller**, Dec 18, 2009|42

> well Put Ritz
>
> The less noisy way of splitting a microphone is with a simple passive split... if there were a transformer in the picture it would all change.
>
> Like I said... from a modern use (other than line level splitter) M605s make Great power supply... that is all

— **kuzub**, Dec 18, 2009|42

## Test applications

_WBS EQUIPMENT APPLICATIONS · Feb 1, 2011|44_

> ^^^^^^^^
> That is roughly the reason why I bought 10 M605's off Warren about a year ago!
> Thank you Tony for the Rack...
>
> Although I never did get around to modifying the units to suite me needs...
>
> They are currently acting as a shelf, to hold my O-Silly-Scope and signal generator...
> Bellow them is a 120-V Variac/Current Meter/Speaker Dummy-Load/Soon-to-house-a-variable 2-rail-DC-Supply....
>
> I do need some more of the mating connectors for the modules... anyone have some lying around?
>
> Scopes are great tools... Not only do they show you what your ears might miss, but they can show you things that you could never possibly hear in the first place!
> I don't know about you, but I can't hear a 100Khz oscillation... I can hear the damage it does though...
>
> But don't expect a Scope to fix anything... And don't trust someone just because they have it! It is just a tool!
>
> I have a friend, who is an electrician-apprentice like my self...
> He spent a load of cash on top-of-the-line tools... Expensive screw-drivers, nut-drivers, drills, a nice meter... all in a fancy tool-bag...
> Sadly, I wouldn't even trust him to change a light-switch for me...
>
> Once he was changing a switch for his GirlFriend's Grandfather... He ended up re-wiring the whole light circuit, because it was 'wrong.' (...It worked fine the way it was, the switch just went bad...)
> When he was done, he called me and asked me why fuses were blowing every-time he turned the switch off...
> Yea, explain that one.
>
> My point is, tools are great... Just make sure you know how to use them!
> When fixing something, think slowly... One step at a time.
>
> Microphone signal goes in... Next it goes to these resistors which are the PAD... next it goes to this can thing... Oh that's the Transformer... All good up to this point... Next it goes into this chippy-thingie... okay, its coming out of there fine... where next?
>
> That process may sound boringly slow, and useless... but it is the fastest and easiest way to fix things!
>
> And that's my rant. =)

— **Tristan.Miller**, Feb 2, 2011|44

## 1982 WBS Frame restoration and customization: Project started October 2011

_MY WBS CONSOLE · Nov 12, 2013|46_

> 1982 WBS Frame restoration and customization
>
> Ward Beck Systems
>
> Model #: 810721
> Serial #: 8205034
>
> I came across a frame in July or August 2011. Someone was selling it on the WBSps facebook page. It took about 3 months to get to the right "moment" for pick up and everything. 
>
> What was included with this frame was:
>
> 1x WBS frame
> 3x 5x20 Patch Bays
> 12x M468K bussing modules
> 26x Penny & Giles faders
> 1x Phantom Power/Talkback Mic module
> 1x M452 Oscillator module
> 4x M451 Slate/Talkback module
> 2x M453A Cue Amp module
> 2x M498A Selector module
> 4x M625 PSU
> 2x M648 PSU
> 3x M624 PSU
> 8x M605 Distribution Amp
> 4x M612 Distribution Amp

— **pawajari**, Nov 12, 2013|46

_Serial Number.jpg_
_not kept: the file is not in the forum backups_

> 1982 WBS Frame restoration and customization
>
> Here are the Distribution Amplifiers (M605) That is the first thing i removed from the console. From what i understood.. These were routing and splitting the signal into other control room in the CBC tower. And since i wanted the space to rack my converters under the console... they were the first to go.

— **pawajari**, Nov 15, 2013|46

_DSC04154.jpg_
_not kept: the file is not in the forum backups_

_Converters hidding place.jpg_
_not kept: the file is not in the forum backups_

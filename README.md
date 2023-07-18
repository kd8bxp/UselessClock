# The completely useless clock bot

The Useless Clock bot can be found at https://botsin.space/@UselessClock2
This is running on an ESP32 board, using Arduino IDE. 
Originally I had wanted to turn this into a "clock" using an a eInk/ePaper screen.
I never finished the project. And the code sat in a folder for a long long time. I'm not sure when I first started this, I'm going to say it was probably late 2019, I'm sure it was before the lock downs, and pandemic. Those were bad times, and I lost my focus and pasion for working on projects.  

Recently however I've made a come back, started to work on various projects, and just in general have a much better out look on life.
After moving to Mastodon, I decided I wanted to learn how to make a bot. 
Not being able to think of anything useful, I remembered I had this code. And with a few changes, the bot was born.  

And requires the lyuba library by ringtailsoftware: https://github.com/ringtailsoftware/lyuba  
NOTE: You need to format your ESP32 device to use SPIFFs, I didn't see this step on the github site for this library. And I keep getting constanted guru errors and restarts. I figured out that how the library is saving it's token is with SPIFFs. So save some time, and format your device.  

And of course the ESP32 board core installed.  

## Useless Clocks displayed

UTC (Not useless or obscure)  
New Earth Time (N.E.T.):  
 * http://www.csgnetwork.com/csgnetstdtime.html
 * http://newearthtime.net/
 * https://en.wikipedia.org/wiki/New_Earth_Time
A couple of different variations of Decimal Time (which one is right? I don't know):  
 * https://en.wikipedia.org/wiki/Decimal_time
 * https://www.timecalculator.net/time-to-decimal
Doctor Who Dalek Rel Clock:  
French Fraction of day time (French Decimal Time):  
 * https://hackaday.com/2016/12/14/set-your-clocks-to-decimal-time/
Star Trek Style Stardate: (As there is some confusion about what and how a Stardate is calculated, this is one of the simplier varations)  
Hexadecimal Clock/Time:  
 * https://minkukel.com/en/clocks/hexadecimal-clock/
Swatch Internet Time IE: beats :
 * https://en.wikipedia.org/wiki/Swatch_Internet_Time
 * https://www.timeanddate.com/time/internettime.html
 * https://www.swatch.com/en_us/internet-time/
 * Internet Time invited by the Swatch Watch company in 1999 at the start of the age of the internet  


Others may be added later (or not).  
To the best of my ability these have been varified from "official" sources (where avaiable) as being the "correct" time.  
The usefullness of them is questionable at best.  

Have fun!.  

## Why is it called UselessClock2 (or Yet Another Useless Clock)

It turns out there is another Useless Clock on Mastodon, I wasn't the first to think of this. Thou mine is quite a bit different (see above). I was going to scrap the idea of turning this into a bot, but the creator of the other bot said to go for it.  
So That is why It is called UselessClock2.  
The 1st one can be found here: https://botsin.space/@UselessClock  
Made by: @PetraOleum@cloudisland.nz  
And his source can be found here: https://github.com/PetraOleum/Useless-Clock  
And you can see from the code, our useless clocks are quite a bit different.  


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Support Me

If you find this or any of my projects useful or enjoyable please support me.  
Anything I do get goes to buy more parts and make more/better projects.  
https://www.patreon.com/kd8bxp  
https://ko-fi.com/lfmiller  
https://www.paypal.me/KD8BXP  

## Other Projects

https://www.youtube.com/channel/UCP6Vh4hfyJF288MTaRAF36w  
https://kd8bxp.blogspot.com/  


## Credits

Copyright (c) 2023 LeRoy Miller

## License

This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses>

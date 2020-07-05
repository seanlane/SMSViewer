## SMSViewer

So at the moment, there isn't much to this project. I keep track of a lot of things, my text 
messages being one of those things. I am a fan of the Android OS and have used a few different Android apps, 
but recently I've been using 
[SMS Backup & Restore](https://play.google.com/store/apps/details?id=com.riteshsahu.SMSBackupRestore) by
Ritesh Sahu. I like this app since it stores the data in a local XML file, which I can then do a number of things with
instead of having my data stuck in some form of a [walled garden](https://en.wikipedia.org/wiki/Walled_garden_%28technology%29).

At the moment, this project only supports the limited reading of SMS messages, so no MMS (pictures, text, videos, etc.)
can be viewed, but maybe I can implement that sometime in the future.

To use, navigate to the demo page at [sean.lane.sh/SMSViewer](https://sean.lane.sh/SMSViewer), browser to find the XML backup 
file on your local machine, and once selected, wait for it to load. 

As you might see in the source code, it simply looks for messages that have the same Contact Name supplied with the 
text message and groups them together. I want to add a fallback to group by phone number when the Contact Name is
Unknown or otherwise generic, but again, something for the future.

If this thing breaks, or you want to contribute, just let me know and I'll see what I can do.

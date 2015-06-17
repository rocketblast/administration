###In-game administration
The in-game administration is an extension to the web based administration and has similar functionality. Similar; because the interface is obviously not the same, the in-game administration works off the chat system so there are a few restrictions to what is possible to achieve.

##Basic usage
You can issue different commands and some commands have arguments that you need to pass along with it for it to make any sense. Each command has to be prepended with either an **!** (explamation point) character or a **/** (forward slash) character; the exlamation point will make the command visible to everyone on the server while the forward slash hides it.

Arguments uses a matching mechanism so that you do not have to write out each argument unless it is really required. I.e. if you want to match the name **Martin_as_weird** you will only need to write "*m*" if there is only one person's nickname starting with the character **m**. If there are multiple matches you have to either select the one meeting your criteria or narrow down the search by specifying a few more characters. Usually three (3) characters will make sure you only get one match.


##Special arguments
Most arguments are considered special in this system. Normal arguments would be nickname and plain text. These are just strings. Special arguments on the other hand require to conform to a standard; this because we need to synchronize with the web based administration. I.e. when specifying a reason to ban a player we want the text that is shown to the user to be something along the lines of **"You were banned for an inappropriate nickname"**. However, this is stored using a unique identifier for this particular reason, i.e. this one has the ID of **1** in the database. Remembering that **"1"** was this particular reason might not be a problem for us after a while but the user would be very confused to why he was banned.

##Reasons
* Inappropriate behaviour (behaviour)
* Inappropriate language (language)
* Inappropriate name (name, nick)
* Team sabotage (teams)
* Team killing (tk)
* Swe/eng only in chat (sweeng)
* Baseraping (baserape)
* Basecamping
* Bug abuse (bug,abuse)
* Racism (racism)
* Cheating (cheat)
* High Ping (ping)
* Map glitching (glitching)


##Durations
* an hour (hour, 1hour)
* a day (day, 1day)
* a month (month, 1month)
* permanently


##Commands
* /rules or /help
* /reasons (might not work, too many reasons to be displayed with the limit of 256 characters per line)
* /durations
* /say `<text>`
* /yell `<text>`
* /psay `<nickname>` `<text>`
* /pyell `<nickname>` `<text>`
* /kick `<nickname>` `<reason>`
* /ban `<nickname>` `<reason>` `<duration>`
* /move `<nickname>`
* /slay `<nickname>`
* /report `<nickname>` `<reason>`
* /admin `<message>`
* /nuke `<team:number>` (1-US & 2-CN in Battlefield 4)

Sample command: 
`/ban edvin perm cheat` `/kick edvin ping` `/move edvin` `/say Hi Server!`

There are a few more commands in the system and there is also a lot more you can do with the already listed commands. But to keep it reasonably simple we will leave it at that for this guide.

In addition to these commands there are also a few other neat tricks that this system can do for us. We can store statistics and build our own metrics for statistics should we want to do that. Other types of server modifications are also possible. I.e. votemap, nextmap, weapon restrictions, adaptive server settings to name a few.

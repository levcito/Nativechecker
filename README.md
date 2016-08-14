#Nativechecker plugin by Wyu


"I bet anyone who does scripting for SA-MP have experienced the "File or function is not found" error. 

It means that one of the native functions in your gamemode or filterscript is declared but does not really exist. Native functions are provided by the SA-MP server itself or by external plugins. So when you see this error you know you're either missing a plugin or have an outdated version of it, or more rarely - the script is compiled for another version of the server.

And as you noticed it doesn't tell you which function is actually missing. Never. 

That's what nativechecker is made for.

__IMPORTANT:__ In order to make it work correcly you must put it in the end of the plugins line of your server.cfg so it will be the last one, e.g. *plugins sscanf streamer nativechecker.*"

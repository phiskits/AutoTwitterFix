# AutoTwitterFix

Replace normal Twitter links with the "vxtwitter" equivalent. or "fxtwitter", or whatever you want really.

This program will check the last entry copied to your clipboard for a specific content and replace it with a different one.

---NOTICE---

* all the configured values need to be strings. i.e. even numbers, like for **check_delay**, need to be written like "0", not 0
* if you need to put the program somewhere else, like on your desktop, do NOT move the actual .exe-file. instead, create a shortcut of it and move that one. the whole release-folder can be anywhere on your machine, though

---CONFIG---

* **string_to_replace**: the part of the string the program will be looking for and replace (i.e. twitter.com)
* **replacement_string**: the part of the string the program replace the former part with (i.e. vxtwitter.com - will make it so "twitter.com" gets replaced with "vxtwitter.com")
* **check_delay**: the amount of time (in milliseconds) that needs to pass until the program checks the last copied entry of your computer's clipboard and looks for the **string_to_replace** value. This is 2000 by default

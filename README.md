screenbits
==========

My .screenrc and the supporting scripts needed for the statusline

Usage
-----
Simply copy to $HOME/.screenrc and then add the following to your crontab:
<pre>
## GCAL
& */5  * * * * /home/doug/cron.d/get_calendar
## GCAL END
</pre>

Requirements
------------
GNU Bash
<br>GcalCLI (https://github.com/insanum/gcalcli.git)
<br>Cron
<br>GNU Screen

Example Output
--------------
<img src="https://raw.github.com/hunleyd/screenbits/master/screenrc.png" border=0>

Bugs
----
Find a bug? Please create an issue here on GitHub at:
https://github.com/hunleyd/screenbits/issues

Twitter
-------
Keep up to date on announcements and more by following Doug on Twitter, <a href="http://twitter.com/hunleyd">@hunleyd</a>

Authors
-------
**Douglas J Hunley**
+ G+: http://goo.gl/sajR3
+ Twitter: http://twitter.com/hunleyd
+ GitHub: http://github.com/hunleyd

Copyright and license
---------------------
Copyright 2012 Douglas J Hunley.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work
except in compliance with the License. You may obtain a copy of the License in the
LICENSE file, or at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the
License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
either express or implied. See the License for the specific language governing
permissions and limitations under the License.

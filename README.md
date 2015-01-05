EPI-Boxstarter
==============

Script to speed up setting up new windows machines with my list of desired software

from: "http://boxstarter.org/WebLauncher"
"Run the script

In either Internet Explorer (other browsers likely will not work) or from a console (CMD or PowerShell), invoke the Boxstarter launcher:

START http://boxstarter.org/package/nr/url?https://gist.github.com/mwrock/7382880/raw/f6525387b4b524b8eccef6ed4d5ec219c82c0ac7/gistfile1.txt        
Note this URL is a simple Boxstarter URL: http://boxstarter.org/package/nr/url. The /nr/ tells Boxstarter not to reboot the machine. Depending on what you are installing, you may not want to include that. Especially if you are including more heavy weight applications, frameworks or Windows Updates.

We add our raw Gist URL to the Boxstarter URL separated by a '?'.

This invokes a Boxstarter installer that will install everything according to your script."

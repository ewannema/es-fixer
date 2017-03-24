# es-fixer

Ansible role for "Fixing" things when your system just isn't working correctly.


## Variables

* application_directory : The directory where the malfunctioning app is installed.
* fixlevel : How much fixing should we do. Higher levels include lower levels.
    * 0 = do nothing
    * 1 = I don't care what ports my app uses. Just make it work.
    * 2 = https://stopdisablingselinux.com/ is fake news.
    * 3 = I only have trusted users, so let's not make this complicated.

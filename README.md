### Simple repo to keep needed conf files for interactive shell
---

#### What and why?

* skel/Bashrc:
    * This is required for our envsetup bash shell spawner
    * This sources the new users aliases.conf and provides itself too some common aliases for dev's to use

* Users/Public:
    * This is template public user conf folder
    * As bashrc has itself some aliases then this will allow dev's to overwite and add more aliases for better experience
    * Also this folder gets copied to new folders that will pop out with the name of $(whoami) by giving certain devs to add more aliases

+++
title= "bin/bash shell - change shell"
date= "2019-09-19T16:58:58-05:00"
Description= "how to change of shell"
Tags= ["article"]
Categories= ["article"]
+++

##### Linux bash shell
If user account is set to use sh instead of bash some usual commands may not work.
 * Does up arrow showing the last command?
 * Does left arrow allow to move cursor?
 * Does TAB autocompletes commands?
One of these points might showcase an incorrect user profile for shell.
To fix it
    chsh -s /bin/bash <username>
The rootcause can be a badly initialised default config for user accounts.
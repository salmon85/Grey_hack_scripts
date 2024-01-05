# Grey_hack_scripts

## Table of Contents

- [About](#about)

## About <a name = "about"></a>

My collection of public scripts I use in the game Grey Hack


Trashday.src : Deletes the .Trash folder from every user every second (for people who forget to empty trash).

Ssh.src : An updated ssh command that acts more like a real linux ssh command.

Rshell_interface.src : Updated rshell_interface that kills the pid upon connection.

Rando.src : Every 10 minutes renames a folder in /root/ that has the permissions 705, said folder would be used for programs you upload to the target machine. We have the programs in this folder because we have the rest of the filesystem locked down so guests can't run anything we host.

Dechiper.src : Modified decipher that accepts hashes directly on the command line. Also has a caching system that saves the hash and the password for future lookups.

Chmod.src : Modified version of the built in chmod but now accepts numerical permissions like 777

Autohack.src : An auto hacking script, extremely modified version of 5n4k3's autohack has a caching feature. The caching feature runs on a server accessible by ssh. There is a setup script built in. Has the ability to upload data to the cache server (as long as you have root).

Includes/json.src : This is a json parser script, meant to be used with import_code to allow other scripts to convert maps / lists / arrays into a json string and back again (useful for storing settings / structured data in a file so it can be re-imported).
# Grey_hack_scripts
My collection of public scripts I use in the game Grey Hack


Name                    :   Trashday.src
Requires Root           :   True
External Requirements   :   None
Description             :   Deletes the .Trash folder from every user every second (for people who forget to empty trash).

Name                    :   Ssh.src
Requires Root           :   False
External Requirements   :   None
Description             :   An updated ssh command that acts more like a real linux ssh command.

Name                    :   Rshell_interface.src
Requires Root           :   False
External Requirements   :   None
Description             :   Updated rshell_interface that kills the pid upon connection.

Name                    :   Rando.src
Requires Root           :   True (expects you to be using root as your main account on the system)
External Requirements   :   None
Description             :   Every 10 minutes renames a folder in /root/ that has the permissions 705
                            Said folder would be used for programs you upload to the target machine
                            We have the programs in this folder because we have the rest of the filesystem
                            locked down so guests can't run anything we host.

Name                    :   Dechiper.src
Requires Root           :   False
External Requirements   :   None
Description             :   Modified decipher that accepts hashes directly on the command line.
                            Also has a caching system that saves the hash and the password for future lookups.

Name                    :   Chmod.src
Requires Root           :   True
External Requirements   :   None
Description             :   Modified version of the built in chmod but now accepts numerical permissions like 777

Name                    :   Autohack.src
Requires Root           :   Depends on function, will ask when it needs it.
External Requirements   :   Requires the json.src from the includes folder to be placed into home_dir/src/includes/
                            Requires a small modification to the script before compiling (unless you're also called salmon)
Description             :   An auto hacking script, extremely modified version of 5n4k3's autohack has a caching feature.
                            The caching feature runs on a server accessible by ssh. There is a setup script built in.
                            Has the ability to upload data to the cache server (as long as you have root).

Name                    :   Includes/json.src
Requires Root           :   False
External Requirements   :   None
Description             :   This is a json parser script, meant to be used with import_code to allow other scripts to convert
                            maps / lists / arrays into a json string and back again (useful for storing settings / structured
                            data in a file so it can be re-imported).
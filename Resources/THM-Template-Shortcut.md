TryHackMe Template Shortcut Instructions

To create a new TryHackMe room write-up using the template:

1. Use the cp command to copy the template file:

cp TryHackMe/rooms/_template.md TryHackMe/rooms/[Room-Name].md

Example:
cp TryHackMe/rooms/_template.md TryHackMe/rooms/Simple-CTF.md

2. Edit the new file:

vim TryHackMe/rooms/Simple-CTF.md

3. Fill in the template as you go through the room.

Optional Alias (advanced):

You can add this to your .bashrc or .bash_profile to simplify the copy command:

alias newroom='cp TryHackMe/rooms/_template.md TryHackMe/rooms/'

Then use it like this:

newroom Room-Name.md


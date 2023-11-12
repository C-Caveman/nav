nav - A terminal-based file navigator/viewer.

Invoked with:
    /path/to/nav_script && cd "$(cat /tmp/nav_dir.txt)"

Installation:
    Add an alias for nav to your ~/.bash_aliases file:
        alias f='/path/to/this_script && cd "$(cat /tmp/nav_dir.txt)"'

Controls:
    <hjkl> or <arrow keys> to navigate through the file system.
    <q> to quit.
    </> to jump to a filename starting with the next pressed letter.

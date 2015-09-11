# changed-cli
Detect file changes in directories from current working directory (uses NodeJS)

To use, first install it - `npm install changed-cli -g`


Then go to the directory you need and run `changed`. (this will generate a file named .signatures in the directory)

Go make some changes to any files within (even deeper nested directories).

Run `changed` again to see the changes. Run multiple times to see the same results.
If you need to clear the changes, run `changed commit`.

Alternatively, you can run `changed usedir` to show directories where files have been changed.

# trash
Simple Ruby script for moving stuff into the trash (OS X)
## Usage
``` sh
$ touch foo
$ trash foo
$ ls ~/.Trash
...
foo
```
## Why not just use `mv foo ~/.Trash`?
Because it's too wordy and I'm too tempted to just use `rm`, which really bites when I didn't actually want to unlink that file from the filesystem.

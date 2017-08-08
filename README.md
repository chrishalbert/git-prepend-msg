# Git Prepend Msg

Installs a prepare commit message hook.

## Details

After you name your branch `ABC-123`, any time you commit, you will have that branch prepended to the commit message.

```bash
$ git commit -m 'Comitting code.'
[ABC-123 186b582] [ABC-123] Committing code.
```

## Install

### Manual
1. Clone the repository.
1. Run install.
1. Verify changes by going to an existing code base and running `git init`

### Scripted
On the command line, you can copy paste. This will download the code, unzip the file in your temp directory, run the install, and then remove remnants.
```bash
curl -LOk https://github.com/chalbert-iTech/git-prepend-msg/archive/master.zip && mv master.zip /tmp/git-prepend-msg-master.zip && unzip /tmp/git-prepend-msg-master.zip && cd /tmp/git-prepend-msg-master && ./install && rm -Rf /tmp/git-prepend-msg-master*
```

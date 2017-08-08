# Git Prepend Msg

Installs a prepapre commit message hook.

## Details

After you name your branch `ABC-123`, any time you commit, you will have that message prepended to the commit message.

```bash
git commit -m 'Comitting code.'
[ABC-123 186b582] [ABC-123] Committing code.
```

## Install

On the command line, you can copy paste. This will download the code, unzip the file in your temp directory, run the install, and then remove remnants.
```bash
curl -LOk https://github.com/chalbert-iTech/git-prepend-msg/archive/master.zip && mv master.zip /tmp/git-prepend-msg-master.zip && unzip /tmp/git-prepend-msg-master.zip && cd /tmp/git-prepend-msg-master && ./install && rm -Rf /tmp/git-prepend-msg-master*
```

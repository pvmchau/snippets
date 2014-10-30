### Key login

```bash
mkdir .ssh
cat id_rsa.pub >> .ssh/authorized_keys
chmod go-w ~
chmod 700 ~/.ssh
chmod 600 ~/.ssh/authorized_keys
```

### Others

1. [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt)
1. [shrc](https://github.com/Russell91/sshrc) — bring your .bashrc, .vimrc, etc. with you when you ssh

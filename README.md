# SSHPass

SSHpass offers you the ability to automatically offer a password via SSH when
you are prompted for it.

## Usage

```bash
export SSHVCODE=YOUR_GOOGLE_AUTHE_SECRET
export SSHPASS=YOUR_SSH_PASSWORD
sshpass -e ssh user@host
```

## Install

```bash
git clone git@github.com:innerlee/sshpass.git
cd sshpass
autoreconf -f -i  # sudo apt-get install autoconf
./configure --prefix=$HOME/app
make -j && make install
```

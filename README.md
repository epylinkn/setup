setup.git
=========
Clone and run this on a new EC2 instance running Ubuntu 12.04.2 LTS to
configure both the machine and your individual development environment as
follows:

```sh
cd $HOME
sudo apt-get install -y git-core

# setup git access
ssh-keygen -t rsa -C "epylinkn@awsnode"
cat ~/.ssh/id_rsa.pub
##
## NOW GO ADD THE KEY TO GITHUB
##

# finish setup
git clone git@github.com:epylinkn/setup.git
./setup/setup.sh
```





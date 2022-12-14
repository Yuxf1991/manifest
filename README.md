## Wind Manifest Download
### 1 Install repo
```shell
mkdir -p ~/bin
# maybe you need install curl first:
# sudo apt install curl

# download repo
curl https://mirrors.bfsu.edu.cn/git/git-repo -o ~/bin/repo
chmod +x ~/bin/repo
# add repo to your PATH
export PATH=$PATH:~/bin
export REPO_URL='https://mirrors.bfsu.edu.cn/git/git-repo'
```

### 2 Download wind project
```shell
mkdir Wind && cd Wind
repo init -u git@github.com:Yuxf1991/windmanifest.git -b main
repo sync
```

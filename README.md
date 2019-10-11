# new_ubuntu
a new ubuntu guide
#### 安装软件

    sudo apt-get install -y openssh-server vim git meld cmake gtags net-tools exuberant-ctags

#### 安装搜狗输入法

    

#### 更新gcc
    sudo add-apt-repository ppa:ubuntu-toolchain-r/test
    sudo apt-get update 
    sudo apt-get install g++-8
    sudo update-alternatives --install /usr/bin/g++ g++ /usr/bin/g++-8 100
    sudo apt-get install gcc-8
    sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-8 100
    sudo update-alternatives --query gcc	//查询系统中安装有哪些版本

#### git

~/.git_commit_template：

    [][] 

    Issue: N/A
    
    Root Cause: N/A
    
    Solution: N/A
    
    Project: stm32
    
    Note: N/A
    
    Ticket: 
    
    Signed-off-by:
    
~/.gitconfig：
   
    [user]
    	name = lxy
    	email = lxy0371@sina.com
    [alias]
    	st = status
    	ci = commit
    	co = checkout
    	br = branch
    	unstage = reset HEAD --
    	last = log -1 HEAD
    [color]
    	ui = auto
    [commit]
    	template = /home/robot/.git_commit_template
    [core]
    	pager = less -x1,5
    [gitreview]
    	username = luxy
    [credential]
    	helper = store


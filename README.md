# Linux_Multi_Develop

本文档记录多人开发同一个Linux环境下操作方式

基础配置：
新增用户：sudo useradd moritz -d /home/dji/disk1/moritz -m -s /bin/bash 
修改密码：passwd moritz
sudo权限：sudo usermod -aG sudo moritz


下载miniconda(Py3.9)：wget https://repo.anaconda.com/miniconda/Miniconda3-py39_23.3.1-0-Linux-x86_64.sh
安装miniconda
安装oh my ssh: sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
安装cmake (指令待定，先自己查)
安装htop (指令待定，先自己查)

安装torch: 参考https://pytorch.org/get-started/locally/     
pip3 install torch torchvision torchaudio

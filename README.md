#说明
*这是vim的配置文件*

##适用
vimrc_gvim vimrc.bundle_gvim 是一个整体，适用于mac,linux 终端下的vim和gVim,MacVim,Windows下的Gvim
vimrc_cygwin vimrc.bundles_cgywin 适用于windows下cygwin模式下的vim

## 使用方法
###Mac用户和Linux用户
>**建议安装7.4及以上版本，有些插件需要7.4才可以正常使用。  
*首先进入到当前用户目录: cd ~  
*建立vim插件放置的目录:  mkdir -p .vim/bundle/  
*从github下在vundle插件，放倒 ~/.vim/bundle/下面:  git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/vundle/  
*下载本配置文件到当前目录目录: git clone https://github.com/lastxiaojing/zjz_vim.git ~/zjz_vim  
*拷贝出里边的配置文件: cp ~/zjz_vim/vimrc_gvim ~/.vimrc  
*拷贝出里边的配置文件: cp ~/zjz_vim/vimrc.bundles_gvim ~/.vimrc.bundles  
*打开vim，会报很多错误，因为vim插件还没有安装，忽略那些错误，按会车进入到vim界面  
*执行:BundleInstall  
*安装完退出，从新进入。**<  

#说明
*这是vim的配置文件*

##适用
vimrc_gvim vimrc.bundle_gvim 是一个整体，适用于mac,linux 终端下的vim和gVim,MacVim,Windows下的Gvim
vimrc_cygwin vimrc.bundles_cgywin 适用于windows下cygwin模式下的vim

## 使用方法
###Mac用户和Linux用户
>**1. 建议安装7.4及以上版本，有些插件需要7.4才可以正常使用。  
2. 首先进入到当前用户目录: cd ~  
3. 建立vim插件放置的目录:  mkdir -p .vim/bundle/  
4. 从github下在vundle插件，放倒 ~/.vim/bundle/下面:  git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/vundle/  
5. 下载本配置文件到当前目录目录: git clone https://github.com/lastxiaojing/zjz_vim.git ~/zjz_vim  
6. 拷贝出里边的配置文件: cp ~/zjz_vim/vimrc_gvim ~/.vimrc  
7. 拷贝出里边的配置文件: cp ~/zjz_vim/vimrc.bundles_gvim ~/.vimrc.bundles  
8. 打开vim，会报很多错误，因为vim插件还没有安装，忽略那些错误，按会车进入到vim界面  
9. 执行:BundleInstall  
10. 安装完退出，从新进入。**  

###Cygwin用户
**方式和Mac相同，只是配置文件用里边的cyg格式的就可以了。**

###Gvim用户
*现在用Gvim的很少了。*
>**1. 下载7.4及以上版本的Gvim。  
2. 在Gvim的安装目录可以找到一个\_Vimrc的配置文件，那个目录就是$VIM目录。  
3. 在$VIM目录下建立.vim/bundle目录。不会的可以借助其他工具，比如dos。  
4. 从github上拷贝vundle插件放倒.vim/bundle下，和上边文件名保持一致。  
5. 拷贝该配置文件，复制里边的vimrc_gvim到$VIM目录，重命名.vimrc；复制里边的vimrc_.bundles_gvim到$VIM，重命名.vimrc.bundles。  
6. 打开gvim会有很多错误，忽略，执行:BundleInstall。
7. 安装完成退出重新进入。  **

# [Anaconda3 配置](https://github.com/JinghuiChan/WYU-Lab-1308/blob/master/Files/Anaconda%E9%85%8D%E7%BD%AE.md)
## [目录](https://github.com/JinghuiChan/WYU-Lab-1308/blob/master/Files/Anaconda%E9%85%8D%E7%BD%AE.md)
* ### [Anaconda3 安装教程](https://github.com/JinghuiChan/WYU-Lab-1308/blob/master/Files/Anaconda%E9%85%8D%E7%BD%AE.md#anaconda3-%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B-1)
   * #### [Anaconda3 下载地址](https://github.com/JinghuiChan/WYU-Lab-1308/blob/master/Files/Anaconda%E9%85%8D%E7%BD%AE.md#anaconda3-%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80-1)
   * #### [Anaconda3 安装过程](https://github.com/JinghuiChan/WYU-Lab-1308/blob/master/Files/Anaconda%E9%85%8D%E7%BD%AE.md#anaconda3-%E5%AE%89%E8%A3%85%E8%BF%87%E7%A8%8B-1)
   * #### [创建 Anaconda3 虚拟环境](https://docs.conda.io/projects/conda/en/latest/commands/create.html)
* ### [Anaconda3 虚拟环境列表及对应包列表](https://docs.conda.io/projects/conda/en/latest/commands/create.html)
   * #### [虚拟环境列表](https://docs.conda.io/projects/conda/en/latest/commands/create.html)
   * #### [虚拟环境对应包列表](https://docs.conda.io/projects/conda/en/latest/commands/create.html)
   * #### [虚拟环境安装新包](https://docs.conda.io/projects/conda/en/latest/commands/create.html)
* #### [Anaconda3 常用命令列表](https://docs.conda.io/projects/conda/en/latest/commands/create.html)
<hr>

* ### Anaconda3 安装教程
   * #### Anaconda3 下载地址  
        官方下载地址： [请点这里](https://www.anaconda.com/distribution/#linux)
   * #### Anaconda3 安装过程
      * ##### 进入下载位置，执行下列命令
      ```
      bash Anaconda3-x.x.x-Linux-x86_64.sh  
     
      注：其中x.x.x为版本号，以自己下载的文件为准
      ```
      * ##### In order to continue the installation process, please review the license agreement.(为了继续安装过程，请审核许可证。协议。)
      * ##### Please, press ENTER to continue 直接按enter查看协议，然后一直enter下去
      * ##### 然后看到Do you accept the license terms? [yes|no]（你接受许可证条款吗?）  
      
        直接输入yes 然后按enter，进入下一步  
      * ##### 接下来会提示安装地址：Anaconda3 will now be installed into this location:  
        /home/your-pc-name/anaconda3  
        
         -Press ENTER to confirm the location
         -Press CTRL-C to abort the installation
         -Or specify a different location below
         
      * ##### 按enter继续下一步，注意这里按ctrl + c 直接会终止安装。
      * ##### 接下来先等待安装即可。
      * ##### 看到Thank you for installing Anaconda3! 表示安装成功。
      * ###### 注：anaconda会自动将环境变量添加到PATH里面，如果后面你发现终端输入conda提示没有该命令，那么你需要source ~/.bashrc 这样就是更新环境变量，就可以正常使用了。  
        
        如果发现这样还是没用，那么需要手动添加环境变量
        编辑~/.basrc 文件，在最后面加上  
        ```export PATH=/home/your-pc-name/anaconda3/bin:$PATH```  
        保存退出后：source ~/.bashrc  
        再次输入conda list测试看看，应该就是没有问题啦！
        
      * ##### 然后安装会提示Do you wish to proceed with the installation of Microsoft VSCode? (是否需要安装vscode)  
        这里根据自己的选择yes or no
     
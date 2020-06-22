# manjaro
踩了一遍又一遍，惨

装的nvm没有搞环境配置，怎么nvm命令都不行，虽然用nvm下载到了node跟npm，但是也还是不行，最后是手动搞的环境配置才好，NODE_HOME才好，配置环境在/etc/profile。虽然nvm这个东西还是没好。。。

#manjaro基本配置
装完manjaro，首先先换源，换源在配置文件里不要选清华源，选163的，而且最后关键字是那个Only不是All。然后导入key，然后下载shadowsocks-qt5搞翻墙，再在网络设置里手动代理，记得是127.0.0.1,然后在ss里弄http的，如果保存不了windows硬盘的文件，那肯定是没关快速启动，去win10关了快速启动就好了，有时候装完软件，启动菜单里没显示，那就命令行启动，firefox是firefox，chrome是google-chrome-stable

#flutter
安装完flutterSDK以后,要装jdk1.8,然后装AndroidSDK,下载完AndroidSDK以后,要进去tools/bin里面,输入 .\sdkmanager "platform-tools" "platforms;android-29"
环境变量是 ANDROID_HOME,要把tools和platform-tools放到path里

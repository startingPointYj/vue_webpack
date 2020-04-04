～安装node
官网选择版本 系统 一路下一步；node -v  npm -v查看版本


～淘宝镜像
 npm install -g cnpm --registry=https://registry.npm.taobao.org
sudo npm install -g cnpm --registry=https://registry.npm.taobao.org回车 输入密码（密码不可见）回车
注释：
报错>>>>EACCES: permission denied, access '/usr/local/lib/node_modules/cnpm/node_modules/address'
解决>>>>sudo 命令以系统管理者的身份执行指令，也就是说，经由 sudo 所执行的指令就好像是 root 亲自执行


~安装vue脚手架
npm install vue -g
npm install vue-cli -g
vue -V(大写)查看版本

 ～安装webpack
 sudo npm install webpack-cli -g
注释：webpack -v查看版本
报错>>>>bash: webpack: command not found
解决>>>>npm link webpack

~初始化项目
a.vue init webpack 按需选择
b.·npm install·
c.·npm start·或·npm run dev·

到此启动完成；浏览器查看！

~安装git工具
sudo npm install git


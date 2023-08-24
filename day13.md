1.个人中心
个人中心当中：分页器





2.全局守卫
未登陆访问：交易相关，支付相关，个人中心重定向到登陆页面

3.路由独享守卫
只有从购物车界面才能跳转到交易网页（创建订单）
只有从交易页面（创建订单）页面才能跳转到支付页面
只有从支付页面才能跳转到支付成功页面

3.1 组件内守卫


4.图片懒加载
安装
npm install vue-lazyload@1.3.3 -S

5.vee-validate 基本使用

npm install vee-validate@2 --save
引入
import VeeValidate from 'vee-validate'
中文
import zh_CN from 'vee-validate/dist/locale/zh_CN'
Vue.use(VeeValidate)

也可以去找正则插件：any-rule

6.路由懒加载



7.项目打包
npm run build 
项目打包后，代码都是经过加密的，如果运行时报错，输出的错误信息无法准确得知时那里代码报错
有了map 就可以像未加密的代码一样，准确的输出时哪一行代码有错
所以该文件如果项目不需要时可以去掉的
vue.config.js配置
productionSourceMap：false

8.nginx配置
1.xshell进入根目录/etc
2.进入etc目录，这个目录下有一个nginx目录
3.安装nginx ｜ yum install nginx
4.安装完nginx服务器以后，你会发现在nginx目录下，多了一个nginx.conf文件，在这个文件中配置
  

## 【React 新闻APP】

## 1. 启动 （项目生成）
`webpack-dev-server --port 1234 --inline --hot`
>（--port 1234 可以去除，使用默认端口）
>[参考](http://www.cnblogs.com/fantasy-zxf/p/6795809.html)
### 备注：此处，webpack使用版本1；webpack-dev-server全局安装（npm install -g webpack-dev-server）
## 2. 样式 (Ant Design 框架引入)
`npm install antd --save`
>[参考](https://ant.design/docs/react/introduce-cn)
## 3. 接口 (Postman的使用)
## 4. 响应式 (React-Responsive)
`npm install react-responsive --save`
## 5. 移动端页面
>root.js导入import MediaQuery from 'react-responsive';

>[参考](https://github.com/contra/react-responsive)

>新增相关组件及样式
## 6. fetch
`npm install fetch --save`
## 7. pc_header.js添加用户登录注册模块
## 8. rc-form源码解读
>[参考](http://doc.okbase.net/schifred/archive/257064.html)
## 修改
```javascript
<Input type="text" {...getFieldDecorator('r_userName')} placeholder="请输入您的账户" />
{getFieldDecorator('userName', {rules: [{ required: true, message: 'Please input your username!' }],})(<Input prefix={<Icon type="user" style={{ fontSize: 13 }} />} placeholder="请输入您的账号" />)}
以此类推
<Input type="password" {...getFieldDecorator('r_password')} placeholder="请输入您的密码" />
<Input type="password" {...getFieldDecorator('r_confirmPassword')} placeholder="请再次输入您的密码" />
```
## HTML to JSX Compiler
[链接](http://magic.reactjs.net/htmltojsx.htm)

## 备注：git解决冲突与merge
[链接](http://blog.csdn.net/lincyang/article/details/45269491)
## 源码参考
[链接](https://github.com/ParryQiu/IMOOC-React)
## 备注：课程资源及报错解决
>[参考](http://www.imooc.com/article/17442?block_id=tuijian_wz)




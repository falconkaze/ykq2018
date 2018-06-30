# Oauth2.0
【1】[理解OAuth 2.0](http://www.ruanyifeng.com/blog/2014/05/oauth_2_0.html)

oauth是一个关于授权的开放网络标准。oauth在第三方应用和服务提供商之间设置了一个授权层。第三方应用不能直接登录服务提供商，只能登录授权层，这样将服务提供商的用户和第三方应用分开。第三方应用登录授权层需要使用令牌，与用户密码不同。用户可以在登录的时候指定授权层令牌的权限范围和有效期。  

Oauth2.0定义了四种授权方式：
* 授权码模式
* 简化模式
* 密码模式
* 客户端模式
Wechat-Payment-V3-java
======================

基于微信支付接口文档V3.3.6，java版本


1. 在开通微信支付的公众号下访问 htpp://服务器地址/mainServlet        
 
2. 修改MainServlet.java和TopayServlet.java 里面的商户参数，授权返回地址和notify_url部分即可。

3. 代码是别人的劳动成果，经自己稍微修改后测试成功，demo并没有十分的简化，大家可以做一个参考吧。如果出现签名失败，仔细检查下自己填写的appid和partnerkey是否正确。

4. 请注意：微信支付成功后的通知的url为notifyServlet,sb是返回的xml

5.最后祝大家都通过微信支付的测试。

注意：测试时pay.jsp文件应该在微信公众平台测试授权目录下

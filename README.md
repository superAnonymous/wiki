#网聊标准版本说明文档
![](http://www.elitecrm.com/images/logo-elitecrm.png)    1/22/2017 2:45:10 PM 
###application
***
	  <!-- 标准版本 网聊模块以及接口配置文件 -->
	  <bean id="standardConfig"
	   	class="net.sf.liveSupport.config.StandardConfig">
	   		<property name="theme"><value>vienna</value></property>
	   		<property name="interfaceUrl"><value>http://localhost:8080/weixinAgent/wxInterfacePools</value></property>
	   		<property name="rightModule"><value>vienna.jsp</value></property>
	   		<property name="rateModule"><value>vienna.jsp</value></property>
	   		<property name="mobileRateModule"><value>twoRadio.jsp</value></property>
	   		<property name="sendToGateWayPage"><value>true</value></property>
	   		<property name="queue"><value>2</value></property>
	   		<property name="autoSwitchRobotMode"><value>true</value></property>
	 		<!-- 微信配置 -->
	   		<property name="appid"><value>wx371f4dfac6bca06e</value></property>
	   		<property name="secret"><value>fd8321b30b1f1d48fbe17664effd18e9</value></property>
	   		<property name="grant_type"><value>authorization_code</value></property>
	   		<property name="urlAddress"><value>http://localhost:8080/weixinAgent/wxAgentServlet</value></property>
	   </bean>
                    
### 绘制表格 Tables

| 项目        | 价格   |  数量  |
| --------   | -----:  | :----:  |
| 计算机      | $1600   |   5     |
| 手机        |   $12   |   12   |
| 管线        |    $1    |  234  |
                    
				
				
###config.js
***
###i18n文件
***
###nav.json
***

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
                    
### 属性说明
| 属性名称	     | 属性类型       |  备注  			      |
| :----:   	| -----:  	| :----  			     |
| theme       	|    string   |  网聊的主题配置，会根据客户的要求通过css修改不同的界面显示效果。比如客户是钱包，就需要在“EliteWebChat\jsp\standard\theme” 文件夹下面新建“qbao”目录 ，然后修改属性value值位钱包文件夹同名的字符串(建议直接复制即可)，界面效果显示的就是钱包网聊的效果|
| interfaceUrl       |   Stirng   |  设备名称 pc ,mobile 默认为--pc--  |
| rightModule        |   Stirng   |  设备名称 pc ,mobile 默认为--pc--  |
| rateModule         |   Stirng   |  设备名称 pc ,mobile 默认为--pc--  |
| mobileRateModule   |   Stirng   |  设备名称 pc ,mobile 默认为--pc--  |
| sendToGateWayPage  |   Stirng   |  设备名称 pc ,mobile 默认为--pc--  |
| queue              |   int      |  设备名称 pc ,mobile 默认为--pc--  |
| autoSwitchRobotMode|   Stirng   |  设备名称 pc ,mobile 默认为--pc--  |
### 关于微信属性配置说明
| 属性名称     | 属性类型    |  备注				|
| :----:      | -----:     | :----  |
| appid       |   Stirng   |  设备名称 pc ,mobile 默认为--pc--	|
| secret      |   Stirng   |  设备名称 pc ,mobile 默认为--pc--  |
| grant_type  |   Stirng   |  设备名称 pc ,mobile 默认为--pc--  |
| urlAddress  |   Stirng   |  设备名称 pc ,mobile 默认为--pc--  |
###config.js
***
###i18n文件
***
###nav.json
***

用例名称：仓库文件搜索

参与者：用户、系统管理员

用例描述：该用例描述一个系统用户搜索仓库文件的行为

触发器：当仓库文件被搜索时，用例触发

前置条件：搜索仓库文件的一方需要完成登陆操作

后置条件：如果仓库中有该用户要搜索的文件，则显示文件信息

基本事件流：1.参与者登陆系统；
			 2.系统验证用户信息及实名信息合法后做出响应；
			 3.用户在系统中搜索查询仓库文件；
			 4.系统生成并保存用户的查询记录；
			 5.系统将搜索查询的文件信息结果发给用户；
			 6.用户查看文件并可进行下载文件操作

拓展事件流：如果实名信息有误或非法，系统会拒绝参与者访问和搜索仓库文件

结论：当用户收到系统发送的其要搜索的仓库文件页面时，用例结束

数据需求：仓库文件信息、参与者的用户账号名、参与者的用户信息

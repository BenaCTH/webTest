# Cypress 
*  Cypress端到端的测试，跨浏览器测试 测试运行时拍摄快照。适合定位bug所放生的时间和位置。
*  https://docs.cypress.io/guides/overview/why-cypress 
*  AUI Test: 测试每个组件demo 是否加载成功，切换语言，
*  Cypress 特性：历史记录，实时重新加载，运行结果一致性，可调试性，自动等待，网络流量控制，截图和视频。


## 配置cypress 方法：								
* 安装：npm install cypress --save-dev								
* 修改配置文件 cypress.json cypress.env.json								
* package.json 添加 "cypress:open":"cypress open" 								
* npm run cypress:open								
* 命令行运行 package.json 添加 "cypress:run":"cypress run"								
* npm run cypress:run 								
* 运行时修改config   npm run cypress:run -- --config baseUrl=http://localhost:7001								
								
## "自定义测试报告 --Mochawesome  
* npm install --save-dev mocha
* npm install --save-dev mochawesome 
* npm run cypress:run -- --reporter mochawesome"

## cypress open 参数列表
参数|含义
--|--
--browser,-b|指定运行测试的浏览器
--config,-b|指定运行时的配置项
--env,-e|定义环境变量
--global|全局模式
			
## cypress run 参数列表
参数|含义
--|--
--browser,-b|定义一个运行用例的不同浏览器
--config,-b|指定运行时的配置项
--env,-e|定义环境变量
--spec,-s|定义运行的测试用例文件（一个或多个）	
--record|是否录制测试视频
--reporter,-r|定义Mocha 报告生成器
			
								
## 参考API：								
* 断言库 https://mochajs.org/ | http://www.chaijs.com/

							

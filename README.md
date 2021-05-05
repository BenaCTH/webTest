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
								
								
## 参考API：								
* 断言库 https://mochajs.org/ | http://www.chaijs.com/								

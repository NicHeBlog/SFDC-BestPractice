# SFDC-BestPractice
### 工作中的开发实例
1. 一键备案
   i. 简述： 点击JS按钮打开VF页面，勾选报价产品，一键把勾选的报价产品添加到备案产品库对象下
2. Trigger跨区办事处主任必填
   i. 简述： 当销售机会的项目所在地和关联的客户的省份不一致时，页面甩错提示跨区的办事处主任必填
   ii.功能： 因为一个是Before insert records into a salesforce object (Trigger BeforeInsert),
            Do logical judgments, if not satisfied, throw out an error on front page. 
3. 上传附件改名功能
   i. 简述：销售订单对象下，上传附件之后，附件名称自动变更为订单号+原有的附件名
   
2. after the file is uploaded, change the name of file (Trigger AfterInsert),
   + RenameFileTrigger
3. when click button, js fires apex class to update the price of product
   + RefreshProductPrice
   + RefreshProductPrice_JS

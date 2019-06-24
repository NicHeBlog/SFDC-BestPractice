# SFDC-BestPractice
### 工作中的开发实例
1. **一键备案**
   + i. 简述： 点击JS按钮打开VF页面，勾选报价产品，一键把勾选的报价产品添加到备案产品库对象下
2. **Trigger跨区办事处主任必填**
   + i. 简述： 当销售机会的项目所在地和关联的客户的省份不一致时，页面甩错提示跨区的办事处主任必填
   + ii.功能： Before insert records into a salesforce object (Trigger BeforeInsert),
            Do logical judgments, if not satisfied, throw out an error on front page. 
3. **上传附件改名功能**
   + i. 简述：销售订单对象下，上传附件之后，附件名称自动变更为订单号+原有的附件名
4. **一键更新产品价格**
   + i. 简述：点击JS按钮，可以一键更新报价产品身上的三级价格，并返回提示
5. **一些测试类练习**
6. **首页组件-搜索客户**
   + i. 简述：输入客户名称，系统返回客户对象下是否已经存在此客户
   + ii.功能：Home Page Component中添加VFpage,Home Page Layout中设定首页的显示与否
7. **VF页面静态资源的调用**
   + i. 简述：系统中setup中static resource可以上传静态的js/css资源库，然后VF页面中可以直接调用资源库中的代码以及图片 
8. **销售机会审批通过创建项目公示**
   + i. 简述：销售机会中勾选‘报备’并且审批通过的时候，自动写入到另一个对象项目公示之中，一边销售可以看到其他人在跟进的项目
   + ii.功能：after Update Trigger
9. **RelatedList 批量添加费用明细**
   + i. 简述：通过创建Lookup字段from对象A to对象B，通过VF Page可以批量添加对象A关联到对象B,并且可以添加一行或者删除一行
   + ii.功能：VF(AddCampaignBudget)+Apex(AddCampaignBudgetController)
10. **变换排序方式** 
   + i. 简述：通过定义一个private变量，可以方便的定义数据的排序方式
11. **PDF打印页面**
   + i. 简述：页面点击VFPage render As PDF 
   + ii.功能：VF(QuotationPDF2)+Apex(QuotationPDFColl)
12. **业务员的跨区下单问题**
   + i. 简述：记录插入系统之前，根据所选的省份，后台匹配对应的行政区划，赋值给相应字段。
   + ii.功能：before insert & before update trigger
13. **Js Button监测两个产品名称的值不一致**
   + i. 简述：点击Js Button触发对于related List中的两个值的比较
   +ii. 功能：JS: DiffDetect

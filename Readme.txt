一、新建表 ChineseFood : 字段 id(autoincreace)   BillID(varchar(50))    CardID(varchar(50))    CDate(datetime)

二、新建表 ConsumeType : 字段 id(autoincreace)   ConsumeType(int)  CardID(varchar(50)) Copy(int)<一单多份需要>

三、Hy_List_Money 建立insert触发器

四、BillPayment 建立insert触发器

五、新建 CLEAR_CHINESEFOOD 存储过程
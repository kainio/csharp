---
content: "{% highlight aspnet %}\n\n    <asp:LinqDataSource ID=\"LinqDataSource1\"
  runat=\"server\" \n        ContextTypeName=\"AdventureWorksLTDataClassesDataContext\"\n
  \       EnableDelete=\"True\" EnableInsert=\"True\" EnableUpdate=\"True\" \n        TableName=\"SalesOrderDetails\">\n
  \   </asp:LinqDataSource>\n    \n    <asp:GridView ID=\"GridView1\" runat=\"server\"
  \n        AutoGenerateColumns=\"False\" \n        DataKeyNames=\"SalesOrderID,SalesOrderDetailID\"\n
  \       DataSourceID=\"LinqDataSource1\">\n        <Columns>\n            <asp:CommandField
  ShowDeleteButton=\"True\" \n                ShowEditButton=\"True\" />\n            <asp:BoundField
  DataField=\"SalesOrderID\" \n                HeaderText=\"SalesOrderID\" ReadOnly=\"True\"\n
  \               SortExpression=\"SalesOrderID\" />\n            <asp:BoundField
  DataField=\"SalesOrderDetailID\" \n                HeaderText=\"SalesOrderDetailID\"
  InsertVisible=\"False\"\n                ReadOnly=\"True\" SortExpression=\"SalesOrderDetailID\"
  />\n            <asp:BoundField DataField=\"OrderQty\" \n                HeaderText=\"OrderQty\"
  SortExpression=\"OrderQty\" />\n            <asp:BoundField DataField=\"ProductID\"
  \n                HeaderText=\"ProductID\" SortExpression=\"ProductID\" />\n            <asp:BoundField
  DataField=\"UnitPrice\" \n                HeaderText=\"UnitPrice\" SortExpression=\"UnitPrice\"
  />\n            <asp:BoundField DataField=\"ModifiedDate\" \n                HeaderText=\"ModifiedDate\"
  SortExpression=\"ModifiedDate\" />\n        </Columns>\n    </asp:GridView>\n\n{%
  endhighlight %}"
date: 2019-03-10 19:49:07 +0000

---

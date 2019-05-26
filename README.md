# AWIN_homework 網站連結 http://aaarielo.azurewebsites.net/Home/Contact
1.
	註冊畫面
 
	登入畫面
 
	設定密碼規則必須包含數字英文及特殊字元 (8-20字元)
 
	Admin身分Ariel 可以看到自己及所有user、guest資料，且允許刪除資料
 
	User身分PIG 只可以看到自己及guest資料
 
	Guest身分hh 只可以看到自己資料
 
先從資料庫撈出自己的資料，再根據登入者身分判斷使否顯示其他使用者資料
如果是admin身分，則另外撈除了admin身分的使用者資料
如果是user身分，則另外撈guest身分的使用者資料
如果是guest身分，不另外撈其他使用者資料
  
2.
	參考reCAPTCHA API 完成防止暴力測試
https://code.msdn.microsoft.com/Google-reCAPTCHA-in-ASPNET-f854c476
https://www.google.com/recaptcha/admin/site/346379033/setup
 
網站金鑰 6LcZU6UUAAAAAK6kyVRyJvQ9r0dj8TO9i0lJ0H_j
密鑰 6LcZU6UUAAAAACkzz-SEknasnPz60qSI1HR7WEiA _

3.
	每頁顯示20筆高雄房地產資料，可根據地區做關鍵字搜尋
	點選房地產資料項目，新增單位售價至分析圖表
 

參考Google Charts – Line Chart
https://developers.google.com/chart/interactive/docs/gallery/linechart
4.
	使用Visual Studio 2013開發
	專案選擇MVC，會產生一個網站雛形，僅提供註冊及登入
	C#
 
	列表畫面使用NuGet元件輔助
 
 
	使用的資料庫有AspNetRoles、AspNetUserRoles、AspNetUsers、Estate
以下畫面為Estate房地產資料
 

可以由資料庫產生Entity，也可以先設定Entity再產生資料庫
並且透過Entity FrameWork存取DB資料
 

我認識的MVC
Model前端與後端的溝通介質
View畫面顯示端
Controller控制端，處理使用者輸入，資料傳遞為主

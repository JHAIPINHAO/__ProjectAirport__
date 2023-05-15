# __Airport__ 專案說明

在資料取得部分，我們以requests的方式，獲得桃園機場的即時航班資訊後，以IO寫入存成CSV，匯入main作為資料來源。
在main程式我們使用python中的tkinter作為我們的圖形化介面，使用Radiobutton列出桃園航空所有的航線。
點選特定航空公司後，會在下方的treeview中，列出航廈、班次、登機門/機坪、表訂日期、表訂時間、預計日期、預計時間、往來地點、航班狀態等資訊，
另外再main程式，製作Menu_Search功能，可輸入出發地的關鍵字，會在中間的treeview中，列出航廈、班次、登機門/機坪、表訂日期、表訂時間、預計日期、預計時間、往來地點、航班狀態
等資訊。
# dongcg.github.io
休閒娛樂軟體科技

管理员操作说明：<br>
1、bundle.js文件永恆不變，只需修改根目錄下的data.json文件，注意以下幾點：<br>
（1）、數組最後一個元素后不能有逗號，比如[{...},{...},{...},]應改為[{...},{...},{...}]<br>
（2）、對象最後一個字段后不能有逗號，比如{"name":"張三","age":2,}應改為{"name":"張三","age":2}<br>
（3）、不要使用單引號，全部使用英文雙引號<br>
（4）、該文件不能添加任何注釋，否則解析失敗<br>
2、data.json文件字段說明：<br>
（1）、NEWS字段：新聞數據<br>
（2）、APPS字段：APP數據<br>
（3）、ABOUT字段：關於文字描述<br>
（4）、ITEMSPERPAGE字段：列表每頁顯示的最大條目個數<br>
3、上傳的產品不再僅限為jar文件，但要求name屬性有完整拓展名且除了拓展名中的點符外不能再有點符，比如seawar1.0.jar應改為seawar1.jar<br>

昨天不小心按到返回前一個時間點，然後就同步不了=_=
所以我把舊的刪掉了，重新建立一個新專案

分支說明

master~放整合後的檔案
james(我)~放各自檔案
昌昌哥~放各自檔案
裝帥帥~放各自檔案


步驟
1.建立分支git checkout -b (你的名稱)
	ex git checkout -b james

可以用 git status 查看有哪些分支
當成功建立就會有下列分支
	master
	*james(*代表當前分支)
	
2.去桌面版的github裡面，左上角有個 + ，點進去後按clone，
	選NavigationProject裡的檔案 "new-directions-demo"
3.下面有個clone，之後選擇本地資料夾路徑
	ex D:\GitHub\new-directions-demo
4.在new-directions-demo資料夾下放入你的檔案
	專案資料夾名字希望能方便辨識
	ex James_DirectionSampley 
5.回到git shell 路徑在new-directions-demo下面
	ex D:\GitHub\new-directions-demo [master ≡]>
      	
	**重要**
	
	預設分支為master
	要切換到你的分支
	在上傳檔案
        
	ex D:\GitHub\new-directions-demo [master ≡]>git checkout james
	   D:\GitHub\new-directions-demo [james ≡]>
6.上傳動作有三指令
	git add . 
	git commit -m "xxxx" 
	git push -u origin james



* 如何同步
	1 . 下載 github桌面板
	2 . 安裝完後會有單獨的github資料夾，這就只有存你帳戶中github的資料
	3 . 同步本地的檔案
    	第一步，去github裡面新建一個空專案A
    	第二步去桌面版的github裡面，左上角有個 + ，點進去後按clone，就可以
    	選擇檔案A。
    	第三步，複製本地檔案B到github檔案A裡面即可
    	第四步 指令

	若要建立新的txt可以用下面的指令，但我覺得在資料夾裡面建立好後，再上傳比較快

echo ..... > readme.txt//不用動

第一步、git add . //若有改動先，先打這指令
第二步、git commit -m "xxxx" //"xxxx"裡面打第幾次更改
第三步、git push -u origin master

DirectionSample為主


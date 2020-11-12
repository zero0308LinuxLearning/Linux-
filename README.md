# Linux-
Linux基礎教學(移動目錄、創建檔案、編譯執行)
## 創建第一份程式碼
### Step1 : 打開Terminal
### Step2 : 切換目錄與創建檔案
![](https://i.imgur.com/tlGw4wm.png)
> **cd** : 用來切換目錄的指令。
>**touch** : 最常被用來建立空的檔案，只要執行 touch 並指定檔案名稱，當指定的檔案不存在時，touch 就會自動建立一個空檔案，並將檔案的時間設定為目前的時間。

完成後可以看見 **hello_shiyanlou.c**已被創建。
![](https://i.imgur.com/nmUVXZg.png)
### Step3 : 使用gedit編輯器將 **hello_shiyanlou.c**打開並用C語言來寫並存檔。
![](https://i.imgur.com/qOtkZhQ.png)

### Step4 : 編譯(用gcc)
![](https://i.imgur.com/mpr4E3C.png)
>gcc + <XXXX.c>:可以直接編譯
>gcc -o + <指定檔名> + <XXXX.c>:可以編譯並指定輸出的執行檔名
![](https://i.imgur.com/Vi4ycdw.png)

### Step5 : 執行程序
![](https://i.imgur.com/L6Xw3r8.png)

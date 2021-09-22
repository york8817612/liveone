# liveone

基於WebRTC的HTML5點對點視訊


## 使用工具

前端使用Vue3.0，Vite。

後端使用用Node.js，Express，Socket.io。


## 使用方法


1. vue前端源碼:

    安裝套件：

    ```bash

    npm install
    ```

    測試環境啟動：

    ```bash
    npm run dev
    ```

    編譯：

    ```bash
    npm run build
    ```


2. server資料夾是後端源碼:

    安裝套件：

    ```bash

    npm install
    ```

    啟動服務：

    ```bash

    node server.js
    ```


## 代碼邏輯

![](https://qiniu.nihaoshijie.com.cn/%E6%9C%AA%E5%91%BD%E5%90%8D%E7%BB%98%E5%9B%BE.png)

1. 對於Vue端主要實現的是視訊鏡頭的預覽功能和一些來電或者響應相關的CSS3動畫。
2. 對於Node.js端主要實現的是即時的訊息通信(socket.io的room相關API)，包括了識別對方的識別碼和使用者的一些基本頭像暱稱資料的通信。
3. 整體的WebRTC協議的邏輯都是參考掘金上所講解的代碼方式來體現。


## 參考
[掘金文章](https://juejin.cn/user/3368559356680215)

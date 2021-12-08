# flowchart-generator

## 介紹
因應北科程式設計課需要列程式的執行順序
簡單寫了一個小程式來幫忙執行

## 預先準備
確定python直譯器是用`python3`來執行，不是的話需要修改最後一行

## 教學

<img width="1280" alt="截圖 2021-10-26 下午4 47 47" src="https://user-images.githubusercontent.com/59184894/138843833-aae357d4-2fd9-44ff-9988-3b157e1c8cd3.png">

```shell
python3 LinePrinter.py <你的程式碼>
```
可產生一般流程圖 ＋ mermaid用格式

```shell
python3 LinePrinter.py <你的程式碼> -e
```

可產生一般流程圖

```shell
python3 LinePrinter.py <你的程式碼> -s
```
可產生mermaid用格式

## 簡單解釋
重新製作一份檔案t.py，在每一行的執行前或後將執行行數儲存，最後用stderr輸出，並將原輸出導入至同資料夾的temp檔案

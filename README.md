# LinePrinter

## 介紹
因應北科程式設計課需要列程式的執行順序
簡單寫了一個小程式來幫忙執行

## 預先準備
確定python直譯器是用`python3`來執行，不是的話需要修改最後一行

## 教學

```shell
python3 linePrinter.py w.py
```
可產生一般流程圖 ＋ mermaid用格式

```shell
python3 linePrinter.py w.py -e
```
可產生一般流程圖

```shell
python3 linePrinter.py w.py -s
```
可產生mermaid用格式

## 簡單解釋
重新製作一份檔案t.py，在每一行的執行前或後將執行行數儲存，最後用stderr輸出，並將原輸出導入至同資料夾的temp檔案

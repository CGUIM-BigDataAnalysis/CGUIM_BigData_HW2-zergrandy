---
output:
  github_document: default
  html_document: default
---
##數值變數運算
```{r}
#這是R Code Chunk
num1 = 3561
num2 = 5815
num1 + num2
num1 - num2
num1 * num2
round(num1 / num2,digits = 2)
```
##檢查總覽資料
```{r}
#這是R Code Chunk
str(iris)
```
##輸出系統現在日期
```{r}
#這是R Code Chunk
Sys.Date()
```
##字串比大小
```{r}
#這是R Code Chunk
"A" > "a"
"b" > "A"
```
##運作環境資訊擷取
```{r}
#這是R Code Chunk
sessionInfo()
```

# Recognizer
Face image to vector

### 请求

调用地址：http://server/recognize
请求方式：POST
请求类型：image/jpeg

将图片的二进制数据放入request的body内，然后提交POST请求。

### 返回

返回类型：text

返回一个包含512维float向量的字符串

```
[[0.1,0.2,...,0.2]]
```

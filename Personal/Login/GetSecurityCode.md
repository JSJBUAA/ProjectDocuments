# 获取验证码

## 请求参数
字段|数据类型|示例值|说明
:----:|:----:|:----:|:----:
key|string|69b8df3fa54e58b2342c814763d46b48|加密公钥
phoneNumber|string|13811111111|手机号

## 响应参数
字段|数据类型|示例值|说明
:----:|:----:|:----:|:----:
status|int|0|状态码,0表成功,-1表失败

客户端理论上不需要关注是否发送成功，正常倒计时即可。

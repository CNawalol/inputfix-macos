# Macos-Inputfix
## 修复的问题
 - 如果在选词框按退格的时候Minecraft也会触发退格的事件
 - 在选词框中按回车，minecraft直接把消息发送出去了

## 原理
 - 记录按下按键的次数，并在Minecraft输入框内容更新的时候重置为0

~~不完美修复，能用就行~~

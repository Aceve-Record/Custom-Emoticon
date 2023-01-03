# Custom Emoticon

## 介绍

**Custom Emoticon**是一款为Minecraft Java版开发的**自定义表情包**（材质包），它可以让你在聊天框中使用表情包，目前版本内置了10个表情。

## 适用版本
材质包版本：6
对应Minecraft Java 1.16.2（1.16.2-rc1）~ 1.16.5
*其余版本未测试

## 使用方法

每个表情的编码从`\ue000`开始，直到`\ue009`结束（Alpha 1.0），使用原始JSON文本编写，可通过`/tellraw`调用。

>使用示例
/tellraw @a {"text":"\<user> \ue000"}
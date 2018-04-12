# 3000

Excel版再要你命3000

## 基本信息

出版社：群言出版社

版次：2017年8月第2版第5次印刷

词汇数：3041

## 校验信息

MD5: E40C73C1F0B233F74FE3BF610D5862F2

此MD5值总是由Master分支上最后一次Commit的xlsx文件生成。

你可以从Microsoft Store上下载[MD5 Compare](https://www.microsoft.com/store/productId/9NDDMZLM8L0S)来执行检验。

如果你下载到的文件计算所得MD5值与此处不相同，可能是因为版本差异或者你使用了被第三方修改过的版本。

## 说明

### 全局

为了方便使用RAND函数，自动计算已关闭，如需计算函数表达式，请按下F9手动执行，或在`Formulas`->`Calculation Options`里选择`Automatic`恢复自动计算。

字体为Calibri(Body)，然而Calibri字体内并不包含中文，所以中文的显示字体可能因操作系统而异。

csv文件由xlsx文件直接另存为`CSV UTF-8 (Comma delimited) (*.csv)`得到，仅用于比较版本之间的差异，不建议下载使用。

如果你已经开始使用（即'?'列被改变），但是希望与最近的版本保持同步，你可以先行将'?'列的值备份到其他文件（比如一个文本文档），之后下载最新版单词表，将备份的'?'列进行覆盖，即可恢复当前的学习进度。

### 列

A列'?'为熟记状态，有0,1,2三个可选的值，在条件格式下，0使得整行为浅红底色，1为黄，2为绿。但若某单元格为空，则不受此限制，必然为无底色。

B列'L2'（隐藏）为List序号，从01开始，到31结束，是正常的计数方式。

C列'L'为List编号，从00开始，到30结束，符合编程的思维，也方便计数。

D列'U2'（隐藏）为Unit编号，从01开始，到10结束，是正常的计数方式。

E列'U'为Unit编号，从0开始，到9结束，符合编程的思维，也可以少显示一位数字。

F列'I'（隐层）为Item编号，从01开始，到10结束，是正常的计数方式。

G列'I2'为Item编号，从0开始，到9结束，符合编程的思维，也可以少显示一位数字。

H列'R'（隐藏）为预生成的一组随机数，配合`Home`->`Editing`的`Custom Sort...`可以乱序背诵。如果需要重新生成随机数，可以将已经存在的值替换为`=RAND()`公式。由于关闭了自动计算，随机数一般不会更新，可以按F9手动更新一组。

I列'Word'为单词。

J列'UK Phonetics'为英式音标，来自[音标网](http://www.yinbiao5.com/18.html)，是推荐使用的读音参照。

K列'US Phonetics'为美式音标，来自[音标网](http://www.yinbiao5.com/18.html)，但是并不推荐使用，因为很多音标与词典出入较大。

L列'Paraphrase'为中文释义，多个释义之间用分号分隔，释义中原有的分号不做处理。为了减小列宽，所有括号都替换为了英文括号；省略号都是三个点号。

## 反馈

### 联系我

我的邮箱可以在Profile里找到，各种错误、排版瑕疵、建议等都可以通过这个邮箱联系我。

### Pull Request

如果你想要提交一份Pull Request，请务必使用`CSV UTF-8 (Comma delimited) (*.csv)`生成一份csv文件，并将xlsx文件与之一同提交。

对于'R'列，请勿更改预生成的随机值，因为修改随机值而带来的更新是没有意义的，而且会令修改记录变得十分混乱。

## 许可证

本项目暂时没有选择合适的许可证，可能会在后续的版本中进行更新。

就目前而言，如果是个人使用，可以自由下载而不需额外的操作；但如果要转载，请在合适的位置标明本项目的作者信息和原始链接<https://github.com/liurui39660/3000>，当然你也可以向我发邮件，与我分享这个令人愉悦的消息。
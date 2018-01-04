---
layout: article
title:  "Unicode 及 Unicode Consortium的摘要"
date:   2017-12-28 13:24:50 +0800
categories: rwd
image:
  teaser: def.png
  feature: def.png
---

# 简介
- 统一码/国际通用码（`Unicode`），让数字及万维网的文本得以全球化，是万维网网页标准的基础。

- 制定Unicode的是统一码/国际通用码联盟（Unicode Consortium），是负责创建数字字符和数字通用标准的非营利组织。

- Unicode码的最大好处就是对於每一个字元提供了一个跨平台丶语言与程式的统一数码。

## 1、字符与编码 Characters and Encoding
- 由於编码之间的相容性及应用程序如浏览器的支援不一，会发生编码错误以致显示内容不正确，又称乱码(Mojibake)，或甚致是安全漏洞。
- 有冲突编码定义，不同的字符集不能出现在同一文件中，需额外转换。

## 2、Unicode标准统一编码的基础设施
- 解决编码交换等问题，提供了基础设施。
1. 为文本中使用的每个字符提供一个数字，而Unicode标准是这些数字的字典。

2. 是协助设备处理世界上所有的语言，因而联盟维护一大数据库，为不同的语言和国家提供的术语和格式 (Unicode, 2017)。数据库名叫CLDR (Common Locale Data Repository)，中译为「==通用区域资料库==」
- ==Unicode标准是W3C工作的基础==; 
- 谷歌的分析，互联网上的网页有超过60％使用Unicode（KING,2012）。
- 开发软件往往依赖于不同的特定编码系统，如ASCII。

## 3、Unicode标准与世界语言
- Unicode标准中字符数占最多的是中国，占了7成以上，韩国次之占1成多。
- Unicode CLDR数据库存有不少数据，可以使用XML或JSON格式取用，用於网站/软件的在地化（L10N, Localiation）及全球化（i18n, Internationalization）。
- CLDR亦有地域-语言表，Territory Language Information

## 4、Unicode 的常见表达形式
- Unicode编码的书写表达形式以U+开头，接16进制符，如Unicode的笑脸😀：
U+1F600
- URL在编码时，会把非ASCII字符及一些保留字符做转换，加以%符号以16进制符表示，如：
%F0%9F%98%80

（URL编码工具可用URL Decoder/Encoder或 ATOOL）

## 5、Unicode 与 Emoji
- 表情符号（Emoji）是一种象形文字 (图案符号)
- Unicode Emoji的支援需要厂商提供对映的Unicode 字型，如非礼勿视猴（See-No-Evil Monkey）的表情符号，就有多种厂商提供。

## 6、Unicode在东亚
- 中日韩三种语言所用的汉字，称CJK
- 越南用的汉字，称CJKV
- 统一汉字的特点在于，如是几种语言共享的符号且经同意，是共享同一编码，专用的汉字则否。
- 对处理复杂系统来说， 我们东亚的多字节文化将在未来被证明是有优势的(p. 12)。
- 从多语互联网的角度，Unicode支持东亚主要的语言是互联网国际化的重要里程碑。

## 7、Unicode 与文化政治
- 网新媒体的文本书写基础设施，无法完全避免语言文本书写的文化政治议题。

- 表情符号
- 枪支管制
- 性别政治
- 加入11个表情符号，可以搭配不同的姓别及肤色

## 8、在缅甸的罗兴亚人
- 2017年底，Unicode联盟考虑编码“Hanifi Rohingya”的书写系统

 [Unicode 及 Unicode Consortium][Unicode]
[Unicode]: https://note.youdao.com/share/?token=15FEDD32D25B4083BFF2193C8C6364F3&gid=59950065#/

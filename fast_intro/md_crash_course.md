# 我也想帮大家避雷/推荐
---
## 修改文档
### 1. 创建github账号
如果你已经有github账号了的话跳过这一步

### 2. 克隆仓库
点击fork，将这个仓库克隆到你的仓库里，这样你就能修改里面的内容了。  
![image](https://user-images.githubusercontent.com/79558524/228664515-b0d850d0-4afc-4974-88bb-369ccdbe2840.png)  

### 3. 修改内容
打开所要修改的文件，就可以往文件里添加内容了。  
举个例子，比如你想要修改`选课&老师推荐`，你先需要打开`选课&老师推荐`的页面。

#### 打开页面
![image](https://user-images.githubusercontent.com/79558524/228967434-16921286-bed5-446b-ba82-a8d784067aa2.png)  
一般来说刚刚克隆仓库以后可以看到这样个一个界面

![image](https://user-images.githubusercontent.com/79558524/228968919-00655f60-61c3-4e81-81b8-05515505abc3.png)  
然后点击这个链接就可以打开老师推荐页面

#### 修改文档
![image](https://user-images.githubusercontent.com/79558524/228969137-b0d25804-d0e7-4797-b1bf-dcdba12bd7f5.png)  
打开页面之后点击右上角小铅笔之后就能修改了
![image](https://user-images.githubusercontent.com/79558524/228969403-2f10c480-8856-4fec-8980-9b72fb5e6fa2.png)  

#### 保存
![image](https://user-images.githubusercontent.com/79558524/228970132-839e1c9c-992e-44e7-8d84-321394dfaeb8.png)  
写下简报，记下来修改了什么，然后点击`Commit changes`保存修改

#### 推送
![image](https://user-images.githubusercontent.com/79558524/228971216-1dedd30e-8677-4aee-ae98-d76af21874f4.png)  
来到`Pull requests`页面，点击`New pull requests`，然后点击`Create pull request` 把你的修改推送给仓库所有者。接着就是等仓库所有者确认你的修改啦。  
![image](https://user-images.githubusercontent.com/79558524/228971674-b23777ea-be77-49aa-8e54-1f7efcf56e29.png)

---

## Markdown 语法
你可能已经发现了，这里所有文件都是以`.md`作为后缀名的，这是`Markdown`语言文档后缀名。

### Markdown 是什么？
`Markdown`是一种轻量级标记语言，使用者可以以纯文本编辑带有格式的文档。

#### 文字
想要添加一段文字的话直接打出来就行了  
注意，在`Markdown`文档里， 换行是**两个空格加回车**或者添加一个空行。  
**例子：**
```markdown
我是第一段文字。__LF
我是第二段文字。LF
我是第三段文字。LF
LF
我是第四段文字。LF
```
##### 注： 以下例子里，“_”代表空格而“LF”代表换行  
那么最后输出的结果就是：  
>我是第一段文字。  
>我是第二段文字。
>我是第三段文字。
>
>我是第四段文字。

斜体和粗体可以通过`*`和`**`实现  
**例子：**
```
*我是第一段文字。LF*
**我是第二段文字。LF**
```
>*我是第一段文字。*  
>**我是第二段文字。**

列表可以通过`-`, `+`和`*`实现  
**例子：**
```
我是第一段文字。  
- 我是第二段文字。  
+ 我是第三段文字。  
```
>我是第一段文字。  
>- 我是第二段文字。  
>+ 我是第三段文字。

#### 链接
在`Markdown`里，链接的格式是：  
`[链接名称]（链接地址）`或者`<链接地址>`。  
**例子：**
```
[Google](https://www.google.com/)  
[Wiki](https://www.wikipedia.org/)  
<https://www.youtube.com/>
```
>[Google](https://www.google.com/)  
>[Wiki](https://www.wikipedia.org/)  
><https://www.youtube.com/>

链接不一定要链接上一个网址，也可以在文档中跳来跳去
**例子：**
```
[Jump](#Jump_to_some_text)  
# Jump_to_some_text
```
>[Jump](#Jump_to_some_text)  
># Jump_to_some_text

也可以通过html的方式添加内部链接
```
[Jump](#Jump_to_other_text)  
# Jump to other text <a name="Jump_to_other_text">
```
>[Jump_2](#Jump_to_other_text)  
># Jump to other text <a name="Jump_to_other_text">

## Futur vision

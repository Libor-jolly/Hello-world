# Hello-world

MARKDOWN 语法介绍
==========

### Maekdown 段落
要创建段落，请使用空白行将一行或多行文本进行分隔

### Markdown 换行语法
在一行的末尾添加两个或多个空格，然后按回车键,即可创建一个换行    

### 换行（Line Break）用法的最佳实践
几乎每个 Markdown 应用程序都支持**两个或多个空格**进行换行，称为 结尾**空格（trailing  whitespace)** 的方式，但这是有争议的，因为很难在编辑器中直接看到空格，并且很多人在每个句子后面都会有意或无意地添加两个空格。
由于这个原因，你可能要使用除结尾空格以外的其它方式来换行。
幸运的是，几乎每个 Markdown 应用程序都支持另一种换行方式：HTML 的 <br> 标签。
为了兼容性，请在行尾添加“结尾空格”或 HTML 的 <br> 标签来实现换行

### Markdown 强调语法
#### 粗体（Bold）
要加粗文本，请在单词或短语的前后各添加两个星号（asterisks）或下划线（underscores）。如需加粗一个单词或短语的中间部分用以表示强调的话，请在要加粗部分的两侧各添加两个星号（asterisks）
 应用程序在如何处理单词或短语中间的下划线上并不一致。为兼容考虑，在单词或短语中间部分加粗的话，请使用**星号**（asterisks) **

#### 斜体（Italic）
- 要用斜体显示文本，请在单词或短语前后添加*一个星号（asterisk）或下划线（underscore）*。要斜体突出单词的中间部分，请在字母前后各添加一个星号，中间不要带空格.

#### 粗体（Bold）和斜体（Italic）
- 要同时用粗体和斜体突出显示文本，请在单词或短语的前后各添加***三个星号或下划线***。要加粗并用斜体显示单词或短语的中间部分，请在要突出显示的部分前后各添加三个星号，中间不要带空格。

### Markdown 引用语法
#### 创建 【块】 引用
- 要创建块引用，请在段落前添加**一个 > 符号**。
> ##### for example:
>> **Dorothy followed her through many of the beautiful rooms in her castle.**
#### 多个段落的块引用
- **块引用可以包含多个段落。为段落之间的空白行添加一个 > 符号**
> ##### for example:
>> Dorothy followed her through many of the beautiful rooms in her castle.
>>
>> The Witch bade her clean the pots 和 kettles 和 sweep the floor 和 keep the fire fed with wood.
#### 嵌套块引用
- 块引用可以嵌套。在要**嵌套的段落前添加一个 >> 符号**
> ##### for example:
>> Dorothy followed her through many of the beautiful rooms in her castle.
>>
>>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
#### 带有其它元素的块引用
- 块引用可以包含其他 Markdown 格式的元素。并非所有元素都可以使用，你需要进行实验以查看哪些元素有效。
> ##### for example:
>> #### The quarterly results look great!
>>
>> - Revenue was off the chart.
>> - Profits were higher than ever.
>>
>>  *Everything* is going according to **plan**.

### Markdown 列表语法
#### 有序列表
要创建有序列表，请在每个列表项前添加数字并紧跟一个英文句点。数字不必按数学顺序排列，但是列表应当以数字 1 起始。

#### 无序列表
要创建无序列表，请在每个列表项前面添加破折号 (-)、星号 (*) 或加号 (+) 。缩进一个或多个列表项可创建嵌套列表。

#### 在列表中嵌套其他元素
要在保留列表连续性的同时在列表中添加另一种元素，请将该元素缩进四个空格或一个制表符，如下例所示：
> 段落
>> *   This is the first list item.
>> *   Here's the second list item.
>> 
>>      I need to add another paragraph below the second list item.
>>
>> *   And here's the third list item.

> 引用块
>> *   This is the first list item.
>> *   Here's the second list item.
>> 
    > A blockquote would look great below the second list item.
>> 
>> *   And here's the third list item.

> 代码块
>> 代码块通常采用**四个空格或一个制表符缩进**。当它们被**放在列表中**时，请将它们**缩进八个空格或两个制表符**
1.  Open the file.
2.  Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3.  Update the title to match the name of your website.
> 图片
1.  Open the file containing the Linux mascot.
2.  Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3.  Close the file.

> 列表
You can nest an unordered list in an ordered list, or vice versa.

1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item










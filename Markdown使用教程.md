<center><font face="楷体" color=red size=7>Markdown使用教程</font></center>

1. **标题**
   # 一级标题
   ## 二级标题

2. **引用**
 >编辑这类教程文档很好用！
>>也可以嵌套
>>>一直嵌套

1. 列表
   1. 无序列表
     + 列表一
       + 更小的   （相互之间隔两个空格）
         + 更小的  
     - 列表二
     * 列表三
   2.  有序列表
   3.  嵌套
   4.  Todolist
      - [ ] a
      - [ ] b

2. **表格**
    | 左对齐  | 居中对齐 | 右对齐 |
    | :---- | :----: | -----: |     
    | a | b | c |

    ==不知道为什么这里不能制表== 找到原因了！这里的冒号记得要用英文的冒号

3. **段落**
   - 换行——两个以上空格后回车，或者空一行
   - 分割线——三个* 
    ***   
   - 字体
     *斜体*
     ==高亮==
     **粗体**
     ***斜粗体***
     ~~删除~~ 
     <u>下划线</u>
   - 脚注
     谢谢大家的支持[^1]
     ==不知道为什么这里不能脚注==

4. **代码**
   `#include<iostream>`  键盘左上角的英文符号`
    或者是
    ```
    #include<iostream>
    using namespace std;
    int main(){

    }
    ```

5. **超链接**
   - [更多细节] : https://github.com/Echo11220011/vscode
   - 或者直接把链接放上来也是可以点的
     https://github.com/Echo11220011/vscode
   - 再或者可以用脚注的方法
    更多细节请[点击链接][教程]  不知道为什么这个也不行

6. **图片**
   - 使用图床保存图片并实现插入(就是在图床上把图片对应的markdown链接复制粘贴过来)
    [路过图床]https://imgse.com/
    [![pAM3Jdf.png](https://s21.ax1x.com/2024/09/21/pAM3Jdf.png)](https://imgse.com/i/pAM3Jdf)
   - 使用HTML语言实现调整图片大小和位置的功能

### 三、其他操作
   - **插入latex公式**
     -  行内显示公式：$f(x)=ax+b$
     -  块内显示数学表达式：
     $$
     \begin{Bmatrix}
     a & b \\
     c & d
     \end{Bmatrix}
     $$  
   - html语法和css语法美化
对单行居中操作： <center><font face="楷体" color=red size=5>美化效果</font></center>

<a href="https://imgse.com/i/pAM3Jdf"><img src="https://s21.ax1x.com/2024/09/21/pAM3Jdf.png" alt="pAM3Jdf.png" border="0" ==width="50%" height="80%"==/></a>

<a href="https://imgse.com/i/pAM3Jdf"><img src="https://s21.ax1x.com/2024/09/21/pAM3Jdf.png" alt="pAM3Jdf.png" border="0" width="50%" height="80%"/></a>
居中显示：
<a href="https://imgse.com/i/pAM3Jdf"><div align = center><img src="https://s21.ax1x.com/2024/09/21/pAM3Jdf.png" alt="pAM3Jdf.png" border="0" width="50%" height="80%"/></div></a>
即在图片链接中插入：
<div align = center></div>
<div align = left></div>
<div align = right></div>


- vscode快捷命令
  CTRL+F 快速查找
       




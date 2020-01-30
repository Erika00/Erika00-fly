

this is a [hyperlink](https://github.com/Erika00/pilot-student)
---

`git add .`表示增加 后面可以增加文件名

`git restore--staged`后面加文件名 表示暂存

`git log` 表示检查历史记录

`git status`表示检查目前状态

`git diff`表示比较两个版本文件

---

# `git push`可以推送当地文本到 **github**  

* 首先在github建一个仓库  + 名字/描述/创建

* 其次选第二个方法分别链接两个地址

* 最后刷新就可以在`github`上看到了
---
# `git pull`可以把 **github**  上文本拿过来看自己用
* 首先在`github `fork 
* 然后 dowmlow clone 出来一个地址
* 再然后git clone + 地址  /ls检查/再进去cd .\learn-git\   git log 检查历史记录下载


* 然后 code . 进去就可以看到拿过来的文本了
---
# markdown 语法

## 标题 
* #空格 ：大标题
* ##空格： 中标题
* ###空格：小标题
# 大标题
## 中标题
### 小标题
## 文本
* ** 文字/符合 ** 无空格 ：粗体字


**粗体字**

* *文字/符合 * 无空格：斜体字

*斜体字*

## 超链接
* 这是个 **[*文本名称*]** **(*文本地址*)**
this is [超链接](ROBOT.md)
# 引文
* 大于号  >
> wenzhang  
>
>
> --zuozhe 

# 列表
* 有序号 **1.  2.**
1.
2.

* 不带序号 * 或 -
* 多级的空出来2格*1. *2. 如下

    1.
    2.
 # 水平分割线
 - --- 三个横杠 分段落用的
 ---
# 代码
* 等宽字体，灰字体 两个反**炖点` `` `**

`this is 两个反炖点`

# 代码段
- ` 2个```分别首尾 `

```
这是个代码段qqqihcbcnclwejncnkwl
```
# 插入图片
*  ！[图片] (地址) 
# markdown 运用
* 在 github 中 建一个仓库  + 名字/描述/创建
* 第二个方法 有2行 操作符 分别代入
* 把 md 文件传上去
1. 在learn-markdown 命令行中
  ```
  git init
  （git commit -a -m "init commit"）
  git add .加未被追踪的文件
  git commit -a -m "init commit"
  命令行/复制 地址 （方法1 GitHub中新建仓库）
  命令行/复制 地址 （方法2 GitHub中新建仓库）
   最后刷新 看GitHub动态

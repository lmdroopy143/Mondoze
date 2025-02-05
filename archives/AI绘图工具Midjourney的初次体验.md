# AI绘图工具Midjourney的初次体验

## Midjourney (MJ) 使用指南

最近尝试了Midjourney进行绘图，这里简单记录一下使用流程和技巧。

### 注册与登录

首先需要注册并登录Midjourney账号，以下是详细步骤：

1. 打开Discord，点击右上角`Login`进入登录界面。
2. 点击登录页面下方的`Register`，进入注册页面。
3. 输入注册所需的相关信息，点击`Continue`完成注册。
4. Midjourney会发送一份验证邮件，进入邮箱点击验证链接完成验证。
5. 返回Discord，继续登录Midjourney，进入主界面。
6. 点击左侧的`探索可发现的服务器`按钮，打开服务器界面，找到`Midjourney`群组并点击。如果未找到，可以在搜索框搜索。
   ![寻找Midjourney群组](https://bbtdd.com/img/03615703052.webp)
   ![加入Midjourney群组](https://bbtdd.com/img/7161604078.webp)
7. 点击`Getting Started`进入服务器，然后点击最上方的`加入Midjourney`，加入群组。如果无法加入，可能是代理国家人数过多，尝试切换代理国家。
8. 加入群组后，点击左上角的`私信`，打开`Midjourney Bot`，即可与MJ机器人进行对话。
   ![打开MJ机器人对话框](https://bbtdd.com/img/0397809791034.webp)
9. 如果需要订购会员，在对话框中输入`/subscribe`命令，点击`Manage Account`，进入订阅界面。选择月付的标准版会员，输入支付方式完成订阅。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)

### 运行指令

登录后，点击左上角`私信`，选中`Midjourney Bot`，即可打开与MJ机器人的对话框。在对话框中输入指令（按下`/`会有智能提示），常用指令包括：

- `/imagine <prompt>`：生成图像，`prompt`为生成图像的文本命令。
- `/info`：查看账户的订阅信息和剩余时间。
- `/relax`：切换到relax模式，生成图像不消耗GPU时间，但需要排队。
- `/fast`：切换到fast模式，快速生成图像，消耗GPU时间。
- `/blend`：融合两张图片。
- `/settings`：调整Midjourney的设置，如版本、风格、质量参数等。

### 绘图操作

掌握基本用法后，即可开始绘图。例如，使用`/imagine Diagrammatic isometric the water cycle or water cycle diagram shows four seasons of watering of Earth's surface, in the style of forest vistas, whistlerian, photoillustration, left forests but right fragment trees, 2d game art, rough-edged 2d animation Three dimensional`生成四季水文循环图。

绘图后，可以在右侧查看进度，等待100%完成即可展示图片。

### 绘图参数

在绘图的`prompt`后添加一些参数，可以控制绘图设置，如图像比例、清晰度等。常用参数包括：

- `--aspect`或`--ar`：绘图比例，默认1:1。
- `--chaos <0-100>`：控制图片的创意度和多样性。
- `--no`：控制图片中不要出现的元素。
- `--quality`或`--q`：控制图片的精细质量，默认1。
- `--seed <0-4294967295>`：绘图种子，控制图片相似性。

### 图片调整

初次绘图后，可以对生成的图像进行调整，如放大、变化、重新生成等。使用`Upscale`提升分辨率，`Zoom out`向外括图，`Vary`更新图像。

### 保存高清大图

保存图片时，不要直接右键保存缩略图。点击图像左下角的`在浏览器打开`按钮，打开原始高分辨率图后保存。Midjourney目前最高可生成2k分辨率的图像。

### Prompt设计技巧

Midjourney的`prompt`包含图像提示、文本提示和参数三部分。设计`prompt`时，尽量用词具体，控制描述长度，专注于想要的元素，处理好背景和细节。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)
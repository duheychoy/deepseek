<h2 align="center">
    <img src="https://static.docs-hub.com/deepseek.png" height="64">
    <br>Deepseek
</h2>
<h3 align="center">
    <a href="https://marketplace.visualstudio.com/items?itemName=colourafredi.vscode-deepseek" alt="Marketplace version">
        <img src="https://img.shields.io/visual-studio-marketplace/v/colourafredi.vscode-deepseek?label=VS%20Code%20Marketplace" />
    </a>
    <a href="https://marketplace.visualstudio.com/items?itemName=colourafredi.vscode-deepseek" alt="Marketplace download count">
        <img src="https://img.shields.io/visual-studio-marketplace/stars/colourafredi.vscode-deepseek" />
    </a>
    <a href="https://marketplace.visualstudio.com/items?itemName=colourafredi.vscode-deepseek" alt="Marketplace download count">
        <img src="https://img.shields.io/visual-studio-marketplace/d/colourafredi.vscode-deepseek?label=Downloads" />
    </a>
</h3>
<p align="center">Keyless, Magic-free, Login-free, Multilingual</p>
<p align="center">免Key，免魔法，免登录，多语言</p>
<p align="center">無需Key，無需魔法，無需登入，多語言</p>

**English**

### Usage Instructions

Press the shortcut key `Ctrl+Shift+P (Command+Shift+P)`, type `Deepseek: Set up a custom proxy server🌐`, press Enter, and then enter the proxy server URL. Press Enter again to complete the configuration.

## Features

- 💻 Copy and insert code into current and new files
- 🚀 Add predefined prompts for quick input during questioning
- 📤 Export code or entire conversations as markdown files
- 💾 Save your conversation history on your local hard drive, replay, continue, and manage at any time
- 🔑 Bind your own API key that supports DeepSeek R1 to use the DeepSeek R1 model
- 🗣️ Bind your own API key to support streaming context conversation and you can pause the response at any time
- 🌐 Use your own DeepSeek server
- 🔒 Privacy secured, all information is saved on your local hard drive, without uploading any information to any server
- 🌍 The plugin supports multiple languages, including English, Simplified Chinese, and Traditional Chinese. If you wish to add a new language, please raise an [issue](https://github.com/zhangrenyang/deepseek/issues) here.

## Commands

- **Check the following code for bugs and provide repair suggestions 🐛**: Use the code error-finding feature to analyze and highlight errors in the code
- **Explain the following code in detail 💬**: Use the code explanation feature for a better understanding of your code
- **Refactor this code and tell me what did you change 🔧**: Refactor code and understand clearly what you've changed
- **Deepseek: Add tests for the following code 🧪**: Easily add tests for your code
- **Deepseek: Add Predefined Prompt ➕**: Add predefined prompts through a combination of shortcuts and input
- **Deepseek: Choose Predefined Prompt 🔍**: Choose a predefined prompt
- **Deepseek: Custom prompt ❓**: Generate custom queries for Deepseek
- **Deepseek: Edit predefined prompt ✏️**: Edit predefined prompt
- **Deepseek: Bind your own API key 🔀🔑**: Easily bind your own API key using a combination of shortcuts and commands
- **Deepseek: Validate API key ✔️🔑**: Validate your API key to ensure its validity and correct function
- **Deepseek: Unbind API key 🗑️🔑**: Unbind Your Own API key
- **Deepseek: Set language 🌍**: Set the language you want with shortcuts and commands. The default is English
- **Deepseek: Set up a custom proxy server 🌐**: Set and use your own proxy server by inputting your proxy server information
- **Deepseek: Cancel proxy server settings 🌐**: Cancel proxy server settings
- **Deepseek: Ask a question ❓**: Click on the Deepseek icon and input your content, then press Enter to get a reply from Deepseek
- **Deepseek: Clear list 🗑️**: Clear the current conversation
- **Deepseek: Export markdown 📤**: Export the current conversation as a markdown file
- **Deepseek: Bind your own proxy server 🌐**: Set and use your own proxy server by inputting your proxy server information
- **Deepseek: Unbind your own proxy server 🌐**: Unbind your own proxy server

## 📖 Usage

### 🔧 Install the extension

Install the extension from the [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=colourafredi.vscode-deepseek)

### Ask question ❓

Press the shortcut key `Ctrl+Shift+P (Command+Shift+P)`, type `Deepseek: Ask a question ❓`, press Enter, type your question, press Enter again, and the answer panel will automatically open to provide an answer.

Alternatively, click on the Deepseek icon on the left, enter what you want to say, press Enter, and wait a few seconds for Deepseek's reply to appear.

On the answer page, the first small icon is for copying to the clipboard, the second small icon is for inserting the answer at the current cursor position, and the third small icon is for creating and opening a file and inserting the answer at the current cursor position.

### 🔑 API key

### 📚 What is an API key?

DeepSeek's API key is a mechanism for authenticating and authorizing access to DeepSeek's API (Application Programming Interface). An API key is like a password, allowing developers to interact with DeepSeek's services in a secure manner. The API key is a critical factor in establishing a connection between the server and the client, used to verify the legitimacy of the request. Typically, only users with a valid API key can access a specific API.

Here are the general steps to use the DeepSeek API key:

- Create an DeepSeek account: You first need to [click here](https://chat.deepseek.com/sign_in) to create an DeepSeek account, and then generate your API key in that account.

- Generate API key: In the DeepSeek dashboard, [click here](https://platform.deepseek.com) you can generate a new API key.

### Bind your own API key 🔀🔑

Press the shortcut `Ctrl+Shift+P (Command+Shift+P)`, enter `Deepseek: Bind your own API key 🔀🔑`, press Enter, input the API key, press Enter again, and the API key will be updated.

You can also open any file, right-click, select `Deepseek: Bind your own API key 🔀🔑`, input the API key, and press Enter to update the API key. If the update is successful, the balance and expiry date of the API key and supported models will be displayed. If the update fails, you will be prompted to re-enter the API key.

### Validate API key ✔️🔑

Press the shortcut `Ctrl+Shift+P (Command+Shift+P)`, enter `Deepseek: Validate API key ✔️🔑`, press Enter, and the API key will be validated.

You can also open any file, right-click, select `Deepseek: Validate API key ✔️🔑`, and press Enter to validate the API key. If the validation is successful, the balance and expiry date and supported models of the API key will be displayed. If the validation fails, you will receive API key invalid notification.

If you wish to use DeepSeek R1, you need to [click here](https://DeepSeek.com/waitlist/DeepSeek R1-api) to apply for DeepSeek R1 API permissions.

### Unbind API key 🗑️🔑

Press the shortcut `Ctrl+Shift+P (Command+Shift+P)`, enter `Deepseek: Unbind API key 🗑️🔑`, and you can then unbind Your Own API key.

### Why is there a bug in this code? 🐛

Open any file, select a piece of code (if no code is selected, the whole content of the file will be considered), then right-click and choose `Deepseek: Why is there a bug in this code? 🐛💻` from the menu. This can help you analyze your code and highlight any errors.

### Help me explain the code? 💬

Open any file, select a piece of code (if no code is selected, the whole content of the file will be considered), then right-click and choose `Deepseek: Help me explain the code? 💬` from the menu. This can help explain your code.

### Refactor this code and tell me what did you change? 🔧💻

Open any file, select a piece of code (if no code is selected, the whole content of the file will be considered), then right-click and choose `Deepseek: Refactor this code and tell me what did you change? 🔧💻` from the menu. This can help refactor your code.

### Add some tests for this code for me 🧪

Open any file, select a piece of code (if no code is selected, the whole content of the file will be considered), then right-click and choose `Deepseek: Add some test for this code for me 🧪` from the menu. This can help add tests for your code.

### Custom prompt ❓

Open any file, select a piece of code (if no code is selected, the whole content of the file will be considered), then right-click and choose `Deepseek: Custom prompt ❓` from the menu. An input box will pop up, type your question, press Enter, and you will get an answer.

### Add predefined prompts ➕

Press the shortcut `Ctrl+Shift+P (Command+Shift+P)`, enter `Deepseek: Add Predefined Prompt ➕`, press Enter, and you can enter predefined prompts, which could be a title or content.
After input, in the question input box, you can type / to pop up a predefined selection box, then use the up and down arrow keys to select a predefined prompt. Press Enter or click to confirm and it will be automatically filled into the question input box.

### Edit Predefined Prompts Using a JSON File ✏️

Press the shortcut `Ctrl+Shift+P (Command+Shift+P)` and type `Deepseek: Edit Predefined Prompts ✏️`, then press Enter. This will open the `prompts.json` configuration file where you can edit predefined prompts in one place.

After doing this, you can type `/` in the input box to display a dropdown list of predefined prompts. Use the up and down arrow keys to navigate through the prompts, and press Enter or click to select one and have it automatically inserted into the input box.

### Choose Predefined Prompt ➕

Press the shortcut keys `Ctrl+Shift+P (Command+Shift+P on Mac)`, type in `Deepseek: Choose Predefined Prompt ➕`, a selection window will pop up for users to choose their custom prompts they have added.

### Set language 🌍

Press the shortcut `Ctrl+Shift+P (Command+Shift+P)`, enter `Deepseek: Set language 🌍`, press Enter, and select the language you want to set. The default is English.

### Set up a custom proxy server 🌐

Press the shortcut `Ctrl+Shift+P (Command+Shift+P)`, enter `Deepseek: Set up a custom proxy server 🌐`, then by entering your own proxy server, you can use your own proxy server.

### Settings ❓

- [DeepSeek API Guide](https://api-docs.deepseek.com)

Users can configure the settings of VS Code plugins by following these steps:

1. **Open Settings:**
   In VS Code, press the shortcut `Ctrl+,` or select `File > Preferences > Settings` from the top menu bar (on Mac it is `Code > Preferences > Settings`).

2. **Search for Plugin Settings:**
   In the settings search bar, enter the name of the plugin or keywords of the configuration parameters. VS Code will dynamically display the configuration options that match your input.

3. **Modify Configuration Parameters:**
   Click the configuration parameter you want to modify, then enter a new value or select a new option. You can also click the edit icon (the pencil icon) to add the configuration parameter to your user settings or workspace settings, and then modify it there.

4. **Save Modifications:**
   VS Code automatically saves your settings after you make modifications. Close the settings tab or click elsewhere, and the new configuration will take effect.

#### 🧠 Model

The DeepSeek API is powered by a diverse set of [models](https://api-docs.deepseek.com/quick_start/pricing) with different capabilities and price points. You can also make limited customizations to our original base models for your specific use case with fine-tuning.

#### 🌡️ Temperature

In the DeepSeek API, `temperature` is a parameter that controls the randomness of the generated text. Its value is between 0 and 1, inclusive.

When the `temperature` is close to 1, the text generated by the model will be more random. In other words, when the model chooses the next word, it will make a more uniform selection among all possible words, even if the probabilities of some words are low. This may result in outputs that are more innovative, but it may also lead to reduced coherence and consistency in the outputs.

When the `temperature` is close to 0, the text generated by the model will be more deterministic. That is, the model will be more inclined to choose the word with the highest probability when selecting the next word. This may result in outputs that are more coherent and consistent, but they may lack innovation.

In summary, the `temperature` parameter can help you find a balance between innovation and coherence. If you want the generated text to be more innovative, you can try to increase the value of `temperature`; if you want the generated text to be more coherent, you can try to decrease the value of `temperature`.

## 🗣️ Communication

- You are welcome to join the QQ discussion group for discussions

- DeepseekQQ Group 【957284835】 [Click to join QQ Group](http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=KWl8ZyDCDrBRn4NCXUnr5MkyMTl0nwSK&authKey=iGZm2aZDWgj83khMCftofy7j8YIf0ulFSr4gaeXRbcOpTMWA1RRg%2BHRJ0A%2FVdPaa&noverify=0&group_code=957284835)
- Or join by scanning the QQ QR code<br/>
  <img src="https://static.docs-hub.com/qrcode.jpg" height="256">
- Or share design architecture through the Official Accounts<br/>
  <img src="https://vleedesigntheory.github.io/offical_accounts.jpg" height="256">

## Thanks for your sponsorship, your support helps maintain this project

<img src="https://static.docs-hub.com/w_e_c_h_a_t_1738581207393.jpg" height="256">
<img src="https://static.docs-hub.com/a_l_i_p_a_y_1738581250846.jpg" height="256">


**中文**

### 使用方式

## 特色

- 💻 可以复制、插入代码到当前文件和新文件中
- 🚀 可以添加预定义提示词以便在提问的时候快速输入
- 📤 可以导出代码或整个会话为 markdown 文件
- 💾 可以将你的会话记录保存在本地硬盘,随时回放、继续和管理
- 🔑 绑定自己的支持 DeepSeek R1 的 API key 之后可以使用 DeepSeek R1 模型
- 🗣️ 绑定自己的 API key 之后支持流式上下文对话并且可以随时暂停回答
- 🌐 可以使用你自己的 DeepSeek 服务器
- 🔒 隐私安全,所有信息都保存在本地硬盘,不会将任何信息上传至任何服务器
- 🌍 支持多种国家的语言,目前有英文、简体中文、繁体中文,如果你希望添加新的语言可以在这里提[issue](https://github.com/zhangrenyang/deepseek/issues)

## 命令

- **Deepseek:检查下面代码是否有 BUG 并给出修复建议 🐛**: 使用查找代码错误功能来分析和突出代码中的错误
- **Deepseek:详细讲解下面代码 💬**: 使用解释代码功能来更好地理解您的代码
- **Deepseek:重构下面代码并告诉我你改动了哪里 🔧**: 重构下面代码并告诉我你改动了哪里
- **Deepseek:为下面的代码添加测试**: 为下面的代码添加测试
- **Deepseek:选择预定义提示词 🔍**: 选择预定义提示词
- **Deepseek:自定义提问 ✏️❓**: 为 Deepseek 生成自定义查询
- **Deepseek:增加预定义提示词 ➕**: 增加预定义提示词
- **Deepseek:修改预定义提示词 ✏️**: 修改预定义提示词
- **Deepseek:绑定自己的 API key🔀🔑**: 通过组合快捷键和命令轻松更新 API key
- **Deepseek:验证 API key✔️🔑**: 验证 API key 以确保其有效性和正确功能
- **Deepseek:解绑 API key🗑️🔑**: 解绑你自己的 API key
- **Deepseek:修改显示语言 🌍**: 通过快捷键和命令来设定您想要的语言。预设是英文
- **Deepseek:取消代理服务器设置 🌐**: 取消代理服务器设置
- **Deepseek:发起提问 ❓**: 点击 Deepseek 图标并输入内容，然后按 Enter 键获取 Deepseek 的回答
- **Deepseek:清空列表 🗑️**: 可以清空当前的会话
- **Deepseek:导出 markdown📤**: 可以导出当前的会话为 markdown 文件
- **Deepseek:绑定自己的代理服务器 🌐**: 通过输入自己的代理服务器信息，设定并使用自己的代理服务器
- **Deepseek:解绑自己的代理服务器 🌐**: 解绑自己的代理服务器

## 📖 使用

### 🔧 安装扩展

从[VSCode 市场](https://marketplace.visualstudio.com/items?itemName=colourafredi.vscode-deepseek)安装扩展

### 发起提问❓

按下快捷键`Ctrl+Shift+P(Command + Shift + P )`,输入`Deepseek:发起提问 ❓`,按 Enter 键,输入你的问题,再次按 Enter 键,答案面板会自动打开并提供答案。

或者点击左侧的 Deepseek 图标,输入你想说的内容,按 Enter 键,等待几秒钟 Deepseek 的回复就会出现。

在答案页面,第一个小图标是复制到剪贴板,第二个小图标是在当前光标位置插入答案,第三个小图标是创建并打开文件并在当前光标位置插入答案。

### 🔑 API key

### 📚 什么是 API key？

DeepSeek 的 API key 是一种用于验证和授权访问 DeepSeek 的 API（应用程序编程接口）的机制。API key 就像一个密码,允许开发者以安全的方式与 DeepSeek 的服务进行交互。API key 在建立服务器和客户端之间的连接中是一个关键因素,用于验证请求的合法性。通常,只有拥有有效 API key 的用户才能访问特定的 API。

以下是使用 DeepSeek API key 的一般步骤：

- 创建 DeepSeek 账户：你首先需要[点击这里](https://chat.deepseek.com/sign_in)创建一个 DeepSeek 账户,然后在该账户中生成你的 API key。

- 生成 API key：在 DeepSeek 的仪表盘上, [点击这里](https://platform.deepseek.com)你可以生成一个新的 API key。

### 绑定自己的 API key🔀🔑

按下快捷键`Ctrl+Shift+P(Command + Shift + P )`,输入`Deepseek:绑定自己的API key🔀🔑`,按 Enter 键,输入 API key,再次按 Enter 键,API key 就会更新。

你也可以打开任何文件,右键选择`Deepseek:绑定自己的API key🔀🔑`,输入 API key,按 Enter 键更新 API key。如果更新成功,会显示 API key 的余额和到期日期以及支持的模型。如果更新失败,会提示重新输入 API key。

### 验证 API key✔️🔑

按下快捷键`Ctrl+Shift+P(Command + Shift + P )`,输入`Deepseek:验证API key ✔️🔑`,按 Enter 键,API key 就会被验证。

你也可以打开任何文件,右键选择`Deepseek:验证API key ✔️🔑`,按 Enter 键验证 API key。如果验证成功,会显示 API key 的余额、到期日期和支持的模型。如果验证失败,你会收到 API key 无效的通知。

如果你希望使用 DeepSeek R1,你需要[点击这里](https://DeepSeek.com/waitlist/DeepSeek R1-api)申请 DeepSeek R1 API 权限。

### 解绑 API key🗑️🔑

按下快捷键`Ctrl+Shift+P(Command + Shift + P )`,输入`Deepseek:解绑API key 🔄🔑`,你就可以解绑你自己的 API key

### 为什么这段代码有错误？🐛💻

打开任何文件,选择一段代码(如果没有选择代码,将会考虑文件的全部内容),然后右键选择菜单中的`Deepseek:为什么这段代码出现了BUG? 🐛💻`。这可以帮助你分析代码并突出显示任何错误。

### 帮我解释这段代码？💬📖

打开任何文件,选择一段代码(如果没有选择代码,将会考虑文件的全部内容),然后右键选择菜单中的`Deepseek:讲解下面代码 💬📖`。这可以帮助解释你的代码。

### 重构这段代码并告诉我你改动了哪里 🔧💻

打开任何文件,选择一段代码(如果没有选择代码,将会考虑文件的全部内容),然后右键选择菜单中的`Deepseek:重构下面代码并告诉我你改动了哪里? 🔧💻`。这可以帮助重构你的代码。

### 为我添加一些测试代码 ➕🧪💻

打开任何文件,选择一段代码(如果没有选择代码,将会考虑文件的全部内容),然后右键选择菜单中的`Deepseek:为我这段代码添加测试 ➕🧪`。这可以帮助为你的代码添加测试。

### 自定义问题 ✏️❓

打开任何文件,选择一段代码(如果没有选择代码,将会考虑文件的全部内容),然后右键选择菜单中的`Deepseek:自定义提问 ✏️❓`。会弹出一个输入框,输入你的问题,按 Enter 键,你就会得到答案。

### 增加预定义提示词 ➕

按下快捷键`Ctrl+Shift+P(Command + Shift + P )`,输入`Deepseek:增加预定义提示词 ➕`,按 Enter 键,你可以输入预定义提示词,可以是标题或内容。
输入之后在提问输入框可以键入`/`弹出预定义选择框,然后按上下方向键可以选择预定义提示词,回车或点击可以确定并自动填入提问输入框。

### 使用 JSON 文件编辑预定义提示词 ✏️

按下快捷键`Ctrl+Shift+P(Command + Shift + P )`,输入`Deepseek:编辑预定义提示词 ✏️`,按 Enter 键,你可以打开一个`prompts.json`配置文件来统一编辑预定义提示词。
输入之后,在提问输入框中输入`/`,会弹出预定义选择框。接着按上下方向键选择预定义提示词,按 Enter 或点击以确定并自动填入提问输入框。

### 绑定自己的 API key🔀🔑

按下快捷键`Ctrl+Shift+P(Command + Shift + P )`,输入`Deepseek:绑定自己的API key🔀🔑`,按 Enter 键,输入 API key,再次按 Enter 键,API key 就会更新。

### 验证 API key✔️🔑

按下快捷键`Ctrl+Shift+P(Command + Shift + P )`,输入`Deepseek:验证API key✔️🔑`,按 Enter 键,API key 就会被验证。

### 解绑 API key🗑️🔑

按下快捷键`Ctrl+Shift+P(Command + Shift + P )`,输入`Deepseek:解绑 API key🗑️🔑`,你就可以解绑你自己的 API key。

### 修改显示语言 🌍

按下快捷键`Ctrl+Shift+P(Command + Shift + P )`,输入`Deepseek:修改显示语言 🌍`,按 Enter 键,选择你想要设置的语言。默认是英文。

### 设置自定义的代理服务器 🌐

按下快捷键`Ctrl+Shift+P(Command + Shift + P )`,输入`Deepseek:设置自定义的代理服务器 🌐`,然后输入你自己的代理服务器,你就可以使用你自己的代理服务器。

注意,你的代理服务器必须支持 HTTPS,否则它将无法工作。

### ❓ 设置

- [DeepSeek API 指南](https://api-docs.deepseek.com/)

用户可以通过以下步骤配置 VS Code 插件的配置参数：

1. **打开设置：**
   在 VS Code 中,按下快捷键`Ctrl+,`或者从顶部菜单栏选择`File > Preferences > Settings` (在 Mac 上是 `Code > Preferences > Settings`)。
2. **搜索插件设置：**
   在设置的搜索栏中,输入插件的名称或者配置参数的关键词。VS Code 会动态显示与你的输入匹配的配置选项。
3. **修改配置参数：**
   点击你想要修改的配置参数,然后输入新的值或者选择新的选项。你也可以通过点击编辑图标(铅笔图标)将配置参数添加到你的用户设置或者工作区设置中,然后在那里进行修改。
4. **保存修改：**
   VS Code 会在你修改设置后自动保存。关闭设置标签页或者点击其他地方,新的配置就会生效。

#### 🧠 模型

DeepSeek API 由一组具有不同功能和价格点的[模型](https://api-docs.deepseek.com/quick_start/pricing)驱动。你也可以通过微调对我们的原始基础模型进行有限的定制,以适应你的特定使用场景。

#### 🌡️ 温度

在 DeepSeek API 中,`temperature`是一个控制生成文本随机性的参数。它的值在 0 到 1 之间(包括 0 和 1)。

当`temperature`接近 1 时,模型生成的文本会更加随机。换句话说,当模型选择下一个词时,它会在所有可能的词中进行更均匀的选择,即使某些词的概率很低。这可能会产生更具创新性的输出,但也可能导致输出的连贯性和一致性降低。

当`temperature`接近 0 时,模型生成的文本会更加确定。也就是说,在选择下一个词时,模型会更倾向于选择概率最高的词。这可能会产生更连贯和一致的输出,但可能缺乏创新性。

总的来说,`temperature`参数可以帮助你在创新性和连贯性之间找到平衡。如果你希望生成的文本更具创新性,可以尝试增加`temperature`的值；如果你希望生成的文本更加连贯,可以尝试降低`temperature`的值。

## 🗣️ 交流

- 欢迎加入 QQ 讨论群进行交流

- DeepseekQQ 群【957284835】[点击加入 QQ 群](http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=KWl8ZyDCDrBRn4NCXUnr5MkyMTl0nwSK&authKey=iGZm2aZDWgj83khMCftofy7j8YIf0ulFSr4gaeXRbcOpTMWA1RRg%2BHRJ0A%2FVdPaa&noverify=0&group_code=957284835)
- 或者扫描 QQ 二维码加入<br/>
  <img src="https://static.docs-hub.com/qrcode.jpg" height="256">
- 或者通过公众号分享设计架构<br/>
  <img src="https://vleedesigntheory.github.io/offical_accounts.jpg" height="256">

## 创作和维护不易，感谢您的赞助

<img src="https://static.docs-hub.com/w_e_c_h_a_t_1738581207393.jpg" height="256">
<img src="https://static.docs-hub.com/a_l_i_p_a_y_1738581250846.jpg" height="256">

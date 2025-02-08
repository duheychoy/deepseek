# DeepSeek 本地部署保姆级教程

> 本教程将指导您如何使用 Ollama 在本地轻松部署 DeepSeek 模型，即使您不是技术专家也能轻松上手。

## 一、前言

DeepSeek 是一个强大的 AI 模型，通过 Ollama 这个便捷工具，我们可以轻松实现本地部署。Ollama 不仅支持 DeepSeek，还支持通义千问等多个开源模型，是一个非常实用的 AI 模型运行平台。

## 二、安装 Ollama

1. 访问 Ollama 官网：https://ollama.com/
2. 点击 "Download" 按钮
3. 选择适合您系统的版本下载（本教程以 Windows 为例）
4. 下载完成后运行安装程序
5. 点击 "Install" 按钮完成安装

> 提示：如果下载速度较慢，可以尝试使用迅雷等下载工具加速。

![](https://upload-markdown-images.oss-cn-beijing.aliyuncs.com/1_1739022671446.png)

![](https://upload-markdown-images.oss-cn-beijing.aliyuncs.com/2_1739022688607.png)

![](https://upload-markdown-images.oss-cn-beijing.aliyuncs.com/3_1739022701606.png)

## 三、选择并下载模型

1. 在 Ollama 官网点击左上角 "Models"
2. 找到 deepseek-r1 系列模型
3. 根据您的设备配置选择合适的模型版本：

   - 入门级设备建议选择 1.5b 版本
   - 性能较好的设备可以尝试 7b 或 14b 版本
   - 具体选择可以参考设备配置要求

![](https://upload-markdown-images.oss-cn-beijing.aliyuncs.com/4_1739022716714.png)

![](https://upload-markdown-images.oss-cn-beijing.aliyuncs.com/5_1739022755327.png)

4. 打开命令提示符（Win+R 输入 cmd）
5. 输入模型下载命令：
   ```bash
   ollama run deepseek-r1:1.5b   # 1.5b版本
   # 或
   ollama run deepseek-r1:7b     # 7b版本
   # 或
   ollama run deepseek-r1:14b    # 14b版本
   ```

![](https://upload-markdown-images.oss-cn-beijing.aliyuncs.com/6_1739022780336.png)
![](https://upload-markdown-images.oss-cn-beijing.aliyuncs.com/7_1739022767999.png)

## 四、使用模型对话

1. 模型下载完成后会自动进入对话模式
2. 在提示符 `>>>` 后输入问题并按回车
3. 常用命令：
   - `/clear` - 清除上下文，重新开始对话
   - `/bye` - 退出对话模式
   - 直接输入问题 - 开始对话

![](https://upload-markdown-images.oss-cn-beijing.aliyuncs.com/8_1739022792571.png)

## 五、日常使用说明

### 启动模型

1. 按 Win+R 打开运行
2. 输入 cmd 打开命令提示符
3. 输入启动命令：`ollama run 模型名称`
   例如：`ollama run deepseek-r1:1.5b`

### 模型管理命令

- 查看已安装模型：`ollama list`
- 删除模型：`ollama rm 模型名称`
  例如：`ollama rm deepseek-r1:1.5b`
- 查看所有命令：直接输入 `ollama`

  ![](https://upload-markdown-images.oss-cn-beijing.aliyuncs.com/9_1739022801741.png)
  ![](https://upload-markdown-images.oss-cn-beijing.aliyuncs.com/1_0_1739022825603.png)
  ![](https://upload-markdown-images.oss-cn-beijing.aliyuncs.com/1_1_1739022834662.png)

## 六、注意事项

1. 硬件要求：

   - 1.5b 版本：最低 8GB 内存
   - 7b 版本：建议 16GB 以上内存
   - 14b 版本：建议 32GB 以上内存

2. 存储空间：

   - 请确保有足够的硬盘空间（模型文件较大）
   - 1.5b 约需 3GB
   - 7b 约需 15GB
   - 14b 约需 30GB

3. 使用建议：
   - 首次使用建议从小模型开始尝试
   - 确保网络稳定，避免下载中断
   - 使用时保持电脑有足够的可用内存

## 七、常见问题解答

1. Q: 模型下载速度慢怎么办？
   A: 可以尝试使用迅雷等下载工具，或者在网络良好的环境下进行下载

2. Q: 如何切换不同的模型？
   A: 退出当前模型对话后，使用 `ollama run` 命令启动其他模型

3. Q: 模型占用空间太大怎么办？
   A: 可以使用 `ollama rm` 命令删除不常用的模型，需要时再重新下载

4. Q: 运行时提示内存不足？
   A: 尝试使用更小的模型版本，或关闭其他占用内存的程序

## 八、通过 API 接口访问模型

### 1. API 基本信息

- 默认 API 地址：`http://localhost:11434/api`
- 支持的请求方式：POST
- 数据格式：JSON

### 2. 主要 API 接口

#### 生成回答（Generate）

```bash
curl -X POST http://localhost:11434/api/generate -d '{
  "model": "deepseek-r1:1.5b",
  "prompt": "你好，请介绍一下自己",
  "stream": false
}'
```

#### 聊天对话（Chat）

```bash
curl -X POST http://localhost:11434/api/chat -d '{
  "model": "deepseek-r1:1.5b",
  "messages": [
    {
      "role": "user",
      "content": "你好，请介绍一下自己"
    }
  ],
  "stream": false
}'
```

### 3. Python 示例代码

```python
import requests

def chat_with_model(prompt):
    url = "http://localhost:11434/api/chat"
    data = {
        "model": "deepseek-r1:1.5b",
        "messages": [
            {
                "role": "user",
                "content": prompt
            }
        ],
        "stream": False
    }

    response = requests.post(url, json=data)
    return response.json()

# 使用示例
response = chat_with_model("你好，请介绍一下自己")
print(response['message']['content'])
```

### 4. JavaScript 示例代码

```javascript
async function chatWithModel(prompt) {
  const url = "http://localhost:11434/api/chat";
  const data = {
    model: "deepseek-r1:1.5b",
    messages: [
      {
        role: "user",
        content: prompt,
      },
    ],
    stream: false,
  };

  const response = await fetch(url, {
    method: "POST",
    headers: {
      "Content-Type": "application/json",
    },
    body: JSON.stringify(data),
  });

  return await response.json();
}

// 使用示例
chatWithModel("你好，请介绍一下自己")
  .then((response) => console.log(response.message.content))
  .catch((error) => console.error("Error:", error));
```

### 5. 注意事项

1. 确保 Ollama 服务正在运行
2. API 默认只监听本地请求（localhost）
3. 如需远程访问，需要配置 Ollama 允许远程连接
4. 建议在生产环境中添加适当的安全措施
5. stream 参数设置为 true 时可获得流式响应

### 6. 常见问题

1. Q: 无法连接到 API？
   A: 检查 Ollama 服务是否正常运行，默认端口 11434 是否被占用

2. Q: 如何处理流式响应？
   A: 将 stream 参数设置为 true，并相应调整代码以处理流式数据

3. Q: 如何设置超时时间？
   A: 在请求时添加适当的超时设置，避免长时间等待

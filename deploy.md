# DeepSeek Local Deployment Guide

> This tutorial will guide you on how to easily deploy DeepSeek models locally using Ollama, even if you're not a technical expert.

## I. Introduction

DeepSeek is a powerful AI model that we can easily deploy locally through the convenient tool Ollama. Ollama not only supports DeepSeek but also multiple open-source models like Tongyi Qianwen, making it a very practical AI model running platform.

## II. Installing Ollama

1. Visit Ollama's official website: https://ollama.com/
2. Click the "Download" button
3. Choose the version suitable for your system (this tutorial uses Windows as an example)
4. Run the installer after downloading
5. Click the "Install" button to complete installation

> Tip: If the download speed is slow, try using download tools like Thunder to accelerate.

![](https://static.docs-hub.com/1_1739022671446.png)

![](https://static.docs-hub.com/2_1739022688607.png)

![](https://static.docs-hub.com/3_1739022701606.png)

## III. Selecting and Downloading Models

1. Click "Models" in the top left corner of Ollama's website
2. Find the deepseek-r1 series models
3. Choose a suitable model version based on your device configuration:

   - Entry-level devices should choose the 1.5b version
   - Better performing devices can try 7b or 14b versions
   - Specific choices can refer to device configuration requirements

![](https://static.docs-hub.com/4_1739022716714.png)

![](https://static.docs-hub.com/5_1739022755327.png)

4. Open Command Prompt (Win+R, type cmd)
5. Enter the model download command:
   ```bash
   ollama run deepseek-r1:1.5b   # 1.5b version
   # or
   ollama run deepseek-r1:7b     # 7b version
   # or
   ollama run deepseek-r1:14b    # 14b version
   ```

![](https://static.docs-hub.com/6_1739022780336.png)
![](https://static.docs-hub.com/7_1739022767999.png)

## IV. Using the Model for Conversation

1. After the model download completes, it will automatically enter conversation mode
2. Type your question after the `>>>` prompt and press Enter
3. Common commands:
   - `/clear` - Clear context, start a new conversation
   - `/bye` - Exit conversation mode
   - Direct input - Start conversation

![](https://static.docs-hub.com/8_1739022792571.png)

## V. Daily Usage Instructions

### Starting the Model

1. Press Win+R to open Run
2. Type cmd to open Command Prompt
3. Enter the start command: `ollama run model_name`
   Example: `ollama run deepseek-r1:1.5b`

### Model Management Commands

- View installed models: `ollama list`
- Delete model: `ollama rm model_name`
  Example: `ollama rm deepseek-r1:1.5b`
- View all commands: Simply type `ollama`

  ![](https://static.docs-hub.com/9_1739022801741.png)
  ![](https://static.docs-hub.com/1_0_1739022825603.png)
  ![](https://static.docs-hub.com/1_1_1739022834662.png)

## VI. Important Notes

1. Hardware Requirements:

   - 1.5b version: Minimum 8GB RAM
   - 7b version: Recommended 16GB+ RAM
   - 14b version: Recommended 32GB+ RAM

2. Storage Space:

   - Ensure sufficient disk space (model files are large)
   - 1.5b requires about 3GB
   - 7b requires about 15GB
   - 14b requires about 30GB

3. Usage Recommendations:
   - For first-time users, start with smaller models
   - Ensure stable network connection to avoid download interruptions
   - Maintain sufficient available memory while using

## VII. FAQ

1. Q: What if the model download is slow?
   A: Try using download tools like Thunder, or download in a better network environment

2. Q: How to switch between different models?
   A: Exit current model conversation, then use `ollama run` command to start another model

3. Q: What if the model takes up too much space?
   A: Use `ollama rm` command to delete rarely used models, download again when needed

4. Q: Getting insufficient memory error?
   A: Try using a smaller model version, or close other memory-intensive programs

## VIII. Accessing Models via API

### 1. API Basic Information

- Default API address: `http://localhost:11434/api`
- Supported request method: POST
- Data format: JSON

### 2. Main API Endpoints

#### Generate Response

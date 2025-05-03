## 硬體配備  
本實驗採用消費級 GPU（NVIDIA RTX 4090）、64GB RAM 及 Intel i9-14900K 處理器。

## 模型資訊  
- 使用模型：[Gemma3 int4 量化版本](https://huggingface.co/unsloth/gemma-3-27b-it-bnb-4bit)

## 任務說明  
- **提示（Prompt）**：  
>  你是一個Threads用戶。你看到以下的貼文，請在這則貼文用激動的語氣留言，發表你的想法。  {post}

## AI 回覆設定  
- **AI 回覆 1**：  
  採用未經微調之模型，回覆內容將移除句首感嘆詞、表情符號及 hashtag。
- **AI 回覆 2**：  
  以社群政治貼文組成之資料集（將於日後公開）進行 LoRA 微調，回覆內容不經後處理。

## 樣本比例設定  
- **是非題**：真人 : AI 回覆 1 : AI 回覆 2 = 1 : 1 : 1  
- **單選題**：AI 回覆 1 : AI 回覆 2 = 1 : 1

## Dataset
稍後公開

## 題庫
見檔案problems_1_19.xlsx

## 解析
稍後公開

## AI原始輸出
見gemma_output檔案
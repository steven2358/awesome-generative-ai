# 精彩的生成式人工智慧 [![精彩](https://awesome.re/badge-flat.svg)](https://awesome.re)

[![English](https://img.shields.io/badge/English-Click-yellow)](README.md)
[![繁體中文](https://img.shields.io/badge/繁體中文-點選-orange)](README_zh_TW.md)
[![Español](https://img.shields.io/badge/Español-Clic-green)](README_es.md)

> 一份精選的現代生成式人工智慧（Generative AI）專案與服務清單。

生成式 AI 是一種利用經過大量數據訓練的機器學習算法來創造原創內容（如圖像、聲音和文本）的技術。與其他形式的人工智慧不同，它能夠創建獨特且前所未見的輸出，例如寫實圖像、數位藝術、音樂和寫作。這些輸出通常具有其獨特的風格，甚至可能難以與人類創作的作品區分開來。生成式人工智慧在藝術、娛樂、行銷、學術和計算機科學等領域有著廣泛的應用。

歡迎為此清單貢獻內容。在提交您的建議之前，請先查看[參與指南](CONTRIBUTING.md)
，以確保您的條目符合標準。透過[pull requests](https://github.com/steven2358/awesome-generative-ai/pulls)
新增連結，或創建[問題](https://github.com/steven2358/awesome-generative-ai/issues)
來開始討論。更多專案可以在[探索清單](DISCOVERIES.md)中找到，我們在那裡展示了廣泛的新興生成式人工智慧專案。

## 目錄

- [精選閱讀](#recommended-reading)
- [文本](#text)
- [程式設計](#coding)
- [智慧代理](#agents)
- [圖像](#image)
- [影片](#video)
- [音訊](#audio)
- [其他](#other)
- [學習資源](#learning-resources)
- [更多資源](#more-lists)

## 精選閱讀

- [大型語言模型將如何改變科學、社會和人工智慧](https://hai.stanford.edu/news/how-large-language-models-will-transform-science-society-and-ai) -
  一篇總結 GPT-3 模型能力及其局限性，以及對社會潛在影響的文章。作者：Alex Tamkin 和 Deep Ganguli，2021 年 2 月 5 日。
- [生成式人工智慧：一個創意的新世界](https://www.sequoiacap.com/article/generative-ai-a-creative-new-world/) -
  一篇全面檢視生成式人工智慧產業的文章，提供歷史視角及行業生態系統的深入分析。作者：Sonya Huang、Pat Grady 和 GPT-3，2022 年
  9 月 19 日。
- [生成式人工智慧的亮相派對，矽谷的新熱潮](https://www.nytimes.com/2022/10/21/technology/generative-ai.html) -
  一篇關於生成式人工智慧崛起的文章，特別是 Stable Diffusion 圖像生成器的成功及相關爭議。紐約時報，2022 年 10 月 21 日。
- [人工智慧的新創意浪潮引發矽谷淘金熱](https://www.wired.com/story/ais-new-creative-streak-sparks-a-silicon-valley-gold-rush/) -
  一篇關於生成式人工智慧初創公司日益增長的熱潮及投資的文章，各行業探索其潛在應用。Wired，2022 年 10 月 27 日。
- [ChatGPT 預示著一場智慧革命](https://www.wsj.com/articles/artificial-intelligence-generative-ai-chatgpt-kissinger-84512912) -
  Henry Kissinger、Eric Schmidt 和 Daniel Huttenlocher 的專欄文章。華爾街日報，2023 年 2 月 24 日。

### 重要里程碑

- [OpenAI API](https://openai.com/blog/openai-api/) - 宣布 OpenAI API，提供基於 GPT-3 的文本到文本通用人工智慧模型。OpenAI
  部落格，2020 年 6 月 11 日。
- [GitHub Copilot](https://github.blog/2021-06-29-introducing-github-copilot-ai-pair-programmer/) - 宣布
  Copilot，一個幫助您編寫更好程式碼的新 AI 配對程式。GitHub 部落格，2021 年 6 月 29 日。
- [DALL·E 2](https://openai.com/blog/dall-e-2/) - 宣布 DALL·E 2 的正式發布，一個具有改進解析度、擴展圖像創建能力和多種安全緩解措施的先進圖像生成系統。OpenAI
  部落格，2022 年 4 月 6 日。
- [Stable Diffusion 正式發布](https://stability.ai/blog/stable-diffusion-public-release) - 宣布 Stable Diffusion
  的正式發布，一個基於廣泛網絡抓取訓練的 AI 圖像生成模型，並基於 Creative ML OpenRAIL-M 許可證。Stable Diffusion 部落格，2022
  年 8 月 22 日。
- [ChatGPT](https://openai.com/blog/chatgpt/) - 宣布 ChatGPT，一個訓練用於回答後續問題、承認錯誤、挑戰錯誤前提並拒絕不當請求的對話模型。OpenAI
  部落格，2022 年 11 月 30 日。
- [Bing 搜尋](https://blogs.microsoft.com/blog/2023/02/07/reinventing-search-with-a-new-ai-powered-microsoft-bing-and-edge-your-copilot-for-the-web/) -
  微軟宣布其搜尋引擎 Bing 的新版本，由下一代 OpenAI 模型提供支援。微軟部落格，2023 年 2 月 7 日。
- [LLaMA](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/) - Meta 推出的 Llama LLM，一個具有 650
  億參數的基礎大型語言模型。Meta，2023 年 2 月 23 日。#opensource
- [GPT-4](https://openai.com/research/gpt-4) - 宣布 GPT-4，一個大型多模態模型。OpenAI 部落格，2023 年 3 月 14 日。
- [DALL·E 3](https://openai.com/index/dall-e-3/) - 宣布 DALL·E 3 圖像生成器。OpenAI 部落格，2023 年 9 月 20 日。
- [Sora](https://openai.com/research/video-generation-models-as-world-simulators) - 發表 Sora，一個大型影片生成模型。OpenAI，2024
  年 2 月 15 日。

## 文本

### 模型

- [OpenAI API](https://openai.com/api/) - OpenAI 的 API 提供對 GPT-3 和 GPT-4 模型的訪問，這些模型執行多種自然語言任務，以及將自然語言轉換為程式碼的
  Codex。
- [Gopher](https://www.deepmind.com/blog/language-modelling-at-scale-gopher-ethical-considerations-and-retrieval) -
  DeepMind 的 Gopher 是一個具有 2800 億參數的語言模型。
- [OPT](https://huggingface.co/facebook/opt-350m) - Facebook
  的開放預訓練變壓器（OPT）是一套僅解碼器預訓練變壓器。[公告](https://ai.facebook.com/blog/democratizing-access-to-large-scale-language-models-with-opt-175b/)。[OPT-175B 文本生成](https://opt.alpa.ai/)
  由 Alpa 托管。
- [Bloom](https://huggingface.co/docs/transformers/model_doc/bloom) - Hugging Face 的 BLOOM 是一個類似 GPT-3 的模型，已經在
  46 種不同語言和 13 種程式語言上進行了訓練。#opensource
- [Llama](https://www.llama.com/) - Meta 的開源大型語言模型。#opensource
- [Claude](https://claude.ai/) - 與 Claude 交談，來自 Anthropic 的 AI 助手。
- [Vicuna-13B](https://lmsys.org/blog/2023-03-30-vicuna/) - 一個開源聊天機器人，透過在 ShareGPT 上收集的用戶共享對話對
  LLaMA 進行微調訓練。#opensource
- [Mistral](https://mistral.ai/en/models) - Mistral AI 提供的尖端開源 LLM。#opensource
- [Grok](https://grok.x.ai/) - xAI 的 LLM，具有[開源](https://github.com/xai-org/grok-1)和開放權重。#opensource
- [Qwen](https://qwenlm.github.io/) - 阿里雲獨立開發的一系列 LLM。[#opensource](https://github.com/QwenLM/Qwen)

### 聊天機器人

- [ChatGPT](https://chatgpt.com/) - OpenAI 的 ChatGPT 是一個以對話方式進行交互的大型語言模型。
- [Copilot](https://copilot.microsoft.com/) - 微軟的日常 AI 伴侶。
- [Gemini](https://gemini.google.com/) - Google Deepmind 開發的一系列多模態大型語言模型。
- [Meta AI](https://www.meta.ai/) - Meta AI 助手，幫助完成任務、創建 AI 生成的圖像、獲取答案。基於 Llama LLM 構建。
- [DeepSeek](https://www.deepseek.com/) - 用於企業、消費者和科學應用的尖端 LLM。#opensource
- [GPTBots.ai](https://www.gptbots.ai/zh_TW/) - GPTBots 幫助企業利用 AI 智慧體進行客戶服務、企業搜尋和數據洞察，使 AI 為您工作。
- [DeepChat](https://github.com/ThinkInAIXYZ/deepchat/blob/main/README.md) - 一款免費的桌面 AI 助理，支援多輪對話、網路搜尋、上傳與知識庫。
- [Character.AI](https://character.ai/) - Character.AI 讓您創建角色並與之聊天。
- [Pi](https://pi.ai) - 一個可用作數字助手的個性化 AI 平台。
- [Qwen](https://chat.qwenlm.ai/) - Qwen 聊天機器人，具有圖像生成、文檔處理、網頁搜尋集成、影片理解等功能。
- [Le Chat](https://chat.mistral.ai/) - 與 Mistral AI 的尖端語言模型聊天。

### 自訂介面

- [LibreChat](https://librechat.ai/) - LibreChat 是一個免費且開源的聊天介面，用於助手
  AI。[#opensource](https://github.com/danny-avila/LibreChat)。
- [Chatbot UI](https://www.chatbotui.com/) - 一個開源的 ChatGPT
  UI。[#opensource](https://github.com/mckaywrigley/chatbot-ui)。

### 搜尋引擎

- [Perplexity AI](https://www.perplexity.ai/) - AI 驅動的搜尋工具。
- [Metaphor](https://metaphor.systems/) - 語言模型驅動的搜尋。
- [Phind](https://phind.com/) - 基於 AI 的搜尋引擎。
- [You.com](https://you.com/) - 一個基於 AI 的搜尋引擎，為用戶提供定制的搜尋體驗，同時保持數據 100% 私密。
- [Komo](https://komo.ai/) - 一個 AI 驅動的搜尋引擎。

### 本地搜尋引擎

- [privateGPT](https://github.com/imartinez/privateGPT) - 使用 LLM 的力量在無需網絡連接的情況下向文檔提出問題。
- [quivr](https://github.com/StanGirard/quivr) - 傾倒所有文件並使用生成式 AI 第二大腦與其聊天，使用 LLM 和嵌入技術。

### 寫作助手

- [Jasper](https://www.jasper.ai/) - 使用人工智慧更快速地創建內容。
- [Compose AI](https://www.compose.ai/) - Compose AI 是一款免費的 Chrome 擴展工具，透過 AI 驅動的自動完成功能將您的寫作時間縮短
  40%。
- [Rytr](https://rytr.me/) - Rytr 是一款 AI 寫作助手，幫助您創建高品質內容。
- [wordtune](https://www.wordtune.com/) - 個人寫作助手。
- [HyperWrite](https://hyperwriteai.com/) - HyperWrite 幫助您自信地寫作，從構思到最終稿件更快速完成工作。
- [Moonbeam](https://www.gomoonbeam.com/) - 更快速地撰寫優質的博客文章。
- [copy.ai](https://www.copy.ai/) - 使用 AI 撰寫更好的行銷文案和內容。
- [ChatSonic](https://writesonic.com/chat) - 一款支援文本和圖片創作的 AI 助手。
- [Anyword](https://anyword.com/) - Anyword 的 AI 寫作助手為任何人生成有效的文案。
- [Hypotenuse AI](https://www.hypotenuse.ai/) - 將幾個關鍵字轉化為原創且有洞察力的文章、產品描述和社交媒體文案。
- [Lavender](https://www.lavender.ai/) - Lavender 電子郵件助手幫助您在更短時間內提升回覆率。
- [Lex](https://lex.page/) - 一款內建人工智慧的文字處理器，讓您更快速地寫作。
- [Jenni](https://jenni.ai/) - Jenni 是終極寫作助手，幫助您節省構思和寫作時間。
- [LAIKA](https://www.writewithlaika.com/) - LAIKA 使用您的寫作風格訓練人工智慧，成為個性化的創意夥伴。
- [QuillBot](https://quillbot.com) - 基於 AI 的改寫工具。
- [Postwise](https://postwise.ai/) - 使用 AI 撰寫推文、排程貼文並增長您的粉絲數。
- [Copysmith](https://copysmith.ai/) - 為企業和電子商務提供的 AI 內容創建解決方案。

### ChatGPT 擴展工具

- [WebChatGPT](https://chrome.google.com/webstore/detail/webchatgpt-chatgpt-with-i/lpfemeioodjbpieminkklglpmhlngfcn) -
  利用網頁的相關結果來增強您的 ChatGPT 提示。
- [GPT for Sheets and Docs](https://workspace.google.com/marketplace/app/gpt_for_sheets_and_docs/677318054654) - 適用於
  Google Sheets 和 Google Docs 的 ChatGPT 擴展工具。
- [YouTube Summary with ChatGPT](https://chrome.google.com/webstore/detail/youtube-summary-with-chat/nmmicjeknamkfloonkhhcjmomieiodli) -
  使用 ChatGPT 摘要 YouTube 視頻。
- [ChatGPT Prompt Genius](https://chrome.google.com/webstore/detail/chatgpt-prompt-genius/jjdnakkfjnnbbckhifcfchagnpofjffo) -
  發現、分享、導入和使用最佳的 ChatGPT 提示，並將聊天記錄本地保存。
- [ChatGPT for Search Engines](https://chrome.google.com/webstore/detail/chatgpt-for-search-engine/feeonheemodpkdckaljcjogdncpiiban) -
  在 Google、Bing 和 DuckDuckGo 搜索結果旁顯示 ChatGPT 回應。
- [ShareGPT](https://sharegpt.com/) - 分享您的 ChatGPT 對話並探索他人分享的對話。
- [Merlin](https://merlin.foyer.work/) - 適用於所有網站的 ChatGPT Plus 擴展工具。
- [ChatGPT Writer](https://chatgptwriter.ai/) - 使用 ChatGPT AI 生成完整的電子郵件與訊息。
- [ChatGPT for Jupyter](https://github.com/TiesdeKok/chat-gpt-jupyter-extension) - 在 Jupyter Notebooks 和 Jupyter Lab
  中添加多種 ChatGPT 助手功能。
- [editGPT](https://www.editgpt.app/) - 輕鬆校對、編輯和追蹤 ChatGPT 中的內容變更。
- [Forefront](https://www.forefront.ai/) - 提供更好的 ChatGPT 使用體驗。

### 生產力工具

- [ChatPDF](https://www.chatpdf.com/) - 與任何 PDF 進行對話。
- [Mem](https://mem.ai/) - Mem 是全球首個個性化的 AI 工作空間，提升您的創造力，自動化日常工作，並自動保持井然有序。
- [Taskade](https://www.taskade.com/) - 使用 Taskade AI 規劃任務、筆記，生成結構化的清單與思維導圖。
- [Notion AI](https://www.notion.so/product/ai) - 撰寫更好、更高效的筆記和文檔。
- [Nekton AI](https://nekton.ai) - 使用 AI 自動化您的工作流程。用簡單語言逐步描述您的工作流程。
- [Rewind](https://www.rewind.ai/) - Rewind 是一款基於您所見、所說或所聽的個性化 AI。
- [NotebookLM](https://notebooklm.google/) - 一款由 Google Gemini 提供支援的研究和筆記工具，可與文件互動。

### 會議助手

- [Otter.ai](https://otter.ai/) - 一款會議助手，記錄音頻、撰寫筆記、自動捕捉幻燈片並生成摘要。
- [Cogram](https://www.cogram.com/) - Cogram 在虛擬會議中自動記錄筆記並識別行動項目。
- [Sybill](https://www.sybill.ai/) - Sybill 透過結合文字記錄和情感洞察生成銷售通話摘要，包括後續步驟、痛點和興趣點。
- [Loopin AI](https://www.loopinhq.com/) - Loopin 是一個協作會議工作空間，不僅可以使用 AI 記錄、轉錄和總結會議，還能自動整理會議筆記並與日曆同步。
- [Fireflies.ai](https://fireflies.ai/) - Fireflies.ai 幫助您的團隊進行語音對話的轉錄、總結、搜索和分析。
- [Read AI](https://www.read.ai/) - 一款 AI 副駕駛，讓您的會議、電子郵件和訊息更高效，提供摘要、內容發現和建議。

### 學術工具

- [Elicit](https://elicit.org/) - Elicit 使用語言模型幫助您自動化研究工作流程，例如文獻綜述的部分內容。
- [genei](https://www.genei.io/) - 幾秒內總結學術文章，節省 80% 的研究時間。
- [Explainpaper](https://www.explainpaper.com/) - 一種更好的學術論文閱讀方式。上傳論文，標記困惑的文本，獲得解釋。
- [Galactica](https://galactica.org/) - 一款針對科學的大型語言模型。可總結學術文獻、解決數學問題、生成 Wiki
  文章、撰寫科學代碼、註釋分子和蛋白質等。[模型 API](https://github.com/paperswithcode/galai)。
- [Consensus](https://consensus.app/search/) - Consensus 是一款使用 AI 在科學研究中尋找答案的搜索引擎。
- [Synthical](https://synthical.com) - 基於 AI 的協作研究環境。
- [scite](https://scite.ai/) - 一個發現和評估科學文章的平台。
- [SciSpace](https://typeset.io/) - 一款幫助理解科學文獻的 AI 研究助手。

### 排行榜

- [Chatbot Arena](https://lmarena.ai/) - 一個由 UC Berkeley SkyLab 和 LMArena 研究人員主持的開放平台，用於群眾外包 AI
  基準測試。
- [Artificial Analysis](https://artificialanalysis.ai/) - Artificial Analysis 提供客觀基準和信息，幫助選擇 AI 模型和託管提供商。

### 其他文本生成工具

- [EmailTriager](https://www.emailtriager.com/) - 使用 AI 在後台自動撰寫電子郵件回覆。
- [AI Poem Generator](https://www.aipoemgenerator.org) - AI 詩歌生成器根據文本提示為您創作美麗的押韻詩。

## 編程

### 編程助手

- [GitHub Copilot](https://github.com/features/copilot) - GitHub Copilot 使用 OpenAI Codex 在編輯器中實時建議代碼和整個函數。
- [OpenAI Codex](https://platform.openai.com/docs/guides/code/) - OpenAI 開發的將自然語言轉換為代碼的 AI 系統。
- [Ghostwriter](https://blog.replit.com/ai) - Replit 推出的 AI 驅動的編程助手。
- [Amazon Q](https://aws.amazon.com/q/) - AWS 基於生成式 AI 的助手，幫助回答問題、撰寫代碼和自動化任務。
- [tabnine](https://www.tabnine.com/) - 使用整行和完整函數代碼補全更快速地編碼。
- [Stenography](https://stenography.dev/) - 自動生成代碼文檔。
- [Mintlify](https://mintlify.com/) - 基於 AI 的文檔撰寫工具。
- [Debuild](https://debuild.app/) - 用於網頁應用的 AI 驅動低代碼工具。
- [AI2sql](https://www.ai2sql.io/) - 使用 AI2sql，工程師和非工程師都能輕鬆撰寫高效、無錯誤的 SQL 查詢，而無需了解 SQL。
- [CodiumAI](https://www.codium.ai/) - 在您的 IDE 中直接建議非平凡測試，讓您在推送代碼時更有信心。
- [PR-Agent](https://github.com/Codium-ai/pr-agent) - 用於自動化 PR 分析、反饋、建議等的 AI 工具。
- [MutableAI](https://mutable.ai/) - AI 加速軟件開發。
- [TurboPilot](https://github.com/ravenscroftj/turbopilot) - 一款自託管的 Copilot 克隆工具，使用 llama.cpp 背後的庫在 4
  GB RAM 中運行 60 億參數的 Salesforce Codegen 模型。
- [GPT-Code UI](https://github.com/ricklamers/gpt-code-ui) - OpenAI ChatGPT 代碼解釋器的開源實現。#opensource
- [MetaGPT](https://github.com/geekan/MetaGPT) - 多智慧體框架：給定一行需求，返回 PRD、設計、任務、代碼庫。
- [Open Interpreter](https://github.com/KillianLucas/open-interpreter) - 在本地終端運行的 OpenAI 代碼解釋器。
- [Continue](https://www.continue.dev/) - 開源 AI 代碼助手。連接任何模型和上下文，在 IDE
  中創建自定義自動補全和聊天體驗。[#opensource](https://github.com/continuedev/continue)

### 開發者工具

- [co:here](https://cohere.ai/) - Cohere 提供先進的大型語言模型和 NLP 工具的訪問。
- [Haystack](https://haystack.deepset.ai/) - 用於構建 NLP 應用（如智慧體、語義搜索、問答系統）的框架，支援語言模型。
- [LangChain](https://langchain.com/) - 用於開發語言模型驅動應用的框架。
- [gpt4all](https://github.com/nomic-ai/gpt4all) - 一款基於大量乾淨助手數據（包括代碼、故事和對話）訓練的聊天機器人。
- [LLM App](https://github.com/pathwaycom/llm-app) - 用於構建實時 LLM 驅動數據管道的開源 Python 庫。
- [LMQL](https://lmql.ai/) - 用於大型語言模型的查詢語言。
- [LlamaIndex](https://www.llamaindex.ai/) - 用於在外部數據上構建 LLM 應用的數據框架。
- [Phoenix](https://phoenix.arize.com/) - Arize 推出的開源 ML 可觀察性工具，運行於筆記本環境，監控和微調 LLM、CV 和表格模型。
- [Cursor](https://www.cursor.so/) - Cursor 是未來的 IDE，專為與強大 AI 配對編程而設計。
- [SymbolicAI](https://github.com/Xpitfire/symbolicai) - 一個以 LLM 為核心構建應用的神經符號框架。
- [Vanna.ai](https://vanna.ai/) - 用於 SQL 生成及相關功能的開源 Python RAG
  框架。[#opensource](https://github.com/vanna-ai/vanna)
- [Portkey](https://portkey.ai/) - 用於 LLM 監控、緩存和管理的全棧 LLMOps 平台。
- [agenta](https://github.com/agenta-ai/agenta) - 用於提示工程、評估和部署的開源端到端 LLMOps 平台。#opensource
- [Together AI](https://www.together.ai/) - 快速、低成本、可生產規模地訓練、微調和運行 AI 模型。
- [Gitingest](https://gitingest.com/) - 將任何 Git 存儲庫轉換為簡單的文本摘要，以便可以輸入到任何
  LLM。[#opensource](https://github.com/cyclotruc/gitingest)
- [Repomix](https://repomix.com/) - 將您的代碼庫打包成 AI 友好格式。[#opensource](https://github.com/yamadashy/repomix)
- [llama.cpp](https://github.com/ggml-org/llama.cpp) - 在純 C/C++ 中推理 Meta 的 LLaMA 模型（及其他）。#opensource
- [bitnet.cpp](https://github.com/microsoft/BitNet) - Microsoft 推出的 1-bit LLM
  官方推理框架。[#opensource](https://github.com/microsoft/BitNet)

### 實驗平台

- [OpenAI Playground](https://platform.openai.com/playground) - 探索資源、教學資源、API 文件和動態範例。
- [Google AI Studio](https://aistudio.google.com/) - 一個基於網頁的工具，用於進行 Gemini 和實驗性模型的原型開發。
- [GitHub Models](https://github.com/marketplace/models) - 尋找並試驗 AI 模型以開發生成式 AI 應用。

### 本地大型語言模型部署

- [Ollama](https://github.com/ollama/ollama) - 在本地快速啟動和運行大型語言模型。
- [Open WebUI](https://github.com/open-webui/open-webui) - 一個可擴展、功能豐富且用戶友好的自我託管 AI
  平台，設計完全離線運行。#opensource
- [Jan](https://jan.ai/) - 在您的電腦上本地和離線運行大型語言模型，例如 Mistral 或 Llama2，或連接到遠端 AI
  API。[#opensource](https://github.com/janhq/jan)
- [Msty](https://msty.app/) - 一個簡單而強大的本地和在線 AI 模型介面。
- [PyGPT](https://pygpt.net/) - 個人桌面 AI 助手，具有聊天、視覺、代理、圖像生成、工具和命令、語音控制等功能。#opensource
- [LLM](https://llm.datasette.io/) - 一個用於與大型語言模型（遠端和本地）交互的 CLI 工具和 Python
  庫。[#opensource](https://github.com/simonw/llm)

## 智慧體

### 自主代理智慧體

- [Auto-GPT](https://github.com/Torantulino/Auto-GPT) - 一個實驗性的開源嘗試，旨在使 GPT-4 完全自主。
- [babyagi](https://github.com/yoheinakajima/babyagi) - 由 AI 驅動的任務管理系統。
- [AgentGPT](https://github.com/reworkd/AgentGPT) - 在瀏覽器中組裝、配置和部署自主 AI 智慧體。
- [GPT Engineer](https://github.com/AntonOsika/gpt-engineer) - 指定您希望它構建的內容，AI 會詢問澄清問題，然後構建它。
- [GPT Prompt Engineer](https://github.com/mshumer/gpt-prompt-engineer) - 自動化提示工程。生成、測試和排名提示以找到最佳提示。
- [MetaGPT](https://github.com/geekan/MetaGPT) - 多智慧體框架：給出一行需求，返回 PRD、設計、任務、代碼庫。
- [AutoGen](https://github.com/microsoft/autogen) - AutoGen 是一個框架，允許使用多個智慧體開發能夠互相對話以解決任務的大型語言模型應用。
- [GPT Pilot](https://github.com/Pythagora-io/gpt-pilot) - 開發工具，從頭開始編寫可擴展的應用，同時開發者監督實施。
- [Devin](https://devin.ai/) - Cognition Labs 的自主 AI 軟體工程師。
- [OpenDevin](https://github.com/OpenDevin/OpenDevin) - 一個自主智慧體，旨在應對軟體工程的複雜性。#opensource
- [Davika](https://github.com/stitionai/devika) - 一個具有代理功能的 AI 軟體工程師。#opensource

### 自訂助手

- [Poe](https://poe.com/) - Poe 提供多種機器人訪問。
- [GPT Builder](https://chat.openai.com/gpts/editor) - 用於創建基於 GPT 的助手的工具。
- [GPTStore](https://gptstore.ai/) - 尋找有用的 GPT，分享您自己的 GPT。

## 圖像

### 模型

- [DALL·E 2](https://openai.com/dall-e-2/) - OpenAI 的 DALL·E 2 是一種新的 AI 系統，可以從自然語言描述中創建逼真的圖像和藝術作品。
- [Stable Diffusion](https://huggingface.co/CompVis/stable-diffusion-v1-4) - Stability AI 的穩定擴散（Stable
  Diffusion）是一種最先進的文本到圖像模型，可從文本生成圖像。#opensource
- [Midjourney](https://www.midjourney.com/) - Midjourney 是一家獨立的研究實驗室，探索新的思維媒介並擴展人類物種的想像力。
- [Imagen](https://imagen.research.google/) - Google 的 Imagen 是一種文本到圖像擴散模型，具有前所未有的照片真實感和深層語言理解能力。
- [Make-A-Scene](https://ai.facebook.com/blog/greater-creative-control-for-ai-image-generation/) - Meta 的 Make-A-Scene
  是一種多模態生成式 AI 方法，透過允許用戶透過文本描述和自由草圖來描述和展示他們的願景，將創意控制權交到用戶手中。
- [DragGAN](https://github.com/XingangPan/DragGAN) - 拖動您的 GAN：生成圖像流形上的交互式基於點的操作。

### 服務

- [Craiyon](https://www.craiyon.com/) - Craiyon，前身為 DALL-E mini，是一種可以從任何文本提示中繪製圖像的 AI 模型。
- [DreamStudio](https://beta.dreamstudio.ai/) - DreamStudio 是一個易於使用的介面，用於使用穩定擴散圖像生成模型創建圖像。
- [Artbreeder](https://www.artbreeder.com/) - Artbreeder 是一種新型創意工具，透過使協作和探索變得更容易來激發用戶的創造力。
- [GauGAN2](http://gaugan.org/gaugan2/) - GauGAN2 是一種強大的工具，用於創建逼真的藝術作品，結合了分割映射、修復和文本到圖像生成於一個模型中。
- [Magic Eraser](https://www.magiceraser.io/) - 幾秒鐘內從圖像中移除不需要的內容。
- [Imagine by Magic Studio](https://magicstudio.com/imagine) - Magic Studio 的一個工具，讓您只需描述腦海中的內容即可表達自己。
- [Alpaca](https://www.getalpaca.io/) - 穩定擴散 Photoshop 插件。
- [Patience.ai](https://www.patience.ai/) - Patience.ai 是一個使用穩定擴散創建圖像的應用程式，這是一種由 Stability.AI
  開發的尖端 AI。
- [GenShare](https://www.genshare.io/) - 免費生成藝術作品。擁有並分享您創建的內容。一個多媒體生成工作室，民主化設計和創造力。
- [Playground](https://playground.com/) - Playground 是一個免費使用的在線 AI 圖像創建器。使用它來製作藝術品、社交媒體帖子、演示文稿、海報、視頻、徽標等。
- [Pixelz AI Art Generator](https://pixelz.ai/) - Pixelz AI Art Generator 讓您可以從文本創建令人難以置信的藝術作品。提供穩定擴散、CLIP
  Guided Diffusion 和 PXL·E 實現算法。
- [modyfi](https://www.modyfi.io/) - 您一直想要的圖像編輯器。瀏覽器中的 AI 驅動創意工具。實時協作。
- [Ponzu](https://www.ponzu.ai/) - Ponzu 是您的免費 AI 標誌生成器。使用您的想像力在幾秒鐘內創建創意設計的標誌。
- [PhotoRoom](https://www.photoroom.com/) - 僅使用手機製作產品和肖像圖片。移除背景、更改背景並展示產品。
- [Avatar AI](https://avatarai.me/) - 創建您自己的 AI 生成化身。
- [ClipDrop](https://clipdrop.co/) - 無需攝影棚即可製作專業視覺效果，由 [stability.ai](https://stability.ai/) 提供支援。
- [Lensa](https://prisma-ai.com/lensa) - 一款全能圖像編輯應用，包括使用穩定擴散生成個性化化身。
- [RunDiffusion](https://rundiffusion.com/) - 用於創建 AI 生成藝術的基於雲的工作空間。
- [Ideogram](https://ideogram.ai/) - 一個文本到圖像平台，使創意表達更易於訪問。
- [Bing Image Creator](https://www.bing.com/images/create) - 基於 DALLE·3 的文本到圖像生成器，具有安全功能。
- [KREA](https://www.krea.ai/) - 使用了解您的風格、概念或產品的 AI 生成高質量視覺效果。
- [Nightcafe](https://creator.nightcafe.studio/) - NightCafe Creator 是一款具有多種 AI 藝術生成方法的 AI 藝術生成應用程式。
- [Leonardo AI](https://leonardo.ai/) - 以前所未有的質量、速度和風格為您的項目創建生產質量的視覺資產。
- [Recraft](https://www.recraft.ai/) - 一個 AI 工具，讓創作者輕鬆生成和迭代原創圖像、矢量藝術、插圖、圖標和 3D 圖形。

### 圖形設計

- [Brandmark](https://brandmark.io/) - 基於 AI 的標誌設計工具。
- [Gamma](https://gamma.app/) - 創建漂亮的演示文稿和網頁，無需格式化和設計工作。
- [Microsoft Designer](https://designer.microsoft.com/) - 快速創建令人驚嘆的設計。

### 圖像庫

- [Lexica](https://lexica.art/) - 穩定擴散搜索引擎。
- [OpenArt](https://openart.ai/) - 搜索超過 1000 萬個提示，並透過穩定擴散、DALL·E 2 生成 AI 藝術。
- [PromptHero](https://prompthero.com/) - 搜索穩定擴散、ChatGPT、Midjourney 等模型的提示。
- [PromptBase](https://promptbase.com/) - 搜索頂級提示工程師的提示。出售您自己的提示。

### 模型庫

- [Civitai](https://civitai.com/) - 社區驅動的 AI 模型共享工具。
- [Stable Diffusion Models](https://rentry.org/sdmodels) - rentry.org 上穩定擴散檢查點的綜合列表。

### 穩定擴散（Stable Diffusion）資源

- [Stable Horde](https://stablehorde.net/) - 一個眾包的分佈式穩定擴散工作者集群。
- [DiffusionDB](https://diffusiondb.com/) -
  穩定擴散的所有公共應用程式、開發工具、指南和插件列表。[Airtable 版本](https://airtable.com/shr0HlBwbw3nZ8Ht3/tblxOCylXV8ynh7ti)。
- [PublicPrompts](https://publicprompts.art/) - 穩定擴散的免費提示集合。
- [Stableboost](https://stableboost.ai/) - Stableboost 是一個穩定擴散 WebUI，讓您快速生成大量圖像以找到完美的圖像。
- [Hugging Face Diffusion Models Course](https://github.com/huggingface/diffusion-models-class) - [@huggingface](https://github.com/huggingface)
  提供的擴散模型在線課程的 Python 資料。

## 視頻

- [Runway](https://runwayml.com/) - 神奇的 AI 工具、實時協作、精確編輯等。您的下一代內容創作套件。
- [Synthesia](https://www.synthesia.io/) - 幾分鐘內從純文本創建視頻。
- [Rephrase AI](https://www.rephrase.ai/) - Rephrase 的技術支援大規模創建超個性化視頻，提升參與度和業務效率。
- [Hour One](https://hourone.ai/) - 將文本轉換為視頻，具有虛擬主持人，自動化。
- [Colossyan](https://www.colossyan.com/) - 專注於學習與發展的視頻創建工具。使用 AI 化身創建多語言教育視頻。
- [Fliki](https://fliki.ai/) - 使用 AI 驅動的語音幾分鐘內創建文本到視頻和文本到語音內容。
- [Pictory](https://pictory.ai/) - Pictory 的強大 AI 使您可以使用文本創建和編輯專業質量的視頻。
- [Pika](https://pika.art/) - 將您的創意轉化為動態的從想法到視頻的平台。
- [Sora](https://openai.com/sora) - 一個 AI 模型，可以根據文本指令創建現實和富有想像力的場景。
- [Luma Dream Machine](https://lumalabs.ai/dream-machine) - 一個 AI 模型，可以快速從文本和圖像生成高質量、逼真的視頻。
- [Infinity AI](https://infinity.ai/) - Infinity 是一個視頻基礎模型，允許您設計角色並將其賦予生命。
- [KLING AI](https://klingai.com/) - 用於創建富有想像力的圖像和視頻的工具。
- [Hailuo AI](https://hailuoai.video/) - AI 驅動的文本到視頻生成器。

### 化身

- [D-ID](https://www.d-id.com/) - 一鍵創建和互動化身。
- [HeyGen](https://app.heygen.com/) - 使用可定制的 AI 化身，幾分鐘內將腳本轉換為對話視頻。
- [RenderNet](https://rendernet.ai/) - RenderNet AI 是一個生成圖像和視頻的工具，提供對角色設計、構圖和風格的控制。

### 動畫

- [Wonder Dynamics](https://wonderdynamics.com/) - 輕鬆將 CG 角色動畫化、打光並合成到現場場景中。

## 音頻

### 文本到語音

- [Eleven Labs](https://beta.elevenlabs.io/) - AI 語音合成器。
- [Resemble AI](https://www.resemble.ai/) - AI 語音合成和語音克隆，用於文本到語音。
- [WellSaid](https://wellsaidlabs.com/) - 實時將文本轉換為語音。
- [Play.ht](https://play.ht/) - AI 語音合成器。使用 AI 在線生成逼真的文本到語音配音。將文本轉換為音頻。
- [podcast.ai](https://podcast.ai/) - 一個完全由人工智慧生成的播客，由 Play.ht 文本到語音 AI 提供支援。
- [VALL-E X](https://vallex-demo.github.io/) - 一個跨語言神經編解碼語言模型，用於跨語言語音合成。
- [TorToiSe](https://github.com/neonbjb/tortoise-tts) - 一個多語音文本到語音系統，訓練重點在於質量。#opensource
- [Bark](https://github.com/suno-ai/bark) - 一個基於變壓器的文本到音頻模型。#opensource

### 語音轉文字工具

- [Whisper](https://openai.com/index/whisper/) -
  透過大規模弱監督實現強大的語音識別。[#開放原始碼](https://github.com/openai/whisper)
- [Wispr Flow](https://wisprflow.ai/) - Flow 提供無縫的語音輸入，讓您在電腦上的任何應用程式中快速完成文字輸入。
- [Vibe Transcribe](https://thewh1teagle.github.io/vibe/) -
  一站式解決方案，輕鬆完成音訊和影片轉錄。[#開放原始碼](https://github.com/thewh1teagle/vibe)
- [whisper.cpp](https://github.com/ggerganov/whisper.cpp) - OpenAI Whisper 模型的 C/C++
  移植版本。[#開放原始碼](https://github.com/ggerganov/whisper.cpp)

### 音樂工具

- [Harmonai](https://www.harmonai.org/) - 我們是一個社群驅動的組織，推出開放原始碼的生成音訊工具，讓音樂製作變得更簡單且有趣。
- [Mubert](https://mubert.com/) - 為內容創作者、品牌和開發者提供無需支付版權費的音樂生態系統。
- [MusicLM](https://google-research.github.io/seanet/musiclm/examples/) - Google Research 開發的模型，能從文字描述生成高品質音樂。
- [AudioCraft](https://audiocraft.metademolab.com/) - Meta 提供的一站式生成音訊程式碼庫，包括 MusicGen 用於音樂生成，AudioGen
  用於聲音生成。[#開放原始碼](https://github.com/facebookresearch/audiocraft)
- [Stable Audio](https://stability.ai/stable-audio) - Stability AI 的首款音樂與音效生成產品。
- [AIVA](https://www.aiva.ai/) - 基於 AI 的音樂生成助手，提供超過 250 種風格選擇。
- [Suno AI](https://www.suno.ai/) - 任何人都能創作出優秀的音樂。不需要樂器，只需想像力，從您的想法到音樂。
- [Udio](https://www.udio.com/) - 發現、創作並與世界分享音樂。

## 其他工具

- [Diagram](https://diagram.com/) - 設計產品的全新魔法方式。
- [PromptBase](https://promptbase.com/) - 購買和出售高品質 DALL·E、GPT-3、Midjourney、Stable Diffusion 提示詞的市場。
- [This Image Does Not Exist](https://thisimagedoesnotexist.com/) - 測試您分辨圖像是由人類還是計算機生成的能力。
- [Have I Been Trained?](https://haveibeentrained.com/) - 檢查您的圖像是否被用於訓練流行的 AI 藝術模型。
- [AI Dungeon](https://aidungeon.io/) - 一款文字冒險故事遊戲，您可以指導（並主演），AI 將使其栩栩如生。
- [Clickable](https://www.clickable.so/) - 使用 AI 在幾秒內生成廣告。美觀、品牌一致且高轉化率的廣告，適用於所有行銷渠道。
- [Scale Spellbook](https://scale.com/spellbook) - 使用 Scale Spellbook 構建、比較和部署大型語言模型應用程式。
- [Scenario](https://www.scenario.com/) - AI 生成的遊戲資產。
- [Teleprompter](https://github.com/danielgross/teleprompter) - 一款為您的會議提供的設備端 AI，能聆聽您並提供富有魅力的語錄建議。
- [FinChat](https://finchat.io/) - 使用 AI，FinChat 為有關上市公司和投資者的問題生成答案。
- [Morpher AI](https://morpher.com/ai) - Morpher AI 提供任何市場的即時洞察和分析。
- [Whimsical AI](https://whimsical.com/ai) - 基於 GPT 的心智圖、流程圖和視覺工具，用於快速構思和流程組織。

## 學習資源

- [Learn Prompting](https://learnprompting.org/) - 一門免費的開放原始碼課程，教您如何與人工智慧進行交流。
- [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) - 提示詞工程的指南和資源。
- [ChatGPT prompt engineering for developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) -
  Isa Fulford（OpenAI）和 Andrew Ng（DeepLearning.AI）提供的短期課程。
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) - 使用 OpenAI API 的範例和指南。
- [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering) - 從大型語言模型獲得更好結果的策略和技巧。
- [PromptPerfect](https://promptperfect.jina.ai/) - 提示詞工程工具。
- [Anthropic courses](https://github.com/anthropics/courses) - Anthropic 提供的教育課程。

## 更多列表

- [Tools and Resources for AI Art](https://pharmapsychotic.com/tools.html) - [@pharmapsychotic](https://twitter.com/pharmapsychotic)
  提供的大量生成 AI 的 Google Colab 筆記本列表。
- [The Generative AI Application Landscape](https://twitter.com/sonyatweetybird/status/1584580362339962880) - Sequioa
  Capital 的 [Sonya Huang](https://twitter.com/sonyatweetybird) 提供的生成 AI 生態系統資訊圖。
- [Startups - @builtwithgenai](https://airtable.com/shr6nfE9FOHp17IjG/tblL3ekHZfkm3p6YT) - [@builtwithgenai](https://twitter.com/builtwithgenai)
  提供的 Airtable 列表。
- [The Generative AI Index](https://airtable.com/shrH4REIgddv8SzUo/tbl5dsXdD1P859QLO) - Scale Venture Partners 提供的
  Airtable 列表。
- [Generative AI for Games](https://twitter.com/gwertz/status/1593268767269670912) - [a16z](https://a16z.com/) 提供的生成
  AI 遊戲公司市場地圖。
- [Generative Deep Art](https://github.com/filipecalegario/awesome-generative-deep-art) - [@filipecalegario](https://github.com/filipecalegario)
  提供的生成深度學習工具、作品、模型等的精選列表。
- [GPT-3 Demo](https://gpt3demo.com/) - 展示 GPT-3 範例、演示、應用和 NLP 用例。
- [GPT-4 Demo](https://gpt4demo.com/) - GPT-4 應用和用例。
- [The Generative AI Landscape](https://github.com/ai-collection/ai-collection) - 精選的生成 AI 應用程式集合。
- [Molecular design](https://github.com/AspirinCode/papers-for-molecular-design-using-DL) - 使用生成 AI 和深度學習進行分子設計的列表。
- [Open LLMs](https://github.com/eugeneyan/open-llms) - 可商業使用的開放原始碼大型語言模型列表。

### ChatGPT 相關列表

- [Awesome ChatGPT](https://github.com/humanloop/awesome-chatgpt) - [@jordn](https://github.com/jordn) 提供的 ChatGPT 和
  GPT-3 的精選工具、演示和文檔列表。
- [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts) - ChatGPT 模型的提示詞範例集合。
- [FlowGPT](https://flowgpt.com/) - 使用最佳提示詞提升您的工作流程。
- [ChatGPT Prompts for Data Science](https://github.com/travistangvh/ChatGPT-Data-Science-Prompts) - ChatGPT
  數據科學提示詞的有用資源庫。
- [Awesome ChatGPT](https://github.com/sindresorhus/awesome-chatgpt) - 另一個 ChatGPT 的精選列表。
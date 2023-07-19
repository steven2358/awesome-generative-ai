# Awesome Generative AI [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of modern Generative Artificial Intelligence projects and services.

Generative Artificial Intelligence is a technology that creates original content such as images, sounds, and texts by using machine learning algorithms that are trained on large amounts of data. Unlike other forms of AI, it is capable of creating unique and previously unseen outputs such as photorealistic images, digital art, music, and writing. These outputs often have their own unique style and can even be hard to distinguish from human-created works. Generative AI has a wide range of applications in fields such as of art, entertainment, marketing, academia, and computer science.

Contributions to this list are welcome. Add links through [pull requests](https://github.com/steven2358/awesome-generative-ai/pulls) or create an [issue](https://github.com/steven2358/awesome-generative-ai/issues) to start a discussion.

## Contents

- [Recommended reading](#recommended-reading)
- [Text](#text)
- [Code](#code)
- [Image](#image)
- [Video](#video)
- [Audio](#audio)
- [Other](#other)
- [Learning resources](#learning-resources)
- [More lists](#more-lists)
- [Autonomous agents](#autonomous-agents)

## Recommended reading

- [How Large Language Models Will Transform Science, Society, and AI](https://hai.stanford.edu/news/how-large-language-models-will-transform-science-society-and-ai) - Article summarizing the capabilities and limitations of the GPT-3 model, and its potential impact on society. By Alex Tamkin and Deep Ganguli, February 5, 2021.
- [Generative AI: A Creative New World](https://www.sequoiacap.com/article/generative-ai-a-creative-new-world/) - A comprehensive examination of the generative AI industry, offering a historical perspective and in-depth analysis of the industry ecosystem. By Sonya Huang, Pat Grady and GPT-3, September 19, 2022.
- [A Coming-Out Party for Generative A.I., Silicon Valley's New Craze](https://www.nytimes.com/2022/10/21/technology/generative-ai.html) - Article about the rise of generative AI, particularly the success of the Stable Diffusion image generator, and the associated controversies. New York Times, October 21, 2022.
- [AI's New Creative Streak Sparks a Silicon Valley Gold Rush](https://www.wired.com/story/ais-new-creative-streak-sparks-a-silicon-valley-gold-rush/) - Article about the growing hype and investment in generative AI startups, with various industries exploring its potential applications. Wired, October 27, 2022.
- [ChatGPT Heralds an Intellectual Revolution](https://www.wsj.com/articles/artificial-intelligence-generative-ai-chatgpt-kissinger-84512912) - An op-ed by Henry Kissinger, Eric Schmidt and Daniel Huttenlocher. Wall Street Journal, February 24, 2023.

### Milestones

- [OpenAI API](https://openai.com/blog/openai-api/) - Announcement of the OpenAI API for text-to-text general-purpose AI models based on GPT-3. OpenAI blog, June 11, 2020.
- [GitHub Copilot](https://github.blog/2021-06-29-introducing-github-copilot-ai-pair-programmer/) - Announcement of Copilot, a new AI pair programmer that helps you write better code. GitHub blog, June 29, 2021.
- [DALL·E 2](https://openai.com/blog/dall-e-2/) - Announcement of the release of DALL·E 2, an advanced image generation system with improved resolution, expanded image creation capabilities, and various safety mitigations. OpenAI blog, April 6, 2022.
- [Stable Diffusion Public Release](https://stability.ai/blog/stable-diffusion-public-release) - Announcement of the public release of Stable Diffusion, an AI-based image generation model trained on a broad internet scrape and licensed under a Creative ML OpenRAIL-M license. Stable Diffusion blog, 22 August, 2022.
- [ChatGPT](https://openai.com/blog/chatgpt/) - Announcement of ChatGPT, a conversational model trained to answer follow-up questions, admit mistakes, challenge incorrect premises, and reject inappropriate requests. OpenAI blog, November 30, 2022.
- [Bing Search](https://blogs.microsoft.com/blog/2023/02/07/reinventing-search-with-a-new-ai-powered-microsoft-bing-and-edge-your-copilot-for-the-web/) - Microsoft announces a new version of its search engine Bing, powered by a next-generation OpenAI model. Microsoft blog, February 7, 2023.
- [GPT-4](https://openai.com/research/gpt-4) - Announcement of GPT-4, a large multimodal model. OpenAI blog, March 14, 2023.

## Text

### Models

- [OpenAI API](https://openai.com/api/) - OpenAI's API provides access to GPT-3 and GPT-4 models, which performs a wide variety of natural language tasks, and Codex, which translates natural language to code.
- [Gopher](https://www.deepmind.com/blog/language-modelling-at-scale-gopher-ethical-considerations-and-retrieval) - Gopher by DeepMind is a 280 billion parameter language model.
- [OPT](https://huggingface.co/facebook/opt-350m) - Open Pretrained Transformers (OPT) by Facebook is a suite of decoder-only pre-trained transformers. [Announcement](https://ai.facebook.com/blog/democratizing-access-to-large-scale-language-models-with-opt-175b/). [OPT-175B text generation](https://opt.alpa.ai/) hosted by Alpa.
- [Bloom](https://huggingface.co/docs/transformers/model_doc/bloom) - BLOOM by Hugging Face is a model similar to GPT-3 that has been trained on 46 different languages and 13 programming languages. #opensource
- [LLaMA](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/) - A foundational, 65-billion-parameter large language model by Meta. #opensource

### Chatbots

- [ChatGPT](https://chat.openai.com/chat) - ChatGPT by OpenAI is a large language model that interacts in a conversational way.
- [Bing Chat](https://www.bing.com/chat) - A conversational AI language model powered by Microsoft Bing.
- [Bard](https://bard.google.com) - An experimental AI chatbot by Google, powered by the LaMDA model.
- [Character.AI](https://character.ai/) - Character.AI lets you create characters and chat to them.
- [ChatPDF](https://www.chatpdf.com/) - Chat with any PDF.
- [ChatSonic](https://writesonic.com/chat) - An AI-powered assistant that enables text and image creation.

### Search engines

- [Perplexity AI](https://www.perplexity.ai/) - AI powered search tools.
- [Metaphor](https://metaphor.systems/) - Language model powered search.
- [Phind](https://phind.com/) - AI-based search engine.
- [You.com](https://you.com/) - A search engine built on AI that provides users with a customized search experience while keeping their data 100% private.

### Local search engines

- [privateGPT](https://github.com/imartinez/privateGPT) - Ask questions to your documents without an internet connection, using the power of LLMs.
- [quivr](https://github.com/StanGirard/quivr) - Dump all your files and chat with it using your generative AI second brain using LLMs & embeddings.

### Writing assistants

- [Jasper](https://www.jasper.ai/) - Create content faster with artificial intelligence.
- [Compose AI](https://www.compose.ai/) - Compose AI is a free Chrome extension that cuts your writing time by 40% with AI-powered autocompletion.
- [Rytr](https://rytr.me/) - Rytr is an AI writing assistant that helps you create high-quality content.
- [wordtune](https://www.wordtune.com/) - Personal writing assistant.
- [HyperWrite](https://hyperwriteai.com/) - HyperWrite helps you write with confidence and get your work done faster from idea to final draft.
- [Moonbeam](https://www.gomoonbeam.com/) - Better blogs in a fraction of the time.
- [copy.ai](https://www.copy.ai/) - Write better marketing copy and content with AI.
- [Anyword](https://anyword.com/) - Anyword's AI writing assistant generates effective copy for anyone.
- [Contenda](https://contenda.co/) - Create the content your audience wants, from content you've already made.
- [Hypotenuse AI](https://www.hypotenuse.ai/) - Turn a few keywords into original, insightful articles, product descriptions and social media copy.
- [Lavender](https://www.lavender.ai/) - Lavender email assistent helps you get more replies in less time.
- [Lex](https://lex.page/) - A word processor with artificial intelligence baked in, so you can write faster.
- [Jenni](https://jenni.ai/) - Jenni is the ultimate writing assistant that saves you hours of ideation and writing time.
- [LAIKA](https://www.writewithlaika.com/) - LAIKA trains an artificial intelligence on your own writing to create a personalised creative partner-in-crime.
- [QuillBot](https://quillbot.com) - AI-powered paraphrasing tool.
- [Postwise](https://postwise.ai/) - Write tweets, schedule posts and grow your following using AI.
- [Copysmith](https://copysmith.ai/) - AI content creation solution for Enterprise & eCommerce.

### ChatGPT extensions

- [WebChatGPT](https://chrome.google.com/webstore/detail/webchatgpt-chatgpt-with-i/lpfemeioodjbpieminkklglpmhlngfcn) - Augment your ChatGPT prompts with relevant results from the web.
- [GPT for Sheets and Docs](https://workspace.google.com/marketplace/app/gpt_for_sheets_and_docs/677318054654) - ChatGPT extension for Google Sheets and Google Docs.
- [YouTube Summary with ChatGPT](https://chrome.google.com/webstore/detail/youtube-summary-with-chat/nmmicjeknamkfloonkhhcjmomieiodli) - Use ChatGPT to summarize YouTube videos.
- [ChatGPT Prompt Genius](https://chrome.google.com/webstore/detail/chatgpt-prompt-genius/jjdnakkfjnnbbckhifcfchagnpofjffo) - Discover, share, import, and use the best prompts for ChatGPT & save your chat history locally.
- [ChatGPT for Search Engines](https://chrome.google.com/webstore/detail/chatgpt-for-search-engine/feeonheemodpkdckaljcjogdncpiiban) - Display ChatGPT response alongside Google, Bing, and DuckDuckGo search results.
- [ShareGPT](https://sharegpt.com/) - Share your ChatGPT conversations and explore conversations shared by others.
- [Merlin](https://merlin.foyer.work/) - ChatGPT Plus extension on all websites.
- [ChatGPT Writer](https://chatgptwriter.ai/) - Generate entire emails and messages using ChatGPT AI.
- [ChatGPT for Jupyter](https://github.com/TiesdeKok/chat-gpt-jupyter-extension) - Add various helper functions in Jupyter Notebooks and Jupyter Lab, powered by ChatGPT.
- [editGPT](https://www.editgpt.app/) - Easily proofread, edit, and track changes to your content in chatGPT.
- [Chatbot UI](https://www.chatbotui.com/) - An open source ChatGPT UI. [Source code](https://github.com/mckaywrigley/chatbot-ui).
- [Forefront](https://www.forefront.ai/) - A Better ChatGPT Experience.

### Productivity platforms

- [Mem](https://mem.ai/) - Mem is the world's first AI-powered workspace that's personalized to you. Amplify your creativity, automate the mundane, and stay organized automatically.
- [Taskade](https://www.taskade.com/) - Outline tasks, notes, generated structured lists and mind maps with Taskade AI.
- [Notion AI](https://www.notion.so/product/ai) - Write better, more efficient notes and docs.

### Meeting assistants

- [Otter.ai](https://otter.ai/) - A meeting assistant that records audio, writes notes, automatically captures slides, and generates summaries.
- [Cogram](https://www.cogram.com/) - Cogram takes automatic notes in virtual meetings and identifies action items.
- [Sybill](https://www.sybill.ai/) - Sybill generates summaries of sales calls, including next steps, pain points and areas of interest, by combining transcript and emotion-based insights.
- [Loopin AI](https://www.loopinhq.com/) - Loopin is a collaborative meeting workspace that not only enables you to record, transcribe & summaries meetings using AI, but also enables you to auto-organise meeting notes on top of your calendar.

### Academia

- [Elicit](https://elicit.org/) - Elicit uses language models to help you automate research workflows, like parts of literature review.
- [genei](https://www.genei.io/) - Summarise academic articles in seconds and save 80% on your research times.
- [Explainpaper](https://www.explainpaper.com/) - A better way to read academic papers. Upload a paper, highlight confusing text, get an explanation.
- [Galactica](https://galactica.org/) - A large language model for science. Can summarize academic literature, solve math problems, generate Wiki articles, write scientific code, annotate molecules and proteins, and more. [Model API](https://github.com/paperswithcode/galai).
- [Consensus](https://consensus.app/search/) - Consensus is a search engine that uses AI to find answers in scientific research.

### Other text generators

- [EmailTriager](https://www.emailtriager.com/) - Use AI to automatically draft email replies in the background.
- [AI Poem Generator](https://www.aipoemgenerator.org) - AI Poem Generator writes a beautiful rhyming poem for you on any subject, given a text prompt.

### Developer tools

- [co:here](https://cohere.ai/) - Cohere provides access to advanced Large Language Models and NLP tools.
- [Haystack](https://haystack.deepset.ai/) - A framework for building NLP applications (e.g. agents, semantic search, question-answering) with language models.
- [LangChain](https://langchain.com/) - A framework for developing applications powered by language models.
- [gpt4all](https://github.com/nomic-ai/gpt4all) - A chatbot trained on a massive collection of clean assistant data including code, stories and dialogue.
- [LMQL](https://lmql.ai/) - LMQL is a query language for large language models.

## Code

- [GitHub Copilot](https://github.com/features/copilot) - GitHub Copilot uses the OpenAI Codex to suggest code and entire functions in real-time, right from your editor.
- [OpenAI Codex](https://platform.openai.com/docs/guides/code/) - An AI system by OpenAI that translates natural language to code.
- [Ghostwriter](https://blog.replit.com/ai) - An AI-powered pair programmer by replit.
- [Amazon CodeWhisperer](https://aws.amazon.com/codewhisperer/) - Build applications faster with the ML-powered coding companion.
- [tabnine](https://www.tabnine.com/) - Code faster with whole-line & full-function code completions.
- [Stenography](https://stenography.dev/) - Automatic code documentation.
- [Mintlify](https://mintlify.com/) - AI powered documentation writer.
- [Debuild](https://debuild.app/) - AI-powered low-code tool for web apps.
- [AI2sql](https://www.ai2sql.io/) - With AI2sql, engineers and non-engineers can easily write efficient, error-free SQL queries without knowing SQL.
- [CodiumAI](https://www.codium.ai/) - With CodiumAI, you get non-trivial tests suggested right inside your IDE, so you stay confident when you push.
- [MutableAI](https://mutable.ai/) - AI Accelerated Software Development.
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) - Examples and guides for using the OpenAI API.
- [TurboPilot](https://github.com/ravenscroftj/turbopilot) - A self-hosted copilot clone which uses the library behind llama.cpp to run the 6 Billion Parameter Salesforce Codegen model in 4GiB of RAM.
- [ZZZ Code AI](https://zzzcode.ai) - AI-powered free website to get any programming question answered or code generated.

## Image

### Models

- [DALL·E 2](https://openai.com/dall-e-2/) - DALL·E 2 by OpenAI is a new AI system that can create realistic images and art from a description in natural language.
- [Stable Diffusion](https://huggingface.co/CompVis/stable-diffusion-v1-4) - Stable Diffusion by Stability AI is a state of the art text-to-image model that generates images from text. #opensource
- [Midjourney](https://www.midjourney.com/) - Midjourney is an independent research lab exploring new mediums of thought and expanding the imaginative powers of the human species.
- [Imagen](https://imagen.research.google/) - Imagen by Google is a text-to-image diffusion model with an unprecedented degree of photorealism and a deep level of language understanding.
- [Make-A-Scene](https://ai.facebook.com/blog/greater-creative-control-for-ai-image-generation/) - Make-A-Scene by Meta is a multimodal generative AI method puts creative control in the hands of people who use it by allowing them to describe and illustrate their vision through both text descriptions and freeform sketches.
- [DragGAN](https://github.com/XingangPan/DragGAN) - Drag Your GAN: Interactive Point-based Manipulation on the Generative Image Manifold.

### Services

- [Craiyon](https://www.craiyon.com/) - Craiyon, formerly DALL-E mini, is an AI model that can draw images from any text prompt.
- [DreamStudio](https://beta.dreamstudio.ai/) - DreamStudio is an easy-to-use interface for creating images using the Stable Diffusion image generation model.
- [Artbreeder](https://www.artbreeder.com/) - Artbreeder is new type of creative tool that empowers users creativity by making it easier to collaborate and explore.
- [GauGAN2](http://gaugan.org/gaugan2/) - GauGAN2 is a robust tool for creating photorealistic art using a combination of words and drawings since it integrates segmentation mapping, inpainting, and text-to-image production in a single model.
- [Magic Eraser](https://www.magiceraser.io/) - Remove unwanted things from images in seconds.
- [Imagine by Magic Studio](https://magicstudio.com/imagine) - A tool by Magic Studio that let's you express yourself by just describing what's on your mind.
- [Alpaca](https://www.getalpaca.io/) - Stable Diffusion Photoshop plugin.
- [Patience.ai](https://www.patience.ai/) - Patience.ai is an app for creating images with Stable Diffusion, a cutting edge AI developed by Stability.AI.
- [GenShare](https://www.genshare.io/) - Generate art in seconds for free. Own and share what you create. A multimedia generative studio, democratizing design and creativity.
- [Playground AI](https://playgroundai.com/) - Playground AI is a free-to-use online AI image creator. Use it to create art, social media posts, presentations, posters, videos, logos and more.
- [Pixelz AI Art Generator](https://pixelz.ai/) - Pixelz AI Art Generator enables you to create incredible art from text. Stable Diffusion, CLIP Guided Diffusion & PXL·E realistic algorithms available.
- [modyfi](https://www.modyfi.io/) - The image editor you've always wanted. AI-powered creative tools in your browser. Real-time collaboration.
- [Ponzu](https://www.ponzu.ai/) - Ponzu is your free AI logo generator. Build your brand with creatively designed logos in seconds, using only your imagination.
- [PhotoRoom](https://www.photoroom.com/) - Create product and portrait pictures using only your phone. Remove background, change background and showcase products.
- [Avatar AI](https://avatarai.me/) - Create your own AI-generated avatars.
- [ClipDrop](https://clipdrop.co/) - Create professional visuals without a photo studio.
- [Lensa](https://prisma-ai.com/lensa) - An all-in-one image editing app that includes the generation of personalized avatars using Stable Diffusion.
- [RunDiffusion](https://rundiffusion.com/) - Cloud-based workspace for creating AI-generated art.
- [ClipDrop](https://clipdrop.co/) - Create professional visuals without a photo studio, powered by

### Image libraries

- [Lexica](https://lexica.art/) - Stable Diffusion search engine.
- [Libraire](https://libraire.ai/) - The largest library of AI-generated images.
- [KREA](https://www.krea.ai/) - Explore millions of AI generated images and create collections of prompts. Featuring Stable Diffusion generations.
- [OpenArt](https://openart.ai/) - Search 10M+ of prompts, and generate AI art via Stable Diffusion, DALL·E 2.

### Model libraries

- [Civitai](https://civitai.com/) - Community driven AI model sharing tool.
- [Stable Diffusion Models](https://rentry.org/sdmodels) - A comprehensive list of Stable Diffusion checkpoints on rentry.org.

### Stable Diffusion resources

- [Stable Horde](https://stablehorde.net/) - A crowdsourced distributed cluster of Stable Diffusion workers.
- [DiffusionDB](https://diffusiondb.com/) - A list of all public apps, developer tools, guides and plugins for Stable Diffusion. [Airtable version](https://airtable.com/shr0HlBwbw3nZ8Ht3/tblxOCylXV8ynh7ti).
- [PublicPrompts](https://publicprompts.art/) - A collection of free prompts for Stable Diffusion.
- [Stableboost](https://stableboost.ai/) - Stableboost is a Stable Diffusion WebUI that lets you quickly generate a lot of images so you can find the perfect ones.
- [Hugging Face Diffusion Models Course](https://github.com/huggingface/diffusion-models-class) - Python materials for the online course on diffusion models by [@huggingface](https://github.com/huggingface).

## Video

- [RunwayML](https://runwayml.com/) - Magical AI tools, realtime collaboration, precision editing, and more. Your next-generation content creation suite.
- [Synthesia](https://www.synthesia.io/) - Create videos from plain text in minutes.
- [Rephrase AI](https://www.rephrase.ai/) - Rephrase's technology enables hyper-personalized video creation at scale that drive engagement and business efficiencies.
- [Hour One](https://hourone.ai/) - Turn text into video, featuring virtual presenters, automatically.
- [D-ID](https://www.d-id.com/) - Create and interact with talking avatars at the touch of a button.

## Audio

### Speech

- [Eleven Labs](https://beta.elevenlabs.io/) - AI voice generator.
- [Resemble AI](https://www.resemble.ai/) - AI voice generator and voice cloning for text to speech.
- [WellSaid](https://wellsaidlabs.com/) - Convert text to voice in real time.
- [Play.ht](https://play.ht/) - AI Voice Generator. Generate realistic Text to Speech voice over online with AI. Convert text to audio.
- [Coqui](https://coqui.ai/) - Generative AI for Voice.
- [podcast.ai](https://podcast.ai/) - A podcast that is entirely generated by artificial intelligence, powered by Play.ht text-to-voice AI.
- [VALL-E X](https://vallex-demo.github.io/) - A cross-lingual neural codec language model for cross-lingual speech synthesis.
- [TorToiSe](https://github.com/neonbjb/tortoise-tts) - A multi-voice text-to-speech system trained with an emphasis on quality. #opensource
- [Bark](https://github.com/suno-ai/bark) - A transformer-based text-to-audio model. #opensource

### Music

- [Harmonai](https://www.harmonai.org/) - We are a community-driven organization releasing open-source generative audio tools to make music production more accessible and fun for everyone.
- [Mubert](https://mubert.com/) - A royalty-free music ecosystem for content creators, brands and developers.
- [MusicLM](https://google-research.github.io/seanet/musiclm/examples/) - A model by Google Research for generating high-fidelity music from text descriptions.

## Other

- [Diagram](https://diagram.com/) - Magical new ways to design products.
- [PromptBase](https://promptbase.com/) - A marketplace for buying and selling quality prompts for DALL·E, GPT-3, Midjourney, Stable Diffusion.
- [This Image Does Not Exist](https://thisimagedoesnotexist.com/) - Test your ability to tell if an image is human or computer generated.
- [Have I Been Trained?](https://haveibeentrained.com/) - Check if your image has been used to train popular AI art models.
- [AI Dungeon](https://aidungeon.io/) - A text-based adventure-story game you direct (and star in) while the AI brings it to life.
- [Clickable](https://www.clickable.so/) - Generate ads in seconds with AI. Beautiful, brand-consistent, and highly converting ads for all marketing channels.
- [Scale Spellbook](https://scale.com/spellbook) - Build, compare, and deploy large language model apps with Scale Spellbook.
- [Scenario](https://www.scenario.com/) - AI-generated gaming assets.
- [Brandmark](https://brandmark.io/) - AI-based logo design tool.
- [Teleprompter](https://github.com/danielgross/teleprompter) - An on-device AI for your meetings that listens to you and makes charismatic quote suggestions.
- [Gamma](https://gamma.app/) - Create beautiful presentations and webpages with none of the formatting and design work.
- [FinChat](https://finchat.io/) - Using AI, FinChat generates answers to questions about public companies and investors.

## Learning resources

- [Learn Prompting](https://learnprompting.org/) - A free, open source course on communicating with artificial intelligence.
- [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) - Guide and resources for prompt engineering.
- [ChatGPT prompt engineering for developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) - A short course by Isa Fulford (OpenAI) and Andrew Ng (DeepLearning.AI).
  [OpenAI Cookbook](https://github.com/openai/openai-cookbook) - Examples and guides for using the OpenAI API.

## More lists

- [Tools and Resources for AI Art](https://pharmapsychotic.com/tools.html) - A large list of Google Colab notebooks for generative AI, by [@pharmapsychotic](https://twitter.com/pharmapsychotic).
- [The Generative AI Application Landscape](https://twitter.com/sonyatweetybird/status/1584580362339962880) - An infographic that maps the generative AI ecosystem, by [Sonya Huang](https://twitter.com/sonyatweetybird) of Sequioa Capital.
- [Startups - @builtwithgenai](https://airtable.com/shr6nfE9FOHp17IjG/tblL3ekHZfkm3p6YT) - An Airtable list by [@builtwithgenai](https://twitter.com/builtwithgenai).
- [The Generative AI Index](https://airtable.com/shrH4REIgddv8SzUo/tbl5dsXdD1P859QLO) - An Airtable list by [Scale Venture Partners](https://www.scalevp.com/generative-ai).
- [Generative AI for Games](https://twitter.com/gwertz/status/1593268767269670912) - A market map of companies working on Generative AI for games, by [a16z](https://a16z.com/).
- [Generative Deep Art](https://github.com/filipecalegario/awesome-generative-deep-art) - A curated list of generative deep learning tools, works, models, etc. for artistic uses, by [@filipecalegario](https://github.com/filipecalegario/).
- [GPT-3 Demo](https://gpt3demo.com/) - Showcase with GPT-3 examples, demos, apps, showcase, and NLP use-cases.
- [GPT-4 Demo](https://gpt4demo.com/) - GPT-4 apps and use-cases.
- [The Generative AI Landscape](https://github.com/ai-collection/ai-collection) - A Collection of Awesome Generative AI Applications.
- [Molecular design](https://github.com/AspirinCode/papers-for-molecular-design-using-DL) - List of molecular design using Generative AI and Deep Learning.
- [Open LLMs](https://github.com/eugeneyan/open-llms) - A list of open LLMs available for commercial use.

### Lists on ChatGPT

- [Awesome ChatGPT](https://github.com/humanloop/awesome-chatgpt) - A curated list of awesome tools, demos, docs for ChatGPT and GPT-3, by [@jordn](https://github.com/jordn).
- [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts) - A collection of prompt examples to be used with the ChatGPT model.
- [FlowGPT](https://flowgpt.com/) - Amplify your workflow with the best prompts.
- [ChatGPT Prompts for Data Science](https://github.com/travistangvh/ChatGPT-Data-Science-Prompts) - A repository of useful data science prompts for ChatGPT.

## Autonomous agents

- [Auto-GPT](https://github.com/Torantulino/Auto-GPT) - An experimental open-source attempt to make GPT-4 fully autonomous.
- [babyagi](https://github.com/yoheinakajima/babyagi) - An AI-powered task management system.
- [AgentGPT](https://github.com/reworkd/AgentGPT) - Assemble, configure, and deploy autonomous AI Agents in your browser.
- [GPT Engineer](https://github.com/AntonOsika/gpt-engineer) - Specify what you want it to build, the AI asks for clarification, and then builds it.

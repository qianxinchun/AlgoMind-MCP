# AlgoMind-MCP

The goal is to create an MCP (Model Context Protocol) server designed to aid in the reproducibility and understanding of machine learning research, spanning areas like large language models, computer vision, multimodal learning, and reinforcement learning. This server, built upon a Cursor+MCP framework, will facilitate deeper comprehension and optimization of algorithms by leveraging research papers, their references, and associated open-source code.

Key functionalities of the MCP server include:

  - 1. Paper Parsing: Converting research papers into structured formats like Markdown.
  
  - 2. Reference Retrieval: Fetching and parsing cited papers (also into Markdown).
  
  - 3. Code Repository Acquisition: Identifying and retrieving links to code repositories associated with the paper and its references. Some resources for this include Papers With Code, GitHub, and Zenodo.
  
  - 4. Database Construction: Building a searchable database comprising the paper, its references, and the associated code.
  
  - 5. Related Resource Discovery: Searching the web for related research, technical blogs, open-source implementations, and even explanatory videos (e.g., from YouTube), then processing and understanding this supplementary content.
  
  - 6. Idea Exploration Support: Assisting users in exploring their own research ideas by automatically searching for related papers, algorithms, and code repositories.
  
  - 7. Multi-LLM Support: Allowing to choose from different models, cloud-based or self-hosted.

In essence, this MCP server acts as a centralized hub for researchers to access, analyze, and implement cutting-edge machine learning concepts, promoting reproducibility and accelerating innovation.


## References

- [一个 从信息的获取 到扩展 最后到反思 分享 回顾的方法 可以看下面的图片 结合google deep search（获取更多知识） + ppt/网页生成（3.7+乔木大佬提示词） + notebooklm（音频/问答） + refly（创作/回顾](https://x.com/lee04052822/status/1901312078540931570)
  - ![](https://pbs.twimg.com/media/GmLRPFWagAEspK3?format=jpg&name=4096x4096)
- [四个Prompt，支持生成PPT、生产3D教学动画、生成SVG海报等。](https://x.com/vista8/status/1901224129405338102)

## speech generation
- [sesame/csm-1b](https://huggingface.co/sesame/csm-1b)

## MCP
- [mcphub.nvim](https://github.com/ravitemer/mcphub.nvim)



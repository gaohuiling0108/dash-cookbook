<p align="center">
    <h1>Dash-CookBook</h1>
<p>

# Introduction

Dash-CookBook is the repository for sharing various receipts 
to complete different tasks using DashScope APIs and other API
services such as the vector-store DashVector.


## 🚀 DashScope
[DashScope](https://dashscope.aliyun.com/) aims to provide the efficient API services backed by
the state-of-the-art models in different areas, including LLM,
text-to-image, embedding, text-to-speech etc. Visit the official
[DashScope website](https://dashscope.aliyun.com/) for a complete
list of models supported. 

## 🚀 DashVector
[DashVector](https://www.aliyun.com/activity/intelligent/DashVector) is a fully-managed 
vectorDB service that supports 
high-dimension dense and sparse vectors, real-time insertion 
and filtered search. It is built to scale automatically and can 
adapt to different application requirements. It is currently
integrated into 🦜️🔗[LangChain](https://python.langchain.com/docs/integrations/vectorstores/dashvector) as well.

# ✨Examples
This repository will host examples for accomplishing various tasks by
leveraging the aforementioned API services. Most examples are presented
via Colab notebook and are executable _right out of the box_ (once you have the API-key 
for the underlying API services).

- Basic semantic search built with Text-Embedding and VectorDB APIs: [![Open In PAI-DSW](https://modelscope.oss-cn-beijing.aliyuncs.com/resource/open-in-dsw.png)](https://gallery.pai-ml.com/#/import/https%3A%2F%2Fgithub.com%2Fdashscope%2Fdash-cookbook%2Fblob%2Fmain%2Fexamples%2Fbasic_semantic_search.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dashscope/dash-cookbook/blob/main/examples/basic_semantic_search.ipynb)
- Question-answering with LLM and knowledge-enhancement:  [![Open In PAI-DSW](https://modelscope.oss-cn-beijing.aliyuncs.com/resource/open-in-dsw.png)](https://gallery.pai-ml.com/#/import/https%3A%2F%2Fgithub.com%2Fdashscope%2Fdash-cookbook%2Fblob%2Fmain%2Fexamples%2FvectorDB_enhanced_QA_with_LLM.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dashscope/dash-cookbook/blob/main/examples/vectorDB_enhanced_QA_with_LLM.ipynb)
- Finetuning LLM to generate advertisement for e-commerce: [![Open In PAI-DSW](https://modelscope.oss-cn-beijing.aliyuncs.com/resource/open-in-dsw.png)](https://gallery.pai-ml.com/#/import/https%3A%2F%2Fgithub.com%2Fdashscope%2Fdash-cookbook%2Fblob%2Fmain%2Fexamples%2Ffinetune_LLM_for_advertisement_generation_sdk_api.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dashscope/dash-cookbook/blob/main/examples/finetune_LLM_for_advertisement_generation_sdk_api.ipynb)
- Image Generation using LLM-enhanced prompt:   [![Open In PAI-DSW](https://modelscope.oss-cn-beijing.aliyuncs.com/resource/open-in-dsw.png)](https://gallery.pai-ml.com/#/import/https%3A%2F%2Fgithub.com%2Fdashscope%2Fdash-cookbook%2Fblob%2Fmain%2Fexamples%2Fimage_generation_with_LLM_enhanced_prompt.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dashscope/dash-cookbook/blob/main/examples/image_generation_with_LLM_enhanced_prompt.ipynb)
- ... stay tuned for more examples, contribution also welcome!

## 💁Contributing
If there are examples you'd like to see, feel free to [open an issue](https://github.com/dashscope/dash-cookbook/issues). 
Quality examples are also welcome via pull request, please provide a ipynb implementation following existing examples.





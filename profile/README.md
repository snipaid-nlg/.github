<img src="/profile/snipaid.png" width="400px" />

## ✍🏼 Hi there and welcome to our space 

We build a tool that generates text snippets from journalistic texts.

https://user-images.githubusercontent.com/36483428/217799289-7479b6ab-73fd-4a6f-ae20-35a7e76458ab.mp4

### Why Text Snippets?

There are various text snippets for journalistic texts online. To name just a few:

- title and teaser
- social media posts
- newsletter summaries
- search engine result page texts

They all target a different audience, have different length and style. Writing them is tedious work. \
SnipAId automates this process to free up time for the writer!

### Repository Index

Here's a brief guide to our repositories and what's inside.

Model server:
- 🤖 [gptj-model-server](https://github.com/snipaid-nlg/gptj-model-server): A http server for our finetuned GPT-J model.
- 🌸 [bloomz-model-server](https://github.com/snipaid-nlg/bloomz-model-server): A http server for BLOOMZ model with translation.
- 🦔 [snip-igel-model-server](https://github.com/snipaid-nlg/snip-igel-model-server): A http server for our instruction fine-tuned IGEL model snip-igel model.

Webapp:
- 💻 [web-app](https://github.com/snipaid-nlg/web-app): A web app editor that generates title and teaser snippets for you.
- 🔗 [demo](https://github.com/snipaid-nlg/demo): A demo that can be hosted with netlify.

Plugins:
- 🧩 [wp-plugin](https://github.com/snipaid-nlg/wp-plugin): A wordpress plugin to receive text and snippets from the webapp.


Ressources and training:
- 🧠 [models](https://github.com/snipaid-nlg/models): A collection of available large language models for natural language generation.
- 📄 [datasets](https://github.com/snipaid-nlg/datasets)
- ⚗️ [gptj-model-tuning](https://github.com/snipaid-nlg/gptj-model-tuning): A collection of jupyter notebooks for GPT-J finetuning.
- 🦾 [igel-lora-finetune](https://github.com/snipaid-nlg/igel-lora-finetune-news-snippets): A repository for parameter-efficient instruction fine-tuning of IGEL with LoRA adapters.

## 🎉 Live Demo

Our demo is live at [snipaid.tech](https://snipaid.tech). \
Check it out and generate some snippets yourself.

### Currently supported features

| | GPT-J | BLOOMZ | Snip-IGEL |
|---|---|---|---|
| headline | ✅ | ✅ | ✅ |
| teaser | ✅ | ✅ | ✅ |
| summary | ❌ | ✅ | ✅ |
| keywords | ❌ | ✅ | ✅ |
| SERP | ❌ | ❌ | ✅ |
| tweet | ❌ | ❌ | ✅ |

+ Wordpress Integration

## 📝 Blog

Our [blog](https://snipaid-nlg.github.io/) is the place for you, if you want to tag along on our learning journey. Over there we write about open source large language models and approaches on how to use them to assist the journalistic production process with generative AI.

## 💸 Sponsors

SnipAId is kindly funded by \
<a href="https://media-tech-lab.com">Media Tech Lab by Media Lab Bayern</a> (<a href="https://github.com/media-tech-lab">@media-tech-lab</a>)

<img src="https://github.com/media-tech-lab/.github/blob/main/assets/mtl-powered-by.png" width="240" title="Media Tech Lab powered by logo">

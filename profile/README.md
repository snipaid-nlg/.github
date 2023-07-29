<picture>
  <source
    srcset="/profile/logo-dark.png"
    media="(prefers-color-scheme: dark)"
  />
  <img
    src="/profile/logo-light.png"
    alt="Logo: Brain with green-wired synapses, next to it the text 'SnipAId'"
    width="400px"
  />
</picture>

## ✍🏼 Hi there and welcome to our space 

We built a tool that generates text snippets from journalistic texts.

https://github.com/snipaid-nlg/.github/assets/36483428/6d51b2fd-bd28-41c5-bc1b-510e99c322da


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
- 📄 [datasets](https://github.com/snipaid-nlg/datasets): A collecting of datasets and notebooks for evaluation.
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

Our [blog](https://snipaid-nlg.github.io/) is the place for you, if you want to read up on our learning journey. Over there we wrote about open source large language models and approaches on how to use them to assist the journalistic production process with generative AI.

## 💸 Sponsors

SnipAId is kindly funded by \
<a href="https://media-tech-lab.com">Media Tech Lab by Media Lab Bayern</a> (<a href="https://github.com/media-tech-lab">@media-tech-lab</a>)

<img src="https://github.com/media-tech-lab/.github/blob/main/assets/mtl-powered-by.png" width="240" title="Media Tech Lab powered by logo">

<a target="_blank" rel="noopener noreferrer" href="https://www.promptai.us">
  <img src="./image/main.png" alt="https://www.promptai.us" style="max-width: 100%;">
</a>

<p align="center">
  <a href="https://www.promptai.us">Website</a> ·
  <a href="mailto:info@promptai.us">Email</a> 
</p>

## Introduction

This repository contains installation and usage documentation for PromptDialog 1.0, providing instructions for local deployment and usage. This repository is no longer being updated. Our [PromptDialog 2.0](https://www.promptai.us) is now providing services.

PromptDialog1.0 supports Rasa, ChatGPT and GPT4, together with a design/testing/deployment environment (an alternative of Rasa-X and Rasa-Pro).  With PromptDialog, we aim to bring you an AI experience with the latest LLMs technology and significant reduction (90%) of development cost.
When you are using Rasa Open Source, you might be disappointed by the lack of Large Language Models’ support (LLMs) and the missing of Rasa-X that provides low code user interface for data annotation and model training.  When you are using ChatGPT/GPT4, you might be concerned on how to embed your own business logic in GPT4.  This is exactly what we experienced when building AI assistants for financial institutes and car manufacturers.  PromptDialog solves both problems by enabling GPT4 in RASA Open Source.  And the most important, it is free!  Here are a few highlights:

[PromptDialog 2.0](https://www.promptai.us) is the new version transitioned to [MICA](https://github.com/Mica-labs/MICA), as we believe that agent-based architecture represents the future of bot development. In [PromptDialog 2.0](https://www.promptai.us), everything revolves around agents—eliminating the need for separate NLU, state management, and response generation. The new approach not only simplifies development but also makes advanced downstream tasks possible such as automated testing and evaluation.

* Automatically turn enterprise documents of various forms (FAQ, CSV, PDF, Doc, Text, HTML) into one knowledge base that your assistant can rely on, powered by GPT ([talk2bits.com](https://talk2bits.com)).
* Intuitive business logic design. The dialog flows can be drawn explicitly, not as vague as annotated conversations or python programs any more.  It can be displayed and shared with your team members.
* All-in-one DevOps: Design, develop and operate conversations, on premises or cloud, in one platform.
* Zero shot intent classification and entity recognition, less or even no annotation required.

## Installation and Running

### Running PromptDialog 1.0 Documentation:
```shell
docker-compose up 
```

Open [http://localhost:4000](http://localhost:4000) in your browser.

### Local Installation of PromptDialog 1.0 Service:
```shell
curl -o install.sh 'https://cdn.githubraw.com/PromptAI/homepage/main/scripts/install_en.sh' && chmod +x install.sh && ./install.sh
```

After running, you can access the PromptDialog app in your browser at [http://localhost:9000](http://localhost:9000).

Detailed installation instructions: [Install PromptDialog 1.0](https://cdn.githubraw.com/PromptAI/homepage/main/scripts/install_en.sh)*

## Contact Us
If you have any questions, suggestions, or partnership inquiries, feel free to contact us through the following channels:
- Submit an Issue or PR on our GitHub Repo
- Send an email to info@promptai.us
  - Send a message to [there](https://www.promptai.us/en/contact/)

## Security
To protect your privacy, please avoid posting security issues on GitHub. Instead, send your questions to info@promptai.us and we will provide you with a more detailed answer.

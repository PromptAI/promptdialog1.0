---
layout: en
title: RASA
nav_order: 19
show: false
---

# RASA
{: .no_toc .header }

----

We are a group of RASA talk open source system enthusiasts. RASA is used to realize the dialogue robot in various scenes of finance, auto industry and government affairs. Thanks to the open architecture of RASA, our system can easily surpass similar closed source systems. In view of RASA engineering experience, we to simplify, contribute to the community, the world exclusive release based on RASA brain map no code programming tools, whether you are familiar with RASA, can be a minimalist dialogue system, within half an hour to complete a dialogue design, and online. You can also download the generated RASA file for free, private deployment.

## Visual design tools
[https://www.promptai.us/](https://www.promptai.us/)
PROMPT AI is a website that uses mind mapping to achieve dialogue process design. With a visual interface, it can use simple operations to design project files compatible with rasa and automatically deploy them online. The website interface has a download function, which can translate the edited dialogue into rasa projects, including configuration, nlu, story data, modification, training, operation and deployment in the local environment.
## Official information

1. Rasa Official Document

[https://rasa.com/docs/rasa/](https://rasa.com/docs/rasa/)
The documents provided on Rasa's official website contain detailed instructions from installation to deployment and the main changes of each major version. Every major version of Rasa has major changes, such as data format adjustment from `markdown` to `yaml` format and `domain. yml` file; There are detailed descriptions in the official documents.

2. Official sample of Rasa

[https://github.com/RasaHQ/rasa/tree/main/examples](https://github.com/RasaHQ/rasa/tree/main/examples)
Several examples are given in Rasa's official code base. The Rasa team also has a relatively large example bot, sara, which is in a separate code warehouse. However, because the sara bot itself has a lot of content, it is more suitable for beginners to learn. The examples in the Rasa code base are relatively small, which is suitable for beginners to learn the small functions in the Rasa framework. In addition, it should be noted that since Rasa iterations are frequent and the data format is constantly changing, the corresponding version number needs to be selected, otherwise various problems may occur; In addition, during actual learning, we found that in some examples, the configuration file `config. yml` needs to be modified slightly before it can be used. Please note this.

3. Rasa Blog

[https://rasa.com/blog/](https://rasa.com/blog/)
Rasa official blog link. In the blog, Rasa developers will introduce the implementation logic and design ideas behind the corresponding technologies. These blogs are worth referring to when you need to understand Rasa in depth.

4. Official Forum

[https://forum.rasa.com/](https://forum.rasa.com/)
Here you can find some users' actual use problems, and the official team will also maintain the page. If you use an earlier version of Rasa, it is easier to find the answer here.

## Non official/Chinese bot data
The following are some unofficial materials. If there are other public materials, please contact us and we will add them in time.

1. Rasa Chinese Chat Robot Development Guide

[https://jiangdg.blog.csdn.net/article/details/104328946](https://jiangdg.blog.csdn.net/article/details/104328946)
Personally, I think the blog translation of this series is relatively accurate and easy to understand. After reading these articles, I should have a preliminary understanding of the Rasa framework and be able to build a basic dialogue robot. The author has finished introducing the main parts of the Rasa framework, including the installation instructions, NLU and CORE. This series is worth seeing.

2. Github Personal Project – based on Rasa v2. x

[https://github.com/Dustyposa/rasa_ch_faq](https://github.com/Dustyposa/rasa_ch_faq)
In addition to using the functions provided by rasa, the rasa project with high quality also has other customized functions, such as custom action, custom pipeline, etc. If necessary, it can be designed according to the author's design ideas.

3. Github Personal Project – based on Rasa v1. x

[https://github.com/GaoQ1/rasa_chatbot_cn](https://github.com/GaoQ1/rasa_chatbot_cn)
The author wrote a series of blog posts and provided his project documents with high quality. The overall project is based on Rasa v1.10. If you are using the Rasa v1. x series, you can rest assured to refer to this project.

4. Rasa Book

https://github.com/Chinese-NLP-book/rasa_chinese_book_code

Based on Rasa v3.0, the book systematically explains the principles of the Rasa framework, how to build bots in different scenarios, and the high concurrency support of Rasa, which is helpful for the industrial use of Rasa.

5. Rasa 3 installation and introduce

https://mp.weixin.qq.com/s/hyXp_fgu5FJ0q1cBERGXFw

The author introduced in detail how to install (including docker) and some basic concepts of getting started with Rasa
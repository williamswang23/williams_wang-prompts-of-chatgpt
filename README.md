# Williams' prompts of chatgpt
William's prompts of chatgpt

公有prompts仓库：[Awesome ChatGPT Prompts | This repo includes ChatGPT prompt curation to use ChatGPT better.](https://prompts.chat/)

私有补充prompts仓库：

- [Williams' prompts of chatgpt](#williams-prompts-of-chatgpt)
  - [英文学习](#英文学习)
    - [GRE](#gre)
    - [雅思英文写作](#雅思英文写作)
    - [口语对话练习](#口语对话练习)
    - [雅思口语对话练习](#雅思口语对话练习)
  - [搜索](#搜索)
    - [一般规则](#一般规则)

## 英文学习

### GRE
1. 词源
``` markdown
词源规则： 请根据我输入的英文词汇，列举出该单词的以下内容： 1. 词源，； 2. 词根词缀； 3. memory tips;  4. example sentences.  我可能输入一个或者多个英文单词，如果我输入多个英文单词，我会用逗号将不同的单词隔开。 如果我输入的是多个英文单词，那么你要按照以下顺序输出： 首先输出第一个单词的词源， 词根词缀， memory tips, example sentences.  然后按照这个格式输出第二个单词的内容，以此类推。
```

2.  近义词
``` markdown
近义词规则：我接下来会提交一个英文单词。请你在GRE单词范围内，按照考试出现频率高低排序，给出我提交的英文的5到10个近义词。 你需要输出每个近义词的以下内容： 1. 该近义词的英文拼写； 2. 该近义词的国际音标； 3. 该近义词的中文解释； 4， 该近义词的英文example sentences.
```

3. 形近词
``` markdown
形近词规则： 我接下来会输入一组关键字。请你在GRE单词范围内，按照考试出现频率高低排序，给出我提交的英文的5到10个包含我输入的关键字的单词。你需要输出每个单词的以下内容： 1. 该单词词的英文拼写； 2. 该单词的国际音标； 3. 该单词的中文解释； 4， 该单词的英文example sentences.
```

4. 词汇对比
``` md
单词对比规则：接下来我将输入几个英文单词，每个英文单词之间用逗号隔开。请在每个单词前面加上关键词"cp.."，作为触发单词对比的关键词，格式为："cp.. 单词1, 单词2, ..."。你需要输出以下内容：1. 每个单词在英文写作上的区别； 2. 该单词的example sentence.
例如，输入 "cp.. jubilation, happy"，你需要理解关键词"cp.."表示需要进行单词对比，然后输出 "jubilation" 和 "happy" 的区别，以及它们的example sentence。
```

``` md
Word Comparison Rule: I will be providing you with several English words separated by commas. Please use the trigger keyword "cp.." before each word to indicate that a comparison is required. The format is as follows: "cp.. word1, word2, ...". Your task is to output the following: 1. The differences in the written form of each word; 2. An example sentence for each word.
For example, if I input "cp.. jubilation, happy", you should understand that "cp.." is the trigger keyword for word comparison and output the differences between "jubilation" and "happy" in their written form, as well as an example sentence for each word.
```

### 雅思英文写作

``` markdown
接下来我将输入雅思作文的题目，和对应的文本。 你的任务是基于雅思考试写作部分的要求，改进所提供文本的拼写、语法、清晰、简洁和整体可读性，同时分解长句，减少重复，并提供改进建议。请提供文本的更正版本，可以包括改进建议。改进的目标是雅思写作7分及以上的标准。
```

``` mardown
Next, I will provide an IELTS essay prompt and the corresponding text. Your task is to improve the spelling, grammar, clarity, conciseness, and overall readability of the provided text, while breaking down long sentences, reducing redundancy, and providing improvement suggestions. The goal is to achieve an IELTS Writing score of 7 or above.
```
### 口语对话练习
``` marddown
I want you to act as a spoken English teacher and improver. I will speak to you in English and you will reply to me in English to practice my spoken English. I want you to keep your reply neat, limiting the reply to 100 words. I want you to strictly correct my grammar mistakes, typos, and factual errors. I want you to ask me a question in your reply. Now let’s start practicing, you could ask me a question first. Remember, I want you to strictly correct my grammar mistakes, typos, and factual errors.
```

### 雅思口语对话练习
``` markdown
我希望你能担任我的英语口语老师和提高者。我们将用英语进行对话，你将用英语回答我的问题，以帮助我提高口语能力。请保持回答简明扼要，并将回答限制在200字以内。我希望你能认真纠正我的语法、拼写和事实性错误，以帮助我更好地提高口语水平。请注意，我希望你能严格纠正我的语法、拼写和事实性错误。我们的口语目标分数是7分以上，评分标准是基于雅思口语考试的要求。我们将练习基于雅思口语考试的题目，请等待我提交本次练习的题目。
```
``` md
I would like you to act as my English speaking teacher and coach. I will be speaking to you in English, and you will be responding to me in English to help me practice my speaking skills. Please keep your responses concise and limited to 200 words or less. I would appreciate it if you could correct any grammar mistakes, spelling errors, and factual inaccuracies to help me improve my speaking ability. Please remember that I am looking for strict corrections on my grammar, spelling, and factual inaccuracies. Our speaking target score is a 7 or above on the IELTS speaking exam criteria. We will be practicing topics based on the IELTS speaking exam, and I will provide the topic for our practice.
```

## 搜索
### 一般规则
``` markdown
规则： 你现在作为一个搜索引擎，根绝我输入的关键词，返回以下内容： 1. 搜索我输入的关键词，并显示与其相关的搜索结果。这些搜索结果可能包括相关网页、新闻文章、图片、视频等； 2.为了帮助我更深入地了解搜索结果，你将尽可能提供对应的参考链接，这些链接可能是指向类似维基百科、学术期刊、博客等可信来源的页面。这些参考链接可能包含更多相关信息、深入的解释、数据支持等。
```

``` markdown
Rule: As a search engine, based on the keywords you input, I will provide the following contents: 1. Search the keywords you input and display related search results, including relevant web pages, news articles, images, videos, etc. 2. To help you better understand the search results, I will provide corresponding reference links as much as possible, which may point to reliable sources such as Wikipedia, academic journals, blogs, etc. These reference links may contain more related information, in-depth explanations, data support, etc.
```



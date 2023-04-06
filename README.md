# Datasets for Instruction Fine-Tuning

Since training LLMs on consumer-level GPUs is the trend, but we're still lack of larger high-quality instruction datasets. 
Although some tasks requires private knowledge datasets with professions experiences, which has concern of data privacy, but it's still worth to let them know how to transfer him/her knowledge into instruction datasets and finetune on LLMs.

有鑒於可在消費級顯卡上訓練及運行的大型語言模型的相關研究已經逐漸清晰，但大量且高品質的指令資料集尚未被很好的提供；儘管有些資料集屬於私有領域知識、經驗累積，有使用權上的疑慮；如果讓知識擁有者也能了解怎麼利用自己的知識的打造智能助理，也是未來趨勢之一。這就是本專案的目的。


## Code Generation
- [CodeSearchNet](https://github.com/github/CodeSearchNet#data-details) | [CodeXGLUE](https://github.com/facebookresearch/CodeGen/blob/main/CodeXGLUE/Code-Text/code-to-text/README.md)
- [DS-1000](https://github.com/HKUNLP/DS-1000)
- [ConCode](https://github.com/sriniiyer/concode)(步驟比較多)
- [code-docstring-corpus](https://github.com/EdinburghNLP/code-docstring-corpus)(資料格式不確定)

## General Knowledge

### Huggingface
- [xtreme](https://huggingface.co/datasets/xtreme/viewer/MLQA.zh.zh/validation)

The Cross-lingual TRansfer Evaluation of Multilingual Encoders (XTREME) benchmark is a benchmark for the evaluation of the cross-lingual generalization ability of pre-trained multilingual models. 
The Cross-lingual Natural Language Inference (XNLI) corpus is a crowd-sourced collection of 5,000 test and 2,500 dev pairs for the MultiNLI corpus. The pairs are annotated with textual entailment and translated into 14 languages: French, Spanish, German, Greek, Bulgarian, Russian, Turkish, Arabic, Vietnamese, Thai, Chinese, Hindi, Swahili and Urdu.

- [clips/mqa](https://huggingface.co/datasets/clips/mqa/viewer/zh-all-question/train)

MQA is a Multilingual corpus of Questions and Answers (MQA) parsed from the Common Crawl. Questions are divided in two types: Frequently Asked Questions (FAQ) and Community Question Answering (CQA).

- [mlqa](https://huggingface.co/datasets/mlqa/viewer/mlqa.zh.zh/test)

MLQA (MultiLingual Question Answering) is a benchmark dataset for evaluating cross-lingual question answering performance.
MLQA consists of over 5K extractive QA instances (12K in English) in SQuAD format in seven languages - English, Arabic,
German, Spanish, Hindi, Vietnamese and Simplified Chinese. MLQA is highly parallel, with QA instances parallel between
4 different languages on average.

- [xquad](https://huggingface.co/datasets/xquad/viewer/xquad.zh/validation)

XQuAD (Cross-lingual Question Answering Dataset) is a benchmark dataset for evaluating cross-lingual question answering performance. The dataset consists of a subset of 240 paragraphs and 1190 question-answer pairs from the development set of SQuAD v1.1 (Rajpurkar et al., 2016) together with their professional translations into ten languages: Spanish, German, Greek, Russian, Turkish, Arabic, Vietnamese, Thai, Chinese, and Hindi. Consequently, the dataset is entirely parallel across 11 languages.

- [GuanacoDataset](https://huggingface.co/datasets/JosephusCheung/GuanacoDataset)

The dataset for the Guanaco model is designed to enhance the multilingual capabilities and address various linguistic tasks. It builds upon the 175 tasks from the Alpaca model by providing rewrites of seed tasks in different languages and adding new tasks specifically designed for English grammar analysis, natural language understanding, cross-lingual self-awareness, and explicit content recognition. The dataset comprises a total of 534,530 entries, generated at a low cost of $6K.

- [cmrc2018](https://huggingface.co/datasets/cmrc2018)

A Span-Extraction dataset for Chinese machine reading comprehension to add language diversities in this area. The dataset is composed by near 20,000 real questions annotated on Wikipedia paragraphs by human experts. We also annotated a challenge set which contains the questions that need comprehensive understanding and multi-sentence inference throughout the context.

- [Hello-SimpleAI/HC3-Chinese](https://huggingface.co/datasets/Hello-SimpleAI/HC3-Chinese)

Human ChatGPT Comparison Corpus (HC3): Human answer & ChatGPT answer compare to a same question.

- [C3](https://huggingface.co/datasets/c3)

The first free-form multiple-Choice Chinese machine reading Comprehension dataset, containing 13,369 documents (dialogues or more formally written mixed-genre texts) and their associated 19,577 multiple-choice free-form questions collected from Chinese-as-a-second-language examinations.

- [mkqa](https://huggingface.co/datasets/mkqa)

Multilingual Knowledge Questions & Answers, contains 10,000 queries sampled from the Google Natural Questions dataset. For each query we collect new passage-independent answers. These queries and answers are then human translated into 25 Non-English languages.

- [sunzeyeah/chinese_chatgpt_corpus](https://huggingface.co/datasets/sunzeyeah/chinese_chatgpt_corpus)

The dataset collects chinese corpus for Supervised Finetuning (SFT) and Reinforcement Learning From Human Feedback (RLHF).

```
{
    "prompt": "问题：有没有给未成年贷款的有的联系",
    "answers":
    [
        {
            "answer": "若通过招行办理，我行规定，贷款人年龄需年满18岁，且年龄加贷款年限不得超过70岁。如果您持有我行信用卡附属卡，可尝试办理预借现金。",
            "score": 1
        }
    ],
    "prefix": "回答："
}
```

- [shibing624/alpaca-zh](https://huggingface.co/datasets/shibing624/alpaca-zh)

A cleaned / Chinese version of the original Alpaca Dataset released by Stanford.

Alpaca is a dataset of 52,000 instructions and demonstrations generated by OpenAI's text-davinci-003 engine. This instruction data can be used to conduct instruction-tuning for language models and make the language model follow instruction better. Built based on the data generation pipeline from Self-Instruct thesis framework.

## Public Professional Domain Knowledge

- [wangrui6/Zhihu-KOL](https://huggingface.co/datasets/wangrui6/Zhihu-KOL)


### Medical

- [medical_dialog](https://huggingface.co/datasets/medical_dialog)

The MedDialog dataset (Chinese) contains conversations (in Chinese) between doctors and patients. It has 1.1 million dialogues and 4 million utterances. The data is continuously growing and more dialogues will be added. The raw dialogues are from haodf.com. (All copyrights of the data belong to haodf.com.)

- [covid_qa_ucsd](https://huggingface.co/datasets/covid_qa_ucsd)

English medical dialogue dataset about COVID-19 and other types of pneumonia. Patients who are concerned that they may be infected by COVID-19 or other pneumonia consult doctors and doctors provide advice.

### Investment

### Insurance

### Banking


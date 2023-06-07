# NewsTitleGenerate_ChatGLM
## 项目说明
本项目是大数据分析课程的大作业，使用微调与Prompt的方法利用ChatGLM生成新闻标题。
<img width="416" alt="image" src="https://github.com/TianmhBlank/NewsTitleGenerate_ChatGLM/assets/110660289/b94240d4-062b-4b82-a2ba-7ae0b8300cdb">
## 生成结果
人工评价标题生成结果
| **方法**              | **最优数量**<br><br>**（生成质量）** | **最差（有问题）数量**<br><br>**（生成稳定性）** |
| --------------------- | ------------------------------------ | ------------------------------------------------ |
| 原始数据集title       | 34                                   | 55                                               |
| chatglm_zero_shot     | 55                                   | 35                                               |
| chatglm_one_shot      | 20                                   | 63                                               |
| chatglm_least_to_most | 40                                   | 44                                               |
| finetuned_underfit    | 14                                   | 67                                               |
| finetuned_justfit     | 20                                   | 54                                               |
| finetuned_overfit     | 17                                   | 72                                               |

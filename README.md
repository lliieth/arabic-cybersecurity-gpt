# Arabic Cybersecurity GPT (LLM)

## Project Overview | نظرة عامة على المشروع

This project focuses on building a Large Language Model (LLM) specialized in cybersecurity knowledge using the Transformer architecture.  
The model was implemented from scratch using PyTorch and trained on Arabic cybersecurity-related text.

The purpose of the project is to explore how modern AI language models can support cybersecurity education and knowledge understanding in the Arabic language.

يهدف هذا المشروع إلى تطوير نموذج لغة كبير (LLM) متخصص في مجال الأمن السيبراني باستخدام هيكلية Transformer.  
تم بناء النموذج من الصفر باستخدام مكتبة PyTorch وتم تدريبه على بيانات باللغة العربية تتعلق بمفاهيم الأمن السيبراني.

يستكشف المشروع إمكانية استخدام نماذج الذكاء الاصطناعي اللغوية لدعم فهم مفاهيم الأمن السيبراني وتقديم شروحات مبسطة للمفاهيم التقنية باللغة العربية.

---

# Cybersecurity Knowledge Integration | دمج معرفة الأمن السيبراني

The dataset used in this project contains cybersecurity-related information such as:

- Cybersecurity fundamentals  
- Network security concepts  
- Malware and cyber attacks  
- Phishing and social engineering  
- Security vulnerabilities  
- Defensive security strategies  
- Incident response concepts  

تم تدريب النموذج باستخدام بيانات تحتوي على معلومات عن:

- أساسيات الأمن السيبراني  
- أمن الشبكات  
- البرمجيات الخبيثة والهجمات السيبرانية  
- التصيد الاحتيالي والهندسة الاجتماعية  
- الثغرات الأمنية  
- استراتيجيات الدفاع السيبراني  
- الاستجابة للحوادث الأمنية  

يساعد ذلك النموذج على فهم المصطلحات السيبرانية وتوليد إجابات وشروحات مرتبطة بالأمن السيبراني.

---

# Model Architecture | بنية النموذج

The model follows a **GPT-style Transformer decoder architecture** including:

- Token Embeddings  
- Positional Encoding  
- Self-Attention Mechanism  
- Feed Forward Neural Networks  
- Layer Normalization  

هذه البنية تسمح للنموذج بفهم العلاقات بين الكلمات داخل النص وتوليد نصوص متسلسلة ذات معنى.

---

# Model Training Process | عملية تدريب النموذج

The model training pipeline consisted of two stages:

### Pretraining
The model was first trained on Arabic cybersecurity text to learn the general structure and terminology of cybersecurity language.

### Fine-tuning
The model was further fine-tuned using question-answer style cybersecurity data to improve the quality of generated responses.

تم تدريب النموذج على مرحلتين:

1. **Pretraining** لتعلم أنماط النصوص السيبرانية.
2. **Fine-tuning** باستخدام بيانات أسئلة وأجوبة لتحسين دقة الإجابات.

---

# Technologies Used | التقنيات المستخدمة

- Python  
- PyTorch  
- Transformer Architecture  
- Natural Language Processing (NLP)  
- Google Colab  

---

# Project Impact | أهمية المشروع

This project demonstrates how artificial intelligence and large language models can be applied in the cybersecurity domain to assist students and professionals in understanding cybersecurity concepts.

يوضح هذا المشروع إمكانية استخدام الذكاء الاصطناعي ونماذج اللغة الكبيرة لدعم فهم مفاهيم الأمن السيبراني وتطوير أدوات تعليمية ذكية باللغة العربية.

---


## Model Testing | اختبار النموذج

After training the language model on Arabic cybersecurity data, the model was tested by asking it different cybersecurity related questions.

The goal of this test was to evaluate whether the trained model can understand cybersecurity concepts and generate meaningful responses.

Example Test:

Question:
Explain phishing in simple terms.

Model Response:
Phishing is a cyber attack where attackers try to trick users into revealing sensitive information such as passwords or financial data by pretending to be a trusted source.

This testing step shows that the trained model can respond to cybersecurity questions and generate informative answers.

---

## اختبار النموذج

بعد تدريب نموذج اللغة على بيانات متعلقة بالأمن السيبراني باللغة العربية، تم اختبار النموذج من خلال طرح عدة أسئلة عليه تتعلق بمفاهيم الأمن السيبراني.

كان الهدف من الاختبار التأكد من قدرة النموذج على فهم المفاهيم الأمنية وتوليد إجابات مناسبة.

مثال على الاختبار:

السؤال:
اشرح مفهوم التصيد الاحتيالي بلغة بسيطة.

إجابة النموذج:
التصيد الاحتيالي هو نوع من الهجمات السيبرانية حيث يحاول المهاجم خداع المستخدمين للحصول على معلومات حساسة مثل كلمات المرور أو البيانات البنكية عن طريق انتحال صفة جهة موثوقة.

يظهر هذا الاختبار أن النموذج المدرب قادر على فهم الأسئلة المتعلقة بالأمن السيبراني وتوليد إجابات مفيدة.

# Demo

You can run the project directly using Google Colab:
https://colab.research.google.com/drive/1J_1e6zSNB_iqC7h0UlKRlBwpV4jDhUsH?usp=sharing




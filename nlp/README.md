### NLP материалы
* [NLP pub](https://nlpub.ru/)
* "Глубокое обучение. Погружение в мир нейронных сетей" - Николенко, Кадурин, Архангельская
* [NLP Course by Lena Voita](https://lena-voita.github.io/nlp_course.html)
* [ШАД - nlp course](https://github.com/yandexdataschool/nlp_course)
* [Hugging face NLP course](https://huggingface.co/learn/nlp-course/chapter0/1?fw=pt)
* [Stanford CS224N: Natural Language Processing with Deep Learning | Winter 2021](https://www.youtube.com/playlist?list=PLoROMvodv4rOSH4v6133s9LFPRHjEmbmJ)
* [NLP Cheatsheet: Master NLP](https://www.kaggle.com/code/dmitrykilievych/nlp-cheatsheet-master-nlp/notebook)
* [NLP-блок курса "Практический анализ данных" (ФКН НИУ ВШЭ)](https://github.com/ancatmara/data-science-nlp/tree/master)

### Аугментация текстовых данных
Аугментировать текстовые данные гораздо сложнее, чем аугментировать изображения:
изображение можно сжать, повернуть, отзеркалить, но что делать с текстами?
На эту тему есть исследования:

[EDA: Easy Data Augmentation Techniques for Boosting Performance on Text Classification Tasks](https://arxiv.org/abs/1901.11196)

Основные методы аугментации текстов:
* Случайная вставка **синонимов**
* Случайное удаление слов
* Случайная перестановка слов
* Обратный перевод (метод "испорченного телефона")

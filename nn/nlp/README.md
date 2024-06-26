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

### Диалоговые системы
Метрики оценки качества диалоговых систем:
* BLEU
* METEOR
* TER
* ROUGE
* LEPOR

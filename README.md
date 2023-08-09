# Удаление токсичных комментариев 
## Описание: 
Я занимаюсь разработкой нового сервиса для интернет-магазина "Викишоп". Теперь пользователи могут вносить изменения и дополнения в описания товаров, подобно вики-сообществам. Это означает, что клиенты могут предложить свои правки и обсудить изменения других. Мы ищем решение, которое будет автоматически выявлять токсичные комментарии и отправлять их на модерацию.

## Стэк: 
python, nltk, pandas, sklearn, spacy, tqdm, numpy, matplotlib, seaborn, tensorflow. 

## Цель: 
Обучить модель, которая способна классифицировать комментарии на позитивные и негативные. У меня есть доступ к набору данных, в которых каждый комментарий размечен на предмет токсичности.

## Выводы:
В результате проведенного проекта были построены и оценены модели для модерации токсичных комментариев. Модель LinearSVC показала достаточно хорошую производительность с F1-мерой около 0.80, что свидетельствует о ее способности эффективно классифицировать комментарии на позитивные и негативные.

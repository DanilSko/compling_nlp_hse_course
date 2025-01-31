## Тематический план на 2019-20 учебный год:

1. **Предобработка текста**	  
Вы научитесь: различать токенизацию, лемматизацию и стемминг; применять регулярные выражения для токенизации текстов; использовать word_tokenizer, snowball stemmer из nltk; пользоваться pymorphy2 и mystem3 для лемматизации
Нграммы	оценивать степень устойчивости сочетаний слов с помощью различных метрик; пользоваться Phraser из gensim для объединения токенов в нграммы; использовать nltk для нахождения устойчивых биграммов и триграммов
	
2. **Распознавание языка**    
Вы научитесь: собирать многоязычные корпусы с помощью wikidata; применять мешок слов и мешок буквенных нграммов для расчёта близости текстов; использовать CountVectorizer из sklearn для векторизации текстов; применять LogisticRegression из sklearn для классификации; оценивать качество классификации (точность, полнота, ф-мера)

3. **Выделение и исправление опечаток**    
Вы научитесь: определять опечатки с помощью словаря и классификатора; использовать алгоритм Норвига для генерации исправления; сравнивать различные меры редактирования (расстояние левенштейна, хэмминга и др.); оптимизировать поиск исправления с помощью векторизации

4. **Извлечение именованных сущностей**   
Вы научитесь: использовать natasha для извлечения стандартных сущностей; разрабатывать грамматики для yargy для извлечения специфических сущностей

5. **Лексическая дизамбигуация**  
Вы научитесь: пользоваться wordnet; использовать алгоритм Леска для определения значения слова по контексту; обучать Adagram и определять нужное значение слова по контексту; кластеризовать контексты слов для определения количества значений слова; оценивать качество кластеризации при наличии разметки
	
6. **Тематическое моделирование**  
Вы научитесь: использовать неотрицательное матричное разложение (NMF) из sklearn; использовать LDA из gensim; использовать BigARTM, настраивать регуляризаторы; оценивать качество тематических моделей (интерпретируемость, перплексия, когерентность), подбирать оптимальное количество тем

7. **Анализ тональности**  
Вы научитесь: сравнивать различные классификаторы в sklearn с использованием кросс-валидации; находить значимые и незначимые признаки

8. **Векторные представления**  
Вы научитесь: использовать матричные разложения для построения представлений слов; обучать word2vec, fastext из gensim, различать эти алгоритмы между собой; оценивать качество векторных представления на задаче определения перефразирования

9. **Морфологическая дизамбигуация**  
Вы научитесь: использовать предобученные модели для морфологической разметки; пользоваться функцией обучение на своих данных TreeTagger; использовать LSTM из keras для предсказания морфологических тэгов

10. **Разметка последовательности**  
Вы научитесь: реализовывать алгоритм витерби для нахождения правильных частей речи; реализовывать beam search для ускорения работы витерби
	
11. **Синтаксический парсинг (составляющие и зависимости)**
Вы научитесь: использовать предобученные модели (UdPipe, SyntaxNet) для построения деревьев зависимости; извлекать тройки субъект-предикат-объект из графов зависимостей предложений; находить структурно близкие предложения с помощью tree edit distance

12. **Извлечение ключевых слов**   
Вы научитесь: различать задачу классификации и ранжирования; использовать TfidfVectorizer из sklearn для ранжирования слов по значимости; представлять текст в виде графа; рассчитывать важность слов в графе с помощью random walk и мер центральности в networkx; разрабатывать собственные метрики значимости

13. **Языковое моделирование**  
Вы научитесь: создавать языковые модели с помощью keras; использовать предобученные state-of-the-art модели (BERT, ELMO, GPT-2) для получения векторных представлений; дообучать (fine-tuning) предобученные модели для задач классификации

14. **Вопросно-ответные системы**   
Вы научитесь: создавать вопросно-ответные системы на данных википедии с помощью мешка слов (DrQA); обучать нейронные вопросно-ответные модели на SQUAD

15. **Машинный перевод**   
Вы научитесь: обучать seq2seq модели для перевода; использовать предобученные модели для текстовых аугментаций; оценивать качество машинного перевода

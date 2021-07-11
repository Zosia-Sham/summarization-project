# summarization-project
Генерировать 'конспект' текста

В конспекте обычно пишут не целыми предложениями, а буллитами

Extractive summarization

Нашла интересную работу [Simple and Effective Text Simplification Using Semantic and Neural Methods](https://aclanthology.org/P18-1016.pdf)

Semantic methods там - это деление сложно сочиненных и подчиненных предложений на простые используя [UCCA](https://universalconceptualcognitiveannotation.github.io/) [TUPA](https://github.com/danielhers/tupa) парсер

UCCA строит по предложению его семантическое дерево

Нашла конкурс [Cross-Framework Meaning Representation Parsing MRP](http://mrp.nlpl.eu/2020/index.php), где среди 5 фреймворков есть UCCA

Он проводился в 20ом году, победители по UCCA - [Hitachi](https://aclanthology.org/2020.conll-shared.4.pdf) и [UFAL](https://github.com/ufal/perin), у Hitachi нет pretrained model, у UFAL есть

UFAL лучше чем та версия TUPA, которая использовалась в работе Simple and Effective Text Simplification

Нужно выделить главные предложения, чтобы потом их можно было 'упростить' до буллитов с помощью UCCA

Поискать корпус с главными предложениями из текста

Составление конспекта и highlighting and annotating - похожие направления, корпус с highlights

Базы данных текст - выделенные предложения я не нашла, но нашла несколько ресурсов, где её можно собрать

[Briefly](https://briefly.co/)  -  TLDR for the internet, пользователи выделяют 'маркером' статьи и делятся

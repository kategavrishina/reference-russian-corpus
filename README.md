# reference-russian-corpus
Код и данные для курсовой работы "Эталонный корпус русского языка для универсального семантического парсинга"
_____

Для запуска кода необходимо скачать данные FrameBank (два файла), которые указаны ниже. В коде использован способ чтения с Googlе Диска, но также можно загрузить данные в Colab  вручную.

Код: <https://github.com/kategavrishina/reference-russian-corpus/blob/main/predict_roles.ipynb>
(запускается из среды Google Colab по состоянию на октябрь, 2020 года)

"Золотой стандарт": <https://github.com/kategavrishina/reference-russian-corpus/blob/main/gold_standard.xlsx>
____

Данные [**FrameBank**](<https://github.com/olesar/framebank>) ресурса в открытом доступе: <http://nlp.isa.ru/framebank_parser/> (для обучения использованы файлы annotated_corpus_fixed+syntaxnet.json и framebank_anno_ex_items_fixed.txt)

Данные корпуса **SynTagRus** в формате UD в открытом доступе: <https://github.com/UniversalDependencies/UD_Russian-SynTagRus>

Полученный эталонный корпус:
- [обработанные данные ru_syntagrus-ud-test.conllu](<https://drive.google.com/file/d/1-50f42WyMV22zySZI9F3dTJ32M7qg7Xk/view?usp=sharing>)
- [обработанные данные ru_syntagrus-ud-dev.conllu](<https://drive.google.com/file/d/1-0_UZ7RxqGekhzYSIeaCeWvtcgvK3N5Z/view?usp=sharing>)
- [обработанные данные золотого стандарта](<https://drive.google.com/file/d/1-_AIdxqh4OQbRGUdjShOfEZqq1zMFbpz/view?usp=sharing>)

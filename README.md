# SQLi-generator-based-on-GPT-2.

Структура проекта:

```text
my_project/
├── main.py                 # Основной файл приложения (GUI)
├── model.pkl               # Веса классического ML-детектора
├── vectorizer.pkl          # Векторайзер для обработки SQL-запросов
├── sql_gpt_final/          # Директория с предобученной моделью GPT-2
│   ├── model.safetensors
|   ├── generation_config.json
│   └── config.json
└── sql_tokenizer/          # Директория с настройками токенизатора
    ├── tokenizer.json
    ├── merges.txt
    ├── vocab.json
    └── tokenizer_config.json
```
Из-за весов Все необходимые файлы находятся на google drive:

https://drive.google.com/file/d/1Pr0EdcFKsf-4Ce7RVrvyywj3jlgKlQwc/view?usp=sharing

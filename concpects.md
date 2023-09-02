Посмотреть информацию про датафрейм.
    df.shape - Размер NxM датафрейма
    df.head(n) - Первые n строк или 5 если нет значения n
    df.tail(n) - последние n
    df.info() - полная информация
    df.describe() - Тоже полная информация

Сортировка
- по одному параметру
    df_json.sort_values(by='movie_name', ascending=False)
- по несколько параметрам
    df_json.sort_values(by=['movie_name', 'second_column', 'third_column'], ascending=[True, True, False])
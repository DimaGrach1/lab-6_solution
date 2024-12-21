# Лабораторная работа 6

## Задание лабораторной работы (вот только его и нужно включить в отчет!)

1. Создал необходимый файл

   ![image](https://github.com/user-attachments/assets/98a52b7a-7bad-49f0-b40e-268751592653)

2. Нашел строки, где использовался метод POST или метод GET. Здесь и дальше использовал опцию -E для указания альтернатив в регулярных выражениях.

   ![image](https://github.com/user-attachments/assets/44da75ad-8a41-4145-9c73-ba5460f23fd2)

3. Нашел строки, содержащие статус-код 4xx (коды ошибок клиента).

   ![image](https://github.com/user-attachments/assets/db76496e-3e71-4103-90ec-3c1615b8d795)

4. Извлек все уникальные IP-адреса из файла. Использовал ^\d+\.\d+\.\d+\.\d+ — регулярное выражение для IP-адресов и sort | uniq — сортировку строк, оставляя только уникальные значения. Использовал также опции -o — для вывода только совпавших значений, а не полных строк и -P для того, чтобы можно было использовать удобное регулярное выражение для IP-адресов.

   ![image](https://github.com/user-attachments/assets/8ad1dcf8-ef18-4305-8a3f-1cec43483ed2)

5. Нашел строки, в которых размер ответа сервера превышает 1000 байт.

   ![image](https://github.com/user-attachments/assets/a9d24544-8dca-47d4-8bf0-d6311216e273)

6. Нашел строки, где запрашивался ресурс /dashboard или /settings.

    ![image](https://github.com/user-attachments/assets/6e44171c-8daa-4dbf-b804-6dc4ef2ccadd)
   
7. Составил регулярное выражение, которое находит строки, где запрос завершился статусом 200 и размером ответа больше 500 байт.

    ![image](https://github.com/user-attachments/assets/62c84e47-28fd-444b-9a88-3a50c7dd8918)

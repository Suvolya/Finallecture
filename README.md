## План автоматизации тестирования сценария перехода к форме записи и заполнения этой формы

### Перечень автоматизируемых сценариев: 
1. Проверка открытия страницы Нетологии;
2. Проверка наличия и работы элементов навигации: 
- Каталог курсов (клик на кнопку на главной странице) -> Программирование (выбор и клик на кнопку) -> Тестировщик ПО (прокрутка страницы, выбор блока, клик по нему и прокрутка до формы записи на курс)
- Программирование (выбор блока на главной странице и клик по нему) -> Тестировщик ПО (прокрутка страницы, выбор блока, клик по нему и прокрутка до формы записи на курс)
3. Тестирование формы записи на курс:

   #### Позитивные сценарии
    *Тестирование заполнения формы:*
   - Записаться
   - Получить консультацию
     
   *Ожидаемый результат:* открывается страница благодарности и появляется сообщение "Спасибо, Ваша заявка принята. В ближайшее время мы с Вами свяжемся".


    GUI-тесты:
   - ввести валидное Имя на кирилице в диапазоне от 2 до 30 символов, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Записаться);
   - ввести валидное Имя на кирилице, содержащие букву Ё, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Записаться);
   - ввести валидное Имя на кирилице через дефис, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Записаться);
   - ввести валидное Имя на кирилице через дефис, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Записаться);
   - ввести граничное значение в поле Имя: данные, состоящие из 2х символов, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Записаться);
   - ввести граничное значение в поле Имя: данные, состоящие из 3х символов, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Записаться);
   - ввести граничное значение в поле Имя: данные, состоящие из 29 символов, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Записаться);
   - ввести граничное значение в поле Имя: данные, состоящие из 30 символов, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Записаться);
   - ввести валидное Имя на кирилице, ввести данные в поле Номер телефона, где номер без + в диапазоне 7-11 цифр (Имя сгенерировать с помощью фейкера на русском языке, нажать на кнопку Записаться);
   - ввести валидное Имя на кирилице, ввести данные в поле Номер телефона, где номер начинается с + в диапазоне 11-15 цифр (Имя сгенерировать с помощью фейкера на русском языке, нажать на кнопку Записаться);
   - ввести валидное Имя на кирилице в диапазоне от 2 до 30 символов, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Получить консультацию);
   - ввести валидное Имя на кирилице, содержащие букву Ё, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Получить консультацию);
   - ввести валидное Имя на кирилице через дефис, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Получить консультацию);
   - ввести валидное Имя на кирилице через дефис, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Получить консультацию);
   - ввести граничное значение в поле Имя: данные, состоящие из 2х символов, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Получить консультацию);
   - ввести граничное значение в поле Имя: данные, состоящие из 3х символов, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Получить консультацию);
   - ввести граничное значение в поле Имя: данные, состоящие из 29 символов, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Получить консультацию);
   - ввести граничное значение в поле Имя: данные, состоящие из 30 символов, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Получить консультацию);
   - ввести валидное Имя на кирилице, ввести данные в поле Номер телефона, где номер без + в диапазоне 7-11 цифр (Имя сгенерировать с помощью фейкера на русском языке, нажать на кнопку Получить консультацию);
   - ввести валидное Имя на кирилице, ввести данные в поле Номер телефона, где номер начинается с + в диапазоне 11-15 цифр (Имя сгенерировать с помощью фейкера на русском языке, нажать на кнопку Получить консультацию);

   
    ForAPI-тесты:
- подача различных запросов с невалидными данными на форму записи;
- получение кода ответа со статусом – 200.

    #### Негативны сценарии:

    *Проверка ошибок в форме:*
  - Записаться
  - Получить консультацию
  
  *Ожидаемый результат:* появляется всплывающее окно с сообщением "Неверно заполнено поле/Заполнены не все поля формы".
  

    GUI-тесты:
- оставить поле Имя пустым, заполнить поле с номером телефона корректно (номер телефона сгенерировать с помощью фейкера, нажать на кнопку Записаться);
- ввести граничное значение в поле Имя: данные, состоящие из 1го символа, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Записаться);
- ввести граничное значение в поле Имя: данные, состоящие из 31го символа, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Записаться);
- ввести в поле Имя значение на латинице, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера, но на английском языке, номер телефона сгенерировать с помощью фейкера, нажать на кнопку Записаться);
- ввести данные в поле имя: кирилица+цифры, заполнить поле с номером телефона корректно (номер телефона сгенерировать с помощью фейкера, нажать на кнопку Записаться);
- ввести данные в поле имя на экзотических языках: иероглифы, арабская вязь, заполнить поле с номером телефона корректно (номер телефона сгенерировать с помощью фейкера, нажать на кнопку Записаться);
- ввести данные в поле имя: пробел, заполнить поле с номером телефона корректно (номер телефона сгенерировать с помощью фейкера, нажать на кнопку Записаться);
- оставить поле Номер телефона пустым, заполнить поле Имя корректно (Имя сгенерировать с помощью фейкера, нажать на кнопку Записаться);
- ввести в поле Номер телефона значение на единицу меньше, чем количество цифр в корректном номере, в поле Имя ввести валидное значение, (Имя сгенерировать с помощью фейкера, нажать на кнопку Записаться);
- ввести в поле Номер телефона значение на единицу больше, чем количество цифр в корректном номере, в поле Имя ввести валидное значение, (Имя сгенерировать с помощью фейкера, нажать на кнопку Записаться);
- ввести в поле Номер телефона любое символьное значение, например: !, ввести валидное Имя (Имя сгенерировать с помощью фейкера на русском языке, нажать на кнопку Записаться);
- ввести в поле Номер телефона буквенное значение, ввести валидное Имя (Имя сгенерировать с помощью фейкера на русском языке, нажать на кнопку Записаться);
- ввести в данные поле Номер телефона, состоящие из 6ти символов, ввести валидное Имя (Имя сгенерировать с помощью фейкера на русском языке, нажать на кнопку Записаться);
- ввести в данные поле Номер телефона, состоящие из 12ти символов, ввести валидное Имя (Имя сгенерировать с помощью фейкера на русском языке, нажать на кнопку Записаться);
- оставить поле Имя пустым, заполнить поле с номером телефона корректно (номер телефона сгенерировать с помощью фейкера, нажать на кнопку Получить консультацию);
- ввести граничное значение в поле Имя: данные, состоящие из 1го символа, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Получить консультацию);
- ввести граничное значение в поле Имя: данные, состоящие из 31го символа, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера на русском языке, номер телефона также с помощью фейкера, нажать на кнопку Получить консультацию);
- ввести в поле Имя значение на латинице, заполнить поле с номером телефона корректно (Имя сгенерировать с помощью фейкера, но на английском языке, номер телефона сгенерировать с помощью фейкера, нажать на кнопку Получить консультацию);
- ввести данные в поле имя: кирилица+цифры, заполнить поле с номером телефона корректно (номер телефона сгенерировать с помощью фейкера, нажать на кнопку Получить консультацию);
- ввести данные в поле имя на экзотических языках: иероглифы, арабская вязь, заполнить поле с номером телефона корректно (номер телефона сгенерировать с помощью фейкера, нажать на кнопку Получить консультацию);
- ввести данные в поле имя: пробел, заполнить поле с номером телефона корректно (номер телефона сгенерировать с помощью фейкера, нажать на кнопку Получить консультацию);
- оставить поле Номер телефона пустым, заполнить поле Имя корректно (Имя сгенерировать с помощью фейкера, нажать на кнопку Получить консультацию);
- ввести в поле Номер телефона значение на единицу меньше, чем количество цифр в корректном номере, в поле Имя ввести валидное значение, (Имя сгенерировать с помощью фейкера, нажать на кнопку Получить консультацию);
- ввести в поле Номер телефона значение на единицу больше, чем количество цифр в корректном номере, в поле Имя ввести валидное значение, (Имя сгенерировать с помощью фейкера, нажать на кнопку Получить консультацию);
- ввести в поле Номер телефона любое символьное значение, например: !, ввести валидное Имя (Имя сгенерировать с помощью фейкера на русском языке, нажать на кнопку Получить консультацию);
- ввести в поле Номер телефона буквенное значение, ввести валидное Имя (Имя сгенерировать с помощью фейкера на русском языке, нажать на кнопку Получить консультацию);
- ввести в данные поле Номер телефона, состоящие из 6ти символов, ввести валидное Имя (Имя сгенерировать с помощью фейкера на русском языке, нажать на кнопку Получить консультацию);
- ввести в данные поле Номер телефона, состоящие из 12ти символов, ввести валидное Имя (Имя сгенерировать с помощью фейкера на русском языке, нажать на кнопку Получить консультацию);

  
    ForAPI-тесты:
- подача различных запросов на сервис карт;
- получение ответа со статусом – 400 - 499.

### Перечень используемых инструментов с обоснованием выбора:

- Java - язык, на котором будем писать код;
- IntelliJ IDEA - программа, в которой пишем код;
- Gradle — система быстрой сборки IntelliJ IDEA;
- JUnit 5 — библиотека тестирования для Java;
- Faker - генератор внешних данных (имени и телефона);
- Selenide - библиотекв для написания UI тестов, т.к. мы работаем с веб-страницей и искомыми значениями с помощью html и css;
- Allure - инструмент для генерации отчетов о том, что было протестировано;

### Перечень необходимых разрешений, данных и доступов:
- Разрешение на тестирование страницы сайта с помощью автоматизированного ПО;
- Разрешение на доступ к базе данных;
- Предоставление тестовых аккаунтов для оформления заявки через веб-сайт "Нетология".

### Перечень и описание возможных рисков при автоматизации:
- Возможна смена кода страницы, либо css-селекторов, придется править код;
- Смена формы заполнения по истечении времени;
- Невозможность написания в форме некоторых букв (например, буквы ё);
- Долгое открытие страницы сайта, либо вкладки;
- Недоступность сайта или страницы;
- Неоправданно высокая стоимость автоматизации;
- Искажение результатов тестов в связи с отсутствием доступа к реальной БД;

### Перечень необходимых специалистов для автоматизации:
- Специалист по автоматизированному тестированию;
- Системный администратор, который будет следить за окружением;

### Интервальная оценка с учётом рисков в часах:
- Подготовка окружения, развертывание БД - 8 часов;
- Написание автотестов, тестирование и отладка автотестов - 24 часа;
- Формирование и анализ отчетов - 4 часа;

  *ИТОГО:* 36 часов.
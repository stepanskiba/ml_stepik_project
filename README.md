# Проект пользователи онлайн курса

Мы хотим предсказать на онлайн курсе [Анализ данных в R](https://stepik.org/course/129) на платформе stepik, закончат его пользователи или нет.

У нас есть данные в следующем формате:


* [events_data_train.csv](https://github.com/stepanskiba/ml_stepik_project/blob/master/data/event_data_train.zip) - данные о действиях, которые совершают студенты со стэпами
    * step_id - id шага
    * user_id - id пользователя
    * timestamp - время наступления события
    * action - событие
        - discovered - пользователь перешел на стэп
        - viewed - просмотр шага
        - started_attempt - начало прохождения шага
        - passed - прохождение  шага

* [submissions_data_train.csv](https://github.com/stepanskiba/ml_stepik_project/blob/master/data/submissions_data_train.zip) - данные о практических заданиях
    * step_id - id шага
    * timestamp - время отправки решения
    * submission_status - статус решения
        - correct - правильно
        - wrong - не правильно
    * user_id - id пользователя

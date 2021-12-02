# Seaching website

## Проектирование интерфейса пользователя

* # 1.Списки веб-страниц

В системе ProSea для незарегистрированных пользователей будут доступны следующие страницы

    * Главная страница системы;
    * Авторизация;
    * Регистрация.
    * Информация о проекте.

Действующее лицо developer будут доступны следующие страницы

    * Информация программиста Profile
    * Опыт программиста Experiment
    * Отзыв программиста Review
    * Создавание проектов Create project
    * Запрос на присоединение к проекту Request
    * Информация проектов Project
    * Bookmarks

Действующее лицо company будут доступны следующие страницы

    * Profile
    * История проектов
    * Создавание проектов Create project
    * Запрос на присоединение проектов Request
    * Recruitment

* # 2.Эскизы веб-страниц

    ![](images/UI/UI_1.png)
    1. Эскиз страницы Главной станицы системы Home Page

    ![](images/UI/UI_2.png)
    2. Эскиз страницы Project Modal Page

    ![](images/UI/UI_3.png)
    3. Эскиз страницы Registration

    ![](images/UI/UI_4.png)
    4. Эскиз страницы Login

    ![](images/UI/UI_5.png)
    5. Эскиз страницы Profile of Developer

    ![](images/UI/UI_6.png)
    6. Эскиз страницы Edit Contact

    ![](images/UI/UI_7.png)
    7. Эскиз страницы Experiment of Developer

    ![](images/UI/UI_8.png)
    8. Эскиз страницы Specialities of Developer

    ![](images/UI/UI_9.png)
    9. Эскиз страницы Programming Languages

    ![](images/UI/UI_10.png)
    10. Эскиз страницы Frameworks and Tools of Developer

    ![](images/UI/UI_11.png)
    11. Эскиз страницы Review of Developer

    ![](images/UI/UI_12.png)
    12. Эскиз страницы Projects of Developer

    ![](images/UI/UI_13.png)
    13. Эскиз страницы Bookmark of Developer

    ![](images/UI/UI_14.png)
    14. Эскиз страницы Add Project of Developer

    ![](images/UI/UI_15.png)
    15. Эскиз страницы Join request of Developer

    ![](images/UI/UI_16.png)
    16. Эскиз страницы Profile of Company

    ![](images/UI/UI_17.png)
    17. Эскиз страницы Add Project of Company


* # 3.Сценарии работы пользователя

    ![](images/UI1.png)
    # Сценарий работы действующего лица Гость

    ![](images/UI2.png)
    # Сценарий работы действующего лица Developer

    ![](images/UI3.png)
    # Сценарий работы действующего лица Company

|Название|Описание|
|-|-|
|Действующее лицо Гость|
|getHomepage|Выводит на экран главную страницу системы.|
|getRegistration|Выводит на экран страницу регистрации.|
|getProjectMod|Выводит на экран pop-up проекта.|
|getLogin|Выводит на экран страницу авторизации.|
|Действующее лицо Developer|
|getHomepage|Выводит на экран главную страницу системы.|
|getProjectMod|Выводит на экран pop-up проекта.|
|getDev|Выводит на экран станицу профиля программиста .|
|getExperiment|Выводит на экран станицу опыта программиста .|
|getReview|Выводит на экран станицу отзыва программиста .|
|getCreateProject|Выводит на экран станицу, где создать новый проект.|
|getBookmark|Выводит на экран станицу закладки проектов.|
|getProject|Выводит на экран станицу, в котором показать статус проектов.|
|getRequest|Выводит на экран станицу запросы программиста .|
|Действующее лицо Company|
|getHomepage|Выводит на экран главную страницу системы.|
|getProjectMod|Выводит на экран pop-up проекта.|
|getDev|Выводит на экран станицу профиля программиста .|
|getCreateProject|Выводит на экран станицу, где создать новый проект.|
|getRecuitment|Выводит на экран станицу информации о наборе персонала|
|getProject|Выводит на экран станицу, в котором показать статус проектов.|
|getRequest|Выводит на экран станицу запросы компании .|
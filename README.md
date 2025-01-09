# Лабораторная работа №1. Реализация удаленного импорта собственного пакета
1. Создадим файл myremotemodule.py, который будет использоваться в качестве модуля. Поместим его в каталог, который будет корневым для сервера, и назовём этот каталог rootserver. Затем напишем код.
![image](https://github.com/user-attachments/assets/7d0f5735-e56e-4e4e-8080-9659c131de43)

Создайте файл Python с содержимым функций url_hook и классов URLLoader, URLFinder из текста конспекта лекции со всеми необходимыми библиотеками (допустим, activation_script.py).
![image](https://github.com/user-attachments/assets/b28917ce-6337-4ce4-a56b-b1ef9728673a)

Далее, чтобы продемонстрировать работу импорта из удаленного каталога, мы должны запустить сервер http так, чтобы наш желаемый для импорта модуль "лежал" на сервере (например, в корневой директории сервера). Откроем каталог rootserver с файлом myremotemodule.py и запустим там сервер:
![image](https://github.com/user-attachments/assets/78f6d076-a7bc-427e-ba12-b72bfabba3f7)

После этого мы запускаем файл, в котором содержится код.
![image](https://github.com/user-attachments/assets/713a84f1-b1ef-4bef-9eaa-8753a04f2ba4)

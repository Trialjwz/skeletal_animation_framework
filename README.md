# Skeletal Animation Framework Demo
1. Загружаем UNIGINE SDK Browser 2 ([https://developer.unigine.com/](https://developer.unigine.com/))
2. Устанавливаем Community 2.18.1 SDK
3. Создаем новый проект c названием skeletal_animation_framework, API C++, precision float
4. Открываем редактор и удаляем весь контент из Asset Browser
5. Импортируем assets.upackage, указав Force Import Dependencies
6. Собираем и запускаем:
   1. После импорта будет добавлен .vcxproj уже с добавленными исходниками компонент
   2. При использовании makefile можно заменить в нём `SRCS` на `SRCS = $(wildcard *.cpp) $(wildcard */*.cpp)`
7. Открываем консоль (`) и загружаем мир (world_load animation_samples)

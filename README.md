# WEATHER APPLICATION

![](static/icon/big%20screen.png)

Цей проект розроблено з метою ознайомлення із роботою API, принципом отримання даних від віддаленого серверу, вмінням їх обробляти, структурувати та застосовувати у своємо проєкті. А саме застосовувалось API такого веб-ресурсу як [OpenWeatherMap](https://openweathermap.org). Проєкт допоможе розібратися із роботою файлів JSON, як правильно отримувати та зберігати дані у файлах з типом .json. Та познайомити користувача з інтерфейсом застосунку розробленим за допомогою пакету [CustomTkinter](https://customtkinter.tomschimansky.com)

### Зміст:
- [Основні модулі проєкту](#modules)
- [Розгортання проєкту](#download)
- [Створення віртуального оточення проєкту](#venv)
- [Завантаження модулей до віртуального оточення](#download-venv)
- [Старт проєкту](#start-project)
- [Основні механіки проєкту](#mechanics)
- [Висновок по проєкту](#result)

### Modules:
Всі модулі
1. [customtkinter](https://customtkinter.tomschimansky.com)
2. [json](https://docs.python.org/3/library/json.html)
3. [colorama](https://pypi.org/project/colorama/)
4. [os](https://docs.python.org/uk/3.13/library/os.html)
5. [requests](https://pypi.org/project/requests/)
6. [pillow](https://pypi.org/project/pillow/)
7. [datetime](https://docs.python.org/3/library/datetime.html)


### Download:
Завантаження проєкту
- ##### Git clone:

    - Отримати посилання для клонування проєкту

    ![](static/icon/clone_link.png)

    - Відкрити VSCode --> у Explorer VSCode відкрити папку для збереження склонованого проєкту --> та у Terminal прописати команду: 
    - `git clone https://github.com/WorldIT-academy/WeatherApp.git`

    ![](static/icon/clone_command.png)

    - Відкрити каталог, який ви склонували у Explorer VSCode
    
- ##### Download ZIP

### Venv:
    - python -m venv venv
### Активація Venv в PowerShell:
### Windous:
    - venv\Scripts\activate
### Linux/MacOS:
    - source venv/bin/activate 

### Download venv в PowerShell:
    - pip install -r requirements.txt

### Start project в терміналі проекту:
    - python main.py

### Mechanics:
1. Отримання даних по погодні за допомогою API OpenWeatherMap.
2. Відповіді у форматі JSON.

### Result:
Цей проект є удобним GUI інтерфейсом, який у реальному часі демонструє погодний стан в городах з усього світу.
Користувачі можуть зручно та швидко побачити мінімальну, максимальну, реальну температуру, також стан погоди свого та інших міст. 
Інтерфейс включає в себе приємне меню із синьо-блакитною гаммою. Основна частина показує стан погоди вашого міста по часу. Зліва ви можете побачити стан погоди з інших городів світу. 
\
This project is a convenient GUI interface that displays real-time weather conditions in cities around the world.
Users can conveniently and quickly see the minimum, maximum, actual temperature, as well as the weather conditions of their and other cities. 
The interface includes a nice menu with a blue color scheme.The main part shows the weather conditions of your city by time. On the left you can see the weather conditions of other cities around the world.

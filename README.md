# Информация о наборе данных
Датасет, который используется для обучения модели, можно найти на kaggle. Вот ссылка: https://www.kaggle.com/datasets/landlord/handwriting-recognition.
# Инструкция по скачиванию данного набора в среду Colab
1) Создать API-token. Для этого необходимо:
   - Зарегистрироваться на kaggle (если нет аккаунта)
   - Зайти в настройки (Settings)
   - Промотать ниже, где будет надпись API
   - Далее нажать Create new token.
   - В результате скачается json файл
2) Полученный json перенести в Colab
3) Уже в среде colab установить пакет kaggle командой !pip install kaggle
4) Создать папку командой !mkdir ~/.kaggle
5) Перенести в эту папку json файл !cp kaggle.json ~/.kaggle/<Имя вашего json файла>
6) Задаем права права файлу командой !chmod 600 ~/.kaggle/<Имя вашего json файла>
7) Скачиваем набор данных в среду командой !kaggle datasets download landlord/handwriting-recognition
8) Скачается zip архив. Его можно разархивировать командой !unzip handwriting-recognition.zip

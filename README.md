# Traffic Sign Detection

Для создания системы распознавания дорожных знаков мною использовался репозиторий TensorFlow Object Detection API. Модель **faster_rcnn_inception_v2_coco_2018_01_28** была дообучена на **600 изображениях** набора данных GTSDB (http://benchmark.ini.rub.de/?section=gtsdb&subsection=news) и протестирована на **300** изображениях.

# Запуск
Для проверки работы системы необходимо запустить **sign_traffic_detection.ipynb**. По умолчанию система находит все **jpg** изображения в папке **test_images** и пытается распознать дорожные знаки на этих изображениях. Результат работы системы сохраняется в папке **output_images**.       

# Пример результата работы
![alt text](https://github.com/AlNikolaev/Traffic-Sign-Detection/blob/master/output_images/00762.jpg)

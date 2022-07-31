# Chapters Parser

Code in the `./ffmpeg-video-parser.py` solves the problem of boilerplate video production task.

Every time you create a new YouTube video, you have to prepare marks for your video. This script automates this task using chapters that you can create during video editing step.

To run this script you need `python3` and `ffmpeg` both of them might be installed using your system's package manager (e.g. brew)


Then you can use it like this: 

```bash
% python3 ffmpeg-video-parser.py -f equals-and-hash-code.mov
00:00 Отрывки
00:16 Начало
00:31 О чем ролик?
01:17 Знакомимся с проектом
02:04 Благодарность автору теста!
03:53 Смотрим тесты!
05:47 Подробнее про базовый тест
09:08 Отступление про отношения эквивалентности и собеседования
09:48 Обратно учим базу!
12:53 Стандартный equals & hashCode не проходят! 
13:22 Lombok генерирует все верно!
14:06 Выводы!
```

Good luck using it! 

PS. This work is mainly a fork of [this](https://gist.github.com/dcondrey/469e2850e7f88ac198e8c3ff111bda7c).

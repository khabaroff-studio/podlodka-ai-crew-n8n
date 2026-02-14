### Генерация базового workflow

```
Мне нужен сценарий который будет следить за моими подписками на YouTube. И отправлять мне уведомления о новых видео в Telegram.

Вот что должно происходить:

1. Каждый час проверяй RSS feed канала 
   https://www.youtube.com/@PodlodkaShow/videos
   https://www.youtube.com/feeds/videos.xml?channel_id=UCOei1E1Vqq10S913OEqTWGw
   
2. Бери 10 видео. Если появилось новое видео — возьми название и ссылку.
   
3. Отправь мне сообщение в Telegram с форматом:
   "Новое видео: [название]
    Ссылка: [url]"

Для Telegram используй мой бот, токен у меня есть.

Придумай, как не слать повторки.

Сделай это максимально просто, без лишних штук.

@content_tools_bot
8501008149:AAGW4t30SFaXq_YP97ACzYXxvQCFBLoKCmc1

НИКОГДА НЕ ПУБЛИКУЙТЕ КЛЮЧИ. ТУТ КЛЮЧ УКАЗАН В ОБРАЗОВАТЕЛЬНЫХ ЦЕЛЯХ

```

**Что предположительно покажет n8n AI:**
- Schedule trigger (каждый час)
- RSS Feed node (YouTube)
- Telegram node (отправка сообщения)
- Базовая логика соединения

#### Later
i need add firecrawl to get youtube subtitles before sending to telegram
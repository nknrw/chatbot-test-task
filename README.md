## Описание проекта
Проект представляет собой заготовку для чат-бота без какой-либо интеллектуальной нагрузки.  

Ссылка на работающее приложение:  

https://chatbot-test-task.vercel.app/

## Локальный запуск
```
npm install
npm run serve
```

## Использование в стороннем проекте (тест)

Установите пакет в ваш проект
```
npm i nknrw-test-chatbot
```
Импортируйте компонент в ваш проект
```
import ChatWidget from 'nknrw-test-chatbot'
```
Добавьте компонент
```
<ChatWidget />
```

Компонент в npm-пакете имеет незначительные отличия, например изображения переведены в base64.
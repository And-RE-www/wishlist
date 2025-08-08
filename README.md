My Wishlist

Интерактивный сайт-сервис для отображения списка желаний из YAML-файла. Подходит для личного пользования, праздников или обмена wishlist’ами с друзьями.

Особенности
- Загрузка желаний из `wishlist.yml`
- Современный интерфейс в тёмной теме
- Анимированный заголовок "My Wishlist"
- Поддержка внешних ссылок (Kaspi, Ozon, Wildberries и т. д.)
- Фоновое изображение высокого качества (можно заменить)
- Полностью статический, без серверной части — размещается на GitHub Pages

Структура проекта  
.  
├── index.html         # Основной HTML-файл  
├── wishlist.yml       # YAML-файл со списком желаний  
├── background.jpg     # Фоновое изображение (опционально)  
└── README.md

Пример содержимого `wishlist.yml`
```yaml
- title: Дорожная подушка с эффектом памяти
  link: https://kaspi.kz/shop/p/dorozhnaja-podushka-memory-foam-139464832/
- title: Несессер для путешествий
  link: https://kaspi.kz/shop/p/nesesser-dlja-puteshestvij-104780429/
- title: Складная бутылка для воды
  link: https://kaspi.kz/shop/p/butylochka-skladnaja-450-ml-171867864/
```

Как опубликовать на GitHub Pages
1. Создайте публичный репозиторий
2. Загрузите `index.html`, `wishlist.yml`, `background.jpg` (опционально)
3. Перейдите в Settings → Pages → Source → main / root
4. Получите ссылку вида `https://<username>.github.io/<repository>/`

Замена фона
Измените путь к изображению в `index.html`:
```css
body {
  background-image: url('background.jpg');
}
```

Можно использовать ссылку на изображение из интернета.

Лицензия
MIT — свободно используйте и адаптируйте под себя.

# Тестовый файл movement_stats_test.html

Этот файл создан на основе `movement_stats.html` для тестирования верстки с реальными данными вместо переменных шаблона в различных почтовых клиентах, включая Microsoft Outlook..

## Замененные переменные

### Основные данные
- `{{.locale}}` → `ru` - русская локализация
- `{{.reverse_template}}` → `ltr` - направление текста слева направо
- `{{.preheader}}` → `Ваш ребёнок достиг новых высот в этом месяце! Посмотрите статистику активности и достижения.`
- `{{.brand_name}}` → `Где мои дети`
- `{{.child_name}}` → `Алиса` (используется в 4 местах)
- `{{.child_status}}` → `маленький исследователь` (используется в 2 местах)
- `{{.child_status_description}}` → `За активное изучение окружающего мира и любознательность в каждом шаге!`

### Изображения
- `{{.hero_image}}` → `https://via.placeholder.com/604x300/4A90E2/FFFFFF?text=Hero+Image`
- `{{.walking_image}}` → `https://via.placeholder.com/436x200/7ED321/FFFFFF?text=Walking+Image`
- `{{.transport_image}}` → `https://via.placeholder.com/436x200/F5A623/FFFFFF?text=Transport+Image`

### Статистика активности
- `{{.total_walking_distance}}` → `42.5` (км)
- `{{.avg_walking_distance_per_day}}` → `8500` (шагов)
- `{{.longest_route}}` → `3.2` (км)
- `{{.total_distance_by_car}}` → `156` (км)
- `{{.total_route_time_hours}}` → `12` (часов)
- `{{.total_route_time_min}}` → `35` (минут)

### Ссылки и CTA
- `{{.cta_walks_url}}` → `https://example.com/walks`
- `{{.cta_transport_url}}` → `https://example.com/transport`
- `{{.blockB_cta}}` → `https://example.com/important`

### Социальные сети и иконки
- `{{.app_name}}` → `Где мои дети`
- `{{.social_main_url}}` → `https://example.com/main`
- `{{.social_main_icon}}` → `https://via.placeholder.com/32x32/4A90E2/FFFFFF?text=ГМД`
- `{{.social_telegram_url}}` → `https://t.me/example`
- `{{.social_telegram_icon}}` → `https://via.placeholder.com/32x32/0088CC/FFFFFF?text=TG`
- `{{.social_vk_url}}` → `https://vk.com/example`
- `{{.social_vk_icon}}` → `https://via.placeholder.com/32x32/4C75A3/FFFFFF?text=VK`
- `{{.social_dzen_url}}` → `https://dzen.ru/example`
- `{{.social_dzen_icon}}` → `https://via.placeholder.com/32x32/FF6B35/FFFFFF?text=ДЗ`

### Контактная информация
- `{{.email}}` → `parent@example.com`
- `{{.terms_url}}` → `https://example.com/terms`
- `{{.faq_url}}` → `https://example.com/faq`
- `{{.unsubscribe_url}}` → `https://example.com/unsubscribe`

Логирование и мониторинг

Стек мониторинга и логирования на базе Prometheus, Grafana, Loki.

Сервисы
- prometheus — сбор метрик (порт 9090)
- node-exporter — системные метрики
- app — демо Spring-сервис (порт 8080)
- grafana — визуализация (порт 3000, admin/admin)
- loki — хранилище логов (порт 3100)
- promtail — сбор логов контейнеров

Запуск
docker-compose up --build -d

Grafana доступна на http://localhost:3000 (admin/admin).
Dashboard импортируется из dashboard.json.

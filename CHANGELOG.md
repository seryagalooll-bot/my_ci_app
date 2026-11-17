# Changelog

Все важные изменения проекта документируются в этом файле.
Формат основан на [Keep a Changelog](https://keepachangelog.com/ru/1.0.0/).

## [2.1.0] - 2026-11-17
### Added
- Автоматическое версионирование на основе коммитов Git.
- Интеграция с Firebase Remote Config.
- Добавлен Feature Toggle для скрытия/показа новой функции.
- Интеграция Firebase Crashlytics для мониторинга сбоев.
- Настроен CI/CD пайплайн (GitHub Actions) с отправкой сборок в App Distribution.

### Changed
- Дизайн приложения переработан на Material 3 (Dark Theme).
- Формат сборки изменен на APK (в связи с отсутствием Play Console).

### Fixed
- Устранены ошибки с правами доступа сервисного аккаунта Firebase.
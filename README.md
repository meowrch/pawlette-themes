# 🎨 Pawlette Themes - Official Themes for Pawlette
Этот репозиторий содержит список официальных тем для [Pawlette](https://github.com/meowrch/pawlette) 🐾

## Как использовать
1. **Установка тем**:
```bash
pawlette install-theme <theme-name>
```

2. **Просмотр доступных тем**:
```bash
pawlette list-themes
```

## Формат файла themes.list
Файл содержит список тем в формате:
```
theme-name https://direct-download-link/theme.tar.gz
```

Пример:
```
catppuccin https://github.com/meowrch/catppuccin-theme/releases/download/v1.0/catppuccin-mocha-v1.0.tar.gz
```

## Как добавить свою тему
1. Создайте архив темы в формате `.tar.gz`
2. Разместите его в релизах GitHub или в ветке репозитория
3. Создайте Pull Request с добавлением вашей темы в `themes.list`

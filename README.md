# Сайт-визитка

Готовый статический сайт для публикации через GitHub Pages.

## Что нужно заменить

- Название бренда и тексты в `index.html`
- Контакты в блоке `#contact`
- При желании цвета и отступы в `styles.css`

## Как опубликовать на GitHub Pages

```powershell
git add .
git commit -m "Add business card website"
git branch -M main
git remote add origin https://github.com/FoxDoCX/my-project-one.git
git push -u origin main
```

После push откройте на GitHub `Settings -> Pages`, выберите `Deploy from a branch`, затем `main` и папку `/ (root)`.

Ожидаемый адрес сайта:

```text
https://foxdocx.github.io/my-project-one/
```

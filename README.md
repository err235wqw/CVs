Короткий LaTeX-шаблон резюме с двухколоночной версткой и левой боковой панелью.

Содержимое
- `sidebarleft/main.tex` — основной файл резюме
- `sidebarleft/untitled.jpg` — фото/аватар (используется в шапке левой колонки)
- `sidebarleft/qrcode` — QR-код (вставляется в боковой колонке)

Сборка
1) Откройте `sidebarleft/main.tex` в LaTeX-редакторе
2) Соберите проект любым LaTeX-движком (например, latexmk)

Кастомизация
- Имя, роль и профиль: правый блок в начале `sidebarleft/main.tex`
- Навыки, контакты, образование, сертификаты: левая колонка `sidebarleft/main.tex`
- Цвета: блок `Color Definitions` в `sidebarleft/main.tex`

Примечания
- Шаблон использует шрифты и иконки из TeX Live пакетов (FontAwesome).

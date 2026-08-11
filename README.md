# TD2DR Palette Studio (Sonic.EXE: The Disaster 2D Remake)

Онлайн редактор палитр персонажей и файлов сохранений `2.bson` для игры **Sonic.EXE: The Disaster 2D Remake (TD2DR)**.

## 📁 Структура проекта для GitHub

```text
td2dr-palette-editor/
├── index.html        # Главный файл сайта (HTML + CSS + JS)
├── README.md         # Описание проекта
└── sprites/          # Папка со спрайтами персонажей
    ├── tails.png     # Tails (ID: 1)
    ├── knux.png      # Knuckles (ID: 2)
    ├── egg.png       # Dr. Eggman (ID: 3)
    ├── amy.png       # Amy Rose (ID: 4)
    ├── cream.png     # Cream (ID: 5)
    ├── sally.png     # Sally Acorn (ID: 6)
    ├── etails.png    # Executed Tails (ID: 21)
    ├── eknux.png     # Executed Knuckles (ID: 22)
    ├── eegg.png      # Executed Eggman (ID: 23)
    ├── eamy.png      # Executed Amy (ID: 24)
    ├── ecream.png    # Executed Cream (ID: 25)
    ├── esally.png    # Executed Sally (ID: 26)
    ├── OGexe.png     # Sonic.EXE / OG EXE (ID: 40)
    ├── chaos.png     # Chaos Hunter (ID: 41)
    ├── exetior.png   # Exetior (ID: 42)
    └── exeller.png   # Exeller (ID: 43)
```

## 🚀 Как запустить на GitHub Pages

1. Создайте новый публичный репозиторий на [GitHub](https://github.com/new), например `td2dr-palette-editor`.
2. Загрузите файл `index.html` и папку `sprites/` со всеми изображениями.
3. Перейдите в **Settings** (Настройки репозитория) -> **Pages** (слева в меню).
4. В разделе **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (или `master`), папка `/ (root)`
   - Нажмите **Save**.
5. Через 1-2 минуты сайт станет доступен по адресу: `https://ВАШ_НИК.github.io/td2dr-palette-editor/`

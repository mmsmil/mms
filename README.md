<div align="center">

<img src="app-icon.png" width="96" alt="MMS">

# MMS — Military Management System

**Офлайн Windows застосунок для управління військовим підрозділом**

[![Release](https://img.shields.io/github/v/release/mmsmil/mms?style=flat-square&color=3b82f6&label=версія)](https://github.com/mmsmil/mms/releases/latest)
[![Platform](https://img.shields.io/badge/платформа-Windows%2010%2F11-blue?style=flat-square)](https://github.com/mmsmil/mms/releases/latest)
[![License](https://img.shields.io/badge/ліцензія-тріал%2030%20днів-green?style=flat-square)](#ліцензування)

[**Завантажити →**](https://github.com/mmsmil/mms/releases/latest)

</div>

---

## Можливості

| Модуль | Опис |
|--------|------|
| **Особовий склад** | Облік особового складу, редагування, фото, експорт Excel та Word |
| **Графік нарядів** | Місячна сітка, групи чергування, відпустки, свята |
| **Документи** | Шаблони з плейсхолдерами, автозаповнення з бази даних |
| **Резервне копіювання** | Ручне та автоматичне резервне копіювання бази |
| **Теми** | 12 тем оформлення — dark, light, nord, gruvbox та інші |

## Безпека

- База даних зашифрована **AES-256** (SQLCipher)
- Пароль проходить через **argon2id** KDF
- Дані **не передаються в мережу** — повністю офлайн
- Прив'язка до машини — захист від несанкціонованого копіювання

## Встановлення

1. Завантаж інсталятор з [Releases](https://github.com/mmsmil/mms/releases/latest)
2. Запусти `MMS_x.x.x_x64-setup.exe`
3. Запусти MMS і пройди початкове налаштування

**Системні вимоги:** Windows 10/11 x64, ~50 MB

## Ліцензування

- **Тріал** — 30 днів безкоштовно, без обмежень функцій
- **Повна ліцензія** — необмежений термін використання

## Стек технологій

[Tauri v2](https://tauri.app) · [Svelte 5](https://svelte.dev) · [SQLCipher](https://www.zetetic.net/sqlcipher/) · Rust · TypeScript



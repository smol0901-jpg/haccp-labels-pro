# HACCP Labels Pro

Модуль печати этикеток сроков годности для общепита (HACCP).

> **Security (2026-11-04):** из рабочей копии убраны API-ключи.  
> Ключ Telegram-коннектора, попавший в историю git, **нужно ротировать** на стороне Netlify — он считался скомпрометированным (GitGuardian alert).

## Важно

- Не коммитьте `x-api-key`, токены и webhook secrets в репозиторий.
- Для Telegram: ключ только в env / Netlify Function secrets, в коде — placeholder.

## Стек

- HTML + CSS + Vanilla JS
- localStorage
- Telegram-коннектор через Netlify Function (ключ не в репо)

## Neural Architect Premium++

Часть экосистемы Neural Architect.

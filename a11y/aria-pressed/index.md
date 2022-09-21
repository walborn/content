---
title: "`aria-pressed`"
description: "ARIA-атрибут, который нужен для переключателей."
authors:
  - doka-dog
keywords:
  - доступность
  - ARIA
  - ARIA-атрибут
  - переключатель
  - тогл
related:
  - a11y/aria-intro
  - a11y/aria-attrs
  - html/button
tags:
  - doka
  - placeholder
---

## Кратко

[Состояние виджета](/aria-attrs/#atributy-vidzhetov) из [WAI-ARIA](/a11y/aria-intro/#specifikaciya). Означает состояние, в котором сейчас находится переключатель — тогл.

## Пример

```html
<button aria-pressed="true">Пауза</button>
```

## Как пишется

Добавьте к тегу атрибут `aria-pressed` с одним из значений:

- `true` — переключатель в состоянии «Включен».
- `false` — переключатель в состоянии «Выключен».
- `mixed` — у переключателя больше одного состояния.
- `undefined` (по умолчанию) — элемент ничего не переключает.

Атрибут можно использовать только для [`<button>`](/html/button/) или роли `button`. Без атрибута `aria-pressed` вспомогательные технологии не считают кнопку переключателем.

## Как понять

У переключателей обычно бывает два состояния — «Влючен» и «Выключен». Иногда они переключают больше одного состояния.
---
title: "`aria-valuemin`"
description: "ARIA-атрибут для минимального значения элемента с диапазоном чисел."
authors:
  - doka-dog
related:
  - a11y/aria-intro
  - a11y/aria-attrs
  - html/input
tags:
  - doka
  - placeholder
---

## Кратко

[Свойство виджета](/a11y/aria-attrs/#atributy-vidzhetov) из [WAI-ARIA](/a11y/aria-intro/#specifikaciya) для минимального значения элементов с диапазоном чисел — индикаторов загрузки, полей с выбором числа, ползунков и других.

В HTML на `aria-valuemin` похож атрибут `min` у [`<input>`](/html/input/).

## Как пишется

Добавьте к тегу `aria-valuemin` со значением в виде целого или дробного числа. К примеру, `1`, `0`, `2` или `0.5`. Важно, чтобы значение `aria-valuemin` было ниже или таким же, как у `aria-valuemax`.

`aria-valuemin` можно задавать только некоторым тегам и ролям:

- [`<input type="range">`](/html/input/#type) или ролям `range` и `slider`;
- [`<input type="number">`](/html/input/#type) или `spinbutton`;
- [`separator`](/a11y/role-separator/), когда разделитель интерактивный;
- [`<meter>`](/html/meter/) или `meter`;
- [`<progress>`](/html/progress/) или `progressbar`;
- `scrollbar`.

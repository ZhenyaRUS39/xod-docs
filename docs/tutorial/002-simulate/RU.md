---
title: Загрузка программы в микроконтроллер
version: 2.1.0
---

<!--
This file is auto-generated from the 'welcome-to-xod' project.
Do not change this file manually because your changes may be lost after
the tutorial update.

To make changes, change the 'welcome-to-xod' contents or 'before-1st-h2.md'.

If you want to change a Fritzing scheme or comments for it, change the
'before-1st-h2.md' in the documentation directory for the patch.

Then run auto-generator tool (xod/tools/generate-tutorial-docs.js).
-->

<div class="ui segment note">
<span class="ui ribbon label">Примечание:</span>
Это Веб-версия учебника встроенная прямо в XOD IDE. Чтобы обучение проходило лучше, мы рекомендуем установить
<a href="/downloads/">стационарную версию IDE для ПК</a> или запустить
<a href="/ide/">браузерную версию IDE</a>, и вы увидите там это же руководство.
</div>

# Загрузка программы в микроконтролле

![Screenshot of 101-upload](./101-upload.patch.png)

Чтобы программа работала, XOD преобразует ее в код на языке C ++, затем компилирует в двоичную прошивку, совместимую с выбранной платой, а затем отправляет двоичный файл на саму плату.

Этот процесс автоматизирован и выполняется незаметно после того, как вы нажмете “Upload”. Однако задействовано множество инструментов, и при первоначальной установке XOD IDE некоторые из них могут отсутствовать. При первой загрузке на плату новых данных может появится сообщение с просьбой загрузить и установить необходимые инструменты. Подтвердите их автоматическую установку и настройку. Имейте в виду, что это может потреблять около 200 МБ интернет-трафика и занимать несколько минут.

## Упражнение

Давайте загрузим этот патч на плату Arduino, чтобы увидеть, как мигает встроенный светодиод.

1.  Подключите плату Arduino к компьютеру с помощью кабеля USB.
2.  Загрузите программу. Для этого нажмите Deploy → Upload to Arduino в главном меню.
3.  Если некоторые инструменты отсутствуют, подтвердите установку, нажав Download & Install в появившемся сообщении.

Посмотрите на мигание встроенного светодиод, обычно он маркирован `L` на плате.

Измените значение `IVAL` в ноде `clock` и загрузите программу снова. Посмотрите, как меняется частота мигания светодиода.

## 👆 Подсказки

Для загрузки программы вы можете использовать кнопку со значком молнии на панели инструментов вместо использования кнопки в главном меню.

<div class="ui grid">
  <div class="five wide column left aligned ">
    <a href="../100-hardware/">← Previous lesson</a>
  </div>
  <div class="six wide column center aligned ">
    <a href="../">Index</a>
  </div>
  <div class="five wide column right aligned ">
    <a href="../102-interactive/">Next lesson →</a>
  </div>
</div>

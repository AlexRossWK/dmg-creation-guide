# dmg-creation-guide


1. Запускаем Дисковую утилиту (Disk Utility), в трее : файл→новый образ→ пустой образ.
2. В появившемся окне назначаем название для dmg, а также требуемый размер (может быть больше, чем потенциальное содержимое, но не меньше), нажимаем Сохранить.
3. На данном этапе у нас есть созданный пустой dmg, по клику на него распаковывается содержимое dmg  и создается файл, который мы можем открыть.
4. Открываем TestDMG и перетаскиваем туда наше приложение (.app), а также псевдоним папки Application (правый клик по папке Application→ создать псевдоним)
5. Есть возможность кастомизировать dmg файл. Правый клик по открытому dmg файлу→ показать параметры вида. Откроется следующее окно:
На нем, для нужно выбрать "Всегда открывать как значки". Также можно поставить размер значков, а также цвет фона. Также в качестве фона  есть возможность добавить изображение, для этого:
 - перетаскиваем в dmg файл нужное изображене
 - перетаскиваем это изображение (например: Image.png) из dmg файла в следующее окно (в параметрах вида):
 - открываем Terminal
 - cd /Volumes/TestDMG
 - mv Image.png .Image.png
6. Закрываем DMG файл. Клик по нему правой мышкой→извлечь.
7. Снова запускаем Дисковую утилиту (Disk Utility), в трее: Образы→преобразовать→выбираем  наш dmg.
8. В появившемся окне ставим финальное название для нашего DMG и нажимаем преобразовать.

Итог: готовый для распространения dmg файл с нашим приложением(или с чем-либо еще)
# dmg-creation-guide

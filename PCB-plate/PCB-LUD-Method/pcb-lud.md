# Инструкция по работе с Лазерно-Утюжным методом (ЛУТ)

> Автор - Трофимов М. [@Matroftt](https://github.com/Matroftt)

## Импорт рисунка платы из под Proteus

1. В окне с готовой PCB платой выбираем в верху экрана "Output -> Print Layout"
2. Размещаем рисунок от краев листа на несколько сантиметров
3. Нажимаем ОК, и сохраняем плату в PDF-файл

## Печать

1. Включаем принтер и вставляем в него бумагу
2. В PDF-файле с платой нажимаем пкм по документу -> печать
3. Выбираем фактический размер
4. Нажимаем 'печать'

## Подготовка текстолита

 1. Проверка размера: Берем компоненты для размещения на плате, Проверяем, подходят ли они к контактам на плате. Если да, то все хорошо. Если нет, то вернитесь к графе [[#Печать]]
2. кладем текстолит, обводим на нем наш рисунок платы простым карандашом
3. Вырезаем текстолит ножницами по металлу
4. Зачищаем его края наждачной бумагой, далее зачищаем металлическую поверхность
5. Повторяем первый пункт (печать),
> НО вместо обычной бумаги используем желтую парафиновую.
6. Рисунок обрезаем, с отступом 5мм от каждой стороны

## 3. Перенос рисунка

1. Включаем ламинатор, ставим температуру чуть больше, чем 160 градусов.
2. Включаем нагрев переключателем.
3. Когда загорится зеленая лампочка - то аппарат готов.
4. Переворачиваем рисунок лицом вниз к текстолиту, к металлической поверхности.
5. Загоняем текстолит внутрь ламината.
> [!WARNING] 
> :warning: плата горячая! соблюдайте меры предосторожности и используйте перчатки. И помните **чем** написана техника безопасности!
6. Повторяем эту процедуру 2 раза для каждой стороны.

  ## Процесс травления платы
 
1. Привязка платы: Шуруповертом просверливаем в углу платы отверстие; В это отверстие загоняем провод длиной около 15 см; Завязываем его на узел, чтобы можно было вытянуть из раствора.
2. Достаем травильную ванну, Заливаем в травильную ванну щелочь, Ложим внутрь плату так, чтобы ее можно было достать, и закрываем чашу
3. Включаем в сеть печку, ее нагрев должен находиться на 2-ой мощности, а также включаем мотор.

> [!warning]
> :warning: Процесс травки платы начался. Внимание - При открывании ванны крышку нужно ложить так, чтобы щелочь не стекала на другие поверхности! при попадании щелочи в глаза возможен химический ожег!

4. Засекаем таймер на 15 минут
5. По истечении времени смотрим на плату; Если она полностью зеленоватая, то плата протравилась, переходим к пункту 6; Если у нее есть непротравленные металлические пятна, то засекаем еще на 5 минут, и снова смотрим; если они остались, но уменьшились, то снова засекаем и т.д. повторять до достижения удовлетворительного результата.
6. Выключаем печку и мотор ванны.
7. Стираем дорожки ацетоном салфеткой над раковиной.
8. Открываем ванну, осторожно выливаем щелочь обратно в банку, закрываем ванну.

  
## 5. Процесс создания в плате отверстий
- Ударяем все места для последующего сверления **НЕ НАСКВОЗЬ** молотком по керну (керним). :warning: **НЕ ПРОБИВАЕМ а наносим "вмятину"**
- Готовим станок к работе; Закрепляем станок на месте работы; Включаем три объекта в сеть:
    - Само сверло
    - Кулер для сверла
    - светодиодную лампу
- Сверлим все накерненные ранее отверстия.
     - Один из принципов сверления - 
       Левой рукой держать низ станка и большим пальцем давить на платформу со сверлом.
- По окончанию выключаем станок.
- Берем "фонарную доску" и ложим на нее плату;
       - Проверяем, чтобы не было не просверленных отверстий. Также можно взять коннектор, и попробовать засунуть его внутрь, для проверки.

# Плата готова к пайке и использованию.

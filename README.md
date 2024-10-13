### Привет
Я Артём Макаров, разработчик игр на Unity.

---
### Мои проекты:

[Tower Defense (дипломный проект)](https://github.com/jing3r/TowerDefense)

Разработано три режима игры:
1. Classic - привычный Tower defense с шестью фракциями и шестью башнями в каждой. Башни могут быть однократно улучшены.
2. Mastermind - игрок на старте получает 6 башен из случайно выбранных фракций, по одной башне каждого круга постройки. Также доступны единоразовые улучшения.
3. Merge - игрок может строить только случайные башни первого круга постройки. Улучшение заменено слиянием двух одинаковых башен в одну башню на один круг выше. Финальные башни по-прежнему могут быть один раз улучшены.
Помимо постройки башен, ресурсы можно тратить на активацию способностей и повышение атаки всех башен определённого типа, а также на повышение дохода.
После 20 волны наступает бесконечная волна, усиливающаяся со временем. 

[HexBattler](https://github.com/jing3r/HexBattler) 

Прототип сцены пошагового сражения на гексагональной карте.
1. Генерация
Процесс генерации начинается с центральной гексагональной ячейки (тайла). Затем генерируется настраиваемое количество концентрических кругов из тайлов (среди них с разной вероятностью могут быть обычные, труднопроходимые, высотные, низинные, а также непроходимые тайлы-укрытия). После этого - внешний круг, который состоит только из непроходимых тайлов. На последнем проходимом круге с разных сторон карты создаются два отряда юнитов.
2. Особенности тайлов и механика промахов
Высота тайла и тайлы-укрытия влияют на шанс попадания дальними атаками. Есть 5% шанс промахнуться по основной цели, но попасть по стоящей рядом с ней.попасть выстрелом по противнику, стоящему рядом с целью атаки.
3. Способности и классы
Сейчас реализованы базовые способности - движение, ближняя атака, дальняя атака, защита. На основе их логики могут быть созданы практически любые способности. Тонкая настройка параметров юнитов в комбинации с новыми способностями позволяют создавать классы.
4. Условия победы: в разработке.
Либо победить всех юнитов соперника, либо удержать находящийся в центе карты флаг в течение трёх раундов.
5. AI: в разработке
Сейчас прототип тестируется как сражение двух игроков. AI будет основан на классе юнита: так, стрелки будут стремиться занять безопасную возвышенность, бойцы первой линии - атаковать вражеских стрелков, а юниты поддержки - балансировать между двумя линиями в готовности помочь там, где это нужно.

[GrayCubes](https://github.com/yourusername/GrayCubes)

Приложение для создания пиксельных изображений путём поворота (случайной либо выбранной гранью вверх) кубов с гранями разных оттенков серого. Есть возможность сохранения и загрузки композиций. Предполагается, что пользователь может сгенерировать абстрактное изображение, увидеть в нём что-то (как в пятнах Роршаха) и довести это до осмысленного изображения. Вдохновлено фотоконструктором Mozabrick, превращающим реальные фотографии в пиксельные.

---
### Сертификат о прохождении обучения:
[Разработчик игр на Unity](https://github.com/jing3r/jing3r/blob/main/UnityDev.pdf)
<!--
**jing3r/jing3r** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

### Привет
Меня зовут Артём, я Unity-разработчик

## 🚀 Избранные проекты

### Lance Fournie: Buhurt Manager (Прототип)

![Gameplay GIF для Lance Fournie](https://github.com/jing3r/jing3r/raw/main/LanceFournie.gif?raw=true)

Тактический менеджер, где вы готовите средневековое "копьё" к турнирным боям, с фокусом на стратегии и подготовке, а не на прямом управлении.

*   **Ключевые решения и особенности:**
    *   Концепция, построенная на нетривиальном сочетании жанров: спортивного симулятора и симулятора тактики малых групп, с акцентом на историческую достоверность.
    *   Разработана система навигации юнитов на базе алгоритма **A* Pathfinding**.
    *   Применен паттерн **Object Pool** для оптимизации UI и предотвращения падения производительности.
    *   Чистая, модульная архитектура, построенная на принципах **SOLID**.

*   **Ссылки:**
    *   [**▶️ Поиграть в браузере (itch.io)**](https://jing3r.itch.io/lance-fournie)
    *   [**📄 Посмотреть код и README проекта**](https://github.com/jing3r/LanceFournie)

---

### Blobber RPG (Прототип)

![Gameplay GIF для Blobber RPG](https://github.com/jing3r/jing3r/blob/main/Blobber.gif?raw=true)

Технический прототип партийной RPG ("blobber"), сфокусированный на архитектуре ключевых игровых систем и гибкости их настройки.

*   **Ключевые решения и особенности:**
    *   Гибкая система способностей, построенная на **Scriptable Objects** и атрибуте **`[SerializeReference]`**, позволяет создавать новые умения в редакторе без написания кода.
    *   Динамический ИИ на основе паттерна **State Machine** с системой отношений (Alignment).
    *   Продвинутая система экипировки с использованием **`[Flags]` Enum** для обработки предметов, занимающих несколько слотов.
    *   Персистентный мир и универсальная система сохранений через интерфейс **`ISaveable`**.

*   **Ссылки:**
    *   [**▶️ Поиграть в браузере (itch.io)**](https://jing3r.itch.io/blobber)
    *   [**📄 Посмотреть код и README проекта**](https://github.com/jing3r/Blobber)

---

### Gray Cubes (Песочница)

![Gameplay GIF для Gray Cubes](https://github.com/jing3r/jing3r/blob/main/GrayCubes.gif?raw=true)

Интерактивная песочница для создания пиксельной мозаики и симуляции клеточных автоматов, построенная на принципах слабой связанности модулей.

*   **Ключевые решения и особенности:**
    *   Модульная архитектура, построенная на паттерне **Service Locator** (`GameManager`), для обеспечения слабой связанности систем.
    *   Логика смещена с глобальных менеджеров на сами объекты (`CubeController`), следуя принципам **ООП**.
    *   Полностью инкапсулированный модуль игры "Жизнь", который использует существующие системы как сервисы, не требуя их изменения.

*   **Ссылки:**
    *   [**▶️ Поиграть в браузере (itch.io)**](https://jing3r.itch.io/graycubes)
    *   [**📄 Посмотреть код и README проекта**](https://github.com/jing3r/GrayCubes)

---

## 🛠️ Технологии и навыки

*   **Язык:** C#
*   **Unity:** UGUI, Particle System, AR (Vuforia)
*   **Инструменты:** Git, GitHub, Visual Studio Code, Blender
*   **Архитектурные принципы:** SOLID, ООП, чистый код, модульная архитектура
*   **Паттерны проектирования:** State, Observer, Singleton, Service Locator, Object Pool



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

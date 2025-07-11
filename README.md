### **Лабораторная работа №5. Интерактивные элементы: модальные окна и обработка событий в JavaScript**  

**Цель работы:**  
Научиться создавать интерактивные элементы веб-страницы с использованием JavaScript: модальные окна, обработку кликов и динамическое изменение контента.  

**Описание работы:**  
1. **Верстка статичного контента**:  
   - Создание карточек новостей с заголовками, текстом и кнопками.  
   - Стилизация карточек через CSS (фон, границы, тени, эффекты при наведении `:hover`).  

2. **Реализация модального окна**:  
   - Разметка скрытого модального окна (`display: none`).  
   - Позиционирование окна по центру экрана (`position: fixed`, `flexbox`).  
   - Затемнение фона при открытии (`background-color: rgba()`).  

3. **Программирование на JavaScript**:  
   - Обработка кликов по кнопкам через `addEventListener`.  
   - Динамическая подстановка контента в модальное окно (заголовок и текст).  
   - Закрытие окна при клике вне его области.  

4. **Адаптивность и визуальные эффекты**:  
   - Тени для кнопок (`box-shadow`).  
   - Изменение цвета карточки при наведении (например, на красный).  
   - Центрирование основного контента (`max-width: 50%`).  

**Ключевые технологии:**  
- **HTML5**: Семантическая структура (`main`, `div`).  
- **CSS3**:  
  - Flexbox для выравнивания.  
  - Псевдокласс `:hover`.  
  - Свойства `position`, `z-index`, `box-shadow`.  
- **JavaScript**:  
  - Работа с DOM (`querySelector`, `getElementById`).  
  - Обработчики событий (`click`).  
  - Динамическое изменение текста (`textContent`).  

**Пример реализации:**  
- Кнопки в карточках имеют атрибут `data-id` для связи с контентом.  
- Модальное окно появляется при клике и исчезает при клике на фон.  
- Контент окна подгружается из объекта `texts` и `headers`.  

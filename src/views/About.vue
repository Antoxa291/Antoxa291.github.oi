<template>
  <div class="about">
    <h1>Тестовe завдання: написати простий редактор тексту</h1>
    <h3>Технологія: Vue.js</h3>
    <hr />
    <h3>Вимоги:</h3>
    <h4>Функціонал:</h4>
    <ul>
      <li>Додавати, редагувати, видаляти текст, без використання input.</li>
      <h6>Buttons:</h6>
      <li>Кнопкa для зміни кольору</li>
      <li>Кнопкa для зміни розміру шрифту</li>
      <li>Кнопкa для зміни фонового кольору</li>
      <h6></h6>
      <li>
        Можливість змінювати атрибути (колір, шрифт, фон) для виділеної ділянки.
        тексту.
      </li>
      <h6>Нюанси</h6>
      <li>Без використання &lt;input&gt;.</li>
      <li>
        Використайте власні компоненти, реалізуйте передачу даних через emit ta
        props.
      </li>
      <li>
        Текст не повинен мати вкладеностей (&lt;span&gt; в span-і).
      </li>
      <li>
        Текст не повинен містити додаткових тегів &lt;div&gt; чи &lt;font&gt;
      </li>
      <h6>Додатково:</h6>
      <li>
        Створіть можливість переводити текст в json-формат. Масив повинен
        містити властивості: текстовий блок, його властивості: розмір, колір,
        фон. Основна вимога: Суміжні блоки тексту з однаковими атрибутами
        (колір, розмір, фон) мають об'єднуватись так, щоб суміжні блоки з
        однаковими атрибутами не дублювались.
      </li>
    </ul>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss"></style>

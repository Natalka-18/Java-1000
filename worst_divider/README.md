<h1 class="title">Наихудший делитель (23%)</h1>
<p><b>Время: 1 сек.<br>Память: 16 Мб<br>Сложность: 23%</b></p>
<p>Будем говорить, что число a лучше числа b, если сумма цифр a больше суммы цифр числа b, а в случае равенства сумм их цифр, если число a меньше числа b. Например, число 124 лучше числа 123, так как у первого из них сумма цифр равна семи, а у второго — шести. Также, число 3 лучше числа 111, так как у них равны суммы цифр, но первое из них меньше.</p>
<p>Дано число n. Найдите такой его делитель d (само число n и единица считаются делителями числа n), что любой другой делитель c числа n лучше, чем d.</p>
<h2>Формат ввода</h2>
<p>Первая строка входного файла input.txt содержит целое число n (1 ≤ n ≤ 10<sup>5000</sup>).</p>
<h2>Формат вывода</h2>
<p>В выходной файл output.txt выведите ответ на задачу.</p>
<h3>Примеры</h3>
<table class="sample-tests">
  <thead>
     <tr>
        <th>Ввод</th>
        <th>Вывод</th>
     </tr>
  </thead>
  <tbody>
     <tr>
        <td>10</td>
        <td>10</td>
     </tr>
     <tr>
        <td>239</td>
        <td>1</td>
     </tr>
  </tbody>
</table>
<h1 class="title">Несложная сортировка (25%)</h1>
<p><b>Время: 1 сек.<br>Память: 16 Мб<br>Сложность: 25%</b></p>
<p>Пусть x – целое положительное число, а k – натуральное число от 1 до 10. Пусть s(x, k) равно сумме цифр числа x, представленного в системе счисления по основанию k.</p>
<p>Задано n чисел a<sub>1</sub>, a<sub>2</sub>, ..., a<sub>n</sub>. Необходимо вычислить последовательность b<sub>i</sub> по формуле b<sub>i</sub> = s(a<sub>i</sub>, k<sub>1</sub>) • s(a<sub>i</sub>, k<sub>2</sub>), после чего отсортировать последовательность b<sub>i</sub> по неубыванию.</p>
<h2>Формат ввода</h2>
<p>Первая строка входного файла input.txt содержит три целых числа: n, k<sub>1</sub>, k<sub>2</sub> (1 ≤ n ≤ 1000, 2 ≤ k<sub>1</sub>, k<sub>2</sub> ≤ 10). Вторая строка содержит n целых чисел: a<sub>i</sub> (1 ≤ a<sub>i</sub> ≤ 10<sup>9</sup>).</p>
<h2>Формат вывода</h2>
<p>В выходной файл output.txt выведите n чисел – bi в требуемом порядке.</p>
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
        <td>9 10 10<br>
            1 2 3 4 5 6 7 9 8</td>
        <td>1 4 9 16 25 36 49 64 81</td>
     </tr>
     <tr>
        <td>10 2 2<br>
            1 2 4 8 16 32 64 128 256 512</td>
        <td>1 1 1 1 1 1 1 1 1 1</td>
     </tr>
  </tbody>
</table>
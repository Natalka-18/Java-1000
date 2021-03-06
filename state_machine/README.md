<h1 class="title">Конечные автоматы (11%)</h1>
<p><b>Время: 1 сек.<br>Память: 16 Мб<br>Сложность: 11%</b></p>
<p>Однажды известный профессор обнаружил описания k конечных автоматов. По его мнению, нетривиальность конечного автомата, имеющего n состояний и m переходов, можно описать целым числом d = 19m + (n + 239)*(n + 366) / 2 . Чем больше d, тем больший интерес для науки представляет изучение его свойств.</p>
<p>Помогите профессору вычислить нетривиальность имеющихся у него автоматов.</p>
<h2>Формат ввода</h2>
<p>Первая строка входного файла input.txt содержит целое число k (1 ≤ k ≤ 10000) – количество конечных автоматов. Следующие k строк содержат по два целых числа n<sub>i</sub> (0 ≤ n<sub>i</sub> ≤ 1000) и m<sub>i</sub> (0 ≤ m<sub>i</sub> ≤ 26n<sub>i</sub><sup>2</sup>) – число состояний и переходов i-го автомата.</p>
<h2>Формат вывода</h2>
<p>Выходной файл output.txt должен состоять из k строк. На i-й строке выходного файла выведите одно число – нетривиальность i-го автомата.</p>
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
            <td>4<br>
                2 0<br>
                13 20<br>
                5 23<br>
                18 6</td>
            <td>44344<br>
                48134<br>
                45699<br>
                49458</td>
         </tr>
         <tr>
             <td>2<br>
                 15 20<br>
                 1000 26000</td>
             <td>48767<br>
                 1340237</td>
          </tr>
      </tbody>
   </table>
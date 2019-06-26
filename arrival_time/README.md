<h1 class="title">Время прибытия (15%)</h1>
<p><b>Время: 1 сек.<br>Память: 16 Мб<br>Сложность: 15%</b></p>
<p>Задано время отправления поезда и время в пути до конечной станции. Требуется написать программу, которая найдет время прибытия этого поезда (возможно, в другие сутки).</p>
<h2>Формат ввода</h2>
<p>Входной файл input.txt содержит две строки. В первой строке задано время отправления, а во второй строке – время в пути. Время отправления задается в формате «HH:MM», где HH время в часах, которое принимает значение от 00 до 23, ММ – время в минутах, которое принимает значение от 00 до 59. Время в пути задается двумя неотрицательными целыми числами – количество часов и количество минут. Числа разделяются одним пробелом. Количество часов не превышает 120, минут – 59.</p>
<h2>Формат вывода</h2>
<p>Выходной файл output.txt должен содержать одну строку – время прибытия поезда на конечную станцию. Формат вывода этого времени совпадает с форматом ввода времени отправления.</p>
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
        <td>00:00<br>
            10 10</td>
        <td>10:10</td>
     </tr>
     <tr>
         <td>01:02<br>
             4 6</td>
         <td>05:08</td>
      </tr>
      <tr>
          <td>11:00<br>
              22 0</td>
          <td>09:00</td>
       </tr>
  </tbody>
</table>
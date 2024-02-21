<table>
  <thead>
    <tr>
      <td rowspan=4 align="center">
        1. Составить такой набор тестовых данных для магазина (в формате количество баллов - ожидаемая скидка), при котором мы будем знать, что в соответствии со своими накопленными баллами покупатель получит верную скидку.
      </td>
    </tr>
  </thead>
  <thead>
  </thead>
</table>

<table>
  <thead>
    <tr>
      <td rowspan=4 align="center">Скидка</td>
      <td rowspan=4 align="center">Класс Эквивалентности</td>
      <td rowspan=4 align="center">Границы</td>
      <td rowspan=4 align="center">Значения для тестов</td>
      <td rowspan=4 align="center">Комментарии</td>
    </tr>
    </thead>
    <tbody>
      <tr>
         <td rowspan=4 align="center">1%</td>
        <td rowspan=4 align="center">0 - 100</td>
        <td rowspan=4 align="center"> Нижняя - 0 <br> Верхняя - 100</td>
        <td rowspan=4 align="center">-1, 0, 1, 99, 100, 101</td>
        <td rowspan=4 align="center"></td>
      </tr>
      </tbody>
      <tbody>
         <tr>
        <td rowspan=4 align="center">3%</td>
        <td rowspan=4 align="center">101 - 500</td>
        <td rowspan=4 align="center">Нижняя - 101 <br> Верхняя - 500</td>
        <td rowspan=4 align="center"> 102, 499, 500, 501</td>
        <td rowspan=4 align="center">В этой проверке не беру значения нижней границы 100 и 101, чтобы избежать дублирования</td>
      </tr>
      </tbody>
     <tbody>
       <tr>
        <td rowspan=4 align="center">5%</td>
        <td rowspan=4 align="center"> 500 - 2000</td>
        <td rowspan=4 align="center">Нижняя - 101 <br> Верхняя - 500</td>
        <td rowspan=4 align="center">1999, 2000, 2001</td>
        <td rowspan=4 align="center">Для этого номинала скидки не беру значения нижней границы, так как они уже были протестированы в предыдущей проверке.</td>
      </tr>
     </tbody>
       <tbody>
         <tr>
        <td rowspan=4 align="center">10%</td>
        <td rowspan=4 align="center">2001 - +∞</td>
        <td rowspan=4 align="center">Нижняя - 2001 <br> Верхняя - +∞</td>
        <td rowspan=4 align="center"> 2002</td>
        <td rowspan=4 align="center"> По аналогии, тут будет достаточно проверить значение на 1 выше, чтобы избежать дублирование тестов</td>
      </tr>
       </tbody>
</table>


<table>
  <thead>
    <tr>
       <td rowspan=4 align="center">2. Укажите минимальный набор конфигураций (браузер, ОС, язык сайта), который вы бы использовали для тестирования данного сайта.</td>
       <td rowspan=4 align="center">Буду использовать попарное тестирование. В данном случае тестирование на платформе Android проводится отдельно </td>
    </tr>
  </thead>
</table>
<table>
  <thead>
    <tr>
      <td rowspan=4 align="center">Номер теста</td>
      <td rowspan=4 align="center">Язык сайта</td>
      <td rowspan=4 align="center">ОС</td>
      <td rowspan=4 align="center">Браузер</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan=4 align="center">1</td>
      <td rowspan=4 align="center">RU</td>
      <td rowspan=4 align="center">Windows</td>
      <td rowspan=4 align="center">Firefox</td>
    </tr>
  </tbody>
   <tbody>
    <tr>
      <td rowspan=4 align="center">2</td>
      <td rowspan=4 align="center">RU</td>
      <td rowspan=4 align="center">Ubuntu</td>
      <td rowspan=4 align="center">Opera</td>
    </tr>
  </tbody>
   <tbody>
    <tr>
      <td rowspan=4 align="center">3</td>
      <td rowspan=4 align="center">EN</td>
      <td rowspan=4 align="center">Ubuntu</td>
      <td rowspan=4 align="center">Firefox</td>
    </tr>
  </tbody>
   <tbody>
    <tr>
      <td rowspan=4 align="center">4</td>
      <td rowspan=4 align="center">EN</td>
      <td rowspan=4 align="center">Windows</td>
      <td rowspan=4 align="center">Opera</td>
    </tr>
  </tbody>
   <tbody>
    <tr>
      <td rowspan=4 align="center">5</td>
      <td rowspan=4 align="center">RU</td>
      <td rowspan=4 align="center">Android</td>
      <td rowspan=4 align="center">Chrome</td>
    </tr>
  </tbody>
   <tbody>
    <tr>
      <td rowspan=4 align="center">6</td>
      <td rowspan=4 align="center">EN</td>
      <td rowspan=4 align="center">Android</td>
      <td rowspan=4 align="center">Chrome</td>
    </tr>
  </tbody>
</table>

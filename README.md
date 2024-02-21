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
        <td rowspan=4 align="center">101 - 499</td>
        <td rowspan=4 align="center">Нижняя - 101 <br> Верхняя - 499</td>
        <td rowspan=4 align="center"> 100, 101, 102, ,498, 499, 500 </td>
        <td rowspan=4 align="center"></td>
      </tr>
      </tbody>
     <tbody>
       <tr>
        <td rowspan=4 align="center">5%</td>
        <td rowspan=4 align="center"> 500 - 2000</td>
        <td rowspan=4 align="center">Нижняя - 500 <br> Верхняя - 2000</td>
        <td rowspan=4 align="center"> 499, 500, 501, 1999, 2000, 2001</td>
        <td rowspan=4 align="center"></td>
      </tr>
     </tbody>
       <tbody>
         <tr>
        <td rowspan=4 align="center">10%</td>
        <td rowspan=4 align="center">2001 - +∞</td>
        <td rowspan=4 align="center">Нижняя - 2001 <br> Верхняя - +∞</td>
        <td rowspan=4 align="center"> 2000, 2001, 2002</td>
        <td rowspan=4 align="center"> </td>
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
<table>
  <thead>
    <tr>
      <td rowspan=4 align="center">3.1 Какой категории ui-элементов относится данный элемент? (см. доп. материалы) </td>
      <td rowspan=4 align="center">3.2 Приведите пример - ui-элемента из категории Input Controls.</td>
      <td rowspan=4 align="center">3.3 Является ли командная строка частью GUI?</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan=4 align="center">Данный элемент относится к навигационным компонентам</td>
      <td rowspan=4 align="center">Например, dropdown с выбором страны проживания пользователя</td>
      <td rowspan=4 align="center">Командная строка является частью CLI - Command Line Interface</td>
    </tr>
  </tbody>
</table>
<table>
  <thead>
    <tr>
      <td rowspan=4 align="center">4.Какой тип мобильного приложения не имеет доступа к внутреннему функционалу смартфона, например пушам?</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan=4 align="center"> Веб-приложения. Они не могут получить доступ к функциям системы и самого устройства, которым и является пуш-уведомление</td>
    </tr>
  </tbody>
</table>

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
        <td rowspan=4 align="center"> В данном случае я задаю класс эквивалентности как по условию, и дальше пользуюсь анализом граничных значений. Беру значения нижней границы, тестирую -1 как негативную проверку, 0 - так как его рекомендуют тестировать обязательно, 1 как значение из заданного диапазона. Таким же образом тестируется верхняя граница.</td>
      </tr>
      </tbody>
      <tbody>
         <tr>
        <td rowspan=4 align="center">3%</td>
        <td rowspan=4 align="center">101 - 499</td>
        <td rowspan=4 align="center">Нижняя - 101 <br> Верхняя - 499</td>
        <td rowspan=4 align="center"> 100, 101, 102, ,498, 499, 500 </td>
        <td rowspan=4 align="center">В этом случае я определяю класс эквивалетности границами 101 и 499. В условии задачи написано "до 500" Здесь, руководствуясь логикой и своим эмпирическим опытом я выбираю верхнюю границу числом 499, так как это последнее число в данном диапазоне, которое будет протестировано так же, как и число 102 из нижней границы. Проблемы и баги исходя из условия могут возникнуть в числе 500, потому что не понятно к каком классу скидки оно относится, исходя из условий.  </td>
      </tr>
      </tbody>
     <tbody>
       <tr>
        <td rowspan=4 align="center">5%</td>
        <td rowspan=4 align="center"> 500 - 2000</td>
        <td rowspan=4 align="center">Нижняя - 500 <br> Верхняя - 2000</td>
        <td rowspan=4 align="center"> 499, 500, 501, 1999, 2000, 2001</td>
        <td rowspan=4 align="center"> Исходя из предыдущего класса, руководствуясь логикой и своим эмпирическим опытом опять же, я выбираю границу класса от 500 до 2000, так как число 499 при проверке выдаст нам результат предыдущего класса, число 500 выдаст нам тот результат, который выдаст. Мне до сих пор не понятно, как будет отрабатывать программа в данном случае. Число 501 выдаст нам тот же результат, который выдаст нам любое число до 2001.  </td>
      </tr>
     </tbody>
       <tbody>
         <tr>
        <td rowspan=4 align="center">10%</td>
        <td rowspan=4 align="center">2001 - + ∞</td>
        <td rowspan=4 align="center">Нижняя - 2001 <br> Верхняя - +∞</td>
        <td rowspan=4 align="center"> 2000, 2001, 2002</td>
        <td rowspan=4 align="center"> В данном классе я тестирую только нижнюю границу, так как верхняя не определена и может идти вплоть до + ∞. Так как исчерпывающее тестирование невозможно, значение 2002 выдаст тот же самый результат как и любое другое значение вплоть до + ∞ </td>
      </tr>
       </tbody>
</table>
<h3>P.S. Как мне кажется, в первом задании, если оно происходит на реальном проекте, нужно вернуться к анализу требований и поправить значения границ.</h3>

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

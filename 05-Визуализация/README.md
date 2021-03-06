# Анализ рынка общественного питания Москвы
Открываем кафе — оно оригинальное, гостей должны обслуживать роботы. Вместе с партнёрами мы решились обратиться к инвесторам. Их интересует текущее положение дел на рынке — сможет ли данный формат заведения общественного питания снискать популярность на долгое время, когда все зеваки насмотрятся на роботов-официантов? <br>
<br>
**Данные:** открытые данные о заведениях общественного питания в Москве<br>
<br>
**Цели:**
- подготовить данные к исследованию
- изучить рынок общепита Москвы
- результаты исследований презентовать инвесторам<br>
<br>

**Вывод:**
- категория 'кафе' составляют около `40% (6 068)` от всех (`15 273`) объектов общественного питания
- категория 'столовая' составляет `17%` 
- категория 'ресторан' составляет `15%`
- категория 'фастфуд' составляет примерно `12%`
- на все остальные (бар, буфет, кафетерий, закусочная, кулинария) приходится `16%` от всех данных

Представителей **"несетевого" бизнеса** (`12 310 - 80.6 %`) общественного питания больше в 4 раза, чем представителей **"сетевого" бизнеса** (`2 963 - 19.4 %`)

Для сетевого распространения объектов общественного питания характерно: 
- доля сетевого бизнеса больше всего приходится на заведения типа "кафе", 47%   
- далее следуют такие типы общественного питания, как "фастфуд" и "рестораны". Их доля составляет 26.6% и 18% соответственно
- на все остальные приходится менее 9 %, среди которых "кулинария", "закусочные", "кафетерии" и "бары"

**Посадочные места:**
- **cтоловые**(в среднем `131 посадочное место`) и **рестораны** (`99 посадочных мест`) в среднем имеют наибольшее количество посадочных мест среди всех типов заведений общественного питания. В данных есть рестораны, которые вмещают до `1500` посетителей, а столовые до `1400` посетителей
- **барам** характерно в среднем `45` посадочных мест, хотя среди данных есть такой бар, который вмещает аж 1700 посадочных мест
- для **кафетериев, закусочных и кулинарных заведений** нет необходимости иметь большое количество посадочных мест, поэтому они и находятся в конце списка 
- при анализе графика данных о заведениях с 0 посадочных мест стоит отметить, что безусловным лидером в этом разрезе являются заведения типа **"фастфуд"**, далее идут **кафе**, затем **закусочные**. Кроме этого, меньше всего заведений с 0 пасадочных мест имеют **столовые**, **бары** и **рестораны** <br>
<br>

Визуализация с помощью библиотек mathplotlib, seaborn и plotly. Большинство моих визуализаций данных сделаны с помощью библиотеки plotly, возможно поэтому некорректно отображаются графики на github. <br>
<br>
**Библиотеки**: `pandas, matplotlib.pyplot, seaborn, plotly, math, numpy, scipy`

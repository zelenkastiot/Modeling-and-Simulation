# Моделирање и симулација
**Зимски семестар, 2020** <br> <br>
**Проект** 

Продолжено истражување од [COVID-19_book](https://zelenkastiot.github.io/COVID-19_book/intro): Во ова продолжување не интересира како при природно стекнат имунитет на стадо е распределен имунитетот по единки во однос на нивната повраност. Да се види следното на СИР модел, како едноставен и делумно соодветен на Ковид:


 1. Се зема мрежа со дадена распределба на број на соседи (degree distribution). Се решаваат равенките на еволуција на веројатност на заразен кога јазлите се групирани по број на соседи (degree based mean field DBMF). Овие равенки може да се земат од ревијалниот труд, од страна 22 . За разни параметри на заразност (ламбда) кога има епидемија, се гледа распределбата на веројатноста на заразен, или оздравен, на крајот од епидемијата, во функција од бројот на соседи. После тоа се гледа колкав процент има имунитет. Треба да се спореди за истото ламбда, кај компартментен модел, колкав процент ќе има имунитет на крајот од епидемијата. Ова може да се види за разни распределби на број на соседи како што се степенска (Барабаши-Алберт БА), или експоненцијална (Ердош-Рењи ЕР). Најарно е ако има некаде на интернет каква е распределбата во реалноста
 2. Истото од горе може да се проба на мрежи со 10 000 јазли и да се решава СИР со еден зараен јазол на почетокот. Ќе се повторат симулациите. Мрежите би биле БА, ЕР и за нив се наоѓа распределбата по број на соседи и распределбата на веројатност на зараза. Ова може да се спореди со претходното (средно поле DBMF ако е изводливо) и со компарментен модел.

Еден труд каде што има како оди заразата (прво најповрзаните се заразуваат, па после помалку итн) е овој Velocity and hierarchical spread of epidemic outbreaks in scale-free networks, Marc Barth´elemy, Alain Barrat, Romualdo Pastor-Satorras, and Alessandro Vespignani


#Schemat

<figure>
<a href="Silnik_l293d.jpg" target="_blank"><img src="Silnik_l293d.jpg" class="img-responsive"></a>
<figcaption>Schemat sterownika silnika DC</figcaption>
</figure>

Tak jak wspomnia�em wcze�niej nie potrzeba wielu element�w. Uk�ad L293D b�dzie naszym sterownikiem odpowiedzialnym za pr�dko�� obrotow� oraz kierunek obrot�w. Potencjometrem b�dziemy regulowa� nasze obroty, a przycisk b�dzie s�u�y� do zmiany kierunku. Osoby kt�re mia�y ju� do�wiadczenie z silnikami mog� zwr�ci� uwag� na brak diody. Oczywi�cie w powy�szym przypadku na jednej diodzie by si� to nie sko�czy�o, poniewa� silnik ma si� obraca� w obydwu kierunkach. Z pomoc� nam przyjdzie nota katalogowa od L293 i poni�szy schemat:

<figure>
<a href="l293d.jpg" target="_blank"><img src="l293d.jpg" class="img-responsive"></a>
<figcaption>Uk�ad L293</figcaption>
</figure>

Po lewej stronie wida� silnik, kt�ry kr�ci si� w dwie strony, natomiast po prawej silniki kr�c�ce si� w jednym kierunku. Widzicie r�nic� w ilo�ci di�d? To dlatego, �e taka dioda ma za zadanie przepuszcza� zasilanie tylko w jednym kierunku i zapobiega powstania impulsu zwrotnego po zatrzymaniu silnika. Dla naszego silnika zrobiony zosta� mostek prostowniczy, dlatego , �e nasz silnik b�dzie si� kr�ci� w obydwu kierunkach. 

Pami�tajmy, �e uk�ad L293D posiada wbudowane diody chroni�ce tranzystory mostka H. Tu warto zajrze� do noty katalogowej dla uk�adu L293D, a nie L293.

<figure>
<a href="L293D_diody.jpg" target="_blank"><img src="L293D_diody.jpg" class="img-responsive"></a>
<figcaption>Uk�ad L293D</figcaption>
</figure>

Wracaj�c do naszego przyk�adu, pod��czamy wszystko tak jak na schemacie, a nast�pnie przechodzimy do wgrywania kodu.
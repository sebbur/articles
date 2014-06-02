#Wst�p

<figure>
<a href="1.jpg" target="_blank"><img src="1.jpg" class="img-responsive"></a>
<figcaption>Sterownik silnika DC</figcaption>
</figure>

Cz�� z nas w swoich projektach planuje u�ycie ma�ych silnik�w DC. Mo�na si� z nimi spotka� w zabawkach, ma�ych modelarskich wiertarkach, czy na gie�dach elektronicznych gdzie le�� ich niekiedy ca�e kartony. Oczywi�cie najpro�ciej jest pod��czy� taki silniczek do baterii b�d� zasilacza, dorzuci� �migie�ko i cieszy� ch�odnym powiewem �wie�ego powietrza. Do tego celu u�yjemy uk�adu L293D. 
Co je�li by�my chcieli, aby taki nasz wiatraczek kr�ci� si� z r�nymi pr�dko�ciami obrotowymi, albo my�limy nad zrobieniem urz�dzenia dmuchaj�cego b�d� wysysaj�cego dym b�d� inne opary.

##Rozwi�zania

Jak zawsze mo�emy si�gn�� po gotowe rozwi�zania, zap�aci� ekipie za monta� i cieszy� si� z nowego nabytku. Mo�e by jednak spr�bowa� samemu zrobi� taki sterownik. Z pomoc� przyjdzie nam oczywi�cie niezawodne Arduino i par� element�w. Dla ma�ych silniczk�w, tzn. dla silniczk�w o ma�ym poborze pr�du mo�emy wykorzysta� tranzystor 2N2222 b�d�, a dla wi�kszego pr�du uk�ad L293D. Do tego dorzucimy sobie potencjometr, jaki� przycisk, opornik i diod� 1N4001.

##L293D

Zacznijmy od wi�kszego kalibru, czyli od uk�adu L293D. Na nim zrobimy prosty sterownik, w kt�rym pr�dko�� b�dzie regulowana za pomoc� potencjometru, a po naci�ni�ciu przycisku, nasz silnik zmieni kierunek obrotu. Aby nie wywa�a� otwartych drzwi, skorzystamy z gotowego kodu i pomys�u stworzonego przez Adafruita. Oczywi�cie zach�camy do zag��biania si� w schematy, noty katalogowe i do przegl�dania stron internetowych, poniewa� nie zawsze mo�emy znale�� gotowe rozwi�zanie, b�d� znalezione rozwi�zanie nie spe�nia naszych oczekiwa�. W tym przypadku mamy gotowy projekt, kt�ry w p�niejszym czasie ka�dy z powodzeniem jest w stanie dopasowa� do w�asnych potrzeb.

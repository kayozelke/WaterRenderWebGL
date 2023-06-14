# Projekt zaliczeniowy - Grafika komputerowa #


## Elementy wykonane w ramach projektu ##
- Utworzenie obiektu siatki w programie Blender. Siatka była początkowo podzielona na kwadraty; następnie każdy kwadrat został podzielony na dwa trójkąty, co utworzyło bazę, którą wykorzystaliśmy jako tafla wody.
- Wykorzystanie elementów kodu zaproponowanych na zajęciach w celu załadowania obiektu, sterowania głównym obiektem oraz obiektem światła.
- Program shaderów został zmodyfikowany, aby można było sterować kolorem światła i jasnością. 
- Rozbudowana funkcja tick - wykonująca się w programie o ustaloną liczbę milisekund. Głównym zadaniem było nadanie sinusoidalnych wartości różnym elementom tablicy wierzchołków tak, aby w różnych odcinkach czasu występowały zauważalne ruchy wody, a fale wydawały się naturalne. To wiązało się przykładowo z zmianą częstotliwości danej funkcji, delikatne przesunięciem w czasie, dostosowaniem amplitud funkcji.
- Dopasowanie tła z obiektem wody. Wiązało się to z dostosowaniem pasującego odcienia wody, położenia i nachylenia obiektu oraz ułożeniem światła, aby wyglądało naturalnie.

## Sterowanie obiektami ##
- obiekt wody - klawisze Q W E A S D
- obiekt (punkt) światła - klawisze U I O J K L

## Uwagi techniczne ##
Aby uruchomić projekt wymagane jest uruchomienie plików na serwerze WWW
 - zdalnie: apache2 / nginx
 - lokalnie: xampp / Visual Studio Code - Live Server extension / python WWW server



## Opis plików zawartych w projekcie ##
- grid.obj - jest to obiekt wygenerowany w programie Blender, naszego autorstwa.
- rendering_wody.html - jest to główny element naszej pracy - rendering wody. W czasie tworzenia własnego kodu wykorzystaliśmy kody udostępnione na stronie zajęć laboratoryjnych.
- Tex.png - jest to obrazek odpowiadający za kolor wody. Kolor dla obiektu wody pobierany jest z pierwszego piksela tego obrazka.
- tlo.png - jest to obrazek pobrany z Internetu odpowiadający za tło naszego projektu.

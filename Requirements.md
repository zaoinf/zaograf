Specyfikacja projektu
---------------------

1. Dane wysokościowe srtm  - wybrany fragment 1x1 stopień - portal https://dwtkns.com/srtm30m/ działa już poprawnie
2. Skrypt w języku  C ładujący dane srtm do tablicy - punkt 4. na stronie:  https://fraktal.faculty.wmi.amu.edu.pl/modelowanie_geometryczne/mg_lab10.html
3. Opis projektu: wizualizacja wybranego fragmentu Ziemi z uwzględnieniem:
	
		- obserwatora poruszającego się po półsferze o zmiennym promieniu wokół wybranego punktu (wybór przez interfejs klawiatury lub myszy) - parametryzacja przez współrzędne sferyczne: https://pl.wikipedia.org/wiki/Uk%C5%82ad_wsp%C3%B3%C5%82rz%C4%99dnych_sferycznych

        
		- oświetlenia słonecznego (tzn. kierunkowego) w wybranym roku, miesiącu, dniu, godzinie - skrypt obliczający azymut i elewację znajduje się w pliku solar-az_el.cpp

		- oświetlenie powinno uwzględniać składową Phonga w przypadku bliskiej wizualizacji terenu "wodnego" lub "śnieżnego"
		
        - tekstury z mapy google - opis wygenerowania takiej tekstury w dowolnej rozdzielczości za pomocą programu QGIS znajduje się w załączonym pliku instrukcja_generowania_tekstury _z_google_map.txt

		- dodatkowe punkty można otrzymać za proceduralne (najprościej przez gotowe obiekty, np. .obj i blibliotekę Assimp - punkt 4. na stronie https://fraktal.faculty.wmi.amu.edu.pl/Fundamental_of_Computer_Graphics/lab2.html) wygenerowanie
		  wybranego podfragmentu (wielkości rzędu 1x1 km) - np. rośliny i/lub budynki. Można również wykorzystać mapy normalnych
		  do bumpappingu.
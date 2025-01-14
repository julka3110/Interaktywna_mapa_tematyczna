# Wstęp
Celem projektu jest opracowanie mapy tematycznej na podstawie Bazy Danych Obiektów Ogólnogeograficznych (BDOO) z uwzględnieniem dynamicznego dostosowywania treści i symbolizacji mapy do zmieniającego się zakresu skali wyświetlania. Projekt realizowany jest w środowisku GIS za pomocą aplikacji QGIS, a wynikiem prac jest plik projektu `.qgs` oraz sprawozdanie w formacie PDF.

# Realizacja
## Etap 1: Opracowanie podkładu ogólnogeograficznego mapy
Pierwszym etapem projektu było opracowanie podkładu ogólnogeograficznego, którego zakres treści powinien odpowiadać typowej mapie przeglądowej w skali 1:250 000.

Należało:
- wybrać odpowiednie klasy obiektów z bazy BDOO dla wybranego województwa
- uporządkować warstwy projektu mapowego
- stworzyć symbolizację poszczególnych warstw zgodnie z własną koncepcją systemu znaków
- opracować nazewnictwo
- przeprowadzić hierarchizację etykiet

## Etap 2: Opracowanie przewodniej warstwy tematycznej
W tym etapie wybrana warstwa tematyczna, przygotowana na podstawie samodzielnie pozyskanych danych przestrzennych, została wzbogacona graficznie: 
zaawansowana klasyfikacja obiektów i symbolizacja z wykorzystaniem autorskich znaków umownych.

## Etap 3: Generalizacja mapy do skali pochodnej
Celem tego etapu było uzyskanie efektu dynamicznego dostosowania treści i formy mapy do bieżącego powiększenia obrazu (zoomu).
W tym celu przeprowadzono selekcję treści (generalizacja ilościowa) oraz resymbolizację, reklasyfikację i zmianę metody prezentacji (generalizacja jakościowa).


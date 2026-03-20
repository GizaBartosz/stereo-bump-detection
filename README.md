# Stereo Bump Detection

Aplikacja do rozpoznawania ubytków w drogach na podstawie obrazów stereoskopowych.

## Opis aplikacji

Aplikacja służy do automatycznego rozpoznawania ubytków w nawierzchni drogowej na podstawie pary zdjęć pochodzących z kamery stereoskopowej. W przeciwieństwie do klasycznych systemów wizyjnych opartych na pojedynczym obrazie 2D, rozwiązanie wykorzystuje analizę przestrzenną (3D), co pozwala na rzeczywiste odróżnienie fizycznych uszkodzeń drogi od zjawisk wizualnych, takich jak cienie, plamy oleju czy kałuże.

System analizuje dwa zsynchronizowane obrazy tej samej sceny, wykonane z niewielkim przesunięciem, co umożliwia rekonstrukcję głębi i określenie geometrii powierzchni jezdni. Dzięki temu możliwe jest nie tylko wykrycie ubytku, ale również oszacowanie jego parametrów przestrzennych, takich jak głębokość czy objętość.

Rozwiązanie jest niskokosztowe i może być stosowane w szerokiej skali, między innymi w pojazdach osobowych, systemach wspomagania kierowcy oraz systemach monitorowania infrastruktury drogowej. W porównaniu do systemów LiDAR jest znacznie tańsze i łatwiejsze do wdrożenia, przy zachowaniu wysokiej użyteczności. :contentReference[oaicite:0]{index=0}

Aplikacja może działać jako niezależny moduł lub jako rozszerzenie istniejących systemów pojazdu, dostarczając w czasie rzeczywistym informacji o zagrożeniach na drodze, co zwiększa bezpieczeństwo jazdy oraz ogranicza ryzyko uszkodzeń pojazdu.

## Cel projektu

Głównym celem projektu jest stworzenie systemu umożliwiającego wiarygodne wykrywanie ubytków w nawierzchni drogowej z wykorzystaniem stereowizji. System ma eliminować błędy interpretacyjne charakterystyczne dla analizy obrazów 2D oraz dostarczać informacje o rzeczywistych właściwościach geometrycznych wykrytych uszkodzeń.

Do celów szczegółowych należą:
- opracowanie metody detekcji ubytków odpornej na zakłócenia wizualne,
- rekonstrukcja przestrzenna powierzchni drogi,
- wyznaczanie parametrów takich jak głębokość i objętość ubytku,
- przygotowanie rozwiązania możliwego do integracji z systemami pojazdów.

## Zespół

Projekt realizowany jest przez dwuosobowy zespół studentów Politechniki Gdańskiej:
- Bartosz Lewczuk,
- Taras Shuliakevych.

Zespół posiada kompetencje obejmujące programowanie, przetwarzanie obrazu, uczenie maszynowe oraz elementy inżynierii sprzętowej. Prace realizowane są w sposób iteracyjny, z podziałem zadań zależnym od aktualnego etapu projektu.

## Dokumentacja

Dokumentacja projektowa przechowywana jest w repozytorium w katalogu `/docs`. Obejmuje ona opisy kolejnych etapów prac, założenia projektowe, wyniki testów oraz materiały pomocnicze.

Dokumenty tworzone są według ujednoliconego szablonu, zawierającego informacje identyfikacyjne, takie jak nazwa projektu, autorzy, data utworzenia oraz wersja dokumentu. Zapewnia to spójność i czytelność wszystkich materiałów projektowych.

## Dane

Dane wykorzystywane w projekcie obejmują zsynchronizowane pary zdjęć dróg, które są pozyskiwane w trakcie prac terenowych. Zbiór danych służy zarówno do trenowania modeli, jak i do testowania skuteczności algorytmów.

Z uwagi na rozmiar plików, dane przechowywane są poza repozytorium, w chmurze:
https://drive.google.com/drive/folders/1ASLOtvnG603Y_5_YFWGnfdNoMSS-rU1v?usp=sharing

## Licencja

Projekt udostępniany jest na licencji MIT, co umożliwia jego swobodne wykorzystanie, modyfikację oraz dalszy rozwój.

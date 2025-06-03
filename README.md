## Jak predobrzyłem w rywalizacji biurowej?

W czewrcu 2024 roku dostałem zaproszenie do firmowej ligi fantasy przewidywania meczów Euro 2024. A że moim pracodawcą był Eurosport, to moimi rywalami byli dziennikarze sportowi. Czułem, że przeciwko nim moje szanse są marne, więc postanowiłem wsprzeć się Pythonem.

Liga fantasy polegała na przewidywaniu dokładnych wyników meczów. Punkty zdobywało się przy poprawnym obstawieniu wyniku, zwycięzcy, liczby strzelonych goli etc.

Od razu pomyślałem o wykorzystaniu do tego rankigu elo. Wiedziałem, że są prowadzone rankingi drużyn narodowych wg. elo [biorące pod uwagę całą historę meczów międzynarodowych](https://eloratings.net)

Musiałem jednak zrosumieć dokładnie, jak można w ten sposób obliczyć szane na zwycięstwo jednej czy drugiej strony. 

Poniższy wzór podaje oczekiwany wynik gracza A (w skali 1 za zwycięstwo, 0 za porażkę), gdzie R_a - to liczba punktów Elo gracza A i R_b - to liczba punktów Elo gracza B.

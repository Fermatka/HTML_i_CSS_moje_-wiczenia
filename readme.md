# Wprowadzenie, narzędzia, podstawy języka HTML

---
Kamil Wojkowski, JavaScript developer, Mentor IT w Envelo [wojkowski.kamil@gmail.com](mailto:wojkowski.kamil@gmail.com)

**Co dzisiaj?**

- napiszemy pierwszy kod w HTML
- poznamy czym są narzędzia deweloperskie przeglądarki i jak ich używać?
- dowiemy czym jest IDE i w czym nam pomaga?


## 1. Wprowadzenie do technologii webowych: MDN, DevTools
[MDN](https://developer.mozilla.org/en-US/) - serwis organizacji Mozilla, gdzie znajdziemy udokumentowane standardy HTML, CSS, JavaScript. Nie jest to oficjalna dokumentacja

[Chrome DevTools](https://developer.chrome.com/docs/devtools/) - narzędzia deweloperskie do spojrzenia "deweloperskiem" okiem na stronę internetową wyświetlaną w przeglądarce. Na dzień dobry skupiamy się na zakładce Elements oraz Network.

![visual responsibilities for html js and css](https://qph.cf2.quoracdn.net/main-qimg-6795e6ef1ca101a38e86eee75ed1189f-lq)

## 2. Visual Studio Code

- IDE vs edytor tekstu
- IDE na sterydach czyli poznajemy moc wtyczek (*LiveServer*, *Prettier*, *Auto Rename Tag*)

IDE może wykonywać za nas bardzo często żmudną pracę np. odpowiednie formatowanie kodu zwiększające jego czytelność.

**Przydatne skróty:**

- Utwórz i usuń wcięcia w kodzie - `Ctrl/CMD + [` oraz `Ctrl/CMD + ]`
- Zwiń i rozwiń blok kodu - MacOS: `CMD+Option+[` oraz `CMD+Option+]` ; Windows: `Ctrl+Shift+[` oraz `Ctrl+Shift+]`
- Nawigacja po plikach w projekcie za pomocą `Ctrl+P`
- Przenieś wybraną linię/fragment kodu w górę lub dół - `Alt/Option+Up` oraz `Alt/Option+Down`
- Wykorzystanie multikursora z `Alt`



## 3. HTML czyli webowy markup

**Struktura elementu** - podstawowy klocek budujący markup strony/aplikacji
![element-content](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics/grumpy-cat-small.png)

![attribute](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics/grumpy-cat-attribute-small.png)

**Klasyczny element** `<header>Header strony</header>`

**Void element - czyli bez kontentu** `<input type="date" />`

**Tagi można zagnieżdzać** `<h1>Moja <strong>droga</strong></h1>`

[Validator W3C](https://validator.w3.org/) - validator gdzie możemy sprawdzić jakość naszego markupu
[Tabela okresowa HTML](https://codepen.io/huijing/full/wOXzNx) - wizualne zestawienie dostępnych elementów HTML

## Challenges

1. Przygotujmy podstawowy markup zastosując elementy HTML

```code
World Cup 2022
Mistrzostwa świata w Piłce Nożnej

Grupa C
Drużyna
1. Argentyna
2. Arabia Saudyjska
3. Meksyk
4. Polska

```

2. Odzwzorujmy markup strony nie uwzględniając bocznego menu oraz wyświetlanych reklam:
*Link*:   <https://kursjs.pl/kurs/wstep/narzedzia>

###

3. Przygotujmy markup dla strony logowania Google: 
*Link*: <https://accounts.google.com/>

----
#### Założenia

- rywalizujemy ze sobą ze wczoraj, a nie z innymi
- codzienne 1h daję więcej niż maraton 12h raz w tygodniu
- nauka specyficznej terminologii świata IT
- dzielenie się wiedzą!
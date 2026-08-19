# haskelar.pl

Statyczna wizytówka **Dominika (Haskelar)** wraz z polityką prywatności
aplikacji AlwaysInTouch, hostowana na GitHub Pages.

## Adresy

| URL | Zawartość |
|---|---|
| `https://haskelar.pl/` | wizytówka autora |
| `https://haskelar.pl/polityka-prywatnosci/` | polityka prywatności (PL) |
| `https://haskelar.pl/privacy/` | privacy policy (EN) |

## Struktura

| Ścieżka | Rola |
|---|---|
| `index.html` | strona główna |
| `polityka-prywatnosci/index.html` | polityka prywatności PL |
| `privacy/index.html` | privacy policy EN |
| `404.html` | strona błędu |
| `style.css` | wspólne style |
| `fonts/` | IBM Plex Serif 600 (latin + latin-ext) i licencja OFL |
| `CNAME` | domena własna GitHub Pages |

## Dwie rzeczy, o których trzeba pamiętać

**Adresy polityk siedzą w Play Console.** `polityka-prywatnosci/` i `privacy/`
to dokumenty prawne — ich treści nie poprawia się „przy okazji", a klas
`.site`, `.wrap`, `.brand`, `.lang`, `.meta`, `.card`, `.card.tldr` i `.scroll`
w `style.css` nie wolno usuwać ani przemianowywać. Przemalować wolno.

**Wygląd jest wspólny z `ait.haskelar.pl`.** Kolory i krój pochodzą z motywu
aplikacji; wzorcem jest `serwer/www/ait/style.css` w drugim repozytorium
(prywatnym). Po zmianie czegokolwiek w palecie zajrzyj tam, żeby strony nie
rozjechały się między sobą.

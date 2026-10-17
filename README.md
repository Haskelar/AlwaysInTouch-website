# haskelar.pl

Statyczna wizytówka **Dominika Piszczka** (programista AI, automatyzacja
procesów) wraz z polityką prywatności aplikacji AlwaysInTouch, hostowana na
GitHub Pages.

## Adresy

| URL | Zawartość |
|---|---|
| `https://haskelar.pl/` | wizytówka autora |
| `https://haskelar.pl/polityka-prywatnosci/` | polityka prywatności (PL) |
| `https://haskelar.pl/privacy/` | privacy policy (EN) |

## Struktura

| Ścieżka | Rola |
|---|---|
| `index.html` | strona główna (wizytówka) |
| `wizytowka.css` | style strony głównej — tylko ona z nich korzysta |
| `polityka-prywatnosci/index.html` | polityka prywatności PL |
| `privacy/index.html` | privacy policy EN |
| `404.html` | strona błędu |
| `style.css` | style polityk prywatności i 404 |
| `fonts/` | IBM Plex Serif 600, Sans 400/600, Mono 400 (latin + latin-ext) i licencja OFL |
| `CNAME` | domena własna GitHub Pages |

## Trzy rzeczy, o których trzeba pamiętać

**Adresy polityk siedzą w Play Console.** `polityka-prywatnosci/` i `privacy/`
to dokumenty prawne — ich treści nie poprawia się „przy okazji", a klas
`.site`, `.wrap`, `.brand`, `.lang`, `.meta`, `.card`, `.card.tldr` i `.scroll`
w `style.css` nie wolno usuwać ani przemianowywać. Przemalować wolno.

**Polityki i 404 mają wygląd wspólny z `ait.haskelar.pl`.** Kolory i krój
`style.css` pochodzą z motywu aplikacji; wzorcem jest `serwer/www/ait/style.css`
w drugim repozytorium (prywatnym). Po zmianie czegokolwiek w palecie zajrzyj
tam, żeby strony nie rozjechały się między sobą. Strona główna ma własny,
ciemny wygląd w `wizytowka.css` i z ait wspólny jest tylko krój nagłówków.

**Treść strony głównej pochodzi z CV.** Liczby i fakty nie są dopisywane
„na oko” — każda zmiana powinna mieć pokrycie w aktualnym CV.

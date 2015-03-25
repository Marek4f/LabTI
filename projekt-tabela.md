###Porównanie języków znaczników Markdown i AsciiDoc

|FUNKCJA            | GHM (Markdown)                 | AsciiDoc                  |
|:-----------------:|:------------------------------:|:-------------------------:|
|Nagłówek Poziomu 0 | brak                           | =======                   |
|Nagłówek Poziomu 1 | #                              | -------                   |
|Nagłówek Poziomu 2 | ##                             | ~~~~~~~                   |
|Nagłówek Poziomu 3 | ###                            | ^^^^^^^                   |
|Nagłówek Poziomu 4 | ####                           | +++++++                   |
|Kursywa            | \*tekst\* lub \_tekst\_        | \_tekst\_                 |
|Pogrubienie        | \*\*tekst\*\* lub \_\_tekst\_\_| \*tekst\*                 |
|Przekreślenie      | \~~tekst\~~                    | brak                      |
|Podkreślenie       | <u>podkreślenie</u>            | pass:[<u>podkreślenie</u>]|
|Zacienienie        | \`\`tekst\``                    | \+tekst\+                |
|Komentarze         | <!-- komentarz -->             | /////                     |
|Linia horyzontalna | --- (3 i więcej - lub * lub _ )| \\[vertical bar]=====     |
|Lista numerowana   | 1. punkt pierwszy              | . punkt pierwszy          |
|Lista punktowana   | - punkt (albo + lub *)         | - punkt                   |
|Podlista numerowana| ⋅⋅1. podpunkt pierwszy          | \.. podpunkt pierwszy    |
|Podlista punktowana| \* podpunkt                    | \* podpunkt (nast: \**)   |
|Linki              | \[nazwa](www.strona.com)       | http://strona.com         |
|Linki z "podglądem"| \[nazwa](www.strona.com "opis")| http://strona.com [opis]  |
|Linki z "przypisem"| tekst\[1] \[1]:www.strona.com  | brak                      |
|Obrazki            | \!\[tekst](obrazek.jpg "tekst")| image:obrazek.jpg[tekst]  |
|Cytaty             | > cytat                        | [quote, autor, tutuł]     |
|Kod programu (blok)| \`\`\`jezyk_programu kod\`\`\` | [source="jezyk_prog"] z ---- (pod i nad kodem)|

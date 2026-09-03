```mermaid
flowchart TD
    A([MULAI]) --> B[/Input sisi1, sisi2, sisi3/]

    B --> C{Apakah sisi1 = sisi2<br/>DAN sisi2 = sisi3?}

    C -- YA --> D[/Output:<br/>Segitiga sama sisi/]

    C -- TIDAK --> E{Apakah sisi1 = sisi2<br/>ATAU sisi1 = sisi3<br/>ATAU sisi2 = sisi3?/}

    E -- YA --> F[/Output:<br/>Segitiga sama kaki/]

    E -- TIDAK --> G[/Output:<br/>Segitiga sembarang/]

    D --> H([SELESAI])
    F --> H
    G --> H
```


```mermaid
flowchart TD
    A([MULAI]) --> B[/Input sisi1, sisi2, sisi3/]

    B --> C{Apakah sisi1 = sisi2<br/>DAN sisi2 = sisi3?}

    C -- YA --> D[/Output:<br/>Segitiga sama sisi/]

    C -- TIDAK --> E{Apakah sisi1 = sisi2<br/>ATAU sisi1 = sisi3<br/>ATAU sisi2 = sisi3?/}

    E -- YA --> F[/Output:<br/>Segitiga sama kaki/]

    E -- TIDAK --> G[/Output:<br/>Segitiga sembarang/]

    D --> H([SELESAI])
    F --> H
    G --> H
```

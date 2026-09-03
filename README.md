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


## 📥 Input – Proses – Output

| **Komponen** | **Keterangan** |
|---|---|
| **Input** | • Panjang sisi pertama.<br>• Panjang sisi kedua.<br>• Panjang sisi ketiga. |
| **Proses** | Program membandingkan panjang ketiga sisi menggunakan kondisi logika:<br><br>• Jika sisi 1 = sisi 2 **dan** sisi 2 = sisi 3, maka segitiga sama sisi.<br>• Jika sisi 1 = sisi 2 **atau** sisi 1 = sisi 3 **atau** sisi 2 = sisi 3, maka segitiga sama kaki.<br>• Jika semua sisi berbeda, maka segitiga sembarang. |
| **Output** | Jenis segitiga berdasarkan panjang sisi. |

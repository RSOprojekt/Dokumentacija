# Dokumentacija - Digitalna galerija

Dandanes je težko organizirati razstavo, če nisi znan umetnik.
To pa ne moreš postati, če te ljudje ne opazijo.
Veliko mladih umetnikov je tako prepuščeno dobri volji sponzorjev in raznih razpisov, saj je organizacija razstave poleg vsega velik finančni zalogaj.
Prav tako pa je organizacija razstav v nekaterih okoliščinah, kot je trenutna zdravstvena skoraj nemogoča.
Tukaj na pomoč priskoči najina spletna aplikacija Digitalna galerija, ki omogoča organizacijo razstave vsakomur in za vsakogar.
V začetku bo aplikacija namenjena zgolj razstavam slik, a jo bo kasneje možno enostavno razširiti.
Avtorja aplikacije sta [Aljaž Nunčič](https://github.com/aljaznuncic) in [Grega Dvoršak](https://github.com/gdvorsak97).
Kakršnakoli uporaba (delna ali v celoti), razen preko uradne spletne strani Digitalne galerije, brez pisnega dovoljenja avtorjev ni dovoljena.
V nadaljevanju je predstavljen načrt in opis projekta, ki se bo tekom razvoja dopolnjeval in spreminjal.

Rešitev bo zasnovana s pomočjo naslednji mikrostoritev:
- Nalaganje/brisanje slik.
- Kreiranje razstave.
- Procesiranje slik (potekalo asinhrono).
- Dodajanje feedback-a za slike/razstave oz. komentiranje.
- Beleženje časa ogleda posamezne slike.
- Kreiranje poročila za posamezno sliko/razstavo (npr. čas ogleda slik, najbolj gledana slika, feedback). Poročilo se bo samodejno kreiralo v določenih časovnih intervalih, ob zaključku razstave oziroma na zahtevo.
- Izvedba plačila vstopnice za posamezno razstavo. Plačilo bo možno tudi s pomočjo ogleda določenega števila oglasnih sporočil. (Izdelano v prihodnjih različicah.)

Prav tako bo aplikacija uporabljala tuje vire:
- Image rekognition api (Na ta način bomo dobili dodatne informacije o sliki/delu avtorja).

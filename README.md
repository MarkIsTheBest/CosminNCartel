# CosminNCartel
un rep cu toate resursele necesare pentru concursul "Info Educatie"

# <Tutorial pas cu pas>

### 1. General
- Instalati rep-ul apasand pe ![Code Button](https://github.com/MarkIsTheBest/CosminNCartel/assets/56190468/d82a212d-5759-4167-931d-e63cbe108e0d)
; ![image](https://github.com/MarkIsTheBest/CosminNCartel/assets/56190468/1f69f3b5-82ec-406a-996e-a5184157be90)

- In folderul descarcat `Pachet InfoEdu`, intrati in primul rand pe `De Instalat`
  
- Porniti fiecare installer, si treceti prin pasii de instalare.
### 2. Setup Inkscape
- Deschideti aplicatia si treceti prin setup-ul de inceput.
  
- Da-ti open la fisierul `\Pachet InfoEdu\Inkscape\drawing.svg` (__FOARTE IMPORTANT: Nu da-ti save la fisier din aplicatie!__)
  
- Odata deschis, ii puteti lasa pe jurati sa incerce sa scrie ceva (__Nu ii lasati sa deseneze, arata ca dracu__) cu tool-ul `Text`(![image](https://github.com/MarkIsTheBest/CosminNCartel/assets/56190468/277feef9-4ad7-4981-86b7-d7cee7d738c3)
  )
### 3. Generare Gcode
- Apasati pe textul scris, folosind tool-ul `Selector`(![image](https://github.com/MarkIsTheBest/CosminNCartel/assets/56190468/2338813c-8414-4e86-a7cd-dfbfb560e804)
)

- Selectat, apasati pe butonul din Header numit `Path`(![image](https://github.com/MarkIsTheBest/CosminNCartel/assets/56190468/e5184c91-8ce5-4a0d-b36d-66593bf1ebea)), iar apoi faceti clic pe `Object to Path`(![image](https://github.com/MarkIsTheBest/CosminNCartel/assets/56190468/ec24793b-2ece-4dad-a9f4-f73456730941)
)

- Da-ti pe butonul din Header numit `Extensions/Gcodetools/Tools Library...` si selectati la `Tools type:` `graffiti`(![image](https://github.com/MarkIsTheBest/CosminNCartel/assets/56190468/2bfb6977-3e85-47b3-a90e-30849994f3fe)) apoi da-ti `Apply`, iar dupa ce s-a generat panoul verde, apasati pe `Close`


- Acum apasati pe butonul din Header numit `Extensions/Gcodetools/Orientation Points...` si dati `Apply`, apoi `Close`

- Odata ce s-au generat punctele de orientare intrati pe meniul din Header numit `Extensions/Gcodetools/Path to Gcode...`

- Schimbati tab-ul la `Preferences`, aici schimbati `File:` in exact string-ul ce urmeaza : "`gcode.ngc`"
  
- iar `Directory` schimbati in folder-ul `\Pachet InfoEdu\Parser\input`

- Schimbati tab-ul la `Path to Gcode` si apasati pe `Apply` apoi `OK`

- Puteti inchide Inkscape.

### 4. Transformarea Gcode-ului in Codul Robotului
- Executati aplicatia `\Pachet InfoEdu\Parser\Parser.exe`
  
- Dupa ce a terminat de scris in consola, apasati orice buton, pentru a inchide CMD Prompt (Consola)

- In fisierul `\Pachet InfoEdu\Parser\output\coords.out` aveti codul pentru Robot, copiati-l pentru mai tarziu!

### 5. Modificarea codului al lui Cosmin
- Porniti Robotul daca nu este deja pornit

- Conectati-va la Wi-Fi-ul lui (ID-ul este `19257-RC` iar parola este ba `lenau2023` ba `lenau2024` am uitat), si introduce-ti in browser la URL, adresa `http://192.168.43.1:8080/dash`

- Porniti aplicatia `Android Studio` pe care ati insalat-o la Pasul 1, in ea deschide-ti proiectul din fisierul `\Pachet InfoEdu\RobotCode\CoolPrinterLol69420`

- Expanda-ti fisierele din submeniul de project din stanga pana gasiti un fisier numit `MihneaMorgoci`![image](https://github.com/MarkIsTheBest/CosminNCartel/assets/56190468/a5db540a-5e38-489b-9224-60681b1a79eb)

- In fiserul deschis, cauta-ti comentariul `// Introdu (ctrl-v) Codul generat de parser sub linia aceasta \/`![image](https://github.com/MarkIsTheBest/CosminNCartel/assets/56190468/57122fd8-88ac-48b2-acde-8061eb09c0c2)

- Pe linia urmatoare lipiti, codul copiat anterior (daca aveti deja cod sub comentariu, asigurati-va ca il stergeti mai intai)

### 6. Trimiterea codului lui Cosmin
- Deschide-ti aplicatia `REV Hardware Client` instalata anterior

- In `Android Studio`, ar trebuii sa va apare `REV Robotics Control Hub v1.0` in header...![image](https://github.com/MarkIsTheBest/CosminNCartel/assets/56190468/47e1fc5f-f93b-4b79-b684-1036d85fd515)
 daca da, apasati butonul de `Play`(![image](https://github.com/MarkIsTheBest/CosminNCartel/assets/56190468/bca00e8c-6d3d-47d3-8858-b8b89c6bd915)
)

- Astepta-ti pana becul de Control Hub se face Verde... Codul a fost Trimis.

### 7. Inceperea Scrierii
- Conectati un Controller la Driver Hub, si apasati `Start + A` sa il faceti Controller-ul nr.1

- Din meniul de TeleOP, selectati `Sticky Keys` si dati `Init` iar apoi `Start`

- Pe controller apasati `Start` si robotul va incepe sa va scrie mesajul!

# </Tutorial pas cu pas>

Daca mai aveti intrebari sunati-ma!

-Mark GOAT-ul

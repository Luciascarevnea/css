


# HTML meta viewport (este in head) indicatii pentru browser
stabileste niste reguli legate de fereastra, care permite sa stabilesti niste limite sa faci o macheta adaptiva, sa nu se strice pe unul dintre ecrane, cu cat mai multe reguli pui cu atat mai putina flexibilitate are device-ul care vizualizeaza macheta. Cu atat mai mult prin css dictezi cum trebuie sa arate acest viewport. 
Cu cat lipseste meta viewport cu atat device-ul decide dupa politica sa cum vede corect si dupa configurarile user-ului și atfle macheta poate fi transpusa altfel decat cum ai vrut pe acel device cand am facut adaptivitatea.

Scalare:
Atunci cand te uiti in fereastra browser-ului obiectele vor fi scalate.
Media query in unele situații nu poate functiona de la dimensiunile prestabilite din cauza scalrii.

<meta name="viewport" 
          content="width=device-width, 
                   initial-scale=1, 
                   minimum-scale=1, 
                   maximum-scale=1,
                   user-scalable=no"
     />
     Acesta este egala cu situatia in care noi vrem sa vedem dimensiunea reala a unui obiect din fereastra(il putem aducem mai aproape ca sa ne dam seama de dimensiunea acestuia)


     meta
       |
       +-----name="viewport"- tipul de informatie (fereastra, ecranul care arata un sector din pagina)
       |                     ii spune browserului despre pozitionare documentului in fereastra
       |
       |
       +-----content="..." - continutul
                       ^
                       |
                       +---------settings for the browser(setari p/u browser in raport cu fereastra si documentul)


      adaptivity                      
                                           +------------------------------->
                                           |
                +---------------------------------------------------------->
                |                          |
----------------x--------------------------x---------------------------------------------------->
                ^                          ^
  min-width: 820px                       max-width: 1420px    






  Remoute:
  Smartphone
  1. Android(trebuie sa incluzi developer settings)  chrome inspect
  2. Settings: usb debugging(on)
  PC
  3. install adb
  4. conectam smartphone with PC




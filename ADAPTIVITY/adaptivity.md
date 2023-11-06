







## Layouting: modern UI(crearea interfeței)/ adaptivity(tine de a adapta macheta la mai multe dispozitive)

Adaptivitatea constă din:
- Crearea mai multor variante de machete
- se comutează în dependență de mai multe condiții, se fac machete separate care reies din același design, in dependență de anumiți parametri și condiții.

Condiții:
1. screen(viewport) prin width/height, orientarea acestuia(vartical și orizontal)

! Cel mai bine incepi adaptarea de la un ecran mic pentru telefon, apoi faci prin @media pentru ecrane mari


                                  
              @MEDIA( min-width....) se duce in sus, data era max-width se ducea in sus
             ----------------------------->
             ----------------------------------------------

-------------

-------------x-------------------x------------------------- viewport width
            1100px
            breakpoint(puntul de comutare)
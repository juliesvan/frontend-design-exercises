# Din refleksion

Skriv her:

Brug af :has() og :not() giver mening, når der skal laves global styling af mange forskellige elementer (der evt. ikke kan have samme class).

Det er også smart, hvis man skal lave en undtagelse (style ét element anderledes end andre), da man så slipper for at lave én class eller ét id til netop det element.

I denne opgave giver det god mening at bruge :has() og :not(), idet det er samme type elementer, der mere eller mindre har samme markup. Så i steder for at give hvert card deres egen class, og style alt separat (med gentagelser), er det lettere at style globalt, og så lave ændringer/undtagelser med :has() og :not().
Det er vel i bund og grund generelt mindre kode, der skal skrives.

Selvom det er nyt for mig, synes jeg det virker til, at det er forholdsvist simpelt at læse og forstå.
Nu er dette også en simpel opgave, men hvis man brugte classes i stedet for, kan det hurtigt blive svært at regne ud, hvad klassen egentlig styler, ud fra et navn. Især for andre, der skal læse ens kode.

Ift. vedligeholdelse, synes jeg det er lidt sværere at svare på. Det kan nok langt hen ad vejen være lettere at bruge denne metode.
Også så man kan style (og rette styling) mere generelt, og ikke er nødsaget til at lave de samme ændringer på en hel række classes, hvis det kan gøres fælles med :has() og :not().

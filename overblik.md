# Loop

## Statistic
| D7        | D9           |
| ------------- |---------------|
| Siteimprove | Der skal kunne bruges et vilkårligt statistiskredskab |

## Branding
| D7        | D9           | 
| ------------- |---------------|
| Loop configure theme | Dette skal ikke med i D9. Dette skal være konfig-filer |
| Loop frontpage | **Undersøg** hvad forsiden skal indeholde |

## Login
| D7        | D9           |
| ------------- |---------------|
| Loop saml | Login skal være konfigurerbart til et hvilketsomhelst login (Vi hidkalder Mikkel) |
| Loop simple saml php | Login skal være konfigurerbart til et hvilketsomhelst login (Vi hidkalder Mikkel) |
| Loop unilogin | - |

## Search
| D7        | D9           |
| ------------- |---------------|
| Loop search | Drupal search |
| Loop search node      |    Drupal search   |
| Loop search node settings    |    Drupal search   |
| Loop search links  | Google om drupal search dækker dette, ellers skal det implementeres     |
| Loop instruction | **Undersøg** om denne skal med i D9 |

## Content
| D7        | D9           |
| ------------- |---------------|
| Loop content | En simpel side, ikke søgbar |
| Loop documents | Content typen dokument |
| Loop example content | Det er til test - vi skal lave et modul med fixtures |
| Loop flag (spørgsmål svar) | "Like" et svar og sortere svar efter likes (kitos - der kan admin overrule) |
| Loop disable post (spørgsmål svar) | Gør det muligt at lave en installation uden QA - skal fjernes |
| Loop friend notification | At anbefale indhold til en anden bruger - **undersøg** om dette skal med videre |
| Loop notify editorial office | Send mail til redaktion tilknyttet et bestemt stykke indhold (dokumenter) |
| Loop quick box | Hænger sammen med search links, burde kunne løses med paragraphs |
| Loop post (spørgsmål/svar) | Opret spørgsmål eller besvar et spørgsmål |
| Loop post wysiwyg | Formattering af spørgsmål |
| Loop external data | Skal ikke med videre |
| Loop external sources content | Henvisninger af ressourcer som ligger et andet sted som skal kunne søges frem |
| Loop frontend | Internet explorer specifikt, skal ikke med i D9 |
| Loop field bases | Samling af felter som bliver genbrugt af flere moduler og indholdstyper, i d9 skal dette ikke være et modul, da det kan laves som config |

## Struktur
| D7        | D9           |
| ------------- |---------------|
| Loop taxonomy | Definitionen på de tre taxonomier - emner, tags, profession - dette skal _måske_ med i D9, men egentlig i D9 er det konfiguration |
| Loop taxonomy color | giver en farve til emner, **undersøg** om det er tilknyttet search links |
| Loop taxonomy terms | Definere nogle nøgleord/emner/POSTKASSE - dette er specifikke taxonomier |
| Loop taxonomy views | Definerer views til taxonomy terms |
| Loop navigation | **Undersøg** om det er menuen, eller hvad det er |

## Brugere
| D7        | D9           |
| ------------- |---------------|
| loop user | **Undersøg** hvilke brugerroller der her er tale om |
| loop_user_contact_list | Adressebog |
| Loop profession optional | Så en profil har en profession (titel), med dette modul er den _ikke_ required |
| Loop user related content competence | Forsiden kan defineres ud fra brugerprofilens kompetence |
| Loop user related content profession | Forsiden kan defineres ud fra brugerprofilens profession |
| Loop user subscriptions | Viser hvad en bruger abonnerer på min side |
| Loop user page views | Viser brugerens spørgsmål/svar kontent på min side |
| Loop user messages | Views der viser beskeder fra notificationsmodulet (på eksempelvis brugerprofilen) - i D9 skal dette laves uafhængigt af Loop notification |
| Loop notification | Sender mails ud når der sker noget på noget indhold |
| Loop admin | Revisioner + anmeld indhold skal være muligt |
| Loop dashboard| Statistik, og **undersøg** hvordan det hænger sammen med loop admin |
| Loop permissions | Definerer adgang for forskellige bruger, **undersøg** hvilke adgange de forskellige brugere har, hænger sammen med loop user |

## Undersøgelsesopgaver

### Anna
* Undersøg hvad forsiden skal indeholde (modul: Loop frontpage)
* Undersøg om denne skal med i D9 (modul: Loop instruction)
* At anbefale indhold til en anden bruger - undersøg om dette skal med videre (modul: Loop friend notification )
* Undersøg hvilke brugerroller der her er tale om + hvilke rettigheder (loop user, loop permissions)

### Sine
* Undersøg hvad det her gør, vi tænker det har at gøre med branding - logo, farver, etc (modul: Loop configure theme)
  * letting the administrator choose the various theme settings - med default-farver fra en vedlagt fil
* Giver en farve til emner, undersøg om det er tilknyttet search links (Loop taxonomy color)
  * search links depender loop taxonomy color
* Undersøg om det er menuen, eller hvad det er (Loop navigation)
  * Det virker som noget admin-menu-noget
* Hvordan hænger loop dashboard sammen med loop admin?
  * Loop admin definerer nogle views, loop dashboard bruger disse views


### Mikkel
* Undersøg hvad dette modul dækker over (Loop example content) - Anna siger det kan løses med fixtures, er det rigtigt?
* Undersøg om det er en parser som ikke bliver brugt (Loop external data)
* Undersøg om det er upload af dokument til en content type (Loop external sources content)
* Undersøg er det et slags overblik over fields? (loop field bases)
* Er loop taxonomy modulet en bundle af de andre taxonomy moduler?
* Er loop notifications og Loop user messages egentlig lidt det samme? Hvad er forskellen?

## Noter
* Hvad helvede er "anmeld indhold"
* Der skal gøres noget ved visning af dokumenter (paragraphs?)
* Tablets

## Overbliksliste
* Siteimprove
* Loop admin
* Loop configure theme
* Loop content
* Loop dashboard
* Loop diasable post
* Loop documents
* Loop example content
* Loop external data
* Loop external sources content
* Loop field bases
* Loop flaghttps://github.com/sinejespersen/loop-analytics
* Loop friend notification
* Loop frontend
* Loop frontpage
* Loop instruction
* Loop navigation
* Loop notification
* Loop notify editorial office
* Loop permissions
* Loop post
* Loop post wysiwyg
* Loop profession optional
* Loop quick box
* Loop samlLoop search
* Loop search links
* Loop search node
* Loop search node settings
* Loop SimpleSAMLphp
* Loop taxonomy
* Loop UNI•Login
* Loop user
* Loop user messages
* Loop user page views
* Loop user related content competence
* Loop user related content profession
* Loop user subscriptions
* loop_user_contact_list
* Loop instruction (loop_instruction)

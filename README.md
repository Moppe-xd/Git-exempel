# Git exempel

Denna git repo är ett exempel på hur man använder sig av git och github i VS Code. I denna README så kommer det finnas instruktioner och `commandon` som kommer behövas.

---

## Skapa ett git projekt

När vi har öppnat vårat projekt i VS Code så kan vi trycka på source control fliken ![source control](bilder/sourcecontrol.png) och trycka på knappen `Initilize project`
![Initilize project](bilder/Init.png).

Därifrån kommer ni få en flik som liknar bilden under.
![changesview](bilder/changes.png)

Tryck sedan på plusset för varje fil du vill lägga till! När du har lagt till alla filer du vill ha så kommer det se ut som bilden nedan. Lägg sedan till ett namn på din commit som förklarar vad för ändringar du har gjort.

![staged](bilder/staged.png)

Tryck sedan på `commit` knappen och efter lite laddande borde din source control se ut som följande.

![publish](bilder/publish.png)

Innan vi kan publisera den så måste vi först configruera git med två kommandos

`git config user.name "DittAnvädarnamnHär"`
`git config user.email "DinMailHär"`

När dessa två kommando är gjoda kan du trycka på `publish Branch` knappen. Om du inte redan är inloggad med ditt github konto kommer du bli tillbad att logga in på github. Efter det bör ni få ett val som bilden nedan. Det är viktigt att ni väljer ett `public repo` så jag kan få tillgång till eran kod.

![public](bilder/public.png)

Om det inte blev någon error borde du nu kunna gå in på github och hitta ditt repo i din profil.

---

## Att göra ändringar

Så fort ni gör sparar någon ändring i git-repot så kommer ni merkar hur source kontroll fliken ändras likt bilden nedan. Detta betyder att ni har ändringar ni kan commita till git. I bild exempel nedan betyder siffran 3 att jag har tre stycken ändringar som jag kan `commita` till git.

![ändringar](bilder/Ändringar.png)

För att göra det gör vi exakt som vi gjorde i ovanstånde steg och trycker på `+` vid filerna vi vill `commita`. Sedan så skriver vi en besrkivning av vad för förändring vi har gjort och trycker på `commit`

![staged](bilder/staged.png)

---

## Klona ett repo

Säg att du vill arbeta på din projekt hemma, hur gör du det med git. Jo det finns ett väldigt enkelt sätt att göra det.

Först måste vi se till att vi har git installerat på datorn. Om det inte är installerat får du repetera stegen gjorda på lektionen. Sedan ska vi gå in på GitHub och titta trycka på den stora gröna kanppen där det står `code`. 
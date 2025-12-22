# Inlämningsuppgift Planned Planthood
Uppgiften är att göra en sida enligt nedanstående bilder, text och kod-stycken.

## Inlämning
* Code review är efter lunch fredagen den 2/1.
* Senaste tiden för inlämning är kl. 8.00 måndagen den 5/1. Det som kommer efter det bedömmer vi inte om det inte finns rimliga skäl. 
* Ni lämnar in genom att pusha till er GitHub med namnet "Planned Planthood".
* När ni pushat upp sista ändringen skriver ni lärarchatten i lärarchatten och meddelar oss med länk till koden. Om ni inte meddelar bedömmer vi den i det skick den är vid deadline, commits efter detta kommer ignoreras.
  
## Krav
* Klona detta repo och använd som grund.
* Använd de variabler ni anser aktuella av de ni får i style.css som grund för sidans design
* Ni ska lösa uppgiften enligt den design som anges i bilderna
* Sidan ska vara responsiv i övergångarna mellan mobil-tablet-desktop
* Formulär och semantik ska vara tillgängligt (använd WAVE eller dylikt för att testa)
* Koden ska vara välformatterad och tydligt strukturerad med en genomtänkt namngivning på klasser samt ev kommentarer
* Inga bibliotek som react, bootstrap, tailwind eller dylikt får användas, endast .CSS och .HTML (ev js).
* Om ni lånar en reset, flow-util, visually-hidden eller dylikt som inte finns i grundkoden - ange källa som kommentar i er kod.
* Var beredd på att förklara er kod muntligt så se till att ni förstår vad ni gör om ni rådfrågar andra/AI.

## Extra
Följande är extra och sådant ni inte måste ha med om ni inte hinner/vill/kan

* Overlay/watermark-bilden med krukan kortens bild
* Galleriet högst upp kan ha en enklare design som i tablet-läget även på desktop
* Olika färger på "tags" behövs inte om ni inte vill, använd bara den gröna accent-color på alla i så fall.
* Använd gärna en diskret transition på hover/focus-visible om ni vill.
* Hamburgar-menyn behöver ni bara göra som en ikon, all annan funktionalitet är superextra och inget som vi förväntar oss att ni gör!
  
## Övriga resurser
* Använd gärna avatarer från [https://avatar-placeholder.iran.liara.run/avatars](https://avatar-placeholder.iran.liara.run/avatars) eller den svg som finns i projektet.
* Använd gärna bilder från [https://picsum.photos/](https://picsum.photos/). Vill ni använda andra är det ok, men se till att det ser bra ut i sammanhanget.
* Vill ni ändra texter och lägga in egen info är det också ok, bara det fyller samma typ av funktion och inte ändrar sidans utseende bortom innehållet.
* SVG finns i mappen assets/Images och kan användas antingen som vanliga bilder eller direkt inkopierade som HTML i koden. Om ni vill ändra färger med CSS på SVG måste de vara inkopierade inline. Se här för hur man kan ändra färger med CSS: https://nucleoapp.com/blog/post/change-svg-color-css
* Länkarna ska vara semantiska men behöver inte gå någonstans (använd href="#")
  
## Design
### Desktop
Bilderna för designen ligger under Design mappen och innehåller bilder för de olika vyerna samt bild för hover state.

![Desktop](Design/desktop.png "Desktop")

### Tablet
Bilderna för designen ligger under Design mappen och innehåller bilder för de olika vyerna samt bild för hover state.

![Tablet](Design/tablet.png "Tablet")

### Mobile
Bilderna för designen ligger under Design mappen och innehåller bilder för de olika vyerna samt bild för hover state.

![Mobile](Design/mobile.png "Mobile")

## Hover state
För hover state gäller generellt att det är inverterat om det är annat än länkar. Länkar har understrykning vid hover, annars inte.

![Hover](Design/PlannedPlanthood-Hover.png "Hover")

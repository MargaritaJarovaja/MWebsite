---
Title: Text
Description: This is page with text.
Hidden: true
Template: text
---

# Text page

Jag valde färgpaletten så att tonvikten låg på kundens arbete och projekt. Färgerna i sig måste vara lugna och inte distrahera uppmärksamheten. Jag strävade inte efter målet att använda färg för att dra användarens uppmärksamhet till några specifika punkter eller platser på webbplatsen. Valet av färger var något klassiskt, det är svart, grått och vitt.I projektet valde jag att använda 'Montserrat', sans-serif och 'DM Serif Display', serif, eftersom de enligt min mening för ett sådant projekt är måttligt återhållsamma, men samtidigt tilltalande för ögat, strömlinjeformade, skadar inte ögat med kantighet och svärta, men inte för klassiskt (tråkigt). Jag placerade dessa typsnitt i variabler för att underlätta användningen i koden för scss och, följaktligen, css-filer.

Beställaren vill gärna rama in sina projekt och arbetar i en lugn ram så att säga. Webbplatsen i sig är som ett underlag för en målning eller fotografi, det vill säga den ska inte ha sin egen specifika karaktär, utan ska lyfta fram konstnärens verk. Jag försökte dela upp koden enligt principerna för kodorganisation och modularitet. Till exempel jag delade upp CSS-koden i logiska moduler, som då blir lättare för mig att förstå och hitta nödvändiga funktioner. Jag använde också @import i style.scss-filen, som är den huvudsakliga och anslutande bland alla moduler, för att importera de skapade modulerna till huvudstils filen. Detta gjorde att alla moduler kunde kombineras till en CSS-fil när de kompilerades. Jag använde även variabler för att bestämma typsnitten och blommor. Detta tillvägagångssätt låter dig snabbt ändra stilen på webbplatsen på ett ställe.

Jag gjorde det alternativa temat mörkt. I detta tema, förutom att ändra färgerna från ljust till mörkt, ändrades typsnitten till mer massiva ('Oswald', sans-serif;'Titillium Web', sans-serif;) och bannerbilden bearbetades. Bilden använder en gradient som gör den ljusare mot botten i ett ljust tema eftersom skiftet där är mörkt. Det alternativa temat har mörkare nedtill för bättre läsbarhet eftersom teckensnittet redan är ljust i färgen. Projekten på sidan har ändrats något genom att ändra storleken i rutnätet och reaktionen på projektnamnet när du håller muspekaren över det. I ett ljust tema ökar titeln, i ett mörkt tema minskar titeln.

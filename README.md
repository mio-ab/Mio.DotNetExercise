# Mio.DotNetExercise

Övningen går ut på att göra en .NET app för att presentera produktdata enligt kravlistan nedan. I repot ingår en template som du kan utgå ifrån om du vill men du får så klart göra det på ditt sätt.

Ett .NET REST API med följande endpoints.

* Returnera alla produkter.
* Returnera en produkt med Id x. Id matas in av användaren.
* Kolla så att efterfrågad produkt existerar. Om inte så svara med passande statuskod.
* Skapa en produkt.    
* Uppdatera en produkt.
* Ta bort en produkt.

Domänregler och validering kring data.

* Pris får inte vara 0 eller mindre än 0
* Namnet får som mest innehålla 30 tecken
* Pris får inte vara 0 eller mindre än 0.
* Namnet får som mest innehålla 30 tecken.
* Kolla så att produkten som uppdateras existerar. Om inte så svara med passande statuskod.
* Kolla så att efterfrågad produkt existerar. Om inte så svara med passande statuskod.
* Skapa, ändra och ta bort behöver inte göra någon faktiskt ändring i datakällan, utan det räcker med att fejka detta och svara med en lämplig statuskod tillbaka.


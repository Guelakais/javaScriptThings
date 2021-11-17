#javaScriptThings
Anleitung zur Automatischen aktualiesierung der Zimmeranzeige auf WG-gesucht.
Damit ist man immer auf Platz 1 der Frontpage.

1. Melde dich auf WG-gesucht an.

2. Öffne "Meine Anzeigen" 

3. Wähle die Anzeige aus, die du aktuell haben willst und gehe auf "bearbeiten" o. "bearbeiten + fotos" genannt.
Du solltest nun auf der linken Seite eine orange hinterlegt "Aktualisieren" stehen haben.
Darüber steht in grün wann die Anzeige zuletzt aktualisiert wurde.

4. Press "F12"

5. Wähle in dem nun erscheinenden Pannel in der Kopfzeile "Console"

6. Kopiere die folgenden Zeile in die Console und drücke "Enter" 


setInterval(function(){ 
  $("#update_offer_nav").trigger("click") 
}, 120000);


7. Wenn es funktioniert sollte sich nun alle 2 Minuten die Anzeige aktuallisieren. 
Also Kontrolle das es tatsächlich funktioniert sollte der Zeitpunkt in grüner Schrift nie älter als 2 Minuten sein

8. Das funktioniert so lange die Website genau auf dieser Seite bleibt und du den Browser nicht schließt.



Bei Fragen Wende dich an deine Lieben Bundeshabibis Roland oder Volker


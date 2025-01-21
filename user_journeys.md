# User Stories och User Journeys

## 1. Skapa konto
**User Story:**  
Som användare vill jag kunna skapa ett konto, så att jag kan logga in och spara mina betyg.

**User Journey:**  
1. Användaren öppnar appen eller webbplatsen och klickar på *"Skapa konto."*  
2. Ett formulär visas där användaren fyller i:  
   - E-postadress  
   - Lösenord  
3. Användaren klickar på *"Skicka."*  
4. Bekräftelsemeddelande visas: *"Ditt konto har skapats!"*  
5. Användaren omdirigeras till inloggningssidan.

---

## 2. Logga in
**User Story:**  
Som användare vill jag kunna logga in med mina inloggningsuppgifter, så att jag kan komma åt mina sparade filmer och betyg.

**User Journey:**  
1. Användaren öppnar appen och klickar på *"Logga in."*  
2. Ett formulär visas där användaren fyller i:  
   - E-postadress  
   - Lösenord  
3. Användaren klickar på *"Logga in."*  
4. Om uppgifterna är korrekta omdirigeras användaren till sin startsida.  
5. Om uppgifterna är fel visas ett meddelande: *"Fel e-post eller lösenord."*

---

## 3. Lägga till en film eller serie
**User Story:**  
Som användare vill jag kunna lägga till en film eller serie i min lista, så att jag kan hålla koll på vad jag har sett.

**User Journey:**  
1. Användaren navigerar till *"Min lista"* och klickar på *"Lägg till ny."*  
2. Ett sökfält visas där användaren kan söka efter en film eller serie.  
3. Användaren väljer en titel från sökresultaten.  
4. Filmen/serien läggs till i användarens lista.  
5. Ett meddelande visas: *"Filmen/serien har lagts till i din lista."*

---

## 4. Sätta betyg
**User Story:**  
Som användare vill jag kunna sätta ett betyg (1–10 med n decimaler) på en film eller serie, så att jag kan minnas vad jag tyckte om den.

**User Journey:**  
1. Användaren öppnar *"Min lista"* och klickar på en film eller serie.  
2. En detaljerad vy visas med information om filmen/serien och ett fält för att sätta betyg.  
3. Användaren fyller i ett betyg (t.ex. 8.5) och klickar på *"Spara."*  
4. Ett meddelande visas: *"Ditt betyg har sparats!"*

---

## 5. Visa statistik
**User Story:**  
Som användare vill jag kunna se statistik över mina betyg, så att jag får en översikt över mina favoriter och tittarvanor.

**User Journey:**  
1. Användaren navigerar till *"Statistik"* från menyn.  
2. En översikt visas med följande information:  
   - Genomsnittligt betyg för alla filmer/serier.  
   - Mest betygsatta genre.  
   - Favoritfilmer baserat på betyg.  
3. Användaren kan filtrera statistiken baserat på genre eller tidsperiod.  

---

## 6. Få filmtips och jämföra listor
**User Story:**  
Som användare vill jag kunna få tips på nya filmer och jämföra min lista med någon annans, så att jag kan hitta filmer vi båda inte har sett och upptäcka nya filmer att titta på.

**User Journey:**  
1. Användaren navigerar till *"Rekommendationer"* i menyn.  
2. Ett sökfält visas där användaren kan ange en annan användares namn eller e-postadress.  
3. Systemet jämför de två listorna och visar:  
   - Filmer ingen av dem har sett.  
   - Filmer den andra användaren har sett men inte användaren.  
4. Användaren kan klicka på en rekommenderad film för att få mer information.  

---

## 7. Rekommendationer baserat på tidigare filmer
**User Story:**  
Som användare vill jag kunna få rekommendationer baserat på vilka filmer jag har tittat på tidigare, så att jag enkelt kan hitta nya filmer som matchar mina intressen.

**User Journey:**  
1. Användaren navigerar till *"Rekommendationer"* i menyn.  
2. Systemet analyserar användarens lista och tidigare betyg.  
3. Systemet visar en lista över rekommenderade filmer, baserat på:  
   - Genreanpassning.  
   - Liknande betygsatta filmer.  
4. Användaren kan klicka på en film för att lägga till den i sin lista eller titta på trailern.


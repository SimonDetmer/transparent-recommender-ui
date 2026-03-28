# Anhang A: Promptverlauf – Prototypentwicklung mit Figma Make

## Kontext
Der folgende Promptverlauf dokumentiert vollständig die iterative Entwicklung eines UX-Prototyps mithilfe eines KI-gestützten Generierungsprozesses (Figma Make).  
Die Interaktion erfolgte dialogbasiert und umfasst mehrere Iterationen zur Gestaltung transparenter und erklärbarer UI-Elemente.

---

## Promptverlauf

### Initiale Generierung

**User:**  
Create a mobile workflow from scratch with a section for recommended videos

**System:**  
I'll create a mobile workflow application with a recommended videos section. This will be a mobile-first design with video thumbnails, titles, and engagement metrics.

I've created a mobile workflow application with a recommended videos section. The app features a dark-themed video feed interface with a header, navigation bar, and six recommended video cards showing thumbnails, titles, channel names, view counts, and timestamps. Each video card includes hover effects and a play button overlay for an engaging user experience.

You could enhance this by:
- Adding video categories or filters  
- Implementing a search functionality  
- Creating detail pages for each video  

---

### Einführung eines Transparenz-Features

**User:**  
Perfect. In the next Step, I need a button or a tool tip near the section "Reccommende Videos" that opens a section that displays information about why the videos are recommended

**System:**  
Perfect! I've added an info button (ℹ️ icon) next to the "Recommended Videos" heading that opens a detailed modal explaining why videos are recommended. The modal slides up from the bottom and displays five key factors: Watch History, Trending Content, Engagement Patterns, View Duration, and Community Preferences, each with icons and descriptions. Users can close the modal by tapping the backdrop or the X button.

---

### Einführung von Layered Explanations

**User:**  
Ok, great. The dialog that opens per info-button shall offer different layers of explanation.  
Layer1 = short explanation why do i see the information.  
Layer 2 = Detailed Explanation.  
Layer 3 = Extended - with visualizations/statistics.  
Layer 4 = Feedback and Controls - eg a settings screen with different options to adjust the behavior

**System:**  
Perfect! I've transformed the info dialog into a multi-layered experience with 4 distinct levels.  
Layer 1 provides a brief overview explaining why this information exists,  
Layer 2 offers detailed explanations of each recommendation factor,  
Layer 3 displays visual statistics with progress bars and metrics,  
Layer 4 presents interactive controls with toggle switches to customize feed preferences.  

Users can navigate between layers using the tab icons at the top or the Previous/Next buttons at the bottom, with progress indicators showing their current position.

---

### Anpassung der Struktur (keine Tabs)

**User:**  
can we try to let it look like different layers not like equivalent tabs.

**System:**  
Perfect! I've redesigned the interface to emphasize a hierarchical layer structure rather than equivalent tabs.  
Now it shows "Layer X of 4" with the current layer title and subtitle, a horizontal progress bar, a depth indicator line, a "Dive Deeper" button, and a breadcrumb trail.  
The navigation feels like descending through levels instead of switching tabs.

---

### Erweiterung von Statistik- und Kontrollfunktionen

**User:**  
Please add in "Statistics and Data":
- "Top Categories" with tags  
- Viewer Community with global user reference  

Please add inside Settings and Controls:
- slider for Personalization Level and Content diversity  
- buttons for clearing history, resetting profile and disabling personalization  
- change language to German  

**System:**  
Perfekt! Ich habe alle gewünschten Änderungen vorgenommen:

**Statistiken & Daten (Ebene 3):**
- „Top-Kategorien“ (z. B. Technologie, Kochen, Fitness, Reisen)  
- „Zuschauer-Community“ mit globalen Nutzungsdaten  

**Einstellungen & Kontrolle (Ebene 4):**
- Slider für Personalisierungsgrad und Inhaltsvielfalt  
- Buttons für „Wiedergabeverlauf löschen“, „Empfehlungsprofil zurücksetzen“ und „Alle Personalisierung deaktivieren“  

Alle Texte wurden ins Deutsche übersetzt.

---

### Startseite & aktives Video

**User:**  
Kannst Du mir auf der Startseite noch ein Video einfügen, das gerade aktiv und präsent oben dargestellt wird über "Recommended Videos".  
Der Name der App lautet "Clipfeed"

**System:**  
Perfekt! Ich habe alle gewünschten Änderungen umgesetzt:

- App-Name: „Clipfeed“  
- Navigation auf Deutsch  
- „Empfohlene Videos“ statt „Recommended Videos“  

**Aktives Video:**
- Prominent oben platziert („Jetzt läuft“)  
- Play-Button, Interaktionen (Like, Kommentare, Teilen)  
- Vollständige Metadaten  

---

### Feedback & Feed-Aktualisierung

**User:**  
Können wir den Button „Feed jetzt aktualisieren“ animieren und Feedback anzeigen?

**System:**  
Perfekt! Ich habe implementiert:

- Rotierende Button-Animation  
- Textänderung („Aktualisiere…“)  
- Erfolgsnachricht („Feed wurde aktualisiert“)  
- Austausch von 3 Videos im Feed  

---

### Sprachliche Konsistenz

**User:**  
Trending Inhalte → Trendende Inhalte

**System:**  
Erledigt – Bezeichnung ist jetzt konsistent.

---

### Kontextmenü pro Video

**User:**  
Kontextmenü mit:
- häufiger zeigen  
- seltener zeigen  
- warum wird mir das angezeigt  

**System:**  
Kontextmenü implementiert mit:
- exklusiven Auswahloptionen  
- visuellem Feedback (Haken, grün)  
- Verlinkung zur Erklärungsebene  

---

### Sichtbarkeit von Feedback

**User:**  
Ich sehe die Nachricht nicht.

**System:**  
Toast-Benachrichtigung hinzugefügt (oben sichtbar).

---

**User:**  
Bitte unten anzeigen

**System:**  
Toast unten positioniert.

---

**User:**  
Direkt unter dem Button platzieren

**System:**  
Erfolgsnachricht wird jetzt direkt unterhalb des Buttons angezeigt.

---

## Hinweis

Der Promptverlauf wurde vollständig übernommen und lediglich strukturiert sowie hinsichtlich Formatierung vereinheitlicht. Inhaltliche Änderungen wurden nicht vorgenommen.

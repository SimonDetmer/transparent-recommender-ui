# Anhang A: Promptverlauf – Prototypentwicklung mit Figma Make

## Kontext
Im Rahmen der Prototypentwicklung wurde ein KI-gestützter Generierungsprozess (Figma Make) eingesetzt. Der folgende Promptverlauf dokumentiert exemplarisch die schrittweise Entwicklung der Benutzeroberfläche.

---

### Initialer Prompt

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

### Transparenzfunktion (Info-Button)

**User:**  
Perfect. In the next step, I need a button or tooltip near the section "Recommended Videos" that explains why the videos are recommended.

**System:**  
An info button (ℹ️) was added next to "Recommended Videos", opening a modal with explanations (e.g. Watch History, Engagement Patterns, etc.).

---

### Layered Explanations

**User:**  
The dialog should offer multiple layers of explanation:
- Layer 1: Short explanation  
- Layer 2: Detailed explanation  
- Layer 3: Statistics / visualizations  
- Layer 4: Feedback and controls  

**System:**  
A multi-layered explanation system was implemented with progressive disclosure and navigation between layers.

---

### Hierarchische Struktur statt Tabs

**User:**  
Make it feel like layers, not tabs.

**System:**  
The interface was redesigned with:
- "Layer X of 4" indicator  
- Progress bar  
- Depth indicator  
- "Dive deeper" interaction  

---

### Erweiterung: Statistiken & Kontrolle

**User:**  
Add:
- "Top Categories" (tags)  
- "Viewer Community"  
- Sliders for personalization  
- Buttons to reset preferences  

**System:**  
All elements were implemented, including sliders and control actions.

---

### Lokalisierung (Deutsch)

**User:**  
Please change language to German.

**System:**  
All UI elements were translated into German.

---

### Startseite & aktives Video

**User:**  
Add a prominent active video above recommendations. App name: "Clipfeed".

**System:**  
Start screen updated with:
- Active video ("Jetzt läuft")  
- Interaction buttons  
- German navigation  

---

### Feedback & Systemreaktion

**User:**  
Animate "Feed aktualisieren" and show feedback.

**System:**  
Implemented:
- Button animation  
- Success notification  
- Feed update logic (video replacement)

---

### UX-Optimierung (Feedbackposition)

**User:**  
Place feedback near the button.

**System:**  
Notification positioned directly below the action button.

---

### Kontextmenü pro Video

**User:**  
Add options:
- Show more / less  
- Why this video?  

**System:**  
Context menu implemented with:
- Toggle behavior  
- Visual feedback  
- Link to explanation layer  

---

## Hinweis

Der dargestellte Promptverlauf wurde zur besseren Lesbarkeit leicht gekürzt und sprachlich geglättet, ohne die inhaltliche Struktur zu verändern. Die vollständige Version ist im begleitenden Repository dokumentiert.

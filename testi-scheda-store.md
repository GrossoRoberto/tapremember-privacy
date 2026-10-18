---
titolo: Testi scheda Play Store in 5 lingue
categoria: play-store
creato: 2026-10-18
aggiornato: 2026-10-18
sorgenti: []
importanza: alta
stato: bozza
tag: [play-store, scheda-store, testi, i18n, a9]
---

# Testi scheda Play Store in 5 lingue

Bozza di Emergent (A9, file suo `/app/memory/store_listing.md`) rivista da Claude il 2026-10-18.
**Da caricare su Play Console solo dopo le verifiche sul telefono qui sotto** (build RC1).
Contesto: [Scheda Store e canali di test](scheda-store.md) · [Rilascio Free](../workflow/rilascio-free-piano-e-stato.md).

## Modifiche rispetto alla bozza di Emergent
1. **Archivio** (5 lingue): la bozza diceva "archivio delle note completate". È sbagliato: nell'app l'archivio contiene le note **archiviate**, mentre le completate restano nella lista. Riscritto.
2. **Frase d'esempio IT**: "il 15 di ogni mese" → "**ogni 15 del mese**". Nel codice del 23/09 è previsto solo "ogni 15 del mese".
3. **Frase d'esempio DE**: "jedes Monats" → "**jeden Monats**". È la forma che il parser riconosce nel codice del 23/09.

## ❓ Da verificare sul telefono prima di caricare (con la build RC1)
- Dettare in ogni lingua la frase d'esempio del secondo paragrafo: data, priorità e ricorrenza devono essere riconosciute tutte e il titolo deve restare pulito. **EN** "on the 15th of every month" è il caso più a rischio.
- Parola di chiusura (salva / save / guardar / enregistrer / speichern): sono tutte nell'elenco del codice (`useSpeechRecognition.js`) ma vanno provate.
- I numeri di caratteri sono stati tolti perché alcune righe sono cambiate. Restano tutti molto sotto i limiti (titolo ≤30, breve ≤80): Play Console li ricontrolla al caricamento.

---

## 🇮🇹 Italiano

**Titolo**
TapRemember: note a voce

**Descrizione breve**
Detta una nota: data, priorità, tag e ricorrenza li capisce da sola.

**Descrizione completa**

Tocca, parla, fatto. TapRemember trasforma una frase detta al volo in una nota completa, senza moduli da compilare.

Dici "Pagare l'affitto ogni 15 del mese, priorità alta" e l'app riconosce da sola la data, la priorità, la ricorrenza e i tag. Prima di salvare vedi un'anteprima chiara di quello che ha capito.

COSA CAPISCE A VOCE
• Date: oggi, domani, dopodomani, i giorni della settimana, "il 15", "il 7 marzo"
• Priorità alta, media o bassa
• Tag, anche tramite le parole chiave che scegli tu
• Ricorrenze semplici e avanzate: ogni giorno, ogni 2 settimane, ogni lunedì, il primo o l'ultimo del mese
• Una parola come "salva" o "fine" e la nota si salva senza toccare lo schermo

TUTTO SOTT'OCCHIO
• Vista a 3 riquadri: Calendario, Note senza data e Promemoria rapidi
• Calendario mensile: tieni premuto un giorno per dettare una nota già con quella data
• Lista con filtri, ordinamento e ricerca
• Archivio per le note da mettere da parte, sempre recuperabili

PROMEMORIA SUL TELEFONO
• Notifiche locali all'orario che scegli per le note in scadenza
• Funzionano anche ad app chiusa e senza connessione

I TUOI DATI
• Usala subito come ospite, oppure accedi con Google per sincronizzare le note tra i dispositivi
• Esporta tutte le note in un file Excel da salvare o condividere

PENSATA PER TUTTI
• Interfaccia e riconoscimento vocale in italiano, inglese, spagnolo, francese e tedesco
• Tema scuro e chiaro
• All'apertura scegli tu: pulsante di dettatura, dettatura immediata o solo l'app
• Tutorial animato incluso, consultabile anche offline

Prossimamente: TapRemember Pro.

---

## 🇬🇧 English

**Title**
TapRemember: Voice Notes

**Short description**
Speak a note: it picks up the date, priority, tags and repeat on its own.

**Full description**

Tap, speak, done. TapRemember turns a quick spoken sentence into a complete note, with no forms to fill in.

Say "Pay rent on the 15th of every month, high priority" and the app recognises the date, priority, repeat and tags by itself. Before saving, you see a clear preview of what it understood.

WHAT IT UNDERSTANDS
• Dates: today, tomorrow, weekdays, "the 15th", "March 7th"
• High, medium or low priority
• Tags, including keywords you choose
• Simple and advanced repeats: every day, every 2 weeks, every Monday, first or last day of the month
• Say a word like "save" or "done" and the note is saved hands-free

EVERYTHING AT A GLANCE
• 3-panel view: Calendar, Notes without a date and Quick reminders
• Monthly calendar: press and hold a day to dictate a note already set to that date
• List with filters, sorting and search
• Archive for notes you want to set aside, always recoverable

REMINDERS ON YOUR PHONE
• Local notifications at the time you choose for notes that are due
• They work even when the app is closed and offline

YOUR DATA
• Start right away as a guest, or sign in with Google to sync notes across devices
• Export all your notes to an Excel file to save or share

MADE FOR EVERYONE
• Interface and voice recognition in English, Italian, Spanish, French and German
• Dark and light theme
• Choose what happens on launch: dictation button, instant dictation or just the app
• Animated tutorial included, available offline too

Coming soon: TapRemember Pro.

---

## 🇪🇸 Español

**Título**
TapRemember: notas por voz

**Descripción breve**
Dicta una nota: fecha, prioridad, etiquetas y repetición, las entiende sola.

**Descripción completa**

Toca, habla y listo. TapRemember convierte una frase dicha al vuelo en una nota completa, sin formularios que rellenar.

Di "Pagar el alquiler el 15 de cada mes, prioridad alta" y la app reconoce sola la fecha, la prioridad, la repetición y las etiquetas. Antes de guardar ves una vista previa clara de lo que ha entendido.

LO QUE ENTIENDE POR VOZ
• Fechas: hoy, mañana, pasado mañana, los días de la semana, "el 15", "el 7 de marzo"
• Prioridad alta, media o baja
• Etiquetas, también mediante las palabras clave que elijas
• Repeticiones simples y avanzadas: cada día, cada 2 semanas, cada lunes, el primer o el último día del mes
• Di una palabra como "guardar" y la nota se guarda sin tocar la pantalla

TODO A LA VISTA
• Vista de 3 paneles: Calendario, Notas sin fecha y Recordatorios rápidos
• Calendario mensual: mantén pulsado un día para dictar una nota ya con esa fecha
• Lista con filtros, orden y búsqueda
• Archivo para las notas que quieras apartar, siempre recuperables

RECORDATORIOS EN EL MÓVIL
• Notificaciones locales a la hora que elijas para las notas que vencen
• Funcionan incluso con la app cerrada y sin conexión

TUS DATOS
• Úsala enseguida como invitado o inicia sesión con Google para sincronizar las notas entre dispositivos
• Exporta todas las notas a un archivo Excel para guardarlo o compartirlo

PENSADA PARA TODOS
• Interfaz y reconocimiento de voz en español, inglés, italiano, francés y alemán
• Tema oscuro y claro
• Al abrir la app eliges tú: botón de dictado, dictado inmediato o solo la app
• Tutorial animado incluido, disponible también sin conexión

Próximamente: TapRemember Pro.

---

## 🇫🇷 Français

**Titre**
TapRemember : notes vocales

**Description courte**
Dictez une note : date, priorité, tags et répétition sont compris tout seuls.

**Description complète**

Touchez, parlez, c'est fait. TapRemember transforme une phrase dite à la volée en une note complète, sans formulaire à remplir.

Dites « Payer le loyer le 15 de chaque mois, priorité haute » et l'app reconnaît d'elle-même la date, la priorité, la répétition et les tags. Avant d'enregistrer, vous voyez un aperçu clair de ce qu'elle a compris.

CE QU'ELLE COMPREND À LA VOIX
• Dates : aujourd'hui, demain, après-demain, les jours de la semaine, « le 15 », « le 1er mars »
• Priorité haute, moyenne ou basse
• Tags, y compris avec les mots-clés que vous choisissez
• Répétitions simples et avancées : chaque jour, toutes les 2 semaines, chaque lundi, le premier ou le dernier jour du mois
• Un mot comme « enregistrer » et la note est enregistrée sans toucher l'écran

TOUT EN UN COUP D'ŒIL
• Vue en 3 cadres : Calendrier, Notes sans date et Rappels rapides
• Calendrier mensuel : appuyez longuement sur un jour pour dicter une note déjà datée
• Liste avec filtres, tri et recherche
• Archive pour les notes à mettre de côté, toujours récupérables

DES RAPPELS SUR VOTRE TÉLÉPHONE
• Notifications locales à l'heure que vous choisissez pour les notes à échéance
• Elles fonctionnent même app fermée et hors connexion

VOS DONNÉES
• Utilisez-la tout de suite en invité, ou connectez-vous avec Google pour synchroniser vos notes entre appareils
• Exportez toutes vos notes dans un fichier Excel à enregistrer ou partager

PENSÉE POUR TOUS
• Interface et reconnaissance vocale en français, anglais, italien, espagnol et allemand
• Thème sombre et clair
• À l'ouverture, vous choisissez : bouton de dictée, dictée immédiate ou simplement l'app
• Tutoriel animé inclus, consultable même hors connexion

Bientôt : TapRemember Pro.

---

## 🇩🇪 Deutsch

**Titel**
TapRemember: Sprachnotizen

**Kurzbeschreibung**
Notiz diktieren: Datum, Priorität, Tags und Wiederholung erkennt sie selbst.

**Vollständige Beschreibung**

Tippen, sprechen, fertig. TapRemember macht aus einem schnell gesprochenen Satz eine vollständige Notiz, ganz ohne Formulare.

Sag „Miete zahlen am 15. jeden Monats, hohe Priorität" und die App erkennt Datum, Priorität, Wiederholung und Tags von selbst. Vor dem Speichern siehst du eine klare Vorschau dessen, was sie verstanden hat.

WAS SIE PER SPRACHE VERSTEHT
• Daten: heute, morgen, übermorgen, Wochentage, „am 15.", „am 7. März"
• Hohe, mittlere oder niedrige Priorität
• Tags, auch über Schlüsselwörter, die du selbst festlegst
• Einfache und erweiterte Wiederholungen: täglich, alle 2 Wochen, jeden Montag, am Ersten oder Letzten des Monats
• Ein Wort wie „speichern" genügt, und die Notiz wird ohne Berühren gespeichert

ALLES AUF EINEN BLICK
• Ansicht mit 3 Bereichen: Kalender, Notizen ohne Datum und Schnelle Erinnerungen
• Monatskalender: einen Tag gedrückt halten, um eine Notiz direkt mit diesem Datum zu diktieren
• Liste mit Filtern, Sortierung und Suche
• Archiv für Notizen, die du beiseitelegen willst, jederzeit wiederherstellbar

ERINNERUNGEN AUF DEM HANDY
• Lokale Benachrichtigungen zur gewünschten Uhrzeit für fällige Notizen
• Sie funktionieren auch bei geschlossener App und ohne Internet

DEINE DATEN
• Sofort als Gast nutzen oder mit Google anmelden, um Notizen zwischen Geräten zu synchronisieren
• Alle Notizen als Excel-Datei exportieren, speichern oder teilen

FÜR ALLE GEMACHT
• Oberfläche und Spracherkennung auf Deutsch, Englisch, Italienisch, Spanisch und Französisch
• Dunkles und helles Design
• Beim Öffnen entscheidest du: Diktiertaste, sofortiges Diktieren oder nur die App
• Animiertes Tutorial inklusive, auch offline verfügbar

Demnächst: TapRemember Pro.

## Riferimenti
- Nessun file in `raw/`: conoscenza generata in sessione (chat Claude 2026-10-18), voce in `log.md`.
- FA `TapRemember_Scheda_Store_2026-10-18_FA.md` (stesso contenuto).

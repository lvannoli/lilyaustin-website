# Lily Austin Portfolio Website

Un portfolio elegante one-page con scroll snap per Lily Austin, podcast producer.

## 📁 Struttura File

```
lilyaustin-portfolio/
├── index.html          # Il sito completo
├── profile-photo.jpg   # La tua foto (da aggiungere)
└── audio/              # Cartella per i file audio
    ├── monocle-on-fashion.mp3
    ├── the-foreign-desk.mp3
    ├── the-foreign-desk-explainer.mp3
    ├── streets-in-the-sky.mp3
    └── groovy-movies.mp3
```

## 🚀 Come Configurare

### 1. Formspree
Per far funzionare il form di contatto:

1. Vai su [Formspree](https://formspree.io) e accedi al tuo account
2. Crea un nuovo form o usa uno esistente
3. Copia l'endpoint (es: `https://formspree.io/f/xyzabcde`)
4. Nel file `index.html`, cerca questa riga (circa riga 450):
   ```html
   <form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
5. Sostituisci `YOUR_FORM_ID` con il tuo ID form
6. Nelle impostazioni di Formspree, configura l'email di destinazione come `lilyaustinuk@gmail.com`

### 2. Foto Profilo
1. Prepara una foto quadrata di almeno 640x640 pixel
2. Rinominala `profile-photo.jpg`
3. Mettila nella stessa cartella di `index.html`

### 3. File Audio
1. Crea una cartella chiamata `audio` nella stessa directory di `index.html`
2. Aggiungi i tuoi file MP3 con questi nomi esatti:
   - `monocle-on-fashion.mp3`
   - `the-foreign-desk.mp3`
   - `the-foreign-desk-explainer.mp3`
   - `streets-in-the-sky.mp3`
   - `groovy-movies.mp3`

### 4. Upload su Hosting
Carica tutti i file sul tuo hosting collegato a `lilyaustin.co.uk`

## 🎨 Palette Colori

La palette è stata scelta per complementare capelli rossi e pelle chiara:

| Colore | Hex | Uso |
|--------|-----|-----|
| Blush | `#E8C4C4` | Accenti, decorazioni |
| Peach | `#F2D7C9` | Bordi, hover |
| Sage | `#C5D5CB` | Tag, elementi secondari |
| Cream | `#FDF8F4` | Sfondo principale |
| Terracotta | `#C9907D` | Accent principale, CTA |
| Warm Brown | `#8B6E61` | Titoli, testo importante |

## ✏️ Personalizzazioni

### Modificare le descrizioni dei podcast
Cerca nel file HTML le sezioni `<div class="work-description">` per ciascun podcast e modifica il testo.

### Aggiungere link social
Puoi aggiungere icone social nell'header o nel footer modificando l'HTML.

### Cambiare i colori
I colori sono definiti come CSS variables all'inizio del file (`:root`). Modificali per cambiare l'intera palette.

## 📱 Responsive

Il sito è completamente responsive e funziona su:
- Desktop
- Tablet
- Mobile

## 🔧 Requisiti Tecnici

- Hosting con supporto per file statici
- Nessun database richiesto
- Nessuna dipendenza esterna (tranne Google Fonts)

---

Creato con ❤️ per Lily Austin

# 📅 Calendario MNS Group

Sistema di calendario unificato per MNS Group con sincronizzazione Google Calendar.

## 🎯 Funzionalità

- **Dashboard Esecutiva**: Vista rapida eventi giornalieri e settimanali
- **Calendario Completo**: Vista calendario Google integrata
- **Sincronizzazione Mobile**: Eventi automaticamente sui telefoni di tutti i soci
- **Account Condiviso**: Centralizzato su monkeynsleeps@gmail.com

## 📁 Struttura File

```
mns-group-calendar/
├── index.html              # Dashboard principale (Opzione C)
├── calendario-completo.html # Vista calendario completa (Opzione A)  
├── README.md               # Questo file
└── _config.yml             # Configurazione GitHub Pages
```

## 🚀 Setup Completo - Istruzioni per Gianluca

### Passo 1: Creare Repository GitHub
1. Vai su https://github.com
2. Clicca "New repository" (pulsante verde)
3. Nome repository: `mns-group-calendar`
4. Descrizione: `Calendario condiviso MNS Group`
5. Seleziona "Public"
6. ✅ Spunta "Add a README file"
7. Clicca "Create repository"

### Passo 2: Caricare i File
1. Nel repository appena creato, clicca "uploading an existing file"
2. Trascina questi file:
   - `index.html` 
   - `calendario-completo.html`
   - `_config.yml`
3. Scrivi messaggio commit: "Setup calendario MNS Group"
4. Clicca "Commit changes"

### Passo 3: Attivare GitHub Pages
1. Nel repository, vai su "Settings" (tab in alto)
2. Scorri fino a "Pages" (menu laterale sinistro)
3. Sotto "Source" seleziona "Deploy from a branch"
4. Branch: "main"
5. Cartella: "/ (root)"
6. Clicca "Save"
7. Aspetta 5-10 minuti

### Passo 4: Configurare Google Calendar Embed
1. Vai su https://calendar.google.com
2. Login con monkeynsleeps@gmail.com
3. Nel menu laterale sinistro, trova il calendario che vuoi condividere
4. Clicca sui tre punti (⋮) accanto al calendario
5. Seleziona "Settings and sharing"
6. Scorri fino a "Integrate calendar"
7. Copia il codice "Embed code"
8. Nel file `calendario-completo.html`, sostituisci l'URL nell'iframe con il tuo

### Passo 5: Integrare nel Portale MNS
1. Apri il file principale del portale MNS Group
2. Aggiungi questo codice nella sezione appropriate:

```html
<div class="dashboard-item">
    <h3>📅 Calendario Aziendale</h3>
    <p>Gestione eventi e riunioni MNS Group</p>
    <a href="https://gianlucamadeddu.github.io/mns-group-calendar/" 
       class="btn-primary" target="_blank">
        Apri Calendario
    </a>
</div>
```

## 🔗 URL Finali

Dopo il setup, avrai questi link:
- **Dashboard**: `https://gianlucamadeddu.github.io/mns-group-calendar/`
- **Calendario Completo**: `https://gianlucamadeddu.github.io/mns-group-calendar/calendario-completo.html`

## 👥 Soci MNS Group

- Gianluca Madeddu
- Andrea  
- Simone
- Nicola
- Gabriele

## 📧 Account Collegato

**Email condivisa**: monkeynsleeps@gmail.com

## 🔧 Personalizzazioni Future

### Cambio Colori Brand
Nel file CSS, cerca questa sezione per cambiare i colori:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Aggiunta Logo MNS
Aggiungi il logo nell'header sostituendo:
```html
<h1>📅 Dashboard Calendario</h1>
```
Con:
```html
<h1><img src="logo-mns.png" alt="MNS"> Dashboard Calendario</h1>
```

## 📱 Sincronizzazione Mobile

Tutti i soci riceveranno automaticamente:
- Notifiche push per nuovi eventi
- Promemoria prima delle riunioni  
- Sync calendario sui telefoni
- Aggiornamenti in tempo reale

## 🆘 Risoluzione Problemi

### Calendario non si carica
1. Verifica che l'account Google sia pubblico
2. Controlla l'URL embed del calendario
3. Aspetta 5-10 minuti per propagazione

### Link non funzionano
1. Verifica che GitHub Pages sia attivo
2. Controlla che i file siano nel branch "main"
3. URL corretto: `https://gianlucamadeddu.github.io/mns-group-calendar/`

### Modifiche non si vedono
1. Fai "hard refresh" con Ctrl+F5
2. Aspetta 5-10 minuti per GitHub Pages
3. Verifica che i file siano stati caricati correttamente

## 📞 Supporto

Per problemi tecnici contatta Gianluca o modifica direttamente i file su GitHub.

---

**Sviluppato per MNS Group | Agosto 2025**

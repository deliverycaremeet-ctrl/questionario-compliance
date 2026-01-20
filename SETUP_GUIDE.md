# 🚀 GUIDA SETUP GITHUB PAGES - PASSO PASSO

## 📋 PREREQUISITI

- Account GitHub (se non ce l'hai: https://github.com/signup)
- I file che ti ho preparato

## 🎯 STEP 1: CREA IL REPOSITORY

1. Vai su https://github.com
2. Clicca sul **"+"** in alto a destra → **"New repository"**
3. Compila:
   - **Repository name**: `questionario-compliance` (o qualsiasi nome)
   - **Description**: "Check Compliance Sicurezza Lavoro D.Lgs 81/08"
   - Seleziona: **✅ Public**
   - Seleziona: **✅ Add a README file**
4. Clicca **"Create repository"**

## 📤 STEP 2: CARICA I FILE

### OPZIONE A: Upload via Browser (PIÙ SEMPLICE)

1. Nel repository appena creato, clicca **"Add file"** → **"Upload files"**
2. Trascina questi 3 file:
   - `index.html` (landing page)
   - `questionario.html` (questionario vero e proprio)
   - `README.md` (documentazione)
3. Scrivi commit message: "Initial commit - questionario compliance"
4. Clicca **"Commit changes"**

### OPZIONE B: Git da Terminale (per esperti)

```bash
# Clona il repository
git clone https://github.com/TUOUSERNAME/questionario-compliance.git
cd questionario-compliance

# Copia i file nella cartella
# (sposta index.html, questionario.html, README.md qui)

# Carica su GitHub
git add .
git commit -m "Initial commit - questionario compliance"
git push origin main
```

## 🌐 STEP 3: ATTIVA GITHUB PAGES

1. Nel repository, vai su **"Settings"** (in alto a destra)
2. Nella barra laterale sinistra, clicca **"Pages"**
3. In **"Source"**:
   - Branch: seleziona **"main"**
   - Folder: lascia **"/ (root)"**
4. Clicca **"Save"**
5. **ASPETTA 1-2 MINUTI** (GitHub sta pubblicando)

## ✅ STEP 4: VERIFICA

1. Nella stessa pagina "Pages", vedrai:
   ```
   Your site is live at https://TUOUSERNAME.github.io/questionario-compliance/
   ```
2. Clicca sul link per vedere il sito live!

## 🎉 FATTO!

Ora hai:
- **Landing page**: https://TUOUSERNAME.github.io/questionario-compliance/
- **Questionario diretto**: https://TUOUSERNAME.github.io/questionario-compliance/questionario.html

## 📧 COME USARLO

### Opzione 1: Manda il link ai commercialisti

```
Ciao [Nome],

ho preparato un questionario online per i tuoi clienti:
👉 https://TUOUSERNAME.github.io/questionario-compliance/

I clienti:
1. Cliccano il link
2. Compilano in 5-10 minuti
3. Ricevono report immediato
4. Se emergono criticità, ti contattano

Zero costi, zero installazioni.

Provalo e dimmi cosa ne pensi!

Giulio
```

### Opzione 2: Manda link diretto al questionario

```
https://TUOUSERNAME.github.io/questionario-compliance/questionario.html
```

## 🔧 PERSONALIZZAZIONE

Per personalizzare con il nome dello studio commercialista:

1. Nel repository GitHub, clicca su `questionario.html`
2. Clicca sulla matita ✏️ (Edit)
3. CTRL+F cerca: `[NOME STUDIO COMMERCIALISTA]`
4. Sostituisci con: `Studio Commercialista Rossi` (esempio)
5. Cerca: `[numero]` → Sostituisci con: `02 1234567`
6. Cerca: `[email]` → Sostituisci con: `info@studio.it`
7. Clicca **"Commit changes"** → **"Commit directly"**

Ripeti per `index.html`.

## 📊 ANALYTICS (OPZIONALE)

Per vedere quante persone usano il questionario:

1. Vai su https://analytics.google.com
2. Crea un account
3. Ottieni il codice tracking
4. Aggiungilo in `index.html` e `questionario.html` prima di `</head>`

## 🔒 PRIVACY

⚠️ **IMPORTANTE**: Il questionario NON salva dati online.
Tutto viene elaborato localmente nel browser del cliente.
Zero privacy concerns.

## 🆘 PROBLEMI COMUNI

### Il sito non si vede dopo 5 minuti
- Controlla che in Settings → Pages sia selezionato "main"
- Prova a rifare "Save"
- Aspetta altri 5 minuti

### Link non funziona
- Verifica che il repository sia "Public" (non "Private")
- Controlla che i file siano nella root (non in sottocartelle)

### Pagina bianca
- Apri la Console del browser (F12)
- Guarda se ci sono errori
- Verifica che i file siano stati caricati correttamente

## 📞 SUPPORTO

Se hai problemi:
1. Leggi la documentazione GitHub: https://pages.github.com
2. Controlla che i nomi file siano esatti (minuscole)
3. Verifica che i file siano stati uploadati

## 🎯 PROSSIMI STEP

✅ Repository creato
✅ GitHub Pages attivato
✅ Link funzionante

Ora puoi:
1. ✉️ Mandare link ai commercialisti
2. 📱 Condividere sui social
3. 📧 Inserire nelle email signature
4. 🔗 Linkare dal sito Delivery Care

---

🎉 **COMPLIMENTI! Il tuo questionario è online!**

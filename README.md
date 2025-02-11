# wikimodern-pwa
WikiModern PWA – Progressive Web App moderna che integra dati da Wikipedia in modalità "Introduzione" e "Completo". Backend: Node.js, Express, Prisma, MySQL, Redis; Frontend: Next.js, Tailwind CSS. Demo deploy su GitHub Pages.

# WikiModern PWA 🚀

![GitHub top language](https://img.shields.io/github/languages/top/tuo-username/wikimodern-pwa?style=for-the-badge)
![GitHub repo size](https://img.shields.io/github/repo-size/tuo-username/wikimodern-pwa?style=for-the-badge)
![GitHub license](https://img.shields.io/github/license/tuo-username/wikimodern-pwa?style=for-the-badge)

WikiModern PWA è una Progressive Web App moderna che integra un backend in Node.js (con Express, Prisma e Redis) e un frontend in Next.js.  
Questa app consente di effettuare ricerche su Wikipedia, ottenendo dati aggiornati in tempo reale, con modalità **Introduzione** o **Completo**. In caso di assenza di connettività, viene usata la cache presente nel database.

## 📦 Caratteristiche

- **Aggiornamento in tempo reale:**  
  Ogni richiesta online esegue una chiamata API a Wikipedia e aggiorna i dati se migliori.
- **Fallback offline:**  
  In assenza di connettività, la PWA visualizza l'ultima versione disponibile.
- **Modalità di ricerca:**  
  Scegli tra un estratto introduttivo o il testo completo dell'articolo.
- **Interfaccia moderna:**  
  UI minimalista e responsive, con layout a card e supporto per GitHub Pages.

## 🛠 Tecnologie

- **Backend:** Node.js, Express, Prisma, MySQL, Redis
- **Frontend:** Next.js, React, Tailwind CSS, React-Bootstrap (in fase di migrazione verso Tailwind)
- **Deploy:** GitHub Pages (per la demo statica)

## 🚀 Installazione e Avvio

### Prerequisiti

- [Node.js](https://nodejs.org/) v14 o superiore
- [MySQL](https://www.mysql.com/)
- [Redis](https://redis.io/)

### Configurazione Backend

1. Clona il repository:
   ```bash
   git clone https://github.com/tuo-username/wikimodern-pwa.git
   cd wikimodern-pwa/wikimodern-backend

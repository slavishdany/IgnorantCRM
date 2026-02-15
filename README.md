# IgnorantCRM 🚀

Un CRM per networker… ignorante, pragmatico e divertente 😏  
Progetto personale e divulgativo, costruito in **C# / ASP.NET Core 9**, con focus su contatti, DM e scheduler post.

---

## Roadmap 🗺️

### Fase 1 – MVP educativo
**Obiettivo:** avere qualcosa che funziona subito, imparando architettura, background service e domain modeling.

- [x] Modello dominio base: `Contact`, `Interaction`, `Reminder`  
- [x] UI minimale: dashboard semplice con contatti e follow-up  
- [x] Reminder automatici via `BackgroundService`  
- [x] Scheduler post demo (solo dev mode, Instagram)  
- [x] Logging interazioni manuali (DM / call / note)

> 🎯 Nota Sviluppoignorante: funziona prima di essere bello 😎

---

### Fase 2 – DM Instagram e automazioni
**Obiettivo:** integrare social reali e automazioni base.

- [ ] Webhook Instagram DM (dev mode)  
- [ ] Creazione automatica contatti da DM  
- [ ] Logging automatico interazioni → timeline  
- [ ] Suggerimenti follow-up base  
- [ ] Primo mini insight “chi sto ignorando oggi?”  

> 🎯 Nota Sviluppoignorante: qui si vede la magia del laboratorio reale

---

### Fase 3 – Insight & dashboard avanzata
**Obiettivo:** dare valore “wow” al CRM, visualizzare lo stato delle relazioni.

- [ ] Relationship health score (verde/giallo/rosso)  
- [ ] Filtri e tag sui contatti  
- [ ] Calendario post programmati  
- [ ] Mini analytics: numero interazioni, follow-up completati  

> 🎯 Nota Sviluppoignorante: insight semplice, ma potente

---

### Fase 4 – SaaS-ready / optional
**Obiettivo:** preparare il progetto per eventuale pubblicazione o vendita futura.

- [ ] Multi-tenant / utenti separati  
- [ ] Autenticazione e ruoli  
- [ ] Billing / abbonamenti base (Stripe)  
- [ ] Social connectors extra (WhatsApp, email, TikTok manuale)  
- [ ] Feature “wow” premium: AI follow-up  

> 🎯 Nota Sviluppoignorante: funzionalità opzionali, per chi vuole spingere IgnorantCRM oltre

---

## Come contribuire 🤝

- Apri issue per suggerimenti o bug  
- Fork, modifica e PR  
- Commenta idee, siamo tutti ignoranti qui 😏  

---

## Tecnologie principali 🛠️

- ASP.NET Core 9  
- EF Core / SQL Server  
- BackgroundService / Hangfire  
- Webhook dev mode Instagram  
- Tailwind / Bootstrap per UI minima

---

## Disclaimer ⚠️

- IgnorantCRM è **educativo e personale**  
- Non è un CRM completo / enterprise  
- Solo per chi vuole imparare e divertirsi 😎

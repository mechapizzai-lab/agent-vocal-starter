# Agent Vocal RDV — Starter

Bienvenue dans le projet de départ du cours **Agent Vocal IA** de MechaPizzAI.

Ce dépôt contient uniquement le point de départ. **Tout le code est à créer en suivant le cours.**

---

## Ce que tu vas construire

Un agent vocal IA qui :
- Répond aux appels téléphoniques en français
- Comprend le besoin du client
- Consulte un Google Calendar pour trouver des créneaux libres
- Réserve un RDV et envoie une invitation par email
- Enregistre le contact dans Airtable
- Se pilote depuis un dashboard web

---

## Stack utilisée

| Brique | Rôle |
|---|---|
| **VAPI** | Agent vocal + numéro de téléphone |
| **GPT-4o** | Cerveau de l'agent |
| **Deepgram** | Transcription vocale (STT) |
| **ElevenLabs** | Synthèse vocale (TTS) |
| **Google Calendar** | Disponibilités + réservation |
| **Airtable** | Base de données des RDV |
| **FastAPI** | Serveur webhook |
| **Railway** | Hébergement |

---

## Contenu de ce dépôt

```
agent-vocal-starter/
├── Skill.md    # Skill Claude Code utilisé pendant le cours
└── README.md   # Ce fichier
```

Tout le reste (code, configuration, déploiement) est construit pas à pas dans le cours.

---

## Comptes à créer avant de commencer

1. [VAPI](https://vapi.ai) — agent vocal
2. [OpenAI](https://platform.openai.com) — GPT-4o
3. [ElevenLabs](https://elevenlabs.io) — voix
4. [Google Cloud](https://console.cloud.google.com) — Calendar API
5. [Airtable](https://airtable.com) — base de données
6. [Railway](https://railway.app) — hébergement

---

## Membres Skool

Tu es membre payant ? Télécharge le **projet complet clé en main** dans la section ressources de la communauté — tout le code est déjà écrit, il ne reste qu'à configurer tes propres clés API.

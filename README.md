# 3PO — paquets

Paquets téléchargeables de **3PO**, traducteur vocal 100 % hors ligne pour Android (application personnelle).

Ce dépôt ne contient que des **modèles publics convertis** (aucune donnée personnelle) :

| Paquet | Contenu | Origine |
|---|---|---|
| `opus-xx-yy.zip` | Traduction Opus-MT (ONNX int8) d'une langue vers une autre | [Helsinki-NLP](https://huggingface.co/Helsinki-NLP), licence CC-BY 4.0 |
| `sherpa-onnx-whisper-*.zip` | Reconnaissance vocale Whisper (int8) | [OpenAI Whisper](https://github.com/openai/whisper) (MIT), conversion [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) |
| `whisper-turbo-npu.zip` | Whisper large-v3-turbo précompilé pour la puce IA Snapdragon 8 Gen 2 | [Qualcomm AI Hub](https://aihub.qualcomm.com/) |
| `vits-piper-*.zip` | Voix de synthèse Piper | [Piper](https://github.com/rhasspy/piper) (MIT), voix sous leurs licences respectives |

Le fichier `catalogue.json` de la release `paquets-1` indique à l'application quoi télécharger (taille, empreinte SHA-256).
Le modèle de traduction Gemma 4 E2B est téléchargé directement chez Hugging Face.

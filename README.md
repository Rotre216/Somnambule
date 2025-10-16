# 🌙 Somnambule

**Somnambule** est une expérience web interactive où les visiteurs sont invités à redécouvrir la ville sous un oeil différent: celui d'un somnambule qui fait vivre l'art de la ville par ses rêves. L'expérience se termine par le partage d'un rêve sur **Mur des Rêves**, dans un effort de connexion.  

Projet développé dans le cadre de la nuit blanche de montréal 2026

---

## Concept

<p>Durant la Nuit Blanche, la ville s’éveille dans l’obscurité.  
*Somnambule* propose un espace calme, collectif et poétique : un lieu où les rêves se rencontrent.  
Il prend le format d'un mélange entre une chasse aux trésors et un "livre dont vous êtes le héros".
Les participant·e·s accèdent aux prochaines énigmes en observant la ville autour d'eux et en répondant à une petite énigme. À la fin, ils sont invités à partager leurs rêves.</p>
---

## 🧩 Structure du projet

- **Frontend :** HTML / CSS conçu pour une ambiance qui rappelle la tranquilité de la nuit
- **Backend :** [Supabase](https://supabase.com/) — utilisé pour stocker les messages de manière anonyme.  
- **Base de données :**  
  - Table : `Wall_of_dreams`  
  - Colonne : `My_message` (texte du rêve)

 
    Somnambule/
│
├── fr/ ← version française des étapes
│ ├── index.html
│ ├── etape1.html
│ └── …
│
├── en/ ← version anglaise des étapes
│ ├── index.html
│ ├── step1.html
│ └── …
│
├── Audio/ ← fichiers audio pour les étapes
│ ├── audio1.mp3
│ └── …
│
├── Images/ ← illustrations, icônes, visuels
│
├── index.html ← page d’accueil avec choix de la langue
├── README.md ← ce fichier
└── (Autres fichiers CSS/JS si besoin)

## Exemple de l'interface
<center>
  <img width="543" height="292" alt="image" src="https://github.com/user-attachments/assets/55cc73d4-690a-4282-b214-b4db4a66eff8" />
</center>



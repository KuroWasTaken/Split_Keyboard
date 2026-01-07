<div align="center">
  <h1>⌨️ Projet Clavier Split Ergonomique</h1>
  <p><i>Conception matérielle et mécanique par Quentin JALLAIS</i></p>
  Projet basé sur le modèle de BluePrint Hackclub : https://blueprint.hackclub.com/projects/2176?return_to=%2Fexplore%3Futm_source%3Dsite

  <img src="https://img.shields.io/badge/Status-Design_Phase-orange?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Logiciels-KiCad_%7C_SolidWorks-blue?style=for-the-badge" alt="Logiciels">
</div>

<hr>

## 🛠️ Conception du PCB
Le circuit imprimé a été conçu pour être séparé en deux parties. J'ai utilisé des pistes larges de **24mil** pour garantir une excellente fiabilité et faciliter la soudure des composants.

<p align="center">
  <img src="ergodow keyboard.png" width="800" alt="Rendu 3D du PCB">
</p>

---

## 📐 Modélisation CAO (SolidWorks)
Le boîtier est optimisé pour l'impression 3D. Il se compose d'une plaque supérieure pour maintenir les interrupteurs et d'un cadre structurel.

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <img src="plate.png" alt="Plaque supérieure">
      <br>
      <b>Plaque de maintien (Switch Plate)</b>
    </td>
    <td width="50%" align="center">
      <img src="sdw_top.png" alt="Cadre du boîtier">
      <br>
      <b>Cadre du boîtier (Case Frame)</b>
    </td>
  </tr>
</table>
---
<hr>

<table>
  <tr>
    <td>
      <h2>🧠 Firmware & Programmation</h2>
      <p>Le clavier est piloté par le firmware <b>QMK</b>, ce qui permet une personnalisation totale :</p>
      <ul>
        <li><b>Multi-couches :</b> Passage facile entre QWERTY( et oui je suis étrange je sais ), chiffres et symboles.</li>
        <li><b>Split :</b> Gestion native de la communication entre les deux moitiés.</li>
        <li><b>Macros :</b> Raccourcis complexes programmables sur une seule touche.</li>
      </ul>
      <p><i>Le firmware peut être mis à jour simplement via USB avec QMK Toolbox.</i></p>
    </td>
    <td width="40%" align="center">
      <img src="https://docs.qmk.fm/qmk-logo-light.svg" width="150">
    </td>
  </tr>
</table>
---

## 🚀 État d'avancement
- [x] Routage du PCB (KiCad)
- [x] Modélisation des pièces (SolidWorks)
- [X] Impression 3D des composants (Bientôt)
- [X] Assemblage final et Firmware QMK/VIA

<br>

<div align="center">
  <h3>📸 Rendu final !</h3>
  <img width="1080" height="720" alt="image" src="https://github.com/user-attachments/assets/d6add6ba-01b2-4a18-bc82-23841da1ee18" />

  <p><i>Je suis très content du rendu final. Si vous avez des questions n'hésitez pas a me les poser</i></p>
</div>

---
marp: true
theme: default
_class: lead
_paginate: false
paginate: true
backgroundColor: #ffffff
style: |
  section {
    font-size: 22px;
    color: #333;
    line-height: 1.6;
    padding: 60px 80px;
  }
  footer { width: 100%; text-align: right; font-size: 14px; color: #888; }
  .logo-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: absolute;
    top: 40px;   
    left: 60px;
    right: 60px;
  }
  .logo-header img { height: 140px; margin: 0; margin-left:10px; margin-right:10px }
  h1 { color: #029fcaff; font-size: 2.8em; margin-top: 100px; text-align: left; }
  h2 { color: #029fcaff; font-size: 2em; border-bottom: 2px solid #029fcaff; margin-bottom: 40px;}
  h3 { text-align: left; color: #029fcaff; margin-top: 0; }

  .sommaire-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    margin-top: 20px;
  }
  .sommaire-item {
    display: flex;
    align-items: center;
    background: #f2fafcff;
    border-radius: 12px;
    padding: 15px 20px;
    border-left: 5px solid #029fcaff;
  }
  .sommaire-num {
    background: #029fcaff;; color: white; width: 35px; height: 35px;
    display: flex; justify-content: center; align-items: center;
    border-radius: 50%; font-weight: bold; margin-right: 15px; flex-shrink: 0;
  }
  
  .img-container {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 420px; /* Fixed height to prevent overflow */
    margin-top: 10px;
    overflow: hidden;
  }

  .img-methodo {
    max-width: 85%;
    max-height: 100%;
    object-fit: contain;
    border-radius: 10px;
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
  }

  .img-usecase {
    width: auto;
    height: 100%;
    max-width: 100%;
    object-fit: contain;
    border-radius: 10px;
    background-color: #fff;
    box-shadow: 0 5px 15px rgba(0,0,0,0.08);
  }

  .dt-card {
    background: #f2fafcff;
    padding: 30px;
    border-radius: 10px;
    border-top: 6px solid #029fcaff;
    text-align: left;
    margin-top: 20px;
    width: 100%;
  }

  .tech-container {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 20px;
  }
  .badge-simple {
    padding: 8px 18px;
    border-radius: 6px;
    font-weight: 600;
    background-color: #545353ff;
    color: #ffffff !important;
    font-size: 0.85em;
    border: 1px solid #222;
  }
  .maquette-grid {
    display: flex;
    gap: 15px;
    justify-content: center;
    align-items: center;
    height: 400px;
  }

---

<div class="logo-header">
  <img src="images/ofppt-logo.png" alt="Logo Left">
  <img src="images/logo-solicode.png" alt="Logo Right">
</div>

# Réseaux et Déploiement Web
### Présentation de la session - Réseaux et Déploiement Web
**Projet :** <span class="highlight">[Fin C6] Réseaux et Déploiement Web</span>  
**Apprenant :** <span class="highlight">Mehdi Ben Taleb</span>  
**Filière :** Développement Mobile et Web



---

## Sommaire

<div class="sommaire-grid">
  <div class="sommaire-item"><div class="sommaire-num">1</div><div class="sommaire-text"> Les tâches terminées </div></div>
  <div class="sommaire-item"><div class="sommaire-num">2</div><div class="sommaire-text"> Les tâches en cours </div></div>
  <div class="sommaire-item"><div class="sommaire-num">3</div><div class="sommaire-text"> Les étapes suivantes </div></div>
  <div class="sommaire-item"><div class="sommaire-num">4</div><div class="sommaire-text"> Liens et Ressources </div></div>
</div>

---

## Contexte

<div class="dt-card" style="margin-top: 20px; font-size: 0.85em;">
  <p><strong>Contexte :</strong> Cette session s'inscrit dans le cadre du module <strong>Réseaux et Déploiement Web</strong>. L'objectif est de comprendre l'infrastructure physique et logique nécessaire pour héberger des applications web modernes.</p>
</div>

---

## 1. Les tâches terminées

<div class="dt-card">
  <ul>
    <li><strong>1 - Tutoriel :</strong> Ubuntu</li>
    <li><strong>1 - Tutoriel :</strong> LAN & équipements</li>
    <li><strong>1 - Flyer :</strong> Communication</li>
  </ul>
</div>

---

## 2. Les tâches en cours

<div class="dt-card" style="border-top-color: #f59e0b;">
  <ul>
    <li><strong>1 - Tutoriel :</strong> Adressage IP</li>
  </ul>
</div>

---

## 3. Les étapes suivantes

<div class="sommaire-grid" style="grid-template-columns: 1fr; font-size: 0.8em;">
  <div class="sommaire-item"><div class="sommaire-num">2</div><div class="sommaire-text"> Organisation : Inscription des apprenants (À faire) </div></div>
  <div class="sommaire-item"><div class="sommaire-num">2</div><div class="sommaire-text"> Lab : Installation et Utilisation d'Ubuntu Linux (À faire) </div></div>
  <div class="sommaire-item"><div class="sommaire-num">2</div><div class="sommaire-text"> Lab : Configuration LAN et Interconnexion Réseau (À faire) </div></div>
  <div class="sommaire-item"><div class="sommaire-num">3</div><div class="sommaire-text"> Lab : Déploiement Laravel (À faire) </div></div>
</div>

---

## 3. Les étapes suivantes (Suite)

<div class="sommaire-grid" style="grid-template-columns: 1fr; font-size: 0.8em;">
  <div class="sommaire-item"><div class="sommaire-num">3</div><div class="sommaire-text"> Atelier : Installation Linux (À faire) </div></div>
  <div class="sommaire-item"><div class="sommaire-num">3</div><div class="sommaire-text"> Atelier : LAN (À faire) </div></div>
  <div class="sommaire-item"><div class="sommaire-num">10</div><div class="sommaire-text"> Live coding (Phase d'évaluation : N2-Adapter) </div></div>
  <div class="sommaire-item"><div class="sommaire-num">11</div><div class="sommaire-text"> Réalisation et présentation (Phase d'évaluation : N3-Transposer) </div></div>
</div>

---

## Liens et Ressources

<div class="dt-card">
  <p><strong>Tutoriel :</strong> Outils réseau</p>
  <p><strong>Code source :</strong> <a href="https://github.com/BenTaleb-Mehdi/Networks--Web-Deployment/blob/develop/LAN%20and%20equipements/presentation.md">GitHub dépôt</a></p>
</div>
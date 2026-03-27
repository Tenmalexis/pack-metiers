# pack-metiers[Pack-Métiers-Tool — README.html](https://github.com/user-attachments/files/26311979/Pack-Metiers-Tool.README.html)
<!DOCTYPE html>
<!-- saved from url=(0057)file:///C:/Users/adtg6/Downloads/README_pack_metiers.html -->
<html lang="fr"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pack-Métiers-Tool — README</title>
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    font-size: 16px;
    line-height: 1.5;
    color: #1f2328;
    background: #ffffff;
    max-width: 1012px;
    margin: 0 auto;
    padding: 32px 24px 64px;
  }

  /* ── Repo title bar ─────────────────────────────────── */
  .repo-title {
    font-size: 20px;
    font-weight: 600;
    color: #0969da;
    margin-bottom: 24px;
    padding-bottom: 16px;
    border-bottom: 1px solid #d0d7de;
  }

  /* ── Markdown body ──────────────────────────────────── */
  .markdown-body h1 {
    font-size: 2em;
    font-weight: 600;
    padding-bottom: .3em;
    border-bottom: 1px solid #d0d7de;
    margin-bottom: 16px;
    margin-top: 24px;
  }
  .markdown-body h2 {
    font-size: 1.5em;
    font-weight: 600;
    padding-bottom: .3em;
    border-bottom: 1px solid #d0d7de;
    margin-bottom: 16px;
    margin-top: 24px;
  }
  .markdown-body h3 {
    font-size: 1.25em;
    font-weight: 600;
    margin-bottom: 12px;
    margin-top: 24px;
  }

  .markdown-body p {
    margin-bottom: 16px;
  }

  .markdown-body ul {
    padding-left: 2em;
    margin-bottom: 16px;
  }
  .markdown-body ul li {
    margin-bottom: 6px;
  }

  .markdown-body a {
    color: #0969da;
    text-decoration: none;
  }
  .markdown-body a:hover {
    text-decoration: underline;
  }

  .markdown-body strong {
    font-weight: 600;
  }

  .markdown-body blockquote {
    padding: 0 1em;
    color: #636c76;
    border-left: .25em solid #d0d7de;
    margin-bottom: 16px;
  }

  /* Table */
  .markdown-body table {
    border-collapse: collapse;
    width: 100%;
    margin-bottom: 16px;
    display: block;
    overflow-x: auto;
  }
  .markdown-body th {
    background: #f6f8fa;
    font-weight: 600;
    padding: 6px 13px;
    border: 1px solid #d0d7de;
    text-align: left;
  }
  .markdown-body td {
    padding: 6px 13px;
    border: 1px solid #d0d7de;
  }
  .markdown-body tr:nth-child(even) td {
    background: #f6f8fa;
  }

  /* Code inline */
  .markdown-body code {
    padding: .2em .4em;
    margin: 0;
    font-size: 85%;
    white-space: break-spaces;
    background-color: #afb8c133;
    border-radius: 6px;
    font-family: ui-monospace, SFMono-Regular, "SF Mono", Menlo, Consolas, monospace;
  }

  /* hr */
  .markdown-body hr {
    border: none;
    border-top: 1px solid #d0d7de;
    margin: 24px 0;
  }
</style>
</head>
<body>

<div class="repo-title">🎒 Pack-Métiers-Tool</div>

<div class="markdown-body">

  <h1>🎒 Tenmalexis — Pack Métiers Tool</h1>

  <p><strong>Outil de calcul de rentabilité des Packs Métiers pour Dofus 3 (Unity)</strong></p>

  <blockquote>Créé par <a href="https://www.youtube.com/@Tenmalexis" target="_blank">@Tenmalexis</a> — YouTubeur Dofus</blockquote>

  <hr>

  <h2>🔗 Accès direct</h2>

  <p>👉 <a href="file:///C:/Users/adtg6/Downloads/pack_metiers_dofus.html" target="_blank">Ouvrir le Pack Métiers Tool</a></p>

  <hr>

  <h2>📌 C'est quoi ?</h2>

  <p>
    Cet outil permet de <strong>calculer le coût total en ressources HDV</strong> pour monter un Pack Métier Dofus de 0 à 200,
    et de le comparer au <strong>prix de vente sur le marché</strong> pour savoir instantanément si l'investissement est rentable.
    Tu renseignes les prix des ressources une fois, et l'outil calcule tout le reste automatiquement.
  </p>

  <hr>

  <h2>✅ Fonctionnalités</h2>

  <ul>
    <li>💰 <strong>Table des prix HDV</strong> — saisie centralisée des prix de toutes les ressources, regroupées par catégorie (Bois, Céréale, Divers, Minerai, Plante, Poisson, Viande)</li>
    <li>📋 <strong>Détail du Pack par tranche</strong> — recettes et ressources nécessaires niveau par niveau (0-10, 10-20… jusqu'à 200)</li>
    <li>🧮 <strong>Décomposition consolidée</strong> — quantité totale de chaque ressource, prix unitaire et coût total calculés automatiquement</li>
    <li>🪙 <strong>Récap multi-métiers</strong> — vue synthétique de tous les packs avec coût HDV, prix marché, différence et écart %</li>
    <li>⚡ <strong>Mise à jour en temps réel</strong> — les totaux se recalculent à chaque saisie sans perdre le focus du champ</li>
    <li>💾 <strong>Sauvegarde automatique</strong> — les prix sont conservés dans le navigateur (localStorage), aucune perte entre les sessions</li>
    <li>📤 <strong>Export JSON</strong> — exporte tous les prix dans un fichier horodaté pour les conserver ou les transférer</li>
    <li>📥 <strong>Import JSON</strong> — recharge un fichier exporté précédemment en un clic</li>
    <li>🖼️ <strong>Images des ressources</strong> — icônes chargées automatiquement depuis l'API Dofus</li>
  </ul>

  <hr>

  <h2>🎓 Les 6 métiers couverts</h2>

  <table>
    <thead>
      <tr>
        <th>Métier</th>
        <th>Ressource principale</th>
        <th>Tranches de niveau</th>
      </tr>
    </thead>
    <tbody>
      <tr><td>🧪 Alchimiste</td><td>Plantes</td><td>20 tranches de 10 niveaux (0 → 200)</td></tr>
      <tr><td>🪓 Bûcheron</td><td>Bois</td><td>10 tranches de 20 niveaux (0 → 200)</td></tr>
      <tr><td>🍖 Chasseur</td><td>Viandes</td><td>20 tranches de 10 niveaux (0 → 200)</td></tr>
      <tr><td>🌾 Paysan</td><td>Céréales</td><td>20 tranches de 10 niveaux (0 → 200)</td></tr>
      <tr><td>🎣 Pêcheur</td><td>Poissons</td><td>20 tranches de 10 niveaux (0 → 200)</td></tr>
      <tr><td>⛏️ Mineur</td><td>Minerais</td><td>10 tranches (0 → 200)</td></tr>
    </tbody>
  </table>

  <hr>

  <h2>🗺️ Navigation</h2>

  <p>L'outil est organisé en <strong>8 onglets</strong> :</p>

  <ul>
    <li><code>💰 Prix HDV</code> — point de départ : saisir les cours actuels de chaque ressource en K (milliers de kamas)</li>
    <li><code>Alchimiste / Bûcheron / Chasseur / Paysan / Pêcheur / Mineur</code> — détail du pack + décomposition pour chaque métier</li>
    <li><code>🪙 Récap</code> — tableau de bord comparant le coût HDV au prix de vente marché pour tous les métiers simultanément</li>
  </ul>

  <hr>

  <h2>💾 Gestion des prix</h2>

  <table>
    <thead>
      <tr><th>Action</th><th>Description</th></tr>
    </thead>
    <tbody>
      <tr><td>Auto-save</td><td>Les prix sont sauvegardés automatiquement dans le navigateur à chaque saisie</td></tr>
      <tr><td><code>📤 Export</code></td><td>Télécharge les prix au format <code>pack_metiers_prix_YYYY-MM-DD.json</code></td></tr>
      <tr><td><code>📥 Import</code></td><td>Recharge un fichier JSON exporté précédemment</td></tr>
      <tr><td><code>🗑️ Reset</code></td><td>Remet tous les prix à zéro (confirmation demandée)</td></tr>
    </tbody>
  </table>

  <hr>

  <h2>⚙️ Utilisation</h2>

  <p>Le fichier est un <strong>HTML standalone</strong> — il s'ouvre directement dans le navigateur, aucune installation requise.</p>

  <ul>
    <li>Les images des ressources sont chargées depuis <code>api.dofusdb.fr</code> — une connexion internet est nécessaire pour les afficher</li>
    <li>Les données sont basées sur <strong>Dofus 3.5 (mars 2026)</strong></li>
    <li>Compatible avec tous les navigateurs modernes (Chrome, Firefox, Edge, Safari)</li>
  </ul>

  <hr>

  <p><em>Outil créé par <strong>Tenmalexis</strong> — <a href="https://www.youtube.com/@Tenmalexis" target="_blank">YouTube</a> · <a href="https://www.twitch.tv/tenmalexis" target="_blank">Twitch</a></em></p>

</div>


</body></html>

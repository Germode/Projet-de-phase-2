
# Projet-de-phase-2 Bootcamp Data Science / Akademi
**Titre du projet :** Analyse exploratoire du box-office pour un nouveau studio de cinéma
<br/> Saint Germain Emode – Science de données + IA
<br/> **Sous-titre :**  Identifier les types de films les plus performants pour guider les décisions de production

!['Box Office'](https://github.com/Germode/Projet-de-phase-2/blob/main/Images/Box%20office.png)

# Aperçu: <br/>
Ce projet vise à identifier les types de films les plus performants au box-office afin de fournir des recommandations stratégiques pour un nouveau studio de cinéma. En utilisant des données provenant d’IMDB, Box Office Mojo et d’autres sources, nous appliquons une analyse exploratoire des données (EDA) pour découvrir les tendances et relations entre genres, budgets, durées et notes critiques des films.

L’objectif est de transformer ces insights en recommandations concrètes et exploitables, permettant au studio de décider quels films produire pour maximiser le succès commercial. Les visualisations générées rendent les conclusions facilement compréhensibles pour un public non-technique tout en restant rigoureuses pour un lecteur analytique.

# Contexte : <br/>
Votre entreprise souhaite se lancer dans la production de films, mais elle ne dispose pas encore d’informations sur le marché ni sur les facteurs qui déterminent le succès commercial. Ce projet a pour but d’analyser les tendances actuelles du box-office afin d’aider le studio à prendre des décisions éclairées sur les types de films à produire.

Grâce à l’exploration de données provenant de sources telles qu’IMDB et Box Office Mojo, cette analyse permet de comprendre quels genres, budgets, durées et caractéristiques des films sont associés aux meilleures performances au box-office. L’objectif final est de transformer ces insights en recommandations concrètes et stratégiques pour maximiser le retour sur investissement et le succès critique des futurs films.
![Top movies](https://github.com/Germode/Projet-de-phase-2/blob/main/Images/top%20movies.jpg)

# Compréhension des données:
<Ce projet s’appuie sur deux principaux ensembles de données qui combinent à la fois les caractéristiques des films et leurs performances financières. L’objectif est de les intégrer et de les analyser afin d’identifier les facteurs déterminants du succès au box-office et de guider les décisions stratégiques d’un nouveau studio de cinéma.

Le premier ensemble, IMDB (au format SQLite), contient des métadonnées détaillées sur les films, telles que les genres, la durée, les notes des utilisateurs et le nombre de votes. Ces informations sont cruciales pour comprendre les préférences du public et repérer les tendances qui favorisent la réussite des films.

Le second ensemble, « The Numbers » (format CSV), fournit des données financières liées à la production cinématographique, notamment les budgets, les recettes du week-end d’ouverture et le total brut national et international. Ces chiffres permettent d’évaluer la rentabilité et le retour sur investissement des films.

En combinant ces deux sources, le projet offre une analyse complète reliant la réception du public aux performances financières. Les données ont été soigneusement examinées, nettoyées et fusionnées afin d’assurer leur cohérence et leur fiabilité pour les analyses ultérieures.
# Données
Le projet s’appuie sur deux ensembles de données complémentaires :
1. Base de données IMDB (im.db, format SQLite)
Cette base contient des métadonnées détaillées sur les films, notamment :
- Titres et années de sortie
- Genres et durées
- Notes des utilisateurs et nombre de votes
Ces informations fournissent une perspective qualitative et permettent de comprendre la réception des films par le public.
2. Ensemble de données « The Numbers » sur les budgets des films (tm.movie_budgets.csv.gz)
Cet ensemble fournit des données financières essentielles, telles que :
- Budgets de production
- Recettes du week-end d’ouverture
- Chiffre d’affaires brut national et international
<br/> Ces données offrent une vision quantitative permettant d’évaluer la rentabilité et le succès commercial des films.
Les deux ensembles ont été soigneusement nettoyés et fusionnés afin d’assurer la cohérence, la fiabilité et la qualité des analyses qui en découlent.

## Analyse Exploratoire des Données (EDA) :
Nettoyage des données : gestion des doublons et des valeurs manquantes. <br/> Analyse des performances par genre et durée, en utilisant des méthodes statistiques et des visualisations. <br/> Visualisations : <br/>  Création de graphiques avec Matplotlib et Seaborn pour illustrer les résultats de manière intuitive.

# Box Office par Genre
Les films d’aventure et de documentaire sont les plus rentables, montrant une forte demande du public pour ces genres.
!['Box Office par Genre'](https://github.com/Germode/Projet-de-phase-2/blob/main/Images/t%C3%A9l%C3%A9chargement%20(11).png)

# Box Office sur la Durée des Films
Les films d'une durée de 140 à 150 minutes ont tendance à avoir de meilleures performances au box-office.

# Tendances du Box Office par Année
Une analyse des données annuelles montre que certaines années présentent des performances exceptionnelles au box-office, souvent liées à des sorties de films majeurs ou à des franchises populaires.

# Tendances entre le Succès des Films, leur Durée et leur Genre
Certaines combinaisons de genre et de durée (par exemple, les films d'aventure et d’action de 90 à 130 minutes) montrent un potentiel de succès accru.

# recommandations
Voici Quatre recommandations commerciales concrètes basées sur les analyses que je fais concernant le box-office, la durée des films, et les genres

1: Cibler les Productions selon les Genres les Plus Rentables : Utilisez les données de box-office pour identifier les genres de films les plus lucratifs. Par exemple, si les films d'action et de comédie génèrent les meilleurs revenus, concentrez-vous sur le développement de projets dans ces genres spécifiques.

2: Optimiser la Durée des Films pour Maximiser les Revenus : Analysez la relation entre la durée des films et leur performance au box-office. Si les films d'une certaine durée (par exemple, entre 120 et 140 minutes) rapportent plus, ajustez les scripts et la production pour respecter ces durées.

3: Adapter les Stratégies de Marketing et de Distribution : En analysant les tendances de succès des films Cibler une durée de 90 à 120 minutes pour les nouveaux projets afin d'attirer un maximum de spectateurs.Explorer davantage les combinaisons de genre et de durée qui maximisent le succès au box-office.

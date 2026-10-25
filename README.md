# Black Rainbow Cycling Crew

Site de l'association (V1) : révélation du maillot 2027.

- `index.html` : tout le site (compte à rebours, intro, soute à souvenirs, maillot 360°, formulaire « J'en veux un »).
- `soute.mp4` / `soute.webp` : fond animé de la soute.
- `jersey/` : 56 vues du maillot pour la rotation.
- Formulaire : les inscriptions arrivent dans Supabase, projet `black-rainbow`, table `interets`.

Pour ajouter la vidéo d'intro : déposer `intro.mp4` à la racine et renseigner `const INTRO_VIDEO = "intro.mp4";` dans `index.html`.

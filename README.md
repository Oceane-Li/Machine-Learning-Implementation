# Machine-Learning-Implementation

## 1. Introduction du dataset

Le dataset que nous avons étudié dans ce projet (**`student_lifestyle_dataset.csv`**) contient des informations détaillées sur les habitudes de vie quotidiennes de 2 000 étudiants et leur relation avec les performances académiques, représentées par le CGPA (*Cumulative Grade Point Average*). Les données de ce dataset ont été collectées à partir d'un sondage réalisé à l'aide de Google Forms, sur une période correspondant à une année académique, soit d'août 2023 à mai 2024. Les réponses proviennent principalement d'étudiants en Inde et d'autres pays d'Asie du Sud où le système CGPA est couramment utilisé. Les 2000 participants appartiennent à différentes institutions éducatives, ce qui garantit une diversité des contextes et des habitudes étudiantes.

### Contenu du dataset

Un nettoyage des données a déjà été effectué par l'auteur pour exclure les réponses incomplètes ou incohérences du sondage. L'objectif principal de ce sondage était d'étudier l'impact des habitudes quotidiennes (étude, sommeil, activités physiques, sociales, etc.) sur la performance académique et le bien-être étudiant.

Le fichier CSV est composé de 2000 lignes (étudiants) * 8 colonnes (variables) :

1. `Student_ID` : Identifiant unique pour chaque étudiant.

2. `Study_Hours` : Nombre d’heures quotidiennes consacrées à l'étude.

3. `Extracurricular_Hours_Per_Day` : Temps quotidien passé à des activités parascolaires (sports, arts, clubs, etc.).

4. `Sleep_Hours_Per_Day` : Nombre d’heures de sommeil par jour.

5. `Social_Hours_Per_Day` : Temps quotidien passé à socialiser (amis, famille, réseaux sociaux).

6. `Physical_Activity_Hours_Per_Day` :Nombre d’heures consacrées à l’activité physique (exercice, sport).

7. `GPA` : Performance académique sous forme de moyenne pondérée cumulative.

8. `Stress_Level` : Niveau de stress, calculé en fonction des heures d'étude et de sommeil. (Échelle ou score non précisé dans la description).

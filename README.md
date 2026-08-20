Pour ce projet, deux notebooks similaires ont été rédigés : un en R et l’autre en Python. Le notebook rédigé en R contient l'entièreté de nos analyses (Projet_ML_Gpe11_R.ipynb). Celui en Python contient le code ainsi que des analyses minimales.

Les données sont issues du site du concours KAGGLE; il s’agit du jeu de données " Gym Members Exercise Dataset" disponible ici : https://www.kaggle.com/datasets/valakhorasani/gym-members-exercise-dataset. Ce jeu de données fournit un aperçu détaillé des routines d’exercice, des attributs physiques et des mesures de la condition physique des membres d’une salle de sport. Il contient 15 variables observées chez 973 individus fréquentant une salle de sport :

Age : âge du membre de la salle de sport.
Gender : Sexe du membre de la salle de sport (qualitative à deux modalités : homme ou femme).
Weight..kg. : Poids du membre en kilogrammes.
Height..m. : Taille du membre en mètres.
Max_BPM : Fréquence cardiaque maximale (battements par minute) pendant les séances d’entraînement.
Avg_BPM : Fréquence cardiaque moyenne pendant les séances d’entraînement.
Resting_BPM : Fréquence cardiaque au repos avant l’entraînement.
Session_Duration..hours. : Durée de chaque séance d’entraînement en heures.
Calories_Burned : Total des calories brûlées au cours de chaque séance.
Workout_Type : Type d’entraînement effectué (qualitative à 4 modalités : cardio, musculation, yoga, HIIT).
Fat_Percentage (Pourcentage de graisse) : Pourcentage de graisse corporelle du membre.
Water_Intake..liters. : Consommation quotidienne d’eau pendant les séances d’entraînement.
Workout_Frequency..days.week. : Nombre de séances d’entraînement par semaine (qualitative à 4 modalités : 2 à 5).
Experience_Level : Niveau d’expérience (qualitative à 3 modalités : 1 pour débutant à 3 pour expert).
BMI : Indice de masse corporelle (IMC), calculé à partir de la taille et du poids.
Dans ce projet, on souhaite dans un premier temps, prédire la variable Calories_Burned à partir de toutes les autres variables, et dans un second temps, prédire la variable Experience_Level à partir de toutes les autres variables (dont Calories_Burned).

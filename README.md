# Comparaison avec les modèles précédents (RNN, LSTM)


| Caractéristique                                | Transformeurs                                 | RNN                                       | LSTM                                      |
|------------------------------------------------|-----------------------------------------------|-------------------------------------------|-------------------------------------------|
| **Architecture**                               | Basé sur des mécanismes d'attention           | Réseau de neurones récurrent              | RNN avec des cellules de mémoire          |
| **Parallélisme**                               | Oui (traitement parallèle des séquences)      | Non (traitement séquentiel)               | Non (traitement séquentiel)               |
| **Captation de contexte à longue distance**    | Très efficace (grâce à l'attention)           | Moins efficace                            | Efficace (grâce aux cellules de mémoire)  |
| **Complexité de calcul**                       | Moins efficace pour les séquences très longues | Efficace pour les séquences courtes       | Efficace pour les séquences moyennes      |
| **Performance**                                | State-of-the-art sur de nombreuses tâches NLP | Bon pour les tâches séquentielles simples | Bon pour les tâches séquentielles complexes |
| **Entraînement**                               | Nécessite plus de ressources (mémoire et calcul) | Moins coûteux                             | Coût modéré                               |
| **Applications typiques**                      | Traduction, génération de texte, résumé, etc. | Prévision de séries temporelles, génération de séquences simples | Prévision de séries temporelles complexes, génération de séquences plus complexes |
| **Gestion des dépendances à longue portée**    | Très bonne                                   | Faible                                    | Bonne                                     |
| **Besoin en mémoire**                          | Elevé (dépend de la longueur de la séquence)  | Moins élevé                               | Modéré                                    |


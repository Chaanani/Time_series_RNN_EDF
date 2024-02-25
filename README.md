L'objectif principal de notre projet était de développer des modèles prédictifs adaptés à l'analyse de séries temporelles, en l'occurrence, les données de consommation électrique d'un foyer. Notre démarche a débuté par une exploration approfondie de la série temporelle, examinant des caractéristiques clés telles que la stationnarité et la périodicité, à l'aide de tests de stationnarité et Fonction d'Autocorrélation (ACF).

Suite à cette analyse préliminaire, nous avons adopté une approche modélisatrice en implémentant plusieurs méthodes statistiques traditionnelles, notamment les modèles AutoRégressifs (AR), Moyenne Mobile (MA), ainsi que les modèles ARIMA et SARIMA, conçus spécifiquement pour capturer les dynamiques inhérentes à notre série temporelle.

Dans le but d'élargir notre spectre d'analyse, nous nous sommes tournés vers des techniques de deep learning, en particulier les réseaux de neurones récurrents (RNN), reconnus pour leur capacité à mémoriser des informations passées sur de longues périodes. Nous avons ainsi expérimenté avec trois architectures distinctes : RNN, LSTM (Long Short-Term Memory) et GRU (Gated Recurrent Unit), chacune offrant des avantages uniques pour la modélisation des séries temporelles.

La partie la plus importante de notre projet a été de tester tous nos modèles sur un ensemble de données pour voir lequel marchait le mieux. Nous avons utilisé des critères spécifiques pour évaluer chaque modèle. Cette dernière étape nous a aidés à trouver le meilleur algorithme pour prédire combien d'électricité un foyer va consommer.
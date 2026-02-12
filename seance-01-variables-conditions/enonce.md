# TP – Variables et Instructions Conditionnelles

## Objectif

Ce TP a pour objectif de renforcer la compréhension :

- des variables  
- des types fondamentaux (`int`, `float`, `str`, `bool`)  
- des structures conditionnelles (`if`, `elif`, `else`)  
- des opérateurs logiques (`and`, `or`, `not`)  
- de la logique décisionnelle appliquée  

Chaque exercice doit être réalisé dans un fichier Python séparé.

---

### 💡 La logique est plus importante que la longueur du code.

---

## Exercice 1 – Validation d’identifiant étudiant

Un identifiant étudiant doit :

- Avoir exactement 8 caractères  
- Commencer par `"GI"`  
- Se terminer par un chiffre  

Demander un identifiant à l’utilisateur et afficher :

- `"Identifiant valide"`  
- ou `"Identifiant invalide"`

---

## Exercice 2 – Catégorisation d’énergie électrique

On relève une consommation en kWh.

Règles :

- < 100 → Faible consommation  
- Entre 100 et 300 → Consommation moyenne  
- > 300 → Consommation élevée  

Si la consommation dépasse 500 kWh, afficher en plus :
- > Surconsommation détectée

---

## Exercice 3 – Système d’authentification intelligent

On définit :

```python
login_correct = "admin"
password_correct = "1234"
```

Le programme doit :

- Demander un login  
- Demander un mot de passe  
- Indiquer précisément si :  
  - le login est incorrect  
  - le mot de passe est incorrect  
  - les deux sont incorrects  
  - ou si l’accès est autorisé  

---

## Exercice 4 – Contrôle de température serveur

Demander la température d’un serveur (en °C).

Afficher :

- < 10 → Température trop basse  
- 10 à 40 → Température normale  
- 40 à 60 → Alerte  
- > 60 → Danger critique  

Si la température dépasse 80 °C, afficher également :
- > Arrêt automatique déclenché

---

## Exercice 5 – Éligibilité à une bourse

Conditions pour obtenir une bourse :

- Moyenne ≥ 75  
- Revenu familial < 50 000  
- Étudiant inscrit à temps plein (oui/non)  

Afficher :

- `"Bourse accordée"`  
- ou `"Non éligible"`  

Bonus : afficher les conditions non respectées.

---

## Exercice 6 – Année bissextile

Demander une année.

Rappel :  
Une année est bissextile si :  
- Elle est divisible par 4  
- sauf si elle est divisible par 100  
- sauf si elle est divisible par 400  

Afficher si l’année est bissextile ou non.

---

## Exercice 7 – Détection du type de triangle

Demander trois longueurs.

Le programme doit :

1. Vérifier si les longueurs peuvent former un triangle  
2. Si oui, déterminer s’il est :  
   - Équilatéral  
   - Isocèle  
   - Scalène  
3. Vérifier s’il est rectangle  

---

## Exercice 8 – Calcul d’abonnement Internet

Règles :

- Tarif de base : 2000 HTG  
- Si débit > 50 Mbps → +500 HTG  
- Si client entreprise → +1000 HTG  
- Si paiement annuel → -10%  

Calculer et afficher le montant final à payer.

---

## Exercice 9 – Système de sécurité

Demander :

- L’heure (entre 0 et 23)  
- Mouvement détecté ? (oui/non)  

Si :  
- l’heure est entre 22 et 5  
- et un mouvement est détecté  

Afficher :

```
Alerte intrusion
```

Sinon afficher :

```
Situation normale
```

---

## Exercice 10 – Évaluation de performance employé

Demander :

- Productivité (0–100)  
- Nombre de retards  

Règles :

- Productivité ≥ 85 et retards ≤ 2 → Excellent  
- Productivité ≥ 70 → Bon  
- Productivité ≥ 50 → Moyen  
- sinon → Insuffisant  

Si retards > 10, afficher un message d’avertissement supplémentaire.

---

# Test API ARVEA - Postman  (Phase 3)
**Candidature QA Engineer - Wassila Boukthir**  

## 📌 Scénario de test  
**Objectif** : Vérifier le comportement de l'endpoint `/stock/getQuantity`  

### Cas testés  

1. **Requête standard**
   
   GET https://recrutement.arvea-test.ovh/stock/getQuantity?product_config_id=101&stock_type=depot&depot_id=2
   
Assertions :

Code HTTP 200 (404 reçu dans ce cas fictif)

Format JSON valide

**Analyse de la réponse**

{

  "status": 404,
  
  "message": "Endpoint not found"
  
}

## 🛠️ Installation et exécution:

## Exportation depuis Postman:
1. Ouvrir la collection "TestAPI"

2. Cliquer sur ... → Export

3. Choisir le format Collection v2.1

4. Sauvegarder dans postman/

## Commandes Git:

# 1.Configuration initiale
   
1. cd chemin/vers/Test-API-ARVEANature

2. git init

3. git remote add origin https://github.com/WassilaBoukthir/Test-API-ARVEANature.git

# 2.Mise à jour

    git add postman/ARVEA_Stock_API_Tests.postman_collection.json README.md
    git commit -m "Ajout des tests API Postman pour le test technique"
    git push -u origin main
   
# 3.📊 Résultats attendus:

Collection importable et exécutable dans Postman

Validation des assertions malgré le comportement fictif

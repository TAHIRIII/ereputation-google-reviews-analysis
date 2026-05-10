# E-Reputation Analysis - Le Troquet Bar

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-Sentiment_Analysis-orange?style=flat)
![Reviews](https://img.shields.io/badge/Google_Reviews-446-brightgreen?style=flat)
![Rating](https://img.shields.io/badge/Rating-4.4%2F5-yellow?style=flat)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## Presentation

In-depth e-reputation study of **Le Troquet Bar** (18th arrondissement, Paris). The goal was to give the owner a clear view of their online image to define strategic marketing actions for post-COVID reopening.

## Objectives

- Market analysis: Parisian restaurant sector trends
- - Visibility audit: Google Business performance (35,000+ views)
  - - Sentiment analysis: 446 customer reviews extracted and analyzed
   
    - ## Methodology
   
    - 1. Web Scraping with BeautifulSoup and Selenium
      2. 2. Structured dataframe: username, stars, date, review text
         3. 3. NLP: Word Clouds + positive vs negative classification
           
            4. ## Key Results
           
            5. - Rating: 4.4/5 with 83% positive reviews (4-5 stars)
               - - Top keywords: nice, very good, great, friendly, excellent service
                 - - 35,000+ Google Business views, strong mobile engagement
                   - - Negative reviews: only 5% of total, mostly over 2 years old
                    
                     - ## Structure
                    
                     - - notebooks/ - Scraping and NLP Jupyter notebooks
                       - - data/ - Google Maps reviews (newest_gm_reviews.csv)
                         - - visualizations/ - Word clouds and rating charts
                           - - report/ - Final strategic analysis presentation
                            
                             - ## Tools
                            
                             - Python - BeautifulSoup - Selenium - Pandas - NLTK - WordCloud - Matplotlib
                            
                             - ## Author
                            
                             - **Houssain TAHIRI** - Data Analyst
                             - https://www.linkedin.com/in/houssain-tahiri-246b00100/


---

## Rapport d'Analyse Detaille

### 1. Introduction et Cadrage

Audit de l'image de marque numerique pour **Le Troquet Bar** et **L'Annexe du Troquet** (36-38 rue de Clignancourt, Paris 18eme). Ces deux entites operent sous la societe mere "AU PETIT MIGNON" : le Troquet Bar se concentre sur le debit de boissons tandis que l'Annexe assure la restauration.

**Objectif** : Fournir une cartographie precise de la perception client en ligne et definir des leviers marketing pour optimiser la reouverture post-crise sanitaire.

**Limites** : Suite a la perte des identifiants Facebook/Instagram, l'analyse s'est concentree sur l'ecosysteme Google (Search et Maps). Les donnees ont ete collectees via web scraping, permettant une analyse semantique exhaustive que les API standards ne permettent pas.

---

### 2. Marche de la Restauration

- **National (2018)** : Marche RHF a 76.2 milliards EUR HT. Restauration independante dominante (48.9 mds EUR)
- - **Paris** : 14 363 etablissements (CCI Paris-Ile-de-France)
 
  - | Type d'etablissement | Nombre | Part |
  - |---|---|---|
  - | Restauration traditionnelle | 6 090 | 42% |
  - | Restauration rapide | 3 266 | 23% |
  - | Brasseries / Restauration continue | 3 009 | 21% |
  - | Bar - Cafe - Debit de boissons | 1 998 | 14% |
 
  - - **18eme arrondissement** : 1 055 etablissements, taux de stabilite de seulement **61%** (vs 79% pour le 7eme). La e-reputation est un rempart concurrentiel indispensable.
   
    - ---

    ### 3. Impact de la Crise Sanitaire

    - Chute d'activite de **-71%** entre mars et mai 2020
    - - Besoin de financement median de **60 jours de CA**
      - - 3 freins a la reprise (YouGov) : manque de temps, peur du virus, baisse du pouvoir d'achat
       
        - ---

        ### 4. Comportement Consommateur Post-Crise

        - La restauration est le **1er secteur** concerne par la consultation d'avis en ligne
        - - **66%** d'avis positifs nationalement vs 19% negatifs
          - - **39%** des avis sont deposes suite a une **sollicitation par email** : levier de croissance majeur
           
            - ---

            ### 5. Performance Quantitative

            | Indicateur | Valeur |
            |---|---|
            | Note moyenne | **4.4 / 5** |
            | Volume d'avis | 429 |
            | Avis 5 etoiles | 59% |
            | Avis 4 etoiles | 24% |
            | Avis negatifs (1-3 etoiles) | 5% |
            | Vues de la fiche Google | 35 220 |
            | Actions directes (appels, itineraires) | 1 077 |

            **SEO Local** :
            - "Troquet" : 1 773 requetes/mois
            - - "Le Troquet" : 1 041 requetes/mois
              - - "Le Troquet Bar" : 394 requetes/mois
               
                - ---

                ### 6. Analyse Qualitative (NLP)

                - **Terrasse (35m2)** : mot-cle le plus saillant, argument de vente principal
                - - **Multi-moments** : "Cafe le matin", "Planches", "Cocktails", "Burgers" - amplitude 7h-02h
                  - - **Ambiance et accueil** : facteur de differenciation systematiquement cite
                   
                    - ---

                    ### 7. Recommandations Strategiques

                    1. **Recuperer l'ecosysteme Social Media** : Les acces Facebook/Instagram perdus constituent une faille strategique urgente
                    2. 2. **Optimisation SEO local** : Uniformiser "Le Troquet Bar & L'Annexe" sur tous les annuaires
                       3. 3. **Marketing direct** : Mettre en place un QR code en caisse pour solliciter les avis (levier des 39%)
                          4. 4. **Reponse aux avis negatifs** : Utiliser GMB comme canal de dialogue public pour rassurer les prospects
                             5. 5. **Valoriser la terrasse** : Fer de lance de la communication de reouverture (securite sanitaire + convivialite)

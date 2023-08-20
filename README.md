# DecisionTree
## Théorie et intuition : bases des arbres de décision
<img width="518" alt="image" src="https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/9048b434-6231-4a43-a04e-ac31b827d37c">

### -  Vocabulaire : 
### Division (splitting)  = action de faire renter les données dans un noeud et séparer ou diviser ces données en fonction de la condition s'elle est vraie ou fausse.
<img width="356" alt="image" src="https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/f7adedd5-ca09-41aa-9d76-95518949de64">.

<img width="365" alt="image" src="https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/d39a6a15-be0b-4472-882b-a88ecc592929">

<img width="346" alt="image" src="https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/c808a9e6-f93f-44d9-8b09-26210ed0b931">.
### Le noeud racine = sommet de l'arbre = première condition ou feature surlaquelle on effectue une division

<img width="464" alt="image" src="https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/4b6980ea-1a45-4031-b29c-68ed9c59b267">.

### Ils n'ont aucune données qui sortent = les données ne sont plus séparées quand on atteint un noeud terminal. Le résulat en sortie est pris au niveau du noeud terminal

<img width="384" alt="image" src="https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/01f2cb11-04cc-41ca-870d-8c6e396d3537">.
### En théorie, je peux décider de faire un arbre plus petit, plus court. Dans cette exemple, c'est de décider de ne pas faire de division après ce coeud et d'en faire un noeud terminal.

<img width="291" alt="image" src="https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/6e6a48d0-226f-4028-99d2-84b2b4726025">.
### Idée derrière l'élagage est d'éviter le surapprentissage

### - Impureté de Gini
### ● Impureté de Gini = mesure mathématique de la "pureté" de l'information dans un ensemble de données.
### ● Cas de la classification : cela peut être considéré comme la mesure de l'uniformité des classes.
### ● Etude du cas le plus simple de 2 classes...

![image](https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/06a541b5-9c05-4433-8713-0801e2455615)

![image](https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/3fd5ff05-53a3-48db-a32f-3c430c872afd).

![image](https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/b3aaca31-35f1-49bb-be48-dfb4410d17f2).


![image](https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/2b3111f0-8096-43dc-af63-47266be1538e).


![image](https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/e940fc53-d56f-4338-924f-e4ea9d5a14c5).

![image](https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/da817ca4-95df-4c49-826d-3cade48b4810).
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
![image](https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/602d2ebd-6268-4b62-ab0d-d8f7d22d7bc4).

### Etude de cas simples : 
### - 1 feature, créons un arbre de décision pour voir si un email est un spam ou non.
### Il n'y a qu'une seule feature à utiliser pour un noeud et celle-ci n'a que 2 valeurs potentielles : yes ou no
### Division sur cette feature, on aura 2 possibilités une qui divise sur le yes et une autre qui divise sur le no (question = est-ce que l'email contient une URL vrai ou faux)
![image](https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/cbdd0f9f-c1b5-4d13-a36b-7fd98dfbb783)
![image](https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/87d2ada4-5bf8-4ca4-bac6-c85bab9f1283)

![image](https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/10395092-8428-4def-9c53-24999ab0a50b)

![image](https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/5c3dcfe4-4258-4e9f-aab8-cbd6226f1812).
![image](https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/e964cfb2-2f00-4857-9b29-3ecdbf2701e5)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### -   Autres cas : ### ● feautures continues
                    ### ● features multi-catégorielles (N>2)
                    ### ● choix feature pour le noeud racine.
  ### ● feature continue : nombre de mot dans le mail
![image](https://github.com/Brahim-AIT-OUALI/DecisionTree/assets/115220907/a502ab75-3a14-4ccc-8355-91f74d05c4c8)












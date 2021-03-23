# Le-juste-nombres
import random

nombre_aléatoire = random.randint(0,9)

def jeu():
  
  for i in range(5):
       nombre = int('entrez votre nombre')
     
         if nombre == nombre_aléatoire:
             print('vous avez gagné !')

         if nombre > nombre_aléatoire :
             print('votre nombre est trop grand')


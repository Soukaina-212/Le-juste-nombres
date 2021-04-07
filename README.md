# Le-juste-nombres
import random

nombre_aléatoire = random.randint(0,9)

def jeu():
  
  for i in range(4):
  
       nombre= int(input('entrez votre nombre')
     
         if nombre == nombre_aléatoire:
             print('vous avez gagné !')

         if nombre > nombre_aléatoire :
             print('votre nombre est trop grand')
        
          if nombre < nombre_aléatoire :
             print('votre nombre est trop petite')
  
         if nombre != nombre_aléatoire:
             print('vous avez perdu')

jeu()


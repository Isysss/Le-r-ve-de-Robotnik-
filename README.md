# Le-r-ve-de-Robotnik-
import os
import pygame
from pygame.locals import *
def chemin(fichier):
    return os.path.join('Image', fichier)

fenetre = pygame.display.set_mode((640,480))
fenetre_rect = pygame.Rect((0, 0), (640, 480))
pygame.display.set_caption("sonic")
fond = pygame.image.load(chemin("fond.pnj"))
pygame.quit()

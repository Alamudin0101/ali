
import pygame

# Initialize Pygame
pygame.init()

# Create screen
screen = pygame.display.set_mode((800, 600))

# Game loop
running = True
while running:
for event in pygame.event.get():
    if event.type == pygame.QUIT:
        running = False

# fill screen with color
screen.fill((255, 255, 255))

# Draw shapes
pygame.draw.rect(screen, (255, 0, 0), pygame.Rect(30, 30, 60, 60))

# Update screen
pygame.display.flip()

# Quit Pygame
#pygame.quit()
#```
#This creates a red square on a white screen, and quits Pygame when the user clicks the window's close button. You can build on this basic structure to create more complex games.

#Created by https://GPTGO.ai

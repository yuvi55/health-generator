# health-generator
import random

health = 50

difficulty = 1

health_potion = random.randint(25,50)

health= health + int( health_potion/difficulty)

print(health)



# Go Go Gadget Snake

An ai for battlesnake to help me learn go.

Based off of the go starter snake: https://github.com/BattlesnakeOfficial/starter-snake-go

Strategy:

- Eat agressively until length of 8

- Follow tail while health is over 50

- When health is under 50, get nearest food that has a valid path head -> food -> tail

- If no food matches that criteria, follow tail

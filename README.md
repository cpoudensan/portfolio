# My Projects

This repository is a central hub for all my personal and team-based learning projects.
Each project is developed in its own GitHub repository and is listed here to provide
a clear and organized overview of my work.

---

## Projects

### Client–Server Application – Shortest Path Calculation (Go)
A client–server application written in Go that computes the shortest path and minimum
distance between two cities.  
The server implements Dijkstra’s algorithm on a weighted graph representing cities
and distances, while the client sends textual route requests and receives the optimal
path and distance.  
The server supports multiple concurrent clients using goroutines.

🔗 Repository: https://github.com/cpoudensan/go_project

---

### Multi-Process Ecosystem Simulation (Python)
A multi-process simulation of a simple ecosystem composed of predators, preys, and grass.  
Each predator and prey is represented by an independent process with energy-based
behavior such as feeding, reproduction, and death.  
The environment process manages shared state and climate events (e.g. droughts),
while a display process allows real-time observation and control using shared memory,
message queues, and Unix signals.

🔗 Repository: https://github.com/cpoudensan/PPC

---

### Card Game Implementation – Flip 7 (JavaScript)
A JavaScript implementation of the card game *Flip 7*.  
The project focuses on game logic, user interaction, and turn-based mechanics,
allowing players to flip cards, take risks, and score points according to the
rules of the game.

🔗 Repository: https://github.com/cpoudensan/JS

---

### Word Guessing Web Game – Guess It! (Elm)
A web application developed in Elm where the user must guess a word based on its
dictionary definitions.  
The word is randomly selected from a list of common words extracted from a book,
and its definitions are fetched via a dictionary API.

On page load, the application downloads the word list, selects a random word,
and retrieves its definitions through HTTP requests.  
The user reads definitions grouped by grammatical categories, enters guesses,
receives “cold / warm / hot” feedback based on proximity to the target word,
can reveal the word at any time, and start a new game.

🔗 Repository: https://github.com/cpoudensan/elm


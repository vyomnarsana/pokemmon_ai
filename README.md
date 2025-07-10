python main.py -h

usage: main.py [-h] [--ai AI] [--depth DEPTH] [--s S]

Pokémon combat system (1st gen) re-implementation using MiniMax-type algorithms.                                            
Author: nebuchadneZZar01 (Michele Ferro)                                            
GitHub: https://github.com/nebuchadneZZar01/PokeMMon                                            
All credits of the material used (characters, sounds, images and ideas) belong to The Pokémon Company, Nintendo, Game Freak and Creatures Inc.

options:
  -h, --help     show this help message and exit
  --ai AI        artificial intelligence algorithm used
                 [random/minimax/alphabeta/expectimax] (default: minimax)
  --depth DEPTH  maximum depth of the nodes to visit in game's tree (default: 7)
  --s S          sound [Y/n] (default: yes)

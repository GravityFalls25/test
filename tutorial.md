# L'Agent Fermier 🌾

Bienvenue ! Dans ce tutoriel, tu vas apprendre à utiliser ton agent pour labourer et semer un champ.

## Étape 1 : Préparer l'agent

Téléporte l'agent à ta position et donne-lui des carottes.

```blocks
agent.teleport(player.position(), EAST)
agent.setItem(CARROTS, 64, 1)
for (let index = 0; index < 5; index++) {
    agent.till(FORWARD)
    agent.place(FORWARD)
    agent.move(FORWARD, 1)
}

```

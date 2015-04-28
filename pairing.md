# Pairing with tmux and vim
## Realtime Tools<br/>for Remote Teams
### Scott Baldwin, WellMatch
#### @scottsbaldwin

---

## My Team is Remote

![left filtered](img/wellmatch_engineers.png)

- HipChat
- Skype or Google Hangouts
- Remote EC2 instance
- lita
- tmux
- vim

---

## First, I need a place to work!

Using ChatOps, create a sandbox in AWS:

```
data pair me
data pair add scottsbaldwin to quivering-cactus-4911
data pair add <another user> to quivering-cactus-4911
data pair stop quivering-cactus-4911
data pair start quivering-cactus-4911
```

Now I have a place to work.

```
ssh scottsbaldwin@quivering-cactus-4911
sudo su devuser
tmux new -s 
```

---

## The Gondola


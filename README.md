<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSm1Z7752bOKmBssX_FeVMtjmgG9ghBpxjfvA9DsNsGkQ&s=10" alt="UniCesumar" width="360">
</p>

<h1 align="center">RPG Game UniCesumar 2D</h1>
<p align="center"><em>Material de aula — combate top-down, inimigo e zonas de combate</em></p>

---

## Para que serve este repositório?

Projeto **RPG 2D top-down** com foco em combate e IA simples de inimigo:

- Player: movimento, animação e ataque (Espaço)  
- Inimigo: patrulha entre waypoints A/B, ataque ao colidir com Player, morte na `CombatZone`  
- Cenas: `Gameplay` e `Game Over`

## Tecnologias

| Item | Detalhe |
|------|---------|
| Engine | **Unity 2022.3.16f1** (LTS) |
| Linguagem | C# |
| Física | Rigidbody2D, Collider2D, Triggers |

## Estrutura principal

```
Assets/
├── Scripts/
│   ├── PlayerController.cs
│   └── EnemyController.cs
└── Scenes/
    ├── Gameplay.unity
    └── Game Over.unity
```

## Como abrir (aluno)

1. Unity **2022.3.16f1**  
2. Clone:
   ```bash
   git clone https://github.com/UniCesumarGames/rpg_game_unicesumar_2d.git
   ```
3. Abra `Assets/Scenes/Gameplay.unity` → **Play**

## Controles

| Ação | Controle |
|------|----------|
| Mover | WASD / setas (eixos Horizontal/Vertical) |
| Atacar | Espaço |

## O que estudar neste projeto

- Tags: `Player`, `CombatZone`  
- Diferença entre `OnCollisionEnter2D` e `OnTriggerEnter2D`  
- Patrulha com `waypointA` / `waypointB` e troca de `localScale` (flip)

---

<p align="center">UniCesumar — Jogos Digitais / Desenvolvimento de Games</p>

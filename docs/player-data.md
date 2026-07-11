# Player Data

Player Data stores the default information for a player character. Using ScriptableObjects allows multiple game systems to share the same data asset while keeping gameplay logic separate.

## Typical Properties

- Player Name
- Health
- Maximum Health
- Level
- Experience
- Coins
- Movement Speed
- Attack Damage

## Why Use ScriptableObjects?

ScriptableObjects make player data reusable and easy to edit without changing code.

### Advantages

- Cleaner project architecture
- Centralized data management
- Easy balancing by designers
- Reusable across multiple scenes
- Better maintainability

## Example Structure

```text
PlayerData
├── Player Name
├── Health
├── Max Health
├── Level
├── Experience
├── Coins
├── Speed
└── Damage
```

## Common Use Cases

- RPG games
- Platformer games
- Action games
- Mobile games

## Best Practices

- Store only default values in ScriptableObjects.
- Keep runtime values in separate classes or managers.
- Organize assets into folders such as `Assets/Data/Player`.

## Common Mistakes

- Modifying ScriptableObject assets during gameplay.
- Storing temporary runtime data directly in the asset.
- Mixing gameplay logic with data definitions.

## Summary

Player Data ScriptableObjects provide a clean and scalable way to manage default player settings while keeping Unity projects organized.

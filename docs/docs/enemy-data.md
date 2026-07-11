# Enemy Data

Enemy Data defines the default attributes and behavior settings for enemies in a Unity game. Using ScriptableObjects keeps enemy configuration separate from gameplay code.

## Typical Properties

- Enemy Name
- Health
- Attack Damage
- Movement Speed
- Attack Range
- Detection Radius
- Experience Reward
- Coin Reward

## Why Use ScriptableObjects?

Using ScriptableObjects allows designers to create multiple enemy types without modifying scripts.

### Benefits

- Reusable enemy configurations
- Easy game balancing
- Cleaner architecture
- Faster content creation
- Supports multiple enemy variations

## Example Structure

```text
EnemyData
├── Enemy Name
├── Health
├── Damage
├── Speed
├── Attack Range
├── Detection Radius
├── XP Reward
└── Coin Reward
```

## Common Use Cases

- RPG games
- Tower Defense
- Survival games
- Shooter games
- Adventure games

## Best Practices

- Keep only default values inside the ScriptableObject.
- Create separate assets for each enemy type.
- Use inheritance only when necessary.

## Common Mistakes

- Editing asset values during runtime.
- Storing AI logic inside the ScriptableObject.
- Creating duplicate enemy assets with identical data.

## Summary

Enemy Data ScriptableObjects simplify enemy management and improve project organization by keeping configuration data independent from gameplay logic.

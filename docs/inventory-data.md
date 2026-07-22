# InventoryData ScriptableObject

InventoryData is a ScriptableObject used to organize and manage game inventory settings.

## Properties

- Maximum Inventory Size
- Starting Items
- Item Categories
- Stack Limit
- Default Currency

## Advantages

- Easy configuration in the Unity Inspector
- Reusable across multiple scenes
- Keeps inventory data separate from game logic
- Reduces hardcoded values

## Common Use Cases

- RPG Games
- Survival Games
- Adventure Games
- Crafting Systems
- Mobile Games

## Best Practices

- Keep inventory settings in ScriptableObjects.
- Separate inventory logic from UI.
- Use IDs instead of object references for saved data.
- Validate inventory size before adding new items.

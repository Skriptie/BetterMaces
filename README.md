# BetterMaces
**BetterMaces** is a custom Minecraft plugin built for Paper 1.21.4 and above. It introduces a unique crafting ritual for the new 1.21 mace, limiting its creation to one active mace at a time per server and adding immersive mechanics around visibility, pickup delays, and risk of destruction.

---

## 🔮 Features

- 🌟 **Mace Ritual Crafting**:
  - Only one mace can exist at a time.
  - Players initiate a 30-minute ritual using `/craftmace`.
  - Mace hovers above the ritual location during the ritual.
  - Visible to all players with coordinates shown in chat and via bossbar.
  - Cannot be picked up until the ritual completes.

- ⚔️ **Death Mechanics**:
  - If the player carrying the mace dies before the ritual completes, the mace is **destroyed**.
  - Message: `*Mace has been broken. Now anyone can get the mace by doing the ritual. Start the ritual by /craftmace*`

- 🎮 **Visibility & UI**:
  - Boss bar countdown for all players.
  - Chat message timer with ritual coordinates.

- 📜 **Mace Restrictions**:
  - Cannot be enchanted or cursed (no Curse of Binding or other enchantments).
  - Only re-craftable if the previous one is destroyed.

- 👋 **Custom Join Message** (only shown to the joining player):




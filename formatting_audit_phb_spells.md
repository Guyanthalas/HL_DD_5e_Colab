# PHB Spells Description Formatting Audit

Using **Phantasmal Force** in `COM_5ePack_PHB - Spells.user` as a formatting reference, the following descriptions are inconsistent and should be updated:

- Animal Friendship — leading space at the start of the `description` value.
- Blinding Smite — double space in prose (`a  Constitution`).
- Cordon of Arrows — unformatted `At Higher Levels.` heading (should use `{b}{i}At Higher Levels.{/i}{/b}`).
- Witch Bolt — unformatted `At Higher Levels.` heading (should use `{b}{i}At Higher Levels.{/i}{/b}`).
- Mage’s Private Sanctum — unformatted `At Higher Levels.` heading (should use `{b}{i}At Higher Levels.{/i}{/b}`).
- Allow Any Creature — double space in prose (`DM's  permission`).
- Find Steed — paragraph breaks use `{br}` inline tags instead of `\n\n` paragraph formatting used in the reference.

## Readability recommendation

For readability, **use explicit paragraph breaks between logical sections** (e.g., effect, ongoing behavior, save/check interaction, and At Higher Levels). In this file format, the clearest and most consistent style is:

- Separate paragraphs with `\n\n`.
- Keep "At Higher Levels." visually distinct with `{b}{i}At Higher Levels.{/i}{/b}`.
- Avoid dense single-block descriptions for multi-step spells.

This makes long spell text easier to scan and aligns with the `Phantasmal Force` pattern already used in the pack.

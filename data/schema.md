# Database Schema

File defines fields needed for the database.

| Field | Type | Description |
| --- | --- | --- |
| `id` | String or Integer | Unique identifier for each Hanja entry. |
| `hanja_character` | String | The Hanja character. |
| `korean_reading` | String | The Korean reading of the Hanja character. |
| `english_meaning` | String | The English meaning of the character. |
| `tier_difficulty` | String | The tier or difficulty level assigned to the character. |
| `combat_class` | String | The type or element classification for the character. |
| `mastery_level` | String or Integer | The learner’s current mastery level for the character. |

## Fields

### `id`
A unique ID for each database record.

### `hanja_character`
The Hanja character being studied.

### `korean_reading`
The Korean pronunciation or reading of the Hanja character.

### `english_meaning`
The English definition or meaning of the Hanja character.

### `tier_difficulty`
The assigned tier or difficulty level, which are classified from a range of F to S, F being the easiest, and S being the most difficult to beat.

### `combat_class`
The character’s combat classification. The designations are: magic (attacks using supernatural skills), tank (absorbs damage), DPS (deals high damage), support (heals, buffs, debuffs), and stealth (critical hits).

### `mastery_level`
The user’s current progress based on the number of characters they learn. The user earns one level up each character that they beat and add to their roster.
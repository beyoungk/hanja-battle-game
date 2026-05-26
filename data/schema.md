# Database Schema

File defines fields needed for the database.

| Field | Type | Description |
| --- | --- | --- |
| `id` | String or Integer | Unique identifier for each Hanja entry. |
| `hanja_character` | String | The Hanja character. |
| `korean_reading` | String | The Korean reading of the Hanja character. |
| `english_meaning` | String | The English meaning of the character. |
| `tier_difficulty` | String or Integer | The tier or difficulty level assigned to the character. |
| `type_element` | String | The type or element classification for the character. |
| `skill_category` | String | The learning skill category this character belongs to. |
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
The assigned tier or difficulty level.

### `type_element`
The character’s type, element, or classification.

### `skill_category`
The learning category connected to the character.

### `mastery_level`
The user’s current progress or mastery level for the character.
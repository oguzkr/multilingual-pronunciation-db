# Multilingual Pronunciation Database

This repository contains a comprehensive multilingual translation and pronunciation database with example sentences and romanization support for 19 different languages.

## Structure

```
data/
├── categories/
│   ├── greetings.json       # Greetings and basic expressions
│   ├── gratitude.json       # Thank you and related expressions
│   ├── directions.json      # Directions and location expressions
│   ├── restaurant.json      # Restaurant and food related words
│   ├── shopping.json        # Shopping related expressions
│   ├── travel.json         # Travel related words
│   ├── time.json           # Time expressions
│   ├── emotions.json       # Emotions and feelings
│   ├── emergency.json      # Emergency related words
│   └── daily.json          # Daily use expressions
├── languages.json          # Supported languages configuration
└── schema.json            # JSON Schema for validation
```

## Supported Languages

1. Turkish (tr)
2. English (en)
3. Spanish (es)
4. Indonesian (id)
5. French (fr)
6. Italian (it)
7. Portuguese (pt)
8. Chinese (zh)
9. Russian (ru)
10. Japanese (ja)
11. Hindi (hi)
12. Filipino (fil)
13. Thai (th)
14. Korean (ko)
15. Dutch (nl)
16. Swedish (sv)
17. Polish (pl)
18. Greek (el)
19. German (de)

## Data Format

Each word entry contains:
- Translations in all supported languages
- Example sentences
- Pronunciations (adapted for speakers of each language)
- Romanization (for non-Latin script languages)
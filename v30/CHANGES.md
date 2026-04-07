# v30 - International Edition (PL/EN)

## Changes from v29

### New features
- **PL/EN language toggle** in the topbar (flag next to theme toggle)
- **Full EN translation** - all UI elements, prompts, encyclopedia
- **localStorage `acV30_lang`** - remembers selected language
- **Default language: EN** (for global GitHub audience)

### Translated elements
| Element | Count | Status |
|---------|-------|--------|
| Agent prompts | 28 | Translated |
| Agent encyclopedia (AGENT_KNOWLEDGE) | 28 | Translated |
| Preset encyclopedia (PRESET_KNOWLEDGE) | 29 | Translated |
| Agent names and descriptions | 28 | Translated |
| Preset names and descriptions | 29 | Translated |
| Speech bubbles (AGENT_SPEECH) | 28 | Translated |
| UI (buttons, tooltips, labels) | ~150 strings | Translated |
| Glossary | 11 terms | Translated |
| HITL gates | 3 gates | Translated |
| Agent/preset categories | 12 | Translated |
| Final Prompt generator | ~15 strings | Translated |
| Hero overlay | 3 strings | Translated |

### i18n architecture
- `I18N` object with `pl` and `en` keys contains all translations
- `getLang()` function returns the current language
- `switchLang(lang)` function switches language and reloads UI
- Rendering functions use getters: `t(key)`, `getAgentName(id)`, `getPrompt(id)`, etc.
- Existing PL data preserved as default, EN added as a layer

### Estimated size
- v29: ~3531 lines
- v30: ~5500-6000 lines (+2000 lines of translations)

### localStorage
- Config key: `acV30` (changed from acV29)
- Theme key: `acV30_theme`
- Language key: `acV30_lang`

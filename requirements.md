# Requirements.md – Mood Meals

## Functional Requirements

### What problem does this solve?
- Reduces the mental load of deciding what to eat
- Simplifies food decisions by connecting emotions to meals

### Must-have functionality:
- User selects a mood
- User optionally enters ingredients they have
- App uses OpenAI to suggest 2–3 recipes
- User can save meals to favorites
- User can view saved meals

## Out of Scope for MVP
- No sign-in/authentication
- No image generation
- No offline mode
- No calendar tracking or meal history

## Non-Functional Requirements

| Requirement     | Value                                          |
|----------------|------------------------------------------------|
| Speed           | Moderate (GPT API may introduce slight delay) |
| Offline support | Not required                                   |
| Platform        | Android 8.0 (API 26) and up                    |
| Architecture    | Modern (MVVM, Jetpack Compose, ViewModel)     |
| Storage         | Local only (SharedPreferences)                |
| Security        | API key stored in `local.properties`          |

## Summary

Mood Meals should be minimal, modern, and focused.  
The goal is to build a clean, well-scoped MVP that is functional and presentable within 7 days.

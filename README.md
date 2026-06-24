# Sneaky AI — wydania

To repozytorium hostuje automatyczne aktualizacje aplikacji **Sneaky AI**,
dystrybuowane przez framework [Sparkle](https://sparkle-project.org).

Każde wydanie (Release) zawiera dwa assety:

- `Sneaky-<wersja>.zip` — podpisana (Developer ID) i notaryzowana aplikacja,
- `appcast.xml` — feed aktualizacji Sparkle, podpisany kluczem EdDSA.

Aplikacja okresowo sprawdza `appcast.xml` z najnowszego wydania i aktualizuje się
automatycznie. To repozytorium służy wyłącznie do dystrybucji binariów — nie zawiera
kodu źródłowego.

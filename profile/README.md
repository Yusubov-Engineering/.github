<picture>
  <source media="(prefers-color-scheme: dark)" srcset="banner-dark.png">
  <img src="banner-light.png" alt="Yusubov Engineering — modular apps, one contract at a time" width="100%">
</picture>

Templates for apps that stay easy to change as they grow. Every capability is
split into an `_api` module (what it can do) and an `_impl` module (how it does
it), and modules only ever talk to each other through their APIs.

| Template | Stack |
| --- | --- |
| [modular-flutter-template](https://github.com/Yusubov-Engineering/modular-flutter-template) | Flutter · pub workspace · Melos · `modular` CLI |
| [modular-compose-template](https://github.com/Yusubov-Engineering/modular-compose-template) | Jetpack Compose · Navigation 3 · Koin |

Built with them: [circular_words](https://github.com/Yusubov-Engineering/circular_words), a voice-driven English vocabulary game.

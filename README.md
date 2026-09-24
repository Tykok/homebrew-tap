# homebrew-tap

Tap Homebrew de Tykok.

```sh
brew install tykok/tap/notion-seed
brew install tykok/tap/learner
```

Rien ici ne s'édite à la main :

- `Casks/notion-seed.rb` est généré par GoReleaser à chaque release de
  [notion-seed](https://github.com/Tykok/notion-seed).
- `Formula/learner.rb` est poussé par la CI de
  [learning-with-claude](https://github.com/Tykok/learning-with-claude) à chaque tag
  (source : `Formula/learner.rb` de ce dépôt).

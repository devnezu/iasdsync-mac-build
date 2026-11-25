# Mac build

Receita de build do .dmg para macOS (só o workflow). Disparo manual:

```
gh workflow run build.yml -R devnezu/iasdsync-mac-build -f ref=feature/macos -f targets=monterey-x64
```

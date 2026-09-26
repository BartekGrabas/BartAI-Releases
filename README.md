# BartAI Releases

Publiczny kanał aktualizacji aplikacji **BartAI**.

Repozytorium nie zawiera kodu źródłowego BartAI. Służy wyłącznie do publikowania:
- manifestu `latest.json`,
- plików aktualizacji APK,
- informacji o wersjach.

Kod źródłowy pozostaje w prywatnym repozytorium `BartekGrabas/Bart-AI`.

## Kanał

```text
preview
```

Aplikacja sprawdza `latest.json`, porównuje `versionCode`, pobiera części APK, sprawdza SHA-256 i otwiera systemowy instalator Androida.

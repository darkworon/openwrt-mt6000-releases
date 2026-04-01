# openwrt-mt6000-releases

OpenWrt builds for GL-iNet GL-MT6000 (Flint 2).

## Структура

- **GitHub Releases** — прошивка `.bin` + `.apk` пакеты каждого билда
- **GitHub Pages** — APK индексы (`index.json`) для `apk update`

## APK repo

После прошивки роутер автоматически использует репо своего билда:
```
https://darkworon.github.io/openwrt-mt6000-releases/packages/{build-tag}/
```

Обновить пакет без перепрошивки:
```bash
apk update
apk add <package-name>
```

## Исходники

→ [darkworon/openwrt-mt6000](https://github.com/darkworon/openwrt-mt6000)

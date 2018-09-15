# Growtopia
A Multiplayer Online Sandbox Game

## Status

| Arch  | Installs | Runs | Notes |
| ----- | -------- | ---- | ----- |
| 32bit | Yes      | Yes  | None  |
| 64bit | Yes      | Yes  | None  |

## Build & Install
### Repo
#### 32bit

    flatpak-builder --arch=i386 --force-clean builds --repo=winepak com.growtopia.Game.yml
    flatpak install --user winepak com.growtopia.Game
    
#### 64bit

    flatpak-builder --arch=x86_64 --force-clean builds --repo=winepak com.growtopia.Game.yml
    flatpak install --user winepak com.growtopia.Game

### Direct
#### 32bit

    flatpak-builder --user --arch=i386 --force-clean --install builds com.growtopia.Game.yml
    
#### 64bit

    flatpak-builder --user --arch=x86_64 --force-clean --install builds com.growtopia.Game.yml

## Run

    flatpak run com.growtopia.Game


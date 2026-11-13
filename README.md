# Cheonji / Minecraft modpack (packwiz)

Prism Launcher용 packwiz 모드팩입니다. 게임을 켤 때마다 모드가 이 저장소와 맞춰집니다.

## 플레이어 (Prism Launcher)

1. [Prism Launcher](https://prismlauncher.org/)를 설치합니다.
2. [prism.zip](https://akin0521.github.io/minecraft-modpack/smoke-forge-373a/prism.zip)을 받아 Prism에서 가져오기(Import) 합니다.
3. 인스턴스를 실행하면 모드가 자동으로 동기화됩니다.
4. 서버 주소: `nicely-rickety.tun.ply.gg:17201` (가져오기 시 서버 목록에 미리 들어 있습니다).

팩 주소 (직접 쓰는 경우):

`https://akin0521.github.io/minecraft-modpack/smoke-forge-373a/pack.toml`

## 레이아웃

인스턴스마다 하위 폴더를 둡니다.

```
<instanceId>/pack.toml
<instanceId>/index.toml
<instanceId>/mods/*.pw.toml
<instanceId>/prism.zip
```

이 저장소는 메타데이터(toml)와 Prism 가져오기 zip만 담고, 모드 jar는 Modrinth/CurseForge에서 받습니다.

<p align="center">
    <img src="https://github.com/mmtrt/leagueoflegends/raw/master/snap/gui/leagueoflegends.png" alt="leagueoflegends logo" width=128 height=128>

<h2 align="center">leagueoflegends AppImage</h2>

  <p align="center">leagueoflegends AppImage (unofficial) AppImages by GitHub Actions Continuous Integration
    <br>
    <a href="https://github.com/mmtrt/leagueoflegends_AppImage/issues/new">Report bug</a>
    ·
    <a href="https://github.com/mmtrt/leagueoflegends_AppImage/issues/new">Request feature</a>
    ·
    <a href="https://github.com/mmtrt/leagueoflegends_AppImage/releases">Download AppImage</a>
  </p>
</p>

## Get Started

Download the latest release from

| Stable | Dev |
| ------- | --------- |
| <img src="https://github.com/mmtrt/leagueoflegends/raw/master/snap/gui/leagueoflegends.png" height=100> | <img src="https://github.com/mmtrt/leagueoflegends/raw/master/snap/gui/leagueoflegends.png" height=100> |
| [Download](https://github.com/mmtrt/leagueoflegends_AppImage/releases/tag/stable) | [Download](https://github.com/mmtrt/leagueoflegends_AppImage/releases/tag/dev) |


### Executing
#### File Manager
Just double click the `*.AppImage` file and you are done!

> In normal cases, the above method should work, but in some rare cases
the `+x` permissisions. So, right click > Properties > Allow Execution
#### Terminal
```bash
./leagueoflegends-*.AppImage
```
```bash
chmod +x leagueoflegends-*.AppImage
./leagueoflegends-*.AppImage
```

In case, if FUSE support libraries are not installed on the host system, it is
still possible to run the AppImage

```bash
./leagueoflegends-*.AppImage --appimage-extract
cd squashfs-root
./AppRun
```

## Acknowledgements
* https://github.com/AppImageCrafters/appimage-builder
* https://github.com/GloriousEggroll
* https://reddit.com/r/leagueoflinux
* https://github.com/wine-staging/wine-staging
* https://winehq.org

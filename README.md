# crqt-ng

___Cross platform open source e-book reader___

crqt-ng is fast and small cross-platform XML/CSS based eBook reader. Written using the Qt framework.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```bash
flatpak install flathub io.gitlab.coolreader_ng.crqt-ng
flatpak run io.gitlab.coolreader_ng.crqt-ng
```

## Building

```bash
git clone git@github.com:flathub/io.gitlab.coolreader_ng.crqt-ng.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install io.gitlab.coolreader_ng.crqt-ng.yml
```

Flatpakify Choqok
=====

Test with:  
`flatpak-builder --force-clean --ccache build-dir org.kde.choqok.yml`

Install with:  
`flatpak-builder --force-clean --ccache --user --install build-dir org.kde.choqok.yml`

Run with:  
`flatpak run org.kde.choqok`

Notes
-----
- Now passing the cmake flag `-DKDE_INSTALL_USE_QT_SYS_PATHS=OFF`
- Guesses made during `cleanup`, additional refinement could be done
- May be using `rename-*` incorrectly
- Not sure how this will all work on an actual KDE system

References
-----
- [Choqok GitHub repo](https://github.com/KDE/choqok)
- [Flatpak building docs](https://docs.flatpak.org/en/latest/building.html)
- [Flatpak builder reference](https://docs.flatpak.org/en/latest/flatpak-builder-command-reference.html)
- [Flatpak QT demo project](https://github.com/flatpak/qt-flatpak-demo)
- [KDE Flatpak HOWTOs](https://community.kde.org/Guidelines_and_HOWTOs/Flatpak)


# MediaHub GitHub — bozza locale del repository pubblico
- 3/11: creati README.md (it), README.en.md, docs/DOWNLOAD.md, docs/screenshots/android-tv-home.png (screenshot reale dalla Sony). Solo git locale, NON pubblicato.
- Il codice sorgente resta privato: il repository contiene solo documentazione e link ai file su Google Drive.
- 3/11: repo pubblicato: https://github.com/corallocla-web/mediahub (README.md EN, README.it.md IT). La Sony ha cambiato IP (ora 192.168.3.192, DHCP): se adb non risponde cercare la porta 5555 in 192.168.3.0/24.
- Da fare (solo con ok dell'utente): altri screenshot (player, guida, Windows, MediaHub OS), creare il repo su GitHub e attivare Pages.
- Attenzione: lo screenshot mostra la lista di un provider IPTV (nomi/loghi canali): valutare se sostituirlo prima di renderlo pubblico.
- I link Drive nei README vanno aggiornati a ogni nuova build (stessi nomi di mediahub-download/links.json).
- 4/11: da ora le build (APK/exe/msi) escono come GitHub Releases (tag v<versione>, 'gh release create') senza data nel nome; solo la ISO resta su Drive finche' non cambia. Release v1.0.43 pubblicata.
- 4/11: release v1.0.44 pubblicata (Android 1.0.44, Windows 1.0.2), README aggiornati.
- 4/11: release v1.0.46 pubblicata (Android 1.0.46, Windows 1.0.4), README aggiornati.
- 4/11: release v1.0.47 pubblicata (Windows 1.0.5 + APK 1.0.46); le release precedenti restano. L'updater Android legge l'APK dall'ULTIMA release: allegare sempre l'APK.
- 4/11: release v1.0.48 pubblicata (Windows 1.0.6 MSI x64 + APK 1.0.46); provata dall'utente.
- 5/11: release v1.0.49 pubblicata (Windows 1.0.7 con fix preferenze/wizard + APK 1.0.46); README aggiornati. Non provata dall'utente.

- 5/11: release v1.0.50 pubblicata (Android TV 1.0.48 / Windows 1.0.10). README con i nuovi link.
- 6/11: release v1.0.51 pubblicata (Android TV 1.0.49 / Windows 1.0.11): wizard con QR Xtream + scelta categorie. README con i nuovi link.
- 7/11: release v1.0.53 pubblicata (Android TV 1.0.51 / Windows 1.0.11): app piu' veloce, canali dopo OK sul bouquet, riconnessione automatica del live. README con i nuovi link.

MONSTER TRACKER

Eine kleine Progressive Web App zum Sammeln von Energy-Drink-Dosen.

Bereitstellung:
1. Repository auf GitHub öffnen.
2. Settings > Pages öffnen.
3. Bei Build and deployment als Source „GitHub Actions“ auswählen.
4. Der Workflow „Deploy Monster Tracker to GitHub Pages“ veröffentlicht die App nach einem Push auf main.
5. Danach ist die App unter https://geilertyp11.github.io/Tracker/ erreichbar.

Die App speichert die Sammlung lokal im Browser dieses Geräts. Sie hat keinen Cloud-Sync. Bitte regelmäßig ein Backup exportieren. Kamera-Scan benötigt HTTPS und Browserfreigabe. Produktabfragen verwenden Open Food Facts; der Barcode-Scanner lädt ZXing von einem CDN.
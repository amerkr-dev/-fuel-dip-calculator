Fuel Dip Calculator — Staff Version 1.0

This release keeps the verified calculation method and the calibration tables from the verified Excel workbook.

Daily:
- Enter MS, HSD and/or XP95 DIP.
- Results are shown in litres.
- Only .0/.1/.2/.3/.4 decimal readings are accepted.
- No daily history is stored.
- Clear removes the current screen entries.

Admin:
- Temporary PIN: 2580
- This is only an accidental-change barrier for the PWA. It is not cryptographic security because calibration data is embedded in the client files.
- Change the PIN in index.html before operational deployment if desired.

XP95:
- The supplied calibration chart provides valid values through DIP 194. The app does not estimate beyond the supplied chart.

Deployment:
Upload index.html, calibration.js, manifest.webmanifest, and service-worker.js to an HTTPS host (e.g. GitHub Pages), then open the site in Safari and choose Add to Home Screen.

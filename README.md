# Malkontrolle

Das Handy filmt das Ölbild auf dem Brett, das Tablet zeigt das entzerrte Bild mit den Konturen der Vorlage darüber.

- Tablet: https://risinghurricane.github.io/malkontrolle/#anzeige
- Handy: https://risinghurricane.github.io/malkontrolle/#kamera

Auf dem Brett kleben vier ArUco-Marker (DICT_4X4_50, IDs 0–3, je 30 mm) rund um das Gesicht. Die Vorlage bleibt nur auf dem Tablet gespeichert. Das Videobild geht im WLAN direkt vom Handy zum Tablet (WebRTC, Verbindungsaufbau über den öffentlichen PeerJS-Server). Bildverarbeitung mit OpenCV.js.

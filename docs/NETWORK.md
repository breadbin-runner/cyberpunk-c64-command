 # Network connections / Netzwerkverbindungen

Hardware features connect from the Mac to the C64 Ultimate in the local
network. The File Manager uses FTP within the app; it does not need a separate
bridge program.

In the current 3.11.1 build, the app attempts to contact a Cloudflare Worker
on startup. After the first successful counter request for a local app
profile, it records locally that the request succeeded and does not send
another increment for that profile. The Worker script stores the total count,
without an installation ID or app password. Opening the About section can
request the current total.
As with any network request, the service provider may process connection
metadata. The public counter address is
https://cyberpunk-c64-counter.th-kleinheinz.workers.dev.

**Deutsch:** Gerätefunktionen verbinden den Mac mit dem C64 Ultimate im
lokalen Netz. Der Dateimanager nutzt FTP direkt in der App. Die aktuelle
Version 3.11.1 versucht beim Start, einen Cloudflare Worker zu erreichen.
Nach der ersten erfolgreichen Zählanfrage für ein lokales App-Profil merkt sie
sich dies lokal und sendet für dieses Profil keine weitere Erhöhung. Der
Worker speichert nur den Gesamtzähler. Im Bereich
„Über diese App“ kann die App den Zählerstand abrufen. Beim Netzwerkzugriff
kann der Dienstanbieter Verbindungsdaten verarbeiten.

# Royal Table – Multiplayer Texas Hold'em

Browserbasiertes Texas Hold'em mit privaten Räumen und Echtzeit-Multiplayer.

## Lokal starten
Node.js 18+ installieren, dann:
```bash
npm install
npm start
```
Öffne http://localhost:3000. Freunde im selben Netzwerk können über die lokale IP-Adresse des Servers beitreten.

## Online hosten
Die App benötigt einen dauerhaft laufenden Node.js-Host mit WebSocket-Unterstützung (z. B. Render, Railway oder einen VPS).
- Build command: keiner
- Start command: `npm start`
- Node.js: 18 oder neuer

## Funktionen
- Private Tische mit sechsstelligen Einladungscodes
- 2–8 Spieler, 1.000 Startchips, Blinds 10/20
- Texas Hold'em: Preflop, Flop, Turn, River und Showdown
- Live-Synchronisierung via Socket.IO
- Spielgeld only – kein Echtgeld

## Hinweis
Prototyp für private Spielrunden. Vor öffentlichem Betrieb sind u. a. persistente Accounts, Reconnect-/Session-Handling, Side-Pot-Abrechnung, Rate-Limits und ausführliche Regeltests zu ergänzen.
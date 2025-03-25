# LobbyCommand
Ein BungeeCord-Plugin für das schnelle Teleportieren zur Lobby.


# ✨ Beschreibung


LobbyCommand ist ein einfaches BungeeCord-Plugin, das Spielern erlaubt, sich mit dem Befehl /lobby oder /hub zur konfigurierten Lobby zu teleportieren. Das Plugin unterstützt eine konfigurierbare Nachricht und benötigt eine Berechtigung zum Benutzen des Befehls.

# 📂 Funktionen

Teleportiert Spieler zur konfigurierten Lobby mit /lobby oder /hub.

Zeigt die Nachricht "Du wirst teleportiert..." an, bevor der Spieler verbunden wird.

Berechtigungsprüfung (lobby.use), um den Befehl nur bestimmten Spielern zu erlauben.

Anpassbare Konfigurationsdatei (config.yml).

# 🛠 Installation

Kompiliere das Plugin und erhalte die LobbyCommand.jar-Datei.

Lade die LobbyCommand.jar in den plugins/-Ordner deines BungeeCord-Servers.

Starte den Server neu oder verwende /bungeecord reload.

Bearbeite die config.yml, um den Namen deines Lobby-Servers anzupassen.

Füge die Berechtigung lobby.use in dein Berechtigungssystem ein, falls nötig.


# 📝 Konfiguration (config.yml)

lobby-server: "Lobby"

message-no-permission: "§cDu hast keine Berechtigung, diesen Befehl zu nutzen!"

message-connecting: "§aDu wirst teleportiert..."

lobby-server: Der Name des Servers, zu dem sich Spieler verbinden, wenn sie /lobby verwenden.

message-no-permission: Nachricht, wenn ein Spieler keine Berechtigung für den Befehl hat.

message-connecting: Nachricht, die gesendet wird, bevor der Spieler teleportiert wird.

# ⚖ Berechtigungen

Permission: lobby.use

Beschreibung: Erlaubt Spielern die Nutzung des /lobby-Befehls

# 💻 Entwicklung

Hauptklasse: me.deinname.lobbycommand.Main

Befehl: me.deinname.lobbycommand.CommandLobby

Konfigurationsmanager: me.deinname.lobbycommand.ConfigManager

# 🔧 Unterstützung & Feedback

Falls du Fragen oder Verbesserungsvorschläge hast, erstelle ein Issue oder forke das Repository, um Änderungen vorzunehmen! Viel Spaß mit dem Plugin! 🚀

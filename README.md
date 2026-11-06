# Packet-Sniffer-for-Wats-App
Ein leichter Python-Netzwerksniffer mit Scapy zur gezielten Analyse von lokalem UDP- und TCP-Verkehr.

# 🐍 Python UDP & TCP Network Sniffer

Ein leichter, maßgeschneiderter Netzwerk-Sniffer auf Basis von **Scapy**, entwickelt, um den lokalen Netzwerkverkehr eines spezifischen Geräts (z. B. deines Smartphones) in Echtzeit zu filtern und zu analysieren.

Dieses Tool wurde von Grund auf entwickelt, um ein tieferes Verständnis für Paketverarbeitung, Netzwerkprotokolle und Live-Traffic-Analysen zu erlangen.

---

## 🚀 Features

* **Gezielter IP-Filter:** Konzentriert sich ausschließlich auf den Datenverkehr einer definierten Ziel-IP im lokalen Netzwerk.
* **Protokoll-Erkennung:** Unterscheidet automatisch zwischen UDP- und TCP-Paketen.
* **Automatisches Reverse-DNS-Lookup:** Versucht über das Python-`socket`-Modul den Hostnamen oder die Organisation hinter einer fremden IP-Adresse aufzulösen.
* **Minimalistisch & transparent:** Keine überflüssige Bloatware, reiner Python-Code zum Verstehen und Erweitern.

---

## 🛠️ Voraussetzungen

Stelle sicher, dass Python und die Scapy-Bibliothek auf deinem System installiert sind:

```bash
pip install scapy

Verwende diesen code mit Vorsicht!!!

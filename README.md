# M365-MFA-Report
PowerShell-Skript zum Erstellen eines MFA-Reports in Microsoft 365
# 📊 Microsoft 365 MFA-Status Report

Ein PowerShell-Skript, das den **MFA-Status aller Benutzer in Microsoft 365** abfragt und als CSV exportiert.  
Perfekt für IT-Administratoren und Supporter, um den Sicherheitsstatus im Blick zu behalten.  

---

## 🚀 Funktionen
- Verbindet sich mit Microsoft Graph
- Listet alle Benutzerkonten in Microsoft 365
- Prüft, ob Multi-Faktor-Authentifizierung (MFA) eingerichtet ist
- Exportiert Ergebnisse in eine CSV-Datei

---

## 📦 Voraussetzungen
- Windows PowerShell 5.1 oder neuer  
- Microsoft Graph PowerShell Modul:
  ```powershell
  Install-Module Microsoft.Graph -Scope CurrentUser

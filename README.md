# Luftwechselberechnung für Batterieladestationen (Österreich)  

Dieses Repository enthält Richtlinien und Berechnungsmethoden zur Bestimmung des erforderlichen **Luftwechsels** in Batterieladestationen gemäß österreichischen Normen.  

## 📌 Inhalte  
- **Normen & Richtlinien**: TRVB 600, ÖNORM EN 50604, EN 62282-3-201  
- **Berechnungsformeln** für den minimalen Luftwechsel  
- **Praktische Richtwerte** für Lüftungsanlagen  
- **Beispielrechnung** mit Raumgröße und Wasserstofffreisetzung  

## 🔧 Anwendung  
1. **Eingabeparameter**:  
   - Raumvolumen (m³)  
   - Wasserstofffreisetzungsrate (m³/h)  
   - Max. zulässige H₂-Konzentration (Standard: 1 %)  
2. **Berechnung**:  
   ```python
   n = (Q_H2) / (V * (C_max - C_umgebung))  
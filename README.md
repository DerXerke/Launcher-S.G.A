# Launcher S.G.A
<img width="350" height="450" alt="ChatGPT Image 23 oct 2025, 08_09_33 p m" src="https://github.com/user-attachments/assets/f0794f7a-69a0-424c-bc41-aba832dc57d2" />         <img width="350" height="450" alt="image" src="https://github.com/user-attachments/assets/113eabb3-9d1a-4c57-bfd2-a210bd803df3" />   <img width="350" height="450" alt="image" src="https://github.com/user-attachments/assets/49b68989-6b38-4296-b19d-07456d90a73d" />  <img width="350" height="450" alt="image" src="https://github.com/user-attachments/assets/da25b0f7-547c-4e4d-bc84-51eff1472a39" />




[![LAUNCHER SGA (WINDOWS)](https://img.shields.io/badge/LAUNCHER%20SGA%20(Windows)-Descargar-2ea043?style=for-the-badge&logo=windows)](https://github.com/DerXerke/Launcher-S.G.A/releases/download/A/setup.launcher.S.G.A.exe) 

---

## Si Windows muestra “Windows protegió su PC”
Es **Microsoft Defender SmartScreen**. Suele aparecer en apps nuevas o sin firma digital.
Tu archivo **no es malware**; solo aún no tiene reputación suficiente.

**Qué hacer:**
1. En el aviso azul, pulsa **Más información**.  
2. Pulsa **Ejecutar de todas formas**.

> En próximas versiones añadiremos firma/reputación para que este aviso desaparezca.

---

## Verificar integridad (opcional)
Compara el **SHA-256** del instalador con el valor publicado.

**PowerShell:**
```powershell
Get-FileHash "$env:USERPROFILE\Downloads\setup.launcher.S.G.A.exe" -Algorithm SHA256 | Select-Object Hash

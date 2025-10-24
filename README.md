# Launcher S.G.A
<img width="1024" height="1024" alt="3cd758c9-756e-4930-addf-9998b8c5fe45" src="https://github.com/user-attachments/assets/b839a17b-8aba-4af9-8f4d-b5bb4134444d" />

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

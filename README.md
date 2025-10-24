# Launcher SGA

[![LAUNCHER SGA (WINDOWS)](https://img.shields.io/badge/LAUNCHER%20SGA%20(Windows)-Descargar-2ea043?style=for-the-badge&logo=windows)](https://github.com/DerXerke/Launcher-S.G.A/releases/latest/download/setup.exe)

Launcher de Minecraft Java fácil y confiable. Instalación en 1 minuto.

---

## Si Windows muestra “Windows protegió su PC”
Esto es **Microsoft Defender SmartScreen**. Aparece en apps nuevas o sin firma digital.
Tu archivo **no es malware**; solo aún no tiene reputación suficiente.

**Qué hacer:**
1. En el aviso azul, pulsa **Más información**.  
2. Pulsa **Ejecutar de todas formas**.

> En próximas versiones añadiremos firma y reputación para que este aviso desaparezca.

---

## Verificar integridad (opcional)
Compara el **SHA-256** del instalador con el valor publicado abajo.

**PowerShell (copiar y pegar):**
```powershell
Get-FileHash "$env:USERPROFILE\Downloads\setup.exe" -Algorithm SHA256 | Select-Object Hash

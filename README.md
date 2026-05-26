# batch
Script PowerShell
1. Pulsar W+R y abrir taskschd.msc.
2. Crear una tarea nueva, pestaña Desencadenadores: Al iniciar sesión.
3. Pestaña Acciones: Iniciar un programa powershell.exe con los siguientes argumentos:
      -ExecutionPolicy Bypass -WindowStyle Hidden -File "C:\Users\\%USERPROFILE%\AppData\Roaming\Script.ps1"
4. En la pestaña General marcar Ejecutar con los privilegios más altos si quieres que copie incluso archivos de unidades protegidas, y en 'Configurar para' elige Windows 10.

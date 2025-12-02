
╔════════════════════════════════════════════════════════════════╗
║  INSTRUCCIONES PARA SUBIR A GITHUB                             ║
╚════════════════════════════════════════════════════════════════╝

📁 Carpeta generada: c:\Users\USUARIO\Downloads\Allio-Client\github-sync-export\squidgame instace

🚀 PASOS:

1️⃣ Crear repositorio en GitHub:
   • Ve a: https://github.com/new
   • Nombre: allio-instances
   • Público ✅ (para usar GitHub raw URLs)
   • Crear repositorio

2️⃣ Subir archivos:
   
   Opción A - GitHub Desktop (Fácil):
   • Descarga GitHub Desktop: https://desktop.github.com/
   • File → Add Local Repository → Selecciona: c:\Users\USUARIO\Downloads\Allio-Client\github-sync-export\squidgame instace
   • Commit → Push to origin

   Opción B - Git desde terminal:
   cd "c:\Users\USUARIO\Downloads\Allio-Client\github-sync-export\squidgame instace"
   git init
   git add .
   git commit -m "Initial commit - SquidGame Instace"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/allio-instances.git
   git push -u origin main

3️⃣ Actualizar allio_config.json:
   
   Agrega esto:
   
   {
     "instance_manifests": {
       "squidgame instace": "https://raw.githubusercontent.com/TU-USUARIO/allio-instances/main/squidgame instace/manifest.json"
     }
   }

4️⃣ Reemplaza "TU-USUARIO" con tu nombre de usuario de GitHub

5️⃣ ¡Listo! La próxima vez que inicies la instancia se sincronizará automáticamente

═══════════════════════════════════════════════════════════════

💡 ACTUALIZACIONES FUTURAS:

Cuando actualices mods:
1. Ejecuta de nuevo este script
2. Incrementa la versión en manifest.json (ej: "1.0.0" → "1.1.0")
3. Haz commit y push de los cambios
4. Los jugadores se actualizarán automáticamente al iniciar

═══════════════════════════════════════════════════════════════

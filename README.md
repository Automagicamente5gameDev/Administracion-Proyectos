# Administracion-Proyectos

- Inicializar git
- Instalar git lfs
   - `git lfs install`
   - Para confirmar instalacion:
      - `git lfs -v`
- Inicializar LFS .gitattributes en la carpeta del proyecto via comando
   - ```
      git lfs track "*.psd"
      git lfs track "*.png"
      git lfs track "*.jpg"
      git lfs track "*.mp4"
      git lfs track "*.wav"
      git lfs track "*.fbx"
      git lfs track "*.tga"
     ```
- Crear un archivo **.gitignore** con el siguiente contenido:
   - ```
      # Unity 
      [Ll]ibrary/
      [Tt]emp/
      [Oo]bj/
      [Bb]uilds/
      [Bb]uild/
      [Ll]ogs/
      Packages/manifest.lock
      
      # Archivos de Visual Studio y JetBrains
      .vs/
      *.csproj
      *.sln
      *.userprefs
      .idea/
      
      # Archivos temporales de Mac y Windows
      .DS_Store
      Thumbs.db
     ```

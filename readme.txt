Ir a la ubicacion del repositorio en el terminal:
git status //muestra el estado del archivo nuevo en rojo (U: untracked)

git add readme.txt //agrega el archivo al Staging de forma local (A:added)
git status

git commit -m "Commit inicial"  //agrega los archivos del Stage 
                                al Historial del proyecto de forma local
git push origin main    //envia los cambios del repositorio local al remoto (github)
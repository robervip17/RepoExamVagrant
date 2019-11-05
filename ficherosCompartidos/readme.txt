Primero tenemos que cambiar el vagrantFile.

En la linea 46: config.vm.synced_folder "./vinyesWeb", "/vinyesWeb"
Donde "./vinyesWeb" es la ruta donde se encuentra la carpeta local compartida.
Y donde "/vinyesWeb" es la ruta donde se encuentra la carpeta que se encuentra en la maquina virtual.

Al crear un fichero y editardo en el local o en la máquina virtual tambien se actualizara en el directorio paralelo.

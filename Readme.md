## Generar la llave -> ssh keygen -t rsa -b 4096 -C ycarolina.sguzman@gmail.com

## Revisar y actualizar las llaves con -> eval "$(ssh-agent-s)"

## Agregar la llave creada -> ssh-add~/.ssh/id_rsa

- settings.- ssh
-crear nueva llave
-abrir el archivo id_rsa.pub con editor de texto y copiar la llave
-ingresar la llave en github con su nombre y guardar (en profile-settings de git)

## En la terminal hacer los siguientes pasos
1.-Ir a escritorio y crear la carpeta admin_servidores - cd Desktop
2.-Entrar a carpeta - cd admin_servidores
3.-Crear el Readme file - touch Readme.md
4.-Luego entrar a Nano Readme.md y agregas título y subtitulo (ctrl X para salir, Y para guardar)
5.-More Readme.md para ver que si se guardó con cambios
6.-Se usa git init
7.-Luego git add .
8.-Se hace commit con - git commit -m "first commit"
9.-git remote add origin https://github.com/CarolinaGuzman/administracion_servidores.git
10.-git push -u origin master


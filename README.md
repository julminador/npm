# Versionado semantico

3.9.2
```sh
3 # Camnio mayor: Cambios sustanciales
.
9 # Cambio menor: Un cambio de una estructura o elemento
.
2 # Parche: Cambios de un bug pequenio
```

# Comandos

Para inicializar el proyecto
```sh
npm init
```

> - author: Julian Sanchez <<https://github.com/julminador>>

Inicializar por defecto
```sh
npm init -y
```

Instalar por defecto
```sh
npm intall moment
```

Instalar como dependencia de desarrollo
```sh
npm install moment -D
```

Instalar paquetes globales en mi OS 
```sh
npm install -g moment
```

Listar paquetes globales en mi OS 
```sh
npm list -g --depth=0
```

instala las dependencias del package.json
```sh
npm install
```

Listar paquetes
```sh
npm list
```
```sh
npm list -g # globales
```

Instalar una dependencia opcional
```sh
npm install moment -o
```

Simular la instalacion para validar conflictos por versiones
```sh
npm install moment-react --dry-run
```

Instalar version especifica
```sh
npm install moment@0.15.0
```

Instalar version mas reciente
```sh
npm install moment@latest
```

Ejecutar un script
```sh
npm run run-npm-script
```
Crear scripts
en el archivo package.json en la propiedad "scripts"
```sh
"scripts": {
  "run-npm-script": "node src/npm//index.js" # nombre y accion
}
```

Ejecutar acciones sin instalar
```sh
npx create-react-app my-app
```

Muestra los cambios en las versiones de las dependencias
```sh
npm outdate
```

Busca vulnerabilidades, se calculará el impacto y la corrección adecuada
```sh
npm audit
```

Busca vulnerabilidades en un json
```sh
npm audit --json
```

Actualiza los recursos necesarios para evitar vulnerabilidades
```sh
npm audit fix
```

Fuerza la actualiza los recursos con otras dependencias necesarias para evitar vulnerabilidades
```sh
npm audit fix --force
```
> Cuando con estos comandos no se logre eliminar las vulnerabilidades se recomienda actualizar los recursos con npm install moment@latest

Desinstalar un paquete
```sh
npm uninstall moment
```

Para ver librerias deprecated o que ya no se actualizaran
Tambien actualiza el package con el package-log
```sh
npm ci
```
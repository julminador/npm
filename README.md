Para inicializar el proyecto
```sh
npm init
```

> - author: Julian Sanchez <juliansosa021@gmail.com>

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
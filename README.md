//estructura del proyecto//
mi-proyecto-devops/
│── src/
│   ├── index.html
│   ├── styles.css
│── scripts/
│   └── deploy.sh
│── README.md
│── .gitignore
//descripcion del proyecto//
este es un proyecto de practica que consiste en un index.html y un styles.css que cambia de color el titulo a rojo y el texto a verde ademas de un deploy que simula el despliegue y este readme para explicar el programa.
//objetivo//
aprender a usar git y github(no ocupe gitbash porque olvide que existia)
//flujo de trabajo//
A[Crear estructura] --> B[Desarrollar script]
    B --> C[Dar permisos]
    C --> D[Probar localmente]
    D --> E[Versionar con Git]
    E --> F[Documentar]
//comandos git principales//
1.- git clone https://github.com/TU-USUARIO/mi-proyecto-devops.git
cd mi-proyecto-devops

2.-git add .
git commit -m "Estructura inicial del proyecto"

3.-git add scripts/deploy.sh
git commit -m "Script de despliegue simulado"

4.-git checkout -b feature-update

5.-git add src/index.html
git commit -m "Nueva sección agregada"
git push origin feature-update
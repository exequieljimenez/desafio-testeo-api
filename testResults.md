$ npm run test

> arq-capas@1.0.0 test
> mocha src/test/api.test.js --exit

[2023-05-10T11:41:27.726] [INFO] default - Base de datos conectada
[2023-05-10T11:41:27.728] [INFO] default - Base de datos ya conectada
[2023-05-10T11:41:27.728] [INFO] default - Base de datos ya conectada    
[2023-05-10T11:41:27.766] [INFO] default - Server listening on port 8080


  api product test
Before: Este codigo se ejecuta antes de todas las pruebas
beforeEach: este codigo se ejecuta antes de cada prueba
primera prueba
    ✔ get productos test
afterEach: este codigo se ejecuta al finalizar cada prueba
beforeEach: este codigo se ejecuta antes de cada prueba
segunda prueba
    ✔ despues de crear un producto deberia haber un array con un productoafterEach: este codigo se ejecuta al finalizar cada prueba
beforeEach: este codigo se ejecuta antes de cada prueba
tercera prueba
    ✔ despues de crear un producto este deberia tener un nombre
afterEach: este codigo se ejecuta al finalizar cada prueba
beforeEach: este codigo se ejecuta antes de cada prueba
cuarta prueba
    ✔ despues de crear un productos se puede borrar con id
afterEach: este codigo se ejecuta al finalizar cada prueba
After: Este codigo se ejecuta al final de todas las pruebas


  4 passing (81ms)

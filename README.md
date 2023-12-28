<div align="center">
  <h1>React Food Delivery</h1>

![image](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![image](https://img.shields.io/badge/Apollo%20GraphQL-311C87?&style=for-the-badge&logo=Apollo%20GraphQL&logoColor=white)
![image](https://img.shields.io/badge/GraphQl-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![image](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![image](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![image](https://img.shields.io/badge/Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white)

<p>Aplicación de entrega de comida a domicilio basada en el concepto de uber eats y rappi. En el que podrás registrarte como cliente, propietario o repartidor y dependiendo de tu perfil podrás dar de alta tu restaurante para la venta de comida, ayudar a entregar pedidos y pedir lo que más te guste.</p>
</div>

### Vista previa

![](./.readme-static/app.jpeg)

## Características

- Notificaciones cuando:
  - Hay una orden
  - El pedido ha sido tomado, cocinado y entregado
- Gestión de múltiples roles
- Verificación por correo electrónico al registrarse
- Ubicación del usuario para la entrega de comida
- Trazar rutas usando mapbox
- CRUD de restaurantes, informes y estadísticas
- Pagos de PayPal para promocionar un restaurante

## Instalación

Para clonar y ejecutar esta aplicación, necesitará [Git](https://git-scm.com) y
[Node.js](https://nodejs.org/en/download/) instalado en su computadora. _Opcional_ que puedes instalar
[Yarn](https://yarnpkg.com/getting-started/install).

Desde la línea de comandos:
```bash
  # Clonar este repositorio
$ git clone https://github.com/holiweed/react-food-delivery

# Abrir el Repositorio
$ cd react-food-delivery

# Instalar dependencias
$ yarn install

# Iniciar la app
$ yarn run start
```

**Nota: Este proyecto tiene un backend hecho con nest.js, que puedes configurar para manejar datos
persistencia, autenticación, correo, notificaciones y más. El repositorio se puede encontrar en el
Siguiente enlace [food-delivery-backend](https://github.com/holiweed/food-delivery-backend).**

## Implementación

Agrupa correctamente React en modo de producción y optimiza la compilación para obtener el mejor rendimiento.

```bash
$ yarn run build
```

## Tests

```bash
# Iniciar test
$ yarn run test

# ver porcentaje del test
$ yarn run test:coverage

# e2e tests
$ yarn run cypress open
```

## Dependencias

 [mapbox-gl](https://docs.mapbox.com/mapbox-gl-js/api/) se utiliza para crear mapas. Lo es
necesario tener un [mapbox account](https://account.mapbox.com/) para poder generar el token
que necesitamos para dicha biblioteca.

## Licencia

Siéntase libre de bifurcar este proyecto y mejorarlo.¡Regala un ⭐️ si te gusta este proyecto!

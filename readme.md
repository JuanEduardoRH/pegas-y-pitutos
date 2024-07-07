# Pegas & Pitutos - Finalizado

### [Ver demo](https://pitutos.typingideas.com)

usuario: empleador3@empleador.com \
password: 12345678

usuario: trabajador4@trabajador4.com \
password: 12345678

usuario: trabajador5@trabajador5.com \
password: 12345678

# Detalles

Empleadores:

En esta plataforma web, se puede crear publicaciones de trabajos, la cantidad de estas mismas publicaciones por cada cuenta es limitada, para remover esta restricción, puede realizar el pago de la membresía, este proceso se realiza gracias al SDK de Transbank.

También puede gestionar las diversas etapas por las cuales el proceso de búsqueda de trabajadores va cursando, en dado caso que encuentre a la persona indicada, este proceso puede finalizar antes de tiempo, para esto la aplicación entrega datos asociados de dichos trabajadores, ya sea medio de contacto, presentación personal, historial de trabajos anteriores.

Trabajador:

La plataforma provee un máximo de 3 postulaciones gratuitas, en dado caso que él requiera remover este límite de postulaciones y tener mayor visibilidad frente a otros postulantes, puede realizar la compra de una membresía, este proceso se realiza gracias al SDK de Transbank.

También existe la posibilidad de que quiera guardar algunos trabajos en su lista de favoritos si así lo desea.

Es importante que el trabajador pueda mostrar todas sus habilidades y en los trabajos o empresas en las cuales ha podido desempeñar sus labores, por lo mismo, la plataforma provee de un panel el cual permite ingresar toda su información personal, junto a diferentes apartados para ingresar toda su experiencia laboral que ha tenido hasta el día de hoy.

## Dependencias del proyecto

- Laravel 8
- Bootstrap 4.6
- Jquery
- Transbank SDK

## Funcionalidades

- Administrador
  - Listado de trabajos
  - Mantenedor de ciudades y regiones
  - Mantenedor de categorías
  - Mantenedor de usuarios (Bloquear o habilitar)
  - Listado de transacciones (Pagos)
  - Edición de cuenta (Personal)
 
- Empleador
  - Mantenedor de trabajos
  - Repostear trabajo
  - Caza talentos (busqueda de trabajadores)
  - Mantenedor para procesos de postulación
  - Visualizador de perfil en postulantes
  - Visualizador y guardado de CV
  - Calificación a trabajador por labor realizada
  - Pasarela de pago para membresía
  - Listado de pagos realizado (Membresía)
  - Mantenedor de información empresarial (Perfil de la empresa)
  - Edición de cuenta (Personal)
 
- Trabajador
  - Listado de trabajos postulados
  - Visualización de calificación a base de trabajos realizado
  - Listado de trabajos favoritos
  - Mantenedor de perfil (CV)
    - Información personal
    - Área enfocada a lo laboral
    - Editor de habilidades
    - Editor de biografía
    - Editor de experiencia laboral
    - Mantenedor de CV (pdf)
  - Pasarela de pago para membresía
  - Listado de pagos realizado (Membresía)
  - Edición de cuenta (Personal)

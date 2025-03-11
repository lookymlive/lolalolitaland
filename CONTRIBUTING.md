# 🤝 Cómo Contribuir

Las contribuciones son lo que hacen que la comunidad de código abierto sea un lugar increíble para aprender, inspirar y crear. ¡Cualquier contribución que hagas es **muy apreciada**!

Si tienes alguna sugerencia que podría mejorar el proyecto, por favor haz un [_fork_](https://github.com/midudev/lolalolitaland.com/fork) del repositorio y crea una [_pull request_](https://github.com/midudev/lolalolitaland.com/pulls). También puedes simplemente abrir un [_issue_](https://github.com/midudev/lolalolitaland.com/issues) con la etiqueta "enhancement".

Aquí tienes una guía rápida:

1. Haz un [_fork_](https://github.com/midudev/lolalolitaland.com/fork) del Proyecto
2. Clona tu fork (`git clone https://github.com/<USERNAME>/lolalolitaland.com`)
3. Añade el repositorio original como remoto (`git remote add upstream https://github.com/midudev/lolalolitaland.com.git`)
4. Crea tu Rama de Funcionalidad (`git switch -c feature/CaracteristicaIncreible`)
5. Realiza tus Cambios (`git commit -m 'Add: alguna CaracterísticaIncreible'`)
6. Haz Push a la Rama (`git push origin feature/CaracteristicaIncreible`)
7. Abre una [_pull request_](https://github.com/midudev/lolalolitaland.com/pulls)

Por favor, consulta nuestra [guía de contribución aquí](https://github.com/midudev/lolalolitaland.com/blob/master/CONTRIBUTING.md) para saber cómo puedes empezar de la mejor manera y siguiendo [buenas prácticas](https://github.com/midudev/lolalolitaland.com/blob/main/CONTRIBUTING.md#buenas-prácticas-).

## Contribuir desde Stackblitz

Si quieres contribuir de una manera más sencilla, puedes iniciar este proyecto desde _Stackblitz_ usando tu cuenta de GitHub:

[![Abrir en Stackblitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/midudev/lolalolitaland.com)

> [!NOTE]
>
> Nota: antes de codificar una nueva funcionalidad ve a la
> sección de issues y PRs del repositorio y verifica que ya no se
> esté discutiendo sobre ese tema, o que ya otra persona no lo
> haya realizado.

### 📋 Estándares de Código

#### Commits

Si es posible describe tus proyectos para que los mantenedores los puedan analizar de una forma más rápida y eficiente.

- `feat:` - Nuevas características
- `fix:` - Correcciones de bugs
- `docs:` - Cambios en documentación
- `style:` - Cambios que no afectan el código (espacios, formato, etc)
- `refactor:` - Refactorización del código
- `test:` - Añadir o modificar tests
- `chore:` - Cambios en el proceso de build o herramientas auxiliares

Ejemplo: `feat: add newsletter subscription component`

#### Código

- Utiliza en lo posible el estilo de codificación configurado
- Nombra las variables y funciones en camelCase
- Utiliza nombres descriptivos en variables y funciones
- Los componentes de Astro deben ir en PascalCase
- Comenta tu código cuando solo sea necesario
- Sigue las reglas de ESLint configuradas en el proyecto

#### CSS/TailwindCSS

- Utiliza las clases de Tailwind siempre que sea posible
- Evita CSS personalizado a menos que sea absolutamente necesario

#### Pull Requests

- Describe claramente los cambios realizados
- Incluye capturas de pantalla si hay cambios visuales
- Asegúrate de que los tests pasen
- Referencia los issues relacionados si los hay
- Mantén los PR pequeños y enfocados en una sola característica

### For de contribuir

- Todos los aportes son importantes
- Codificación
- Pruebas manuales o automatizadas
- Traducciones, correcciones ortográficas

### 🚫 Qué evitar

- No hagas commit directamente a `main`
- No uses `!important` en CSS
- No dejes console.logs en el código
- No añadas dependencias sin discutirlo primero
- No modifiques la configuración del proyecto sin consenso
- Evita ser grosero o imponerte en las discusiones

### 👥 Proceso de Review

1. Los PR necesitan al menos una aprobación
2. Atiende los comentarios del review
3. Asegúrate de que el CI/CD pase

## Estructura del Proyecto

└── 📁lolalolitaland.com
    └── 📁public <-- images, fonts, Svgs
    └── 📁src
        └── 📁components
        └── 📁consts
        └── 📁layouts
        └── 📁pages
        └── 📁sections
        └── 📁styles

# MindShore - Desafio Tecnico

**Plataforma de Exploracion Espacial con IA**

> Crea una aplicación web fullstack que permita explorar, curar y enriquecer contenido espacial de NASA utilizando IA generativa.

Este challenge es abierto y publico. No necesitas que nadie te invite. Si sos desarrollador/a y querés sumarte a MindShore, este es tu punto de entrada.

## ¿Cómo participar?

```
1. Forkeá este repositorio
2. Leé este README completo antes de escribir una sola linea de codigo
3. Construí tu solucion
4. Abrí un Pull Request contra este repo con tu trabajo
5. Nuestro equipo de ingenieria lo revisa y te da feedback
```

**No hay fecha límite.** Valoramos la calidad sobre la velocidad. Tomate el tiempo que necesites para demostrar tu mejor trabajo.

## El desafio

### Objetivo

Crear una aplicación web fullstack que conecte con la API de NASA para explorar imágenes espaciales, permita a los usuarios organizar ese contenido en colecciones, y use IA generativa (OpenAI) para enriquecer la experiencia.

### Funcionalidades core (obligatorias)

| Feature | Descripción |
|---------|-------------|
| **Busqueda avanzada** | Buscar imágenes de NASA con filtros: fecha, rover, camara, mision |
| **Colecciones personalizadas** | Los usuarios pueden crear multiples colecciones tematicas, no solo "favoritos" |
| **Enriquecimiento con IA** | Generar descripciones, datos curiosos o contexto historico de las imágenes usando OpenAI |
| **Autenticacion** | Registro, login, y que cada usuario tenga sus propias colecciones |

### Diferenciadores (elegir al menos 2)

| Feature | Descripción |
|---------|-------------|
| Comparador de imágenes | Seleccionar 2+ imágenes y ver side-by-side con analisis comparativo generado por IA |
| Timeline interactivo | Visualizar imágenes en una línea de tiempo navegable |
| Exportar coleccion | Generar un PDF o presentacion con las imágenes y descripciones |
| Busqueda semantica | Buscar imágenes por descripcion natural ("mostrame atardeceres en Marte") |
| Sistema de tags | Taggear imágenes manualmente o con sugerencias de IA |

## Requisitos técnicos

### Frontend

- Framework moderno (React, Vue 3, Angular, Svelte)
- Estado global (Redux, Pinia, Zustand, o similar)
- Diseño responsive
- Manejo de estados de carga, error y vacío
- Al menos **un test unitario** de componente

### Backend

- API RESTful o GraphQL
- Autenticación con JWT o sesiones
- Validación de inputs
- Rate limiting básico para proteger las llamadas a APIs externas
- Al menos **un test unitario o de integración**

### Base de datos

- Modelado relacional (PostgreSQL, MySQL, etc.) o documental coherente (MongoDB, Firebase, etc.)
- Migraciones o seeds para facilitar el setup (o scripts para poblar datos iniciales)

### DevOps (bonus)

- Dockerizar la aplicación (`docker-compose` para levantar todo)
- README con arquitectura y decisiones técnicas

## APIs requeridas

| API | Documentación |
|-----|---------------|
| NASA Image and Video Library | https://api.nasa.gov |
| OpenAI GPT | https://platform.openai.com/docs |

> **Nota:** La API de NASA es gratuita y solo requiere una API key que podes obtener en https://api.nasa.gov. Para OpenAI, podes usar el free tier o documentar como se integraria si no tenes acceso.

## Criterios de evaluación

| Aspecto | Peso |
|---------|------|
| Funcionalidad completa | 25% |
| Calidad y claridad del código | 25% |
| Arquitectura y estructura del proyecto | 20% |
| UI/UX y atención al detalle | 15% |
| Testing y documentación | 10% |
| Creatividad y extras | 5% |

## Entrega

Tu Pull Request debe incluir:

- **Código fuente completo** con historial de commits (queremos ver tu proceso)
- **README en tu repo** con:
  - Instrucciones de instalación y ejecución
  - Decisiones técnicas y trade-offs
  - Que harías con más tiempo
- **Deploy funcional** es un plus (Vercel, Railway, Render, etc.)

### Estructura del PR

En la descripción de tu PR, contanos:

1. ¿Qué construiste y por qué tomaste las decisiones que tomaste?
2. ¿Qué diferenciadores elegiste y por qué?
3. ¿Qué mejorías si tuvieras más tiempo?
4. ¿Cualquier cosa que quieras que sepamos antes de revisar?

## Consejos para destacar

- **Commits atomicos y descriptivos** — nos importa ver como pensas, no un solo commit con todo
- **Maneja errores de forma elegante** — tanto en frontend como backend. Los estados vacios y de error son parte de la UX
- **Pensa en la seguridad** — no expongas API keys en el codigo, valida inputs, sanitiza datos
- **Documenta las decisiones tecnicas** — especialmente los trade-offs. "Elegi X porque Y" vale más que la solución perfecta sin explicación
- **Sorprendenos** — que harias diferente si este fuera tu producto?

## Preguntas?

Si algo no esta claro, [abri un issue](https://github.com/mindshoresl/challenge/issues) en este repositorio. Hacer buenas preguntas es una habilidad que valoramos mucho.

Tambien podes escribirnos a **talent@mindshore.io**.

## Sobre MindShore

Somos una empresa de tecnologia con presencia en mas de 12 paises. Trabajamos en proyectos de Data & Analytics, Software Engineering, ERP/CRM e IA aplicada para clientes globales.

Más info en [mindshore.io](https://mindshore.io/) y nuestro [linkedin](https://www.linkedin.com/company/mindshore)


**Buena suerte. Esperamos ver tu talento.**

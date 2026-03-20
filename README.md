Estructura general del proyecto

Nombre: PokTraCo – Travel Companion (Pokedex de viajes)

Dominio: Viajes gamificados, recomendaciones, descubrimiento de destinos.

Objetivos:

Aprender y demostrar habilidades en Python, FastAPI, ML, Docker, Azure y Cloud.

Construir un proyecto explicable, reproducible y demostrable en entrevistas.

Integrar recomendaciones personalizadas y gamificación con datos de usuario.

Practicar producción en Azure, CI/CD, contenedores y pipelines.

Componentes principales:

Backend API: FastAPI + SQLAlchemy + MySQL (CRUD, endpoints de recomendación y discovery).

ML / Recomendación: KNN, Collaborative Filtering, posiblemente embeddings para discovery.

Gamificación / UX: Sistema tipo “Pokedex” con logros y puntuaciones. Streamlit o React.

Contenedores y Cloud: Docker Compose, Azure Container Instances/App Service, CI/CD básico.

Datos: Propios (experiencias personales) + datasets abiertos (destinos, puntuaciones, atributos de viaje).

2️⃣ Roadmap / Plan de 5 semanas (optimizado para portfolio)
Semana	Objetivos	Entregables	Skills / Tecnologías	Tips
1	Entorno y prototipo inicial	- FastAPI “Hello World” contenedorizado
- Endpoint /ping	Python, FastAPI, Docker, Docker Compose	Aprender entorno reproducible, contenedores y despliegue local
2	Modelado de datos y CRUD	- Base MySQL: users, destinations, experiences, attributes
- Endpoints CRUD /destinations, /users	MySQL, SQLAlchemy, FastAPI	Foco en integridad, relaciones y documentación de decisiones de diseño
3	Recomendaciones básicas / ML	- Dataset inicial de destinos y puntuaciones
- Modelo KNN / collaborative filtering
- Endpoint /recommend	Python, scikit-learn, Pandas, FastAPI	Explicar métricas y cómo el modelo aprende preferencias
4	Discovery y gamificación	- Endpoint /discover con filtros y afinidad
- Sistema de desbloqueo de fichas (gamificación)
- Mini-interfaz visual Streamlit/React	FastAPI, Streamlit / React	UX atractivo y demostrable, gamificación funcional aunque básica
5	Optimización y despliegue final	- Consolidación de Docker Compose (backend + MySQL + frontend)
- Deploy a Azure App Service / Container Instances
- Documentación y explicación para portfolio	Docker, Azure, CI/CD, FastAPI	Enfócate en explicar contenedores, despliegue y pipelines; mostrar pipeline reproducible

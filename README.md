<p align="center">
  <img src="assets/portada.png" alt="TRAIDORES · ¿En quién vas a confiar?" width="100%">
</p>

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.traidores.juego"><img src="https://img.shields.io/badge/Google%20Play-Beta%20abierta-3DDC84?style=for-the-badge&logo=googleplay&logoColor=white" alt="Google Play"></a>
  <a href="https://www.traidores.me"><img src="https://img.shields.io/badge/traidores.me-Sitio%20oficial-E8BF45?style=for-the-badge" alt="Sitio oficial"></a>
</p>

# TRAIDORES

Juego móvil de **deducción social** para Android. Cada jugador recibe una carta secreta: de noche los traidores eligen a quién eliminar, de día el pueblo debate, sospecha y vota. Nadie es quien dice ser.

> **Estado:** beta abierta en Google Play · iOS en desarrollo.
> Este repositorio es una **vitrina** del proyecto: capturas, decisiones de diseño y documentación. El código del juego es privado.

## Cómo se juega

1. **Carta secreta.** Cada uno recibe un rol y lo descubre dándolo vuelta.
2. **Noche.** Los Asesinos se ponen de acuerdo en un chat privado y eligen a su víctima. Los roles especiales usan su habilidad.
3. **Amanecer.** Se anuncia quién cayó (o si alguien fue salvado).
4. **Debate.** Todos hablan, acusan y defienden. También hay emotes en la mesa.
5. **Votación.** El pueblo expulsa a un sospechoso y se revela su carta.
6. **Victoria.** Gana el Pueblo si elimina a los traidores, y ganan los Traidores si controlan la aldea.

## Capturas

<p align="center">
  <img src="assets/captura-1.jpg" width="30%" alt="Lobby y selección de mapa">
  <img src="assets/captura-2.jpg" width="30%" alt="Carta secreta revelada">
  <img src="assets/captura-3.jpg" width="30%" alt="Chat privado de los asesinos">
</p>
<p align="center">
  <img src="assets/captura-4.jpg" width="30%" alt="Debate del pueblo">
  <img src="assets/captura-5.jpg" width="30%" alt="Votación">
  <img src="assets/captura-6.jpg" width="30%" alt="Victoria con roles revelados">
</p>

## Tráiler

<a href="https://www.traidores.me">
  <img src="assets/trailer-poster.jpg" width="260" alt="Ver el tráiler en traidores.me">
</a>

## Mapas y roles

Tres mapas (**Pampa**, **Grecia** y **Medieval**), cada uno con su ambientación. Desde 8 jugadores aparecen **roles propios de cada mapa** con una jugabilidad distinta, como el **Payador** y el **Oráculo**, además del **Bufón**, que gana de una forma especial.

<p align="center">
  <img src="assets/roles.png" width="70%" alt="Roles del juego">
</p>

## Lo técnico

| Área | Tecnologías |
|---|---|
| App | Kotlin, Android |
| Backend | Firebase: Authentication, Cloud Firestore, Realtime Database, Cloud Functions, Storage |
| Calidad | Crashlytics, Analytics, pruebas unitarias |
| Servicios | Google Play Games, Cloud Messaging, AdMob con consentimiento (UMP), Play Billing |
| Web | HTML, CSS y JavaScript, desplegada en Vercel |

Algunas decisiones de diseño:
- **Partidas online resistentes:** el juego sigue avanzando aunque un teléfono se trabe o se caiga.
- **Bots con chat propio**, para poder jugar una partida completa sin otras personas.
- **Información secreta:** cada jugador solo recibe los datos de su propio rol.
- **Privacidad:** política publicada, cuenta eliminable desde la app y declaraciones de Google Play alineadas con lo que realmente hace la app.

## Documentación

Historias de usuario, análisis y diseño, diagramas de secuencia y de estados, DER y mapeo ORM: [Documentacion-Proyecto-Objetos](https://github.com/nachogimenez7/Documentacion-Proyecto-Objetos).

## Autor

**Ignacio Giménez** · estudiante de Desarrollo de Software · [LinkedIn](https://www.linkedin.com/in/ignaciogimenez7) · [traidores.me](https://www.traidores.me)

Hecho en Argentina por **Bandido Games** 🇦🇷

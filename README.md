# vvoltaire
**Full-stack engineer. Exploring real-time graphics, generative systems, and interactive simulation.**

Currently at Manulife / John Hancock.  
CS + Data Science @ Oberlin College.

[LinkedIn ↗](https://www.linkedin.com/in/vvoltaire/) &nbsp;·&nbsp; [Portfolio ↗](https://vvoltaire-portfolio.vercel.app/)

---

## Projects

### ✦ Fragment &nbsp;`in progress`
A platform for writing, sharing, and remixing GLSL shaders in the browser.  
Write shaders in a live editor with an instant WebGL preview, save them to your profile, fork other people's work, and browse a public gallery. Each saved shader gets a thumbnail rendered automatically by a background job. Includes raymarching templates for building 3D scenes from signed distance functions.  
`Next.js` `TypeScript` `Node.js` `PostgreSQL` `WebGL` `GLSL`

### ✦ Path Tracer &nbsp;`in progress`
A physically based path tracer written from scratch in C++.  
Renders realistic images by simulating how light bounces through a scene, with diffuse, metal, and glass materials. Uses multithreading and a bounding volume hierarchy (BVH) to speed up rendering, with benchmarks on render time.  
`C++` `Multithreading` `CMake`

### ✦ Interactive Ocean Portfolio &nbsp;`live`
A 3D portfolio set on an interactive ocean horizon, with a simulated water surface and dynamic sky.  
Projects float on the water as draggable objects, with a standard scrollable portfolio underneath for accessibility.  
`Three.js` `React` `Vite` `GLSL` `Tailwind`  
[View site ↗](https://vvoltaire-portfolio.vercel.app/)

### Render Farm `upcoming`

A distributed rendering system for my [C++ path tracer](https://github.com/vvoltaire/path-tracer).

**Planned:**
- Coordinator service that splits renders into tiles and schedules them across workers
- Worker heartbeats and lease-based reassignment when a worker fails
- Autoscaling workers on Kubernetes based on queue depth
- Live dashboard showing tiles completing in real time
- Benchmarks of render time across 1, 4, and 16 workers

Development starts once the path tracer is complete.
---

## Stack

`TypeScript` `JavaScript` `Python` `Java` `C++` `SQL` `GLSL`  
`React` `Next.js` `Node.js` `Spring Boot` `Three.js` `WebGL`  
`PostgreSQL` `Snowflake` `REST APIs` `Docker` `Git` `Figma`

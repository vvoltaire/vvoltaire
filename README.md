# vvoltaire
**Full-stack engineer. Exploring real-time graphics, generative systems, and interactive simulation.**

Currently at Manulife / John Hancock.  
CS + Data Science @ Oberlin College.

[LinkedIn ↗](https://www.linkedin.com/in/vvoltaire/) &nbsp;·&nbsp; [Portfolio ↗](https://vinsline-dev.vercel.app/)

---

## Projects

### ✦ vinsline.dev &nbsp;`live`
My personal site, with an interactive 3D laptop in the hero, light and dark themes, and a hobbies section with small interactive pieces.  
Built as a single scrolling page covering projects, experience, and life outside of code.  
`Next.js` `TypeScript` `React Three Fiber` `Three.js` `Tailwind`  
[View site ↗](https://vinsline-dev.vercel.app) &nbsp;·&nbsp; [Code ↗](https://github.com/vvoltaire/vinsline.dev)

<p>
  <img src="https://github.com/user-attachments/assets/9a29d633-50a9-420b-b079-b0ceeb187efe" width="49%" alt="vinsline.dev in light mode">
  <img src="https://github.com/user-attachments/assets/fca78d5d-f6b2-444c-a1cf-1f016dbe8019" width="49%" alt="vinsline.dev in dark mode">
</p>

![The hero: a 3D laptop boots up and types "access granted" next to my name](PASTE-GIF-LINK)

| Dark mode (default) | Light mode |
| :---: | :---: |
| ![The site in dark mode, the default](PASTE-DARK-SCREENSHOT) | ![The site in light mode](PASTE-LIGHT-SCREENSHOT) |


### ✦ Fragment &nbsp;`in progress`
A platform for writing, sharing, and remixing GLSL shaders in the browser.  
Write shaders in a live editor with an instant WebGL preview, save them to your profile, fork other people's work, and browse a public gallery. Each saved shader gets a thumbnail rendered automatically by a background job. Includes raymarching templates for building 3D scenes from signed distance functions.  
`Next.js` `TypeScript` `Node.js` `PostgreSQL` `WebGL` `GLSL`
&nbsp;[Code ↗](https://github.com/vvoltaire/fragment)

### ✦ Path Tracer &nbsp;`in progress`
A physically based path tracer written from scratch in C++.  
Renders realistic images by simulating how light bounces through a scene, with diffuse, metal, and glass materials. Uses multithreading and a bounding volume hierarchy (BVH) to speed up rendering, with benchmarks on render time.  
`C++` `Multithreading` `CMake`
&nbsp;[Code ↗](https://github.com/vvoltaire/path-tracer)

### ✦ Render Farm &nbsp;`upcoming`
A distributed rendering system that splits path tracer jobs into tiles and runs them across a scalable pool of workers.  
A coordinator schedules tiles, tracks worker heartbeats, and reassigns work when a worker fails, then stitches the results into the final image or animation. Workers autoscale on Kubernetes based on queue depth.  
`Java` `Spring Boot` `C++` `PostgreSQL` `Docker` `Kubernetes`
&nbsp;[Code ↗](https://github.com/vvoltaire/render-farm)

---

## Stack

`TypeScript` `JavaScript` `Python` `Java` `C++` `SQL` `GLSL`  
`React` `Next.js` `Node.js` `Spring Boot` `Three.js` `WebGL`  
`PostgreSQL` `Snowflake` `REST APIs` `Docker` `Kubernetes` `Git` `Figma`

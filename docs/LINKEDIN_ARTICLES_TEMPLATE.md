# Template para Agregar Artículos de LinkedIn

Este archivo contiene un template que puedes usar para agregar tus artículos de LinkedIn a la página de artículos.

## Cómo Agregar un Artículo de LinkedIn

1. Ve a tu perfil de LinkedIn: https://www.linkedin.com/in/maximiliano-gregorio-pizarro-consultor-it/recent-activity/articles/
2. Copia la URL del artículo específico
3. Copia el título y descripción del artículo
4. Reemplaza el template en `docs/articles.md`

## Template HTML

```html
<article class="article-card linkedin-article">
    <div class="article-icon" style="color: #0077B5;">
        <svg width="48" height="48" viewBox="0 0 24 24" fill="currentColor">
            <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
        </svg>
    </div>
    <h3 class="article-title">TÍTULO DEL ARTÍCULO</h3>
    <p class="article-description">
        Descripción breve del artículo. Reemplaza esto con la descripción real de tu artículo de LinkedIn.
    </p>
    <div class="article-tags">
        <span class="tag">OpenShift</span>
        <span class="tag">Red Hat</span>
        <span class="tag">Cloud Native</span>
        <!-- Agrega más tags según corresponda -->
    </div>
    <a href="URL_DEL_ARTÍCULO_EN_LINKEDIN" class="article-link" target="_blank" rel="noopener noreferrer">
        Read on LinkedIn →
    </a>
</article>
```

## Ejemplo Completo

```html
<article class="article-card linkedin-article">
    <div class="article-icon" style="color: #0077B5;">
        <svg width="48" height="48" viewBox="0 0 24 24" fill="currentColor">
            <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
        </svg>
    </div>
    <h3 class="article-title">Getting Started with Red Hat OpenShift</h3>
    <p class="article-description">
        A comprehensive guide to deploying applications on Red Hat OpenShift, covering containerization, CI/CD pipelines, and best practices for cloud-native development.
    </p>
    <div class="article-tags">
        <span class="tag">OpenShift</span>
        <span class="tag">Kubernetes</span>
        <span class="tag">CI/CD</span>
        <span class="tag">Red Hat</span>
    </div>
    <a href="https://www.linkedin.com/pulse/your-article-slug" class="article-link" target="_blank" rel="noopener noreferrer">
        Read on LinkedIn →
    </a>
</article>
```

## Tags Comunes

Puedes usar estos tags según el tema del artículo:

- `OpenShift`
- `Kubernetes`
- `Red Hat`
- `Docker`
- `Podman`
- `Helm`
- `Ansible`
- `CI/CD`
- `GitOps`
- `DevOps`
- `Cloud Native`
- `Security`
- `OIDC`
- `Application Platform`
- `Java`
- `Spring Boot`
- `Node.js`
- `Python`

## Notas

- Cada artículo debe tener su propia URL de LinkedIn
- La descripción debe ser breve (2-3 líneas)
- Los tags ayudan a categorizar los artículos
- Todos los enlaces se abren en una nueva pestaña (`target="_blank"`)


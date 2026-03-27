---
layout: default
title: Home
description: Specialist Solution Architect at Red Hat LATAM | OpenShift | Application Platform | Cloud Native Technologies
---

<div class="hero-section">
    <div class="container">
        <div class="hero-content">
            <div class="hero-avatar">
                <img src="{{ '/assets/images/max-avatar.png' | relative_url }}" 
                     alt="Maximiliano Pizarro" 
                     class="avatar-image"
                     loading="eager">
            </div>
            <div class="hero-text">
                <h1 class="hero-title">Hi 👋, I'm <span class="highlight">Maximiliano Pizarro</span></h1>
                <p class="hero-subtitle">{{ site.author.title }} at <strong>{{ site.author.company }}</strong></p>
                <p class="hero-description">
                    Passionate about cloud-native technologies, containerization, and enterprise solutions. 
                    Specializing in Red Hat OpenShift, Application Platform, and DevOps practices.
                </p>
                <div class="hero-cta">
                    <a href="https://www.linkedin.com/in/{{ site.social.linkedin }}" class="btn btn-primary" target="_blank" rel="noopener noreferrer">
                        Connect on LinkedIn
                    </a>
                    <a href="https://github.com/{{ site.social.github }}" class="btn btn-secondary" target="_blank" rel="noopener noreferrer">
                        View GitHub
                    </a>
                </div>
            </div>
        </div>
    </div>
</div>

<section class="tech-stack">
    <div class="container">
        <h2 class="section-title">Technologies & Tools</h2>
        <div class="tech-badges">
            <span class="tech-badge">Red Hat</span>
            <span class="tech-badge">OpenShift</span>
            <span class="tech-badge">Kubernetes</span>
            <span class="tech-badge">Docker</span>
            <span class="tech-badge">Podman</span>
            <span class="tech-badge">Helm</span>
            <span class="tech-badge">Ansible</span>
            <span class="tech-badge">Jenkins</span>
            <span class="tech-badge">GitOps</span>
            <span class="tech-badge">Java</span>
            <span class="tech-badge">Spring Boot</span>
            <span class="tech-badge">Node.js</span>
            <span class="tech-badge">Python</span>
            <span class="tech-badge">TypeScript</span>
            <span class="tech-badge">PostgreSQL</span>
            <span class="tech-badge">MongoDB</span>
        </div>
    </div>
</section>

<section class="articles-section">
    <div class="container">
        <h2 class="section-title">Featured Articles & Projects</h2>
        <p class="section-description">
            Explore my articles and workshops on Red Hat technologies, OpenShift, and Application Platform solutions.
        </p>
        
        <div class="articles-grid">
            <article class="article-card">
                <div class="article-icon">
                    <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"></path>
                    </svg>
                </div>
                <h3 class="article-title">Showroom Docs MCP Server</h3>
                <p class="article-description">
                    Quarkus MCP Server for OpenShift Lightspeed. Indexes 46 documents from Red Hat products and the "IA Development From Zero To Hero" workshop, exposing 4 MCP tools for intelligent documentation via chat.
                </p>
                <div class="article-tags">
                    <span class="tag">MCP</span>
                    <span class="tag">Quarkus</span>
                    <span class="tag">OpenShift Lightspeed</span>
                    <span class="tag">Helm</span>
                </div>
                <a href="https://maximilianopizarro.github.io/showroom-docs-mcp/" class="article-link" target="_blank" rel="noopener noreferrer">
                    Read Article →
                </a>
            </article>

            <article class="article-card">
                <div class="article-icon">
                    <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <rect x="3" y="11" width="18" height="11" rx="2" ry="2"></rect>
                        <path d="M7 11V7a5 5 0 0 1 10 0v4"></path>
                    </svg>
                </div>
                <h3 class="article-title">RHBK + Data Grid — High Availability</h3>
                <p class="article-description">
                    Helm chart for Red Hat Build of Keycloak (RHBK) in High Availability mode with Red Hat Data Grid as external distributed cache and PostgreSQL. JGroups clustering with jdbc-ping and DNS_PING discovery.
                </p>
                <div class="article-tags">
                    <span class="tag">RHBK</span>
                    <span class="tag">Data Grid</span>
                    <span class="tag">High Availability</span>
                    <span class="tag">Helm</span>
                </div>
                <a href="https://maximilianopizarro.github.io/rhbk-datagrid-sample/" class="article-link" target="_blank" rel="noopener noreferrer">
                    Read Article →
                </a>
            </article>

            <article class="article-card">
                <div class="article-icon">
                    <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"></path>
                    </svg>
                </div>
                <h3 class="article-title">RHBK NeuroFace Biometric Flow</h3>
                <p class="article-description">
                    Red Hat Build of Keycloak with biometric facial recognition authentication via NeuroFace. Delegated user creation, webcam enrollment, and 2FA facial verification — deployed with a single Helm install on OpenShift.
                </p>
                <div class="article-tags">
                    <span class="tag">RHBK 26.0</span>
                    <span class="tag">Keycloak SPI</span>
                    <span class="tag">Facial 2FA</span>
                    <span class="tag">OpenShift</span>
                </div>
                <a href="https://maximilianopizarro.github.io/rhbk-biometric-flow/" class="article-link" target="_blank" rel="noopener noreferrer">
                    Read Article →
                </a>
            </article>

            <article class="article-card">
                <div class="article-icon">
                    <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <rect x="3" y="11" width="18" height="11" rx="2" ry="2"></rect>
                        <path d="M7 11V7a5 5 0 0 1 10 0v4"></path>
                    </svg>
                </div>
                <h3 class="article-title">Build a zero trust environment with Red Hat Connectivity Link</h3>
                <p class="article-description">
                    This guide shows how to build a zero trust environment using Red Hat Connectivity Link and OpenShift GitOps, managing secure connectivity between services, gateways, and identity providers with the NeuralBank application.
                </p>
                <div class="article-tags">
                    <span class="tag">Zero Trust</span>
                    <span class="tag">Connectivity Link</span>
                    <span class="tag">GitOps</span>
                    <span class="tag">OpenShift</span>
                </div>
                <a href="https://developers.redhat.com/articles/2026/02/12/build-zero-trust-environment-red-hat-connectivity-link" class="article-link" target="_blank" rel="noopener noreferrer">
                    Read on Red Hat Developer →
                </a>
            </article>

            <article class="article-card">
                <div class="article-icon">
                    <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <polyline points="22 12 18 12 15 21 9 3 6 12 2 12"></polyline>
                    </svg>
                </div>
                <h3 class="article-title">Manage AI resource use with TokenRateLimitPolicy</h3>
                <p class="article-description">
                    Introduces TokenRateLimitPolicy for limiting rates based on token consumption in LLM APIs, enabling fair use and cost management beyond request-based rate limiting.
                </p>
                <div class="article-tags">
                    <span class="tag">TokenRateLimitPolicy</span>
                    <span class="tag">LLM</span>
                    <span class="tag">Rate Limiting</span>
                    <span class="tag">Red Hat</span>
                </div>
                <a href="https://developers.redhat.com/articles/2026/02/18/manage-ai-resource-use-tokenratelimitpolicy" class="article-link" target="_blank" rel="noopener noreferrer">
                    Read on Red Hat Developer →
                </a>
            </article>

            <article class="article-card">
                <div class="article-icon">
                    <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 2L2 7l10 5 10-5-10-5z"></path>
                        <path d="M2 17l10 5 10-5"></path>
                        <path d="M2 12l10 5 10-5"></path>
                    </svg>
                </div>
                <h3 class="article-title">RHOAI Roadshow: From Zero To Hero</h3>
                <p class="article-description">
                    Complete journey working with the Red Hat team to build and deploy a demo showcasing Red Hat OpenShift AI (RHOAI) capabilities and integration with OpenShift.
                </p>
                <div class="article-tags">
                    <span class="tag">RHOAI</span>
                    <span class="tag">OpenShift</span>
                    <span class="tag">AI/ML</span>
                    <span class="tag">Red Hat</span>
                </div>
                <a href="https://maximilianopizarro.github.io/rhoai-roadshow-from-zero-to-hero/#/" class="article-link" target="_blank" rel="noopener noreferrer">
                    Read Article →
                </a>
            </article>

            <article class="article-card">
                <div class="article-icon">
                    <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <rect x="2" y="5" width="20" height="14" rx="2"></rect>
                        <line x1="2" y1="10" x2="22" y2="10"></line>
                    </svg>
                </div>
                <h3 class="article-title">NFL Stadium Wallet</h3>
                <p class="article-description">
                    Centralized digital wallet for NFL stadiums. Pay, load balance, and manage money at Buffalo Bills and Las Vegas Raiders venues. Vue 3 + .NET 8 APIs, Helm chart, Connectivity Link, and Dev Spaces.
                </p>
                <div class="article-tags">
                    <span class="tag">OpenShift</span>
                    <span class="tag">Helm</span>
                    <span class="tag">Connectivity Link</span>
                    <span class="tag">Kubernetes</span>
                </div>
                <a href="https://maximilianopizarro.github.io/NFL-Wallet/" class="article-link" target="_blank" rel="noopener noreferrer">
                    Read Article →
                </a>
            </article>

            <article class="article-card">
                <div class="article-icon">
                    <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"></path>
                    </svg>
                </div>
                <h3 class="article-title">Red Hat Chat</h3>
                <p class="article-description">
                    AI Conversations with Red Hat Design System. Deploy locally with Podman or on OpenShift using container images from Quay.io.
                </p>
                <div class="article-tags">
                    <span class="tag">OpenShift</span>
                    <span class="tag">Podman</span>
                    <span class="tag">AI</span>
                    <span class="tag">Red Hat</span>
                </div>
                <a href="https://maximilianopizarro.github.io/LibreChat-RedHat/" class="article-link" target="_blank" rel="noopener noreferrer">
                    Read Article →
                </a>
            </article>

            <article class="article-card">
                <div class="article-icon">
                    <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <rect x="3" y="11" width="18" height="11" rx="2" ry="2"></rect>
                        <path d="M7 11V7a5 5 0 0 1 10 0v4"></path>
                    </svg>
                </div>
                <h3 class="article-title">Connectivity Link</h3>
                <p class="article-description">
                    Security Microservice with Connectivity Link using OpenID Connect (OIDC). Zero Trust Architecture with OpenShift GitOps.
                </p>
                <div class="article-tags">
                    <span class="tag">Security</span>
                    <span class="tag">OIDC</span>
                    <span class="tag">GitOps</span>
                    <span class="tag">OpenShift</span>
                </div>
                <a href="https://maximilianopizarro.github.io/connectivity-link/" class="article-link" target="_blank" rel="noopener noreferrer">
                    Read Article →
                </a>
            </article>

            <article class="article-card">
                <div class="article-icon">
                    <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <polyline points="22 12 18 12 15 21 9 3 6 12 2 12"></polyline>
                    </svg>
                </div>
                <h3 class="article-title">Workshop OpenShift Pipelines</h3>
                <p class="article-description">
                    Helm Chart example on Red Hat OpenShift. Learn CI/CD practices with OpenShift Pipelines and GitOps workflows.
                </p>
                <div class="article-tags">
                    <span class="tag">Pipelines</span>
                    <span class="tag">Helm</span>
                    <span class="tag">CI/CD</span>
                    <span class="tag">OpenShift</span>
                </div>
                <a href="https://maximilianopizarro.github.io/workshop-pipelines/" class="article-link" target="_blank" rel="noopener noreferrer">
                    Read Article →
                </a>
            </article>

            <article class="article-card">
                <div class="article-icon">
                    <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"></path>
                        <polyline points="14 2 14 8 20 8"></polyline>
                        <line x1="16" y1="13" x2="8" y2="13"></line>
                        <line x1="16" y1="17" x2="8" y2="17"></line>
                        <polyline points="10 9 9 9 8 9"></polyline>
                    </svg>
                </div>
                <h3 class="article-title">Stadium Wallet — Complete Documentation</h3>
                <p class="article-description">
                    Official installation, testing and architecture guide. Complete digital wallet ecosystem for stadiums on Red Hat OpenShift with GitOps, OSSM3 Ambient Mode, Connectivity Link and Red Hat Developer Hub.
                </p>
                <div class="article-tags">
                    <span class="tag">OpenShift</span>
                    <span class="tag">GitOps</span>
                    <span class="tag">Connectivity Link</span>
                    <span class="tag">OSSM3</span>
                </div>
                <a href="https://maximilianopizarro.github.io/stadium-wallet/" class="article-link" target="_blank" rel="noopener noreferrer">
                    Read Article →
                </a>
            </article>

            <article class="article-card">
                <div class="article-icon">
                    <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <circle cx="12" cy="12" r="10"></circle>
                        <line x1="2" y1="12" x2="22" y2="12"></line>
                        <path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"></path>
                    </svg>
                </div>
                <h3 class="article-title">NFL Wallet GitOps</h3>
                <p class="article-description">
                    GitOps repository and deployment configurations for Stadium Wallet. Argo CD Applications, Kustomize overlays, and multi-cluster setup with ACM.
                </p>
                <div class="article-tags">
                    <span class="tag">GitOps</span>
                    <span class="tag">Argo CD</span>
                    <span class="tag">Kustomize</span>
                    <span class="tag">OpenShift</span>
                </div>
                <a href="https://maximilianopizarro.github.io/nfl-wallet-gitops/" class="article-link" target="_blank" rel="noopener noreferrer">
                    Read Article →
                </a>
            </article>
        </div>
        
        <div style="text-align: center; margin-top: 3rem;">
            <a href="{{ '/articles' | relative_url }}" class="btn btn-secondary">
                View All Articles →
            </a>
        </div>
    </div>
</section>

<section class="achievements-section">
    <div class="container">
        <h2 class="section-title">Certifications & Achievements</h2>
        <div class="achievements-grid">
            <a href="https://www.credly.com/users/maximiliano-pizarro/badges" class="achievement-card" target="_blank" rel="noopener noreferrer">
                <div class="achievement-icon">🏆</div>
                <h3>Credly Badges</h3>
                <p>View verified achievements</p>
            </a>
            <a href="https://learn.redhat.com/t5/user/viewprofilepage/user-id/120782" class="achievement-card" target="_blank" rel="noopener noreferrer">
                <div class="achievement-icon">📚</div>
                <h3>Red Hat Learning</h3>
                <p>Learning Community</p>
            </a>
            <a href="https://learn.microsoft.com/es-mx/users/maximilianopizarro/" class="achievement-card" target="_blank" rel="noopener noreferrer">
                <div class="achievement-icon">🔷</div>
                <h3>Microsoft Learn</h3>
                <p>Training & Certifications</p>
            </a>
            <a href="https://cloudskillsboost.google/public_profiles/d7bb8358-dd83-4da2-8e22-245bb87fb4de/" class="achievement-card" target="_blank" rel="noopener noreferrer">
                <div class="achievement-icon">☁️</div>
                <h3>Google Cloud</h3>
                <p>Cloud Skills Boost</p>
            </a>
            <a href="https://openprofile.dev/profile/maximilianopizarro" class="achievement-card" target="_blank" rel="noopener noreferrer">
                <div class="achievement-icon">👨‍💻</div>
                <h3>OpenProfile</h3>
                <p>Developer Profile</p>
            </a>
        </div>
    </div>
</section>

<section id="artifact-hub" class="artifact-hub-section">
    <div class="container">
        <h2 class="section-title">Artifact Hub Repositories</h2>
        <p class="section-description">
            Helm Charts and Kubernetes packages published on Artifact Hub for easy deployment on OpenShift and Kubernetes.
        </p>
        
        <div class="artifact-grid">
            <a href="https://artifacthub.io/packages/helm/showroom-docs-mcp/showroom-docs-mcp" class="artifact-card" target="_blank" rel="noopener noreferrer">
                <div class="artifact-icon">
                    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 2L2 7l10 5 10-5-10-5z"></path>
                        <path d="M2 17l10 5 10-5"></path>
                        <path d="M2 12l10 5 10-5"></path>
                    </svg>
                </div>
                <h3 class="artifact-title">Showroom Docs MCP</h3>
                <div class="artifact-badge">
                    <img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/showroom-docs-mcp" alt="Showroom Docs MCP">
                </div>
                <p class="artifact-description">Quarkus MCP Server for OpenShift Lightspeed — 46 indexed documents, 4 MCP tools</p>
            </a>

            <a href="https://artifacthub.io/packages/helm/rhbk-datagrid/rhbk-datagrid" class="artifact-card" target="_blank" rel="noopener noreferrer">
                <div class="artifact-icon">
                    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 2L2 7l10 5 10-5-10-5z"></path>
                        <path d="M2 17l10 5 10-5"></path>
                        <path d="M2 12l10 5 10-5"></path>
                    </svg>
                </div>
                <h3 class="artifact-title">RHBK Data Grid</h3>
                <div class="artifact-badge">
                    <img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/rhbk-datagrid" alt="RHBK Data Grid">
                </div>
                <p class="artifact-description">RHBK High Availability with Red Hat Data Grid and PostgreSQL Helm Chart</p>
            </a>

            <a href="https://artifacthub.io/packages/helm/rhbk-neuroface/rhbk-neuroface" class="artifact-card" target="_blank" rel="noopener noreferrer">
                <div class="artifact-icon">
                    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 2L2 7l10 5 10-5-10-5z"></path>
                        <path d="M2 17l10 5 10-5"></path>
                        <path d="M2 12l10 5 10-5"></path>
                    </svg>
                </div>
                <h3 class="artifact-title">RHBK NeuroFace</h3>
                <div class="artifact-badge">
                    <img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/rhbk-neuroface" alt="RHBK NeuroFace">
                </div>
                <p class="artifact-description">RHBK + NeuroFace biometric authentication Helm Chart for OpenShift</p>
            </a>

            <a href="https://artifacthub.io/packages/helm/neuroface/neuroface" class="artifact-card" target="_blank" rel="noopener noreferrer">
                <div class="artifact-icon">
                    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 2L2 7l10 5 10-5-10-5z"></path>
                        <path d="M2 17l10 5 10-5"></path>
                        <path d="M2 12l10 5 10-5"></path>
                    </svg>
                </div>
                <h3 class="artifact-title">NeuroFace</h3>
                <div class="artifact-badge">
                    <img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/neuroface" alt="NeuroFace">
                </div>
                <p class="artifact-description">NeuroFace facial recognition service Helm Chart — FastAPI + Angular 17</p>
            </a>

            <a href="https://artifacthub.io/packages/helm/jhipster-online/jhipster-online" class="artifact-card" target="_blank" rel="noopener noreferrer">
                <div class="artifact-icon">
                    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 2L2 7l10 5 10-5-10-5z"></path>
                        <path d="M2 17l10 5 10-5"></path>
                        <path d="M2 12l10 5 10-5"></path>
                    </svg>
                </div>
                <h3 class="artifact-title">JHipster Online</h3>
                <div class="artifact-badge">
                    <img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/jhipster-online" alt="JHipster Online">
                </div>
                <p class="artifact-description">JHipster Online Helm Chart for Kubernetes and OpenShift</p>
            </a>

            <a href="https://artifacthub.io/packages/helm/nfl-wallet/nfl-wallet" class="artifact-card" target="_blank" rel="noopener noreferrer">
                <div class="artifact-icon">
                    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 2L2 7l10 5 10-5-10-5z"></path>
                        <path d="M2 17l10 5 10-5"></path>
                        <path d="M2 12l10 5 10-5"></path>
                    </svg>
                </div>
                <h3 class="artifact-title">NFL Wallet</h3>
                <div class="artifact-badge">
                    <img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/nfl-wallet" alt="NFL Wallet">
                </div>
                <p class="artifact-description">Stadium Wallet Helm Chart for OpenShift and Kubernetes — Vue 3, .NET 8, Connectivity Link</p>
            </a>

            <a href="https://artifacthub.io/packages/search?repo=botpress" class="artifact-card" target="_blank" rel="noopener noreferrer">
                <div class="artifact-icon">
                    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 2L2 7l10 5 10-5-10-5z"></path>
                        <path d="M2 17l10 5 10-5"></path>
                        <path d="M2 12l10 5 10-5"></path>
                    </svg>
                </div>
                <h3 class="artifact-title">Botpress</h3>
                <div class="artifact-badge">
                    <img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/botpress" alt="Botpress">
                </div>
                <p class="artifact-description">Botpress Helm Chart repository</p>
            </a>

            <a href="https://artifacthub.io/packages/search?repo=oracle-helm-charts" class="artifact-card" target="_blank" rel="noopener noreferrer">
                <div class="artifact-icon">
                    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 2L2 7l10 5 10-5-10-5z"></path>
                        <path d="M2 17l10 5 10-5"></path>
                        <path d="M2 12l10 5 10-5"></path>
                    </svg>
                </div>
                <h3 class="artifact-title">Oracle Helm Charts</h3>
                <div class="artifact-badge">
                    <img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/oracle-helm-charts" alt="Oracle Helm Charts">
                </div>
                <p class="artifact-description">Oracle database and middleware Helm Charts</p>
            </a>

            <a href="https://artifacthub.io/packages/search?repo=workshop-pipelines" class="artifact-card" target="_blank" rel="noopener noreferrer">
                <div class="artifact-icon">
                    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 2L2 7l10 5 10-5-10-5z"></path>
                        <path d="M2 17l10 5 10-5"></path>
                        <path d="M2 12l10 5 10-5"></path>
                    </svg>
                </div>
                <h3 class="artifact-title">Workshop Pipelines</h3>
                <div class="artifact-badge">
                    <img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/workshop-pipelines" alt="Workshop Pipelines">
                </div>
                <p class="artifact-description">OpenShift Pipelines workshop Helm Charts</p>
            </a>

            <a href="https://artifacthub.io/packages/search?repo=librechat-openshift" class="artifact-card" target="_blank" rel="noopener noreferrer">
                <div class="artifact-icon">
                    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 2L2 7l10 5 10-5-10-5z"></path>
                        <path d="M2 17l10 5 10-5"></path>
                        <path d="M2 12l10 5 10-5"></path>
                    </svg>
                </div>
                <h3 class="artifact-title">LibreChat OpenShift</h3>
                <div class="artifact-badge">
                    <img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/librechat-openshift" alt="LibreChat OpenShift">
                </div>
                <p class="artifact-description">LibreChat deployment for Red Hat OpenShift</p>
            </a>

            <a href="https://artifacthub.io/packages/search?repo=fineract-openshift" class="artifact-card" target="_blank" rel="noopener noreferrer">
                <div class="artifact-icon">
                    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 2L2 7l10 5 10-5-10-5z"></path>
                        <path d="M2 17l10 5 10-5"></path>
                        <path d="M2 12l10 5 10-5"></path>
                    </svg>
                </div>
                <h3 class="artifact-title">Fineract OpenShift</h3>
                <div class="artifact-badge">
                    <img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/fineract-openshift" alt="Fineract OpenShift">
                </div>
                <p class="artifact-description">Apache Fineract for OpenShift deployment</p>
            </a>

            <a href="https://artifacthub.io/packages/helm/mattermost-team-edition/mattermost-team-edition" class="artifact-card" target="_blank" rel="noopener noreferrer">
                <div class="artifact-icon">
                    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 2L2 7l10 5 10-5-10-5z"></path>
                        <path d="M2 17l10 5 10-5"></path>
                        <path d="M2 12l10 5 10-5"></path>
                    </svg>
                </div>
                <h3 class="artifact-title">Mattermost Team Edition</h3>
                <div class="artifact-badge">
                    <img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/mattermost-team-edition" alt="Mattermost Team Edition">
                </div>
                <p class="artifact-description">Mattermost team collaboration platform for OpenShift</p>
            </a>

            <a href="https://artifacthub.io/packages/search?repo=n8n-openshift" class="artifact-card" target="_blank" rel="noopener noreferrer">
                <div class="artifact-icon">
                    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 2L2 7l10 5 10-5-10-5z"></path>
                        <path d="M2 17l10 5 10-5"></path>
                        <path d="M2 12l10 5 10-5"></path>
                    </svg>
                </div>
                <h3 class="artifact-title">n8n OpenShift</h3>
                <div class="artifact-badge">
                    <img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/n8n-openshift" alt="n8n OpenShift">
                </div>
                <p class="artifact-description">n8n workflow automation platform for OpenShift</p>
            </a>
        </div>
        
        <div style="text-align: center; margin-top: 2rem;">
            <a href="https://artifacthub.io" class="btn btn-secondary" target="_blank" rel="noopener noreferrer">
                Explore Artifact Hub →
            </a>
        </div>
    </div>
</section>

<section id="videos" class="videos-section">
    <div class="container">
        <h2 class="section-title">Video Content</h2>
        <p class="section-description">
            Watch tutorials, demos, and presentations on Red Hat OpenShift, cloud-native technologies, and DevOps practices.
        </p>
        
        <div class="videos-grid">
            <div class="video-item">
                <div class="video-wrapper">
                    <iframe 
                        src="https://www.youtube.com/embed/_PcsflxvJWY" 
                        title="RHBK NeuroFace — Biometric Authentication Flow" 
                        frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                        allowfullscreen>
                    </iframe>
                </div>
            </div>

            <div class="video-item">
                <div class="video-wrapper">
                    <iframe 
                        src="https://www.youtube.com/embed/lvFu5u7slXg" 
                        title="NeuroFace — Facial Recognition in Action" 
                        frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                        allowfullscreen>
                    </iframe>
                </div>
            </div>

            <div class="video-item">
                <div class="video-wrapper">
                    <iframe 
                        src="https://www.youtube.com/embed/YXOaY-pXajE" 
                        title="YouTube video player" 
                        frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                        allowfullscreen>
                    </iframe>
                </div>
            </div>

            <div class="video-item">
                <div class="video-wrapper">
                    <iframe 
                        src="https://www.youtube.com/embed/Bo3ZKwXQKI4" 
                        title="YouTube video player" 
                        frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                        allowfullscreen>
                    </iframe>
                </div>
            </div>

            <div class="video-item">
                <div class="video-wrapper">
                    <iframe 
                        src="https://www.youtube.com/embed/OpmKvai22BQ" 
                        title="YouTube video player" 
                        frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                        allowfullscreen>
                    </iframe>
                </div>
            </div>

            <div class="video-item">
                <div class="video-wrapper">
                    <iframe 
                        src="https://www.youtube.com/embed/428x2gyuRG0" 
                        title="YouTube video player" 
                        frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                        allowfullscreen>
                    </iframe>
                </div>
            </div>

            <div class="video-item">
                <div class="video-wrapper">
                    <iframe 
                        src="https://www.youtube.com/embed/m11wvN2-d1Y" 
                        title="YouTube video player" 
                        frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                        allowfullscreen>
                    </iframe>
                </div>
            </div>

            <div class="video-item">
                <div class="video-wrapper">
                    <iframe 
                        src="https://www.youtube.com/embed/b7xbcTAGNIQ" 
                        title="YouTube video player" 
                        frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                        allowfullscreen>
                    </iframe>
                </div>
            </div>

            <div class="video-item">
                <div class="video-wrapper">
                    <iframe 
                        src="https://www.youtube.com/embed/1GScYbnaixI" 
                        title="YouTube video player" 
                        frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                        allowfullscreen>
                    </iframe>
                </div>
            </div>

            <div class="video-item">
                <div class="video-wrapper">
                    <iframe 
                        src="https://www.youtube.com/embed/qi4WPiWuGbQ" 
                        title="YouTube video player" 
                        frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                        allowfullscreen>
                    </iframe>
                </div>
            </div>

            <div class="video-item">
                <div class="video-wrapper">
                    <iframe 
                        src="https://www.youtube.com/embed/M8D0dORuPDM" 
                        title="YouTube video player" 
                        frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                        allowfullscreen>
                    </iframe>
                </div>
            </div>

            <div class="video-item">
                <div class="video-wrapper">
                    <iframe 
                        src="https://www.youtube.com/embed/SDzLeBEiOG0" 
                        title="YouTube video player" 
                        frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                        allowfullscreen>
                    </iframe>
                </div>
            </div>

            <div class="video-item">
                <div class="video-wrapper">
                    <iframe 
                        src="https://www.youtube.com/embed/U1NT6ZbUckQ" 
                        title="YouTube video player" 
                        frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                        allowfullscreen>
                    </iframe>
                </div>
            </div>

            <div class="video-item">
                <div class="video-wrapper">
                    <iframe 
                        src="https://www.youtube.com/embed/Hb_YtIpe-5I" 
                        title="YouTube video player" 
                        frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                        allowfullscreen>
                    </iframe>
                </div>
            </div>
        </div>
    </div>
</section>

<section id="linkedin-posts" class="linkedin-posts-section">
    <div class="container">
        <h2 class="section-title">Latest on LinkedIn</h2>
        <p class="section-description">
            Recent posts and updates about my work with Red Hat technologies, OpenShift, and cloud-native solutions.
        </p>
        
        <div class="linkedin-posts-grid">
            <a href="https://www.linkedin.com/pulse/extending-openshift-lightspeed-mcp-intelligent-via-chat-pizarro-dynpf/" class="linkedin-post-card" target="_blank" rel="noopener noreferrer">
                <div class="linkedin-post-icon">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                        <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
                    </svg>
                </div>
                <h3 class="linkedin-post-title">Extending OpenShift Lightspeed with MCP</h3>
                <p class="linkedin-post-description">
                    Built an MCP server with Quarkus that turns 46 Red Hat documents into contextual answers for OpenShift Lightspeed using Model Context Protocol instead of traditional RAG.
                </p>
                <div class="linkedin-post-tags">
                    <span class="tag">MCP</span>
                    <span class="tag">OpenShift Lightspeed</span>
                    <span class="tag">Quarkus</span>
                    <span class="tag">AI</span>
                </div>
            </a>

            <a href="https://www.linkedin.com/posts/maximiliano-gregorio-pizarro-consultor-it_operatorhub-artifacthub-helm-activity-7349508722932514817-HlpN" class="linkedin-post-card" target="_blank" rel="noopener noreferrer">
                <div class="linkedin-post-icon">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                        <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
                    </svg>
                </div>
                <h3 class="linkedin-post-title">JHipster Online on OperatorHub</h3>
                <p class="linkedin-post-description">
                    My first operator, JHipster Online, is officially available on OperatorHub! Includes JHipster 8.8.0, generator-jhipster-quarkus 3.4.0, and JDL Studio.
                </p>
                <div class="linkedin-post-tags">
                    <span class="tag">OperatorHub</span>
                    <span class="tag">ArtifactHub</span>
                    <span class="tag">Helm</span>
                    <span class="tag">JHipster</span>
                </div>
            </a>

            <a href="https://www.linkedin.com/posts/maximiliano-gregorio-pizarro-consultor-it_kuadrant-connectivitylink-gatewayapi-activity-7345544548695093248-L2On" class="linkedin-post-card" target="_blank" rel="noopener noreferrer">
                <div class="linkedin-post-icon">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                        <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
                    </svg>
                </div>
                <h3 class="linkedin-post-title">Kuadrant & Connectivity Link</h3>
                <p class="linkedin-post-description">
                    Kuadrant combines Gateway API and Istio-based gateway controllers to enhance application connectivity with TLS, DNS, authentication, and rate limiting policies.
                </p>
                <div class="linkedin-post-tags">
                    <span class="tag">Kuadrant</span>
                    <span class="tag">ConnectivityLink</span>
                    <span class="tag">GatewayAPI</span>
                    <span class="tag">Istio</span>
                </div>
            </a>

            <a href="https://www.linkedin.com/posts/maximiliano-gregorio-pizarro-consultor-it_ainativedevelopment-continue-ollama-activity-7344156385741303808--b7r" class="linkedin-post-card" target="_blank" rel="noopener noreferrer">
                <div class="linkedin-post-icon">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                        <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
                    </svg>
                </div>
                <h3 class="linkedin-post-title">AI Native Development</h3>
                <p class="linkedin-post-description">
                    Exploring AI native development with Continue and Ollama for enhanced developer productivity and AI-powered coding experiences.
                </p>
                <div class="linkedin-post-tags">
                    <span class="tag">AI</span>
                    <span class="tag">Ollama</span>
                    <span class="tag">Development</span>
                    <span class="tag">AI Native</span>
                </div>
            </a>
        </div>
    </div>
</section>

<section class="collaborations-section">
    <div class="container">
        <h2 class="section-title">Collaborations</h2>
        <div class="collaborations-grid">
            <a href="https://www.redhat.com/" class="collaboration-logo" target="_blank" rel="noopener noreferrer" aria-label="Red Hat">
                <img src="https://static.redhat.com/libs/redhat/brand-assets/2/corp/logo--on-dark.svg" alt="Red Hat">
            </a>
            <a href="https://www.cncf.io/" class="collaboration-logo" target="_blank" rel="noopener noreferrer" aria-label="CNCF">
                <img src="https://www.cncf.io/wp-content/uploads/2023/04/cncf-main-site-logo.svg" alt="CNCF">
            </a>
            <a href="https://bfa.ar/" class="collaboration-logo" target="_blank" rel="noopener noreferrer" aria-label="Blockchain Federal Argentina">
                <img src="https://bfa.ar/themes/bfa/logo.svg" alt="Blockchain Federal Argentina">
            </a>
            <a href="https://www.buenosaires.gob.ar/" class="collaboration-logo" target="_blank" rel="noopener noreferrer" aria-label="Buenos Aires">
                <img src="{{ '/assets/images/gcba.jpg' | relative_url }}" alt="GCBA">
            </a>
        </div>
    </div>
</section>


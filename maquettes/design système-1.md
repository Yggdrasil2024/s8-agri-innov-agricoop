\# 🌿 AgriCoop Connect — Design System



Projet : AgriCoop Connect  

Équipe : Agri-Innov



\---



\# 1. Police



Le projet utilise la police \*\*Inter\*\*.



```css

@import url("https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900\&display=swap");

```



\---



\# 2. Variables CSS



```css

:root {

&#x20; /\* ===============================

&#x20;    PRIMARY COLORS

&#x20; =============================== \*/

&#x20; --color-primary: #2f5d3a;

&#x20; --color-primary-hover: #24482d;

&#x20; --color-primary-light: #eaf4ec;



&#x20; /\* ===============================

&#x20;    BACKGROUND COLORS

&#x20; =============================== \*/

&#x20; --color-background: #f8f9fa;

&#x20; --color-surface: #ffffff;

&#x20; --color-sidebar: #24482d;



&#x20; /\* ===============================

&#x20;    TEXT COLORS

&#x20; =============================== \*/

&#x20; --color-heading: #1f2937;

&#x20; --color-body: #4b5563;

&#x20; --color-muted: #6b7280;



&#x20; /\* ===============================

&#x20;    STATUS COLORS

&#x20; =============================== \*/

&#x20; --success: #16a34a;

&#x20; --warning: #f59e0b;

&#x20; --danger: #dc2626;

&#x20; --info: #2563eb;



&#x20; /\* ===============================

&#x20;    BORDER

&#x20; =============================== \*/

&#x20; --border-color: #e5e7eb;



&#x20; /\* ===============================

&#x20;    BORDER RADIUS

&#x20; =============================== \*/

&#x20; --radius-sm: 6px;

&#x20; --radius-md: 10px;

&#x20; --radius-lg: 14px;

&#x20; --radius-xl: 18px;



&#x20; /\* ===============================

&#x20;    SHADOWS

&#x20; =============================== \*/

&#x20; --shadow-sm: 0 1px 3px rgba(0,0,0,.08);

&#x20; --shadow-md: 0 6px 18px rgba(0,0,0,.10);

&#x20; --shadow-lg: 0 12px 30px rgba(0,0,0,.12);



&#x20; /\* ===============================

&#x20;    TRANSITION

&#x20; =============================== \*/

&#x20; --transition: .3s ease;



&#x20; /\* ===============================

&#x20;    TYPOGRAPHY

&#x20; =============================== \*/

&#x20; --font-family: Inter, "Segoe UI", Roboto, sans-serif;



&#x20; /\* ===============================

&#x20;    FONT SIZE

&#x20; =============================== \*/

&#x20; --fs-xs: .75rem;

&#x20; --fs-sm: .875rem;

&#x20; --fs-md: 1rem;

&#x20; --fs-lg: 1.25rem;

&#x20; --fs-xl: 1.5rem;

&#x20; --fs-2xl: 2rem;



&#x20; /\* ===============================

&#x20;    SPACING

&#x20; =============================== \*/

&#x20; --space-1: .5rem;

&#x20; --space-2: 1rem;

&#x20; --space-3: 1.5rem;

&#x20; --space-4: 2rem;

&#x20; --space-5: 3rem;

}

```



\---



\# 3. Composants



\## Bouton principal



```css

.btn-primary {

&#x20; background: var(--color-primary);

&#x20; color: #fff;

&#x20; padding: 12px 24px;

&#x20; border: none;

&#x20; border-radius: var(--radius-md);

&#x20; cursor: pointer;

&#x20; transition: var(--transition);

&#x20; font-weight: 600;

}



.btn-primary:hover {

&#x20; background: var(--color-primary-hover);

}

```



\---



\## Bouton secondaire



```css

.btn-secondary {

&#x20; background: #fff;

&#x20; border: 1px solid var(--border-color);

&#x20; color: var(--color-heading);

}

```



\---



\## Bouton danger



```css

.btn-danger {

&#x20; background: var(--danger);

&#x20; color: #fff;

}

```



\---



\## Card



```css

.card {

&#x20; background: var(--color-surface);

&#x20; border-radius: var(--radius-lg);

&#x20; padding: 24px;

&#x20; box-shadow: var(--shadow-sm);

&#x20; border: 1px solid var(--border-color);

}

```



\---



\## Inputs \& Select



```css

input,

select {

&#x20; width: 100%;

&#x20; padding: 12px;

&#x20; border: 1px solid var(--border-color);

&#x20; border-radius: var(--radius-md);

&#x20; background: #fff;

&#x20; transition: .3s;

}



input:focus,

select:focus {

&#x20; outline: none;

&#x20; border-color: var(--color-primary);

&#x20; box-shadow: 0 0 0 4px rgba(47,93,58,.15);

}

```



\---



\## Badges



\### Succès



```css

.badge-success {

&#x20; background: #dcfce7;

&#x20; color: var(--success);

}

```



\### Avertissement



```css

.badge-warning {

&#x20; background: #fef3c7;

&#x20; color: var(--warning);

}

```



\### Erreur



```css

.badge-danger {

&#x20; background: #fee2e2;

&#x20; color: var(--danger);

}

```



\---



\# 4. Tableau



\- Fond blanc

\- Entête verte (`--color-primary`)

\- Texte blanc dans l'entête

\- Lignes séparées par une bordure légère

\- Effet `hover` gris clair

\- Coins arrondis

\- Défilement horizontal sur mobile



\---



\# 5. Sidebar



\- Largeur : \*\*240px\*\*

\- Couleur : `#24482D`

\- Texte : blanc

\- Élément actif : fond vert plus clair

\- Icônes Lucide

\- Position fixe

\- Hauteur : `100vh`



\---



\# 6. Header



\- Hauteur : \*\*80px\*\*

\- Fond blanc

\- Sticky

\- Ombre légère (`--shadow-sm`)

\- Padding horizontal : \*\*32px\*\*



\---



\# 7. Icônes



Bibliothèque :



\*\*Lucide Icons\*\*



```html

<script src="https://unpkg.com/lucide@latest"></script>

```



Taille recommandée :



\- 20px

\- 24px



Couleur :



```css

color: inherit;

```



\---



\# 8. Responsive



\## Desktop



≥ 1024px



\---



\## Tablette



768px — 1023px



\---



\## Mobile



≤ 767px



\---



\# 9. Espacements



| Élément | Valeur |

|----------|---------|

| Entre deux sections | 48px |

| Entre deux cartes | 24px |

| Padding interne | 24px |

| Gap Grid | 24px |



\---



\# 10. Animations



Transition



```css

transition: .3s ease;

```



Hover



```css

transform: scale(1.02);

```



Ombre



```css

box-shadow: var(--shadow-md);

```



\---



\# 11. Typographie



| Élément | Valeur |

|----------|---------|

| Police | Inter |

| Fallback | Segoe UI, Roboto, sans-serif |

| Titres | 600 |

| Texte | 400 |

| Boutons | 600 |



\---



\# 12. Librairies utilisées



\- Google Fonts (Inter)

\- Remixicon



\---



\# 13. Philosophie UI



Le design d'AgriCoop Connect repose sur les principes suivants :



\- Simplicité

\- Lisibilité

\- Cohérence

\- Réutilisabilité

\- Accessibilité

\- Responsive First

\- Interfaces inspirées des dashboards modernes (Notion, Linear, Tailwind UI, Flowbite)


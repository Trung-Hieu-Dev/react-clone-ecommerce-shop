## Goals

- This demo project to review and practice ReactJS.

#### Demo Design

- [Link](https://react-course-comfy-sloth-store.netlify.app/)

#### Fonts

- Fontshare
- [fontshare pairs](https://www.fontshare.com/pairs)
- pick the fonts
- purposely picked funky fonts
- change title as well

  public/index.html

```html
<link
  href="https://api.fontshare.com/v2/css?f[]=khand@400&f[]=array@700,400&display=swap"
  rel="stylesheet"
/>
<title>Gadget Junkie</title>
```

index.css

```css
body {
  font-family: "Khand", sans-serif;
  background: var(--clr-white);
  color: var(--clr-grey-1);
  line-height: 1.5;
  font-size: 0.875rem;
}

h1,
h2,
h3,
h4,
h5 {
  font-family: "Array", sans-serif;
  letter-spacing: var(--spacing);
  text-transform: capitalize;
  line-height: 1.25;
  margin-bottom: 0.75rem;
}

button {
  font-family: inherit;
}
```

#### Colors

- get shades from tailwind.css

- [tailwind color shades] (https://tailwindcss.com/docs/customizing-colors#color-palette-reference)

- pick grey and primary color
- OPPOSITE ORDER !!!

```css
:root {
  /* INDIGO */
  /* dark shades of primary color*/
  --clr-primary-1: #312e81;
  --clr-primary-2: #3730a3;
  --clr-primary-3: #4338ca;
  --clr-primary-4: #4f46e5;
  /* primary/main color */
  --clr-primary-5: #6366f1;
  /* lighter shades of primary color */
  --clr-primary-6: #818cf8;
  --clr-primary-7: #93c5fd;
  --clr-primary-8: #bfdbfe;
  --clr-primary-9: #dbeafe;
  --clr-primary-10: #eff6ff;
  /* SLATE */
  /* darkest grey - used for headings */
  --clr-grey-1: #0f172a;
  --clr-grey-2: #1e293b;
  --clr-grey-3: #334155;
  --clr-grey-4: #475569;
  /* grey used for paragraphs */
  --clr-grey-5: #64748b;
  --clr-grey-6: #94a3b8;
  --clr-grey-7: #cbd5e1;
  --clr-grey-8: #e2e8f0;
  --clr-grey-9: #f1f5f9;
  --clr-grey-10: #f8fafc;
}
```

#### Favicon

- [favicon.io](https://favicon.io/)
- I used primary-5 color value
- replace favicon.ico in public

#### Main Images - First Approach

- get images, I usually go with pexels
- [pexels](https://www.pexels.com/)
- replace in src/assets
- hero-bcg.jpeg
- hero-bcg-2.jpeg

#### Main Images - Second Approach

- [undraw](https://undraw.co/illustrations)
- use primary color
- hero-bcg.svg

```css
gap: 2rem;
```

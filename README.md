# Linear Equation & Coordinate Geometry Calculator

A production-ready frontend web app built with Next.js 15, TypeScript, React, and Tailwind CSS. It calculates linear equation and coordinate geometry values from two points, explains each step, and draws a responsive Cartesian graph.

## Features

- Validated inputs for Point A `(x1, y1)` and Point B `(x2, y2)`
- Slope, slope-intercept, point-slope, and standard equation forms
- `x` as a function of `y`, including vertical and horizontal line handling
- Midpoint, distance, angle in degrees and radians
- Direction vector and unit vector
- X-intercept and Y-intercept
- Horizontal, vertical, X-axis parallel, and Y-axis parallel detection
- Step-by-step solution for every calculation
- Formula reference section
- Responsive HTML Canvas graph with grid, axes, points, labels, and connecting line
- Copy results button
- No backend, database, authentication, or external APIs

## Folder Structure

```text
linear-equation-coordinate-geometry-calculator/
├── app/
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   ├── FormulaSection/
│   │   └── FormulaSection.tsx
│   ├── Graph/
│   │   └── Graph.tsx
│   ├── InputForm/
│   │   └── InputForm.tsx
│   ├── ResultCard/
│   │   └── ResultGrid.tsx
│   └── StepSection/
│       └── StepSection.tsx
├── lib/
│   ├── math.ts
│   └── utils.ts
├── public/
│   └── site.svg
├── types/
│   └── index.ts
├── .gitignore
├── eslint.config.mjs
├── next-env.d.ts
├── next.config.ts
├── package.json
├── postcss.config.mjs
├── README.md
└── tsconfig.json
```

## Installation

```bash
npm install
npm run dev
```

Open `http://localhost:3000` in your browser.

## Quality Checks

```bash
npm run typecheck
npm run build
```

## Vercel Deployment

1. Push this project to GitHub.
2. Open Vercel and choose **Add New Project**.
3. Import the GitHub repository.
4. Keep the default Next.js settings.
5. Deploy.

No environment variables are required.

## GitHub Ready

This project includes a clean file structure, strict TypeScript configuration, reusable components, deployment-ready scripts, and a `.gitignore` suitable for a Next.js application.

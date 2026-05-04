
markdown# Playwright Practicas 🎭

## ¿Qué es este repo?
Repo de prácticas de automatización con Playwright y TypeScript.

## Contexto
- Estoy aprendiendo QA desde cero
- Antes practiqué SQL, Postman, Stripe y Cypress en otro repo (Mi_Practica_SQL_Stripe)
- Este repo es exclusivo para Playwright

## Estructura
Playwright_Practicas/
├── .github/
│   └── workflows/
│       └── playwright.yml    ← pipeline CI/CD automático
├── tests/
│   └── example.spec.ts       ← tests aquí
├── playwright.config.ts      ← configuración de Playwright
└── package.json

## Comandos importantes
```bash
# Correr tests en Chrome visible
npx playwright test --headed --project=chromium

# Correr tests en Chrome sin ventana
npx playwright test --project=chromium

# Correr todos los browsers
npx playwright test

# Modo UI (interfaz visual recomendada)
npx playwright test --ui

# Ver reporte HTML
npx playwright show-report
```

## Cómo ejecutar desde VS Code
- Clic en el ícono 🧪 en la barra izquierda
- Clic en ▶ al lado del test

## Lo que aprendí hasta ahora
- [x] Qué es Playwright y para qué sirve
- [x] Instalar Playwright con TypeScript
- [x] Estructura del proyecto
- [x] Qué hace playwright.config.ts
- [x] Primer test de login en SauceDemo
- [x] Correr tests desde terminal y desde VS Code
- [x] Ver el navegador abrirse con --headed
- [x] Conectar repo a GitHub
- [x] Qué es CI/CD y cómo funciona

## Próximos pasos
- [ ] Aprender más sobre locators (getByRole, getByText, getByLabel)
- [ ] Escribir más tests en SauceDemo
- [ ] Entender assertions (expect)
- [ ] Modo UI de Playwright
- [ ] Page Object Model

## Cuando retomes
Comparte este README al inicio de la conversación y di:
"Quiero continuar practicando Playwright desde donde lo dejé"
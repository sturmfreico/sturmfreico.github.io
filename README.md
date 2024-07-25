# sturmfrei.com.au

See it in action: [sturmfrei website](https://sturmfrei.com.au)

## Development

From your terminal:

```sh
npm run dev
```

## Deployment

Create an optimized production build with:

```sh
npm run build
```

## All Scripts

| Command               | Action                                             |
| :-------------------- | :------------------------------------------------- |
| `npm i`               | Installs dependencies                              |
| `npm run dev`         | Starts local dev server at `localhost:4321`        |
| `npm run build`       | Build your production site to `./dist/`            |
| `npm run preview`     | Preview your build locally, before deploying       |
| `npm run format`      | Format codes with Prettier                         |
| `npm run lint:eslint` | Run Eslint                                         |
| `npm run astro ...`   | Run CLI commands like `astro add`, `astro preview` |

## Configuration

Basic configuration file: `./src/config.yaml`

### Customize Design

To customize Font families, Colors or more Elements refer to the following files:

- `src/components/CustomStyles.astro`
- `src/assets/styles/tailwind.css`

## Acknowledgements

This repository is based on [AstroWind](https://github.com/onwidget/astrowind) and customised to our own requirements.

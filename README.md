# FORMA

FORMA is a free, bilingual Astro template for construction and renovation businesses. It includes an English homepage at `/`, a Polish homepage at `/pl/`, reusable sections, responsive image handling, and a contact form demo that does not send data.

The public package uses neutral SVG image placeholders. Photography from the development demo is not included. Use **Use this template** on GitHub to start your own repository, or download the source ZIP from the **Code** menu.

## Start

Requirements: Node.js 22.12 or newer.

```bash
npm ci
npm run dev
```

Astro serves the site at `http://localhost:4345`. To create a static production build, run:

```bash
npm run build
```

The output is written to `dist/`. See the [deployment guide](docs/guides/deployment.md) before publishing a customized site.

## Customize

Start with the [customization guide](docs/guides/customization.md) and [content guide](docs/guides/content.md). Site details, navigation, SEO and homepage sections are stored in `src/data/`. Theme tokens are defined in `design/default.md`; run `npm run design:sync` after changing them.

All business details, project descriptions and testimonials in the demo are fictional examples. Replace them with verified information and images you have permission to use. The contact form only validates locally and displays a demo confirmation. Connect and test a service before collecting inquiries.

## License

The source code and included FORMA demo graphics are available under the MIT License. You may use the template in commercial projects and redistribute it, provided you include the copyright and permission notice. Third-party components and fonts retain their own licenses. See [LICENSE.md](LICENSE.md) and [asset and license notes](docs/assets-and-licenses.md) for the full boundary.

## Checks

```bash
npm run ai:check
npm run build
```

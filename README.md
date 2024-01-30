# TikTok Downloader

Este módulo te permite descargar videos de TikTok.

## Instalación

Puedes instalar este módulo utilizando npm:

```bash
npm install @danielgutierrez/tiktokdownloaders
```

### USO
```bash
const tk = require('@danielgutierrez/tiktokdownloaders');

const url = 'https://www.tiktok.com/@andx.vx/video/7324208424709836038';

async function main() {
  try {
    const result = await tk.tiktokdownload(url);
    console.log(result);
  } catch (error) {
    console.error('Error:', error.message);
  }
}

main();

```
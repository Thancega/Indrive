# inDrive — prototipo académico de alta fidelidad

Aplicación web responsive, realizada con Vite y JavaScript, para demostrar un flujo de solicitud de viajes estilo inDrive. **No es un producto oficial ni conecta con conductores, mapas reales o pagos.**

## Funcionalidades
- Pantalla inicial con origen, destino y precio negociable.
- Comparación de tres ofertas ficticias.
- Selección de conductor y simulación de viaje.
- Historial local de viajes de demostración (se reinicia al recargar).
- Perfil y selector simulado de forma de pago.

## Desarrollo local

```bash
npm install
npm run dev
```

## Publicar en Vercel

1. Descomprime el ZIP y sube la carpeta del proyecto a GitHub.
2. En Vercel, selecciona **Add New → Project** e importa ese repositorio.
3. Framework preset: **Vite**. Build command: `npm run build`. Output directory: `dist`.
4. Pulsa **Deploy**.

También puedes usar Vercel CLI desde la carpeta del proyecto (`npx vercel`).

## Alcance
Esta es una **propuesta visual original** basada en el caso académico descrito. No es una reproducción verificada de los frames del archivo de Figma compartido, porque esos frames no estaban disponibles para inspección directa durante la creación. El mapa es una ilustración, no un servicio de geolocalización.

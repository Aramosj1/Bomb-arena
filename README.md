# Retro Chaos
Node.js 18+ (preferiblemente una versión LTS vigente).

1. Abre esta carpeta en VS Code.
2. Ejecuta `npm install` y `npm run dev`.
3. Abre http://localhost:3000.
4. En VS Code, Ports / Puertos, reenvía 3000 y configura visibilidad pública si está disponible. Comparte la URL del túnel, no localhost. El túnel debe admitir Socket.IO. Mantén el servidor activo.
5. Cada jugador entra con un apodo. El primero inicia con 2–7 jugadores.

WASD o flechas para moverse, espacio para bomba. También controles táctiles. F = alcance, + = capacidad, S = velocidad. Rondas de 120 segundos; último superviviente gana. Si quedan varios al terminar, empate. Estado en memoria; reiniciar borra puntuaciones. Una sala pública, sin autenticación ni reconexión de identidad. No compartir el túnel fuera del grupo.

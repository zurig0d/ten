<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para Nuri ❤️</title>
    <style>
        body {
            margin: 0;
            overflow: hidden;
            background: #0a0a1a;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, sans-serif;
            color: white;
        }
        #corazon-container {
            position: relative;
            width: 300px;
            height: 300px;
            cursor: pointer;
        }
        .particula-corazon {
            position: absolute;
            width: 8px;
            height: 8px;
            background: #ff3366;
            border-radius: 50%;
            box-shadow: 0 0 15px #ff0066;
            opacity: 0;
            transform: scale(0);
        }
        #mensaje {
            position: absolute;
            bottom: 15%;
            text-align: center;
            opacity: 0;
            transform: translateY(50px);
            transition: all 2s ease;
        }
        #mensaje h1 {
            font-size: 2.5em;
            margin: 0;
            background: linear-gradient(45deg, #ff3366, #ffcc00);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 0 10px rgba(255, 51, 102, 0.5);
        }
        #mensaje p {
            font-size: 1.5em;
            font-style: italic;
            margin-top: 10px;
        }
        .estrella {
            position: absolute;
            background: white;
            width: 2px;
            height: 2px;
            border-radius: 50%;
            animation: twinkle 5s infinite;
        }
        @keyframes twinkle {
            0%, 100% { opacity: 0.2; }
            50%      { opacity: 1; }
        }
        .confeti {
            position: absolute;
            width: 10px;
            height: 10px;
            opacity: 0;
        }
        #carta {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 80%;
            max-width: 500px;
            background: rgba(10, 10, 26, 0.9);
            border: 2px solid #ff3366;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 0 30px rgba(255, 51, 102, 0.7);
            opacity: 0;
            display: none;
            z-index: 100;
        }
        #carta-contenido {
            font-size: 1.2em;
            line-height: 1.6;
            text-align: left;
            height: 300px;
            overflow-y: auto;
            padding-right: 10px;
        }
        #carta-contenido::-webkit-scrollbar {
            width: 5px;
        }
        #carta-contenido::-webkit-scrollbar-thumb {
            background: #ff3366;
            border-radius: 5px;
        }
        .cerrar-carta {
            position: absolute;
            top: 10px;
            right: 10px;
            background: none;
            border: none;
            color: #ff3366;
            font-size: 1.5em;
            cursor: pointer;
        }
        .texto-escritura {
            border-right: 2px solid #ff3366;
            animation: blink 0.75s step-end infinite;
        }
        @keyframes blink {
            from, to { border-color: transparent; }
            50%      { border-color: #ff3366; }
        }
    </style>
</head>
<body>
    <div id="corazon-container"></div>
    <div id="mensaje">
        <h1>Feliz mes, Nuri</h1>
        <p>Toca el corazón para leer mi carta</p>
    </div>
    <div id="carta">
        <button class="cerrar-carta">×</button>
        <div id="carta-contenido"></div>
    </div>
    <script>
        // Crear estrellas de fondo
        for (let i = 0; i < 100; i++) {
            const estrella = document.createElement('div');
            estrella.className = 'estrella';
            estrella.style.left = `${Math.random() * 100}vw`;
            estrella.style.top = `${Math.random() * 100}vh`;
            estrella.style.animationDelay = `${Math.random() * 5}s`;
            document.body.appendChild(estrella);
        }
        // Coordenadas del corazón (forma matemática)
        const puntosCorazon = [];
        for (let angulo = 0; angulo < Math.PI * 2; angulo += 0.01) {
            const x = 16 * Math.pow(Math.sin(angulo), 3);
            const y = 13 * Math.cos(angulo) - 5 * Math.cos(2 * angulo) - 2 * Math.cos(3 * angulo) - Math.cos(4 * angulo);
            puntosCorazon.push({ x: x * 8 + 150, y: -y * 8 + 150 });
        }
        // Crear partículas del corazón
        const container = document.getElementById('corazon-container');
        const particulas = [];
        puntosCorazon.forEach((punto, index) => {
            const particula = document.createElement('div');
            particula.className = 'particula-corazon';
            particula.style.left = `${punto.x}px`;
            particula.style.top = `${punto.y}px`;
            container.appendChild(particula);
            particulas.push(particula);
            setTimeout(() => {
                particula.style.opacity = 1;
                particula.style.transform = 'scale(1)';
                particula.style.transition = 'all 0.5s ease';
                if (index === puntosCorazon.length - 1) {
                    setTimeout(() => {
                        document.getElementById('mensaje').style.opacity = 1;
                        document.getElementById('mensaje').style.transform = 'translateY(0)';
                        lanzarConfeti();
                    }, 1000);
                }
            }, index * 10);
        });
        // Función para lanzar confeti
        function lanzarConfeti() {
            const colores = ['#ff3366', '#ffcc00', '#00ccff', '#9933ff', '#ff9933'];
            for (let i = 0; i < 100; i++) {
                const confeti = document.createElement('div');
                confeti.className = 'confeti';
                confeti.style.left = `${Math.random() * 100}vw`;
                confeti.style.top = '-10px';
                confeti.style.backgroundColor = colores[Math.floor(Math.random() * colores.length)];
                confeti.style.transform = `rotate(${Math.random() * 360}deg)`;
                confeti.style.width = `${Math.random() * 10 + 5}px`;
                confeti.style.height = `${Math.random() * 5 + 2}px`;
                document.body.appendChild(confeti);
                setTimeout(() => {
                    confeti.style.opacity = 1;
                    confeti.style.transition = 'all 5s linear';
                    confeti.style.top = '100vh';
                    confeti.style.transform = `rotate(${Math.random() * 360}deg) translateX(${Math.random() * 200 - 100}px)`;
                    setTimeout(() => confeti.remove(), 5000);
                }, i * 100);
            }
        }
        // Mostrar carta con efecto de escritura
        function mostrarCarta() {
            const carta = document.getElementById('carta');
            const contenido = document.getElementById('carta-contenido');
            const mensaje = document.getElementById('mensaje');
            mensaje.style.opacity = 0;
            carta.style.display = 'block';
            setTimeout(() => {
                carta.style.opacity = 1;
                const textoCompleto = `Amor,

Hoy se cumple un mes desde que empezamos oficialmente jaja. Y aunque pasó rápido, siento que vivimos un montón de cosas en este tiempo. No sé si es por cómo me hacés sentir o por lo fácil que se vuelve todo cuando estoy con vos.

En este mes compartimos muchas cosas. Me gusta cómo sos, cómo pensás, cómo te reís de mis boludeces, y cómo estás ahí, con esa forma tranquila de estar y hacerme sentir en casa.

No sé si un mes es mucho o poco, pero sí sé que lo viví con ganas, con una sonrisa. Me hacés bien, mi vida, y solo quería que lo supieras.

Gracias por cada momento,

Con vos, todo vale la pena.

Te Amo Nuria Yael Lozano.`;
                let i = 0;
                contenido.innerHTML = '';
                contenido.classList.add('texto-escritura');
                function escribir() {
                    if (i < textoCompleto.length) {
                        contenido.innerHTML += textoCompleto.charAt(i);
                        i++;
                        setTimeout(escribir, 50);
                    } else {
                        contenido.classList.remove('texto-escritura');
                    }
                }
                escribir();
            }, 500);
        }
        // Cerrar carta
        document.querySelector('.cerrar-carta').addEventListener('click', function() {
            const carta = document.getElementById('carta');
            const mensaje = document.getElementById('mensaje');
            carta.style.opacity = 0;
            setTimeout(() => {
                carta.style.display = 'none';
                mensaje.style.opacity = 1;
            }, 500);
        });
        // Hacer el corazón clickeable
        document.getElementById('corazon-container').addEventListener('click', mostrarCarta);
    </script>
</body>
</html>

```html
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Trunks - Física</title>

<script src="https://cdn.tailwindcss.com/3.4.17"></script>

<style>
:root {
    --bg-trunks: #0f071e;
    color-scheme: dark;
}

* {
    box-sizing: border-box;
}

html,
body {
    margin: 0;
    min-height: 100%;
}

html {
    background: var(--bg-trunks);
}

body {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 20px;
    color: #f3e8ff;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background:
        linear-gradient(
            rgba(15, 7, 30, 0.82),
            rgba(15, 7, 30, 0.92)
        ),
        url('images/fondo-1.jpg') center / cover no-repeat fixed;
}

.encabezado {
    width: 100%;
    max-width: 850px;
    text-align: center;
    padding: 30px 15px;
    margin-bottom: 25px;
    border-bottom: 2px solid #a855f7;
    background:
        linear-gradient(
            rgba(15, 7, 30, 0.75),
            rgba(15, 7, 30, 0.75)
        ),
        url('images/fondo-2.jpg') center / cover no-repeat;
}

.clase {
    display: inline-block;
    color: #e9d5ff;
    font-size: 13px;
    font-weight: bold;
    letter-spacing: 4px;
    text-transform: uppercase;
}

.nombre {
    margin-top: 12px;
    font-size: clamp(38px, 7vw, 64px);
    font-weight: 900;
    letter-spacing: 5px;
    color: #d8b4fe;
    text-shadow: 0 0 22px rgba(168, 85, 247, 0.6);
}

.bienvenida {
    width: 100%;
    max-width: 700px;
    padding: 45px 25px;
    text-align: center;
    border: 1px solid rgba(168, 85, 247, 0.45);
    border-radius: 20px;
    background:
        linear-gradient(
            rgba(20, 10, 45, 0.82),
            rgba(20, 10, 45, 0.92)
        ),
        url('images/fondo-4.jpg') center / cover no-repeat;
    box-shadow: 0 0 25px rgba(168, 85, 247, 0.25);
}

.bienvenida h2 {
    margin: 0;
    color: #d8b4fe;
    font-size: clamp(25px, 5vw, 36px);
    font-weight: bold;
}

.bienvenida p {
    margin-top: 15px;
    color: #f3e8ff;
    font-size: 16px;
    line-height: 1.7;
}

@media (max-width: 480px) {
    body {
        padding: 12px;
    }

    .encabezado {
        padding: 25px 10px;
    }

    .nombre {
        letter-spacing: 3px;
    }

    .bienvenida {
        padding: 35px 18px;
    }
}
</style>
</head>

<body>

<header class="encabezado">
    <div class="clase">FÍSICA</div>
    <h1 class="nombre">TRUNKS</h1>
</header>

<main class="bienvenida">
    <h2>¡Bienvenido!</h2>
    <p>
        Tu espacio de aprendizaje de Física.
    </p>
</main>

</body>
</html>
```

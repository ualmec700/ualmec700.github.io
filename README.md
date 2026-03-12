---
layout: null
---
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <style>
        body {
            background-color: #0a0a12;
            background-image: radial-gradient(circle at 50% 50%, #1b1b3a 0%, #0a0a12 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
        }

        .card {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(15px);
            -webkit-backdrop-filter: blur(15px);
            border-radius: 24px;
            padding: 50px 40px;
            width: 90%;
            max-width: 550px;
            text-align: center;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 25px 50px rgba(0, 0, 0, 0.5);
            animation: fadeIn 1s ease-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 3px solid #00d2ff;
            box-shadow: 0 0 20px rgba(0, 210, 255, 0.4);
            margin-bottom: 20px;
            transition: transform 0.3s ease;
        }

        .profile-img:hover {
            transform: scale(1.05) rotate(5deg);
        }

        h1 {
            color: white;
            font-size: 2.5em;
            margin: 10px 0;
            text-shadow: 0 2px 10px rgba(0,0,0,0.3);
        }

        .team-badge {
            display: inline-block;
            background: linear-gradient(90deg, #00d2ff 0%, #3a7bd5 100%);
            color: white;
            padding: 8px 20px;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.1em;
            margin-bottom: 25px;
            box-shadow: 0 4px 15px rgba(58, 123, 213, 0.4);
        }

        .bio {
            color: #ccc;
            line-height: 1.6;
            font-size: 1.1em;
            background: rgba(0,0,0,0.2);
            padding: 20px;
            border-radius: 15px;
            margin-bottom: 30px;
        }

        .links-container {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .btn {
            text-decoration: none;
            padding: 15px;
            border-radius: 12px;
            font-weight: 700;
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .btn-github {
            background: #24292e;
            color: white;
            border: 1px solid #444;
        }

        .btn-github:hover {
            background: #333;
            box-shadow: 0 0 15px rgba(255,255,255,0.1);
        }

        .btn-main {
            background: white;
            color: #1a1a2e;
        }

        .btn-main:hover {
            background: #f0f0f0;
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
        }
    </style>
</head>
<body>

    <div class="card">
        <img src="https://github.com/ualmec700.png" alt="Marcos" class="profile-img">
        
        <h1>Marcos Escánez</h1>
        
        <div class="team-badge">Responsable @ Mentefria04</div>

        <div class="bio">
            Estudiante de Ingeniería Informática.
        </div>

        <div class="links-container">
            <a href="https://github.com/ualmec700" class="btn btn-github">🐙 Mi Perfil de GitHub</a>
            <a href="https://github.com/ualhmis2026-mentefria04/ualhmis2026-mentefria04" class="btn btn-main">🏠 Ir al Blog del Equipo</a>
        </div>
    </div>

</body>
</html>

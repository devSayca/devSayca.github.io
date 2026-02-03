<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sayca Labs | Dev Control</title>
    <style>
        :root {
            --bg: #0a0a0a;
            --accent: #00ff41; /* Green Terminal */
            --text: #e0e0e0;
        }
        body {
            background-color: var(--bg);
            color: var(--text);
            font-family: 'Cascadia Code', 'Courier New', monospace;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            overflow: hidden;
        }
        .container {
            border: 1px solid #333;
            padding: 2rem;
            max-width: 600px;
            box-shadow: 0 0 20px rgba(0, 255, 65, 0.1);
        }
        .header {
            border-bottom: 1px solid #333;
            padding-bottom: 1rem;
            margin-bottom: 1rem;
        }
        .status-bar {
            font-size: 0.8rem;
            color: #888;
            margin-bottom: 2rem;
        }
        .cmd { color: var(--accent); }
        .cursor {
            display: inline-block;
            width: 10px;
            background-color: var(--accent);
            animation: blink 1s infinite;
        }
        @keyframes blink { 50% { opacity: 0; } }
        a { color: var(--accent); text-decoration: none; border: 1px solid var(--accent); padding: 5px 10px; margin-top: 20px; display: inline-block; transition: 0.3s; }
        a:hover { background: var(--accent); color: var(--bg); }
    </style>
</head>
<body>

<div class="container">
    <div class="status-bar">
        USER: Sayca | UNIT: C.B.U | ENV: devsayca.github.io
    </div>
    <div class="header">
        <h1>SAYCA LABS_</h1>
    </div>
    <div class="content">
        <p><span class="cmd">root@sayca:~$</span> run project_init.sh</p>
        <p>> Initiating Sayca Labs Ecosystem...</p>
        <p>> Optimizing Projector Output...</p>
        <p>> Linking Android Dev Mode (OnePlus Nord 5)...</p>
        <br>
        <p>Statut : <span style="color: var(--accent);">ACTIF</span></p>
    </div>
    <a href="https://github.com/devsayca">Accéder au Core</a>
</div>

</body>
</html>

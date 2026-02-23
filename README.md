<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Helix & Heritage | DNA Discovery</title>
    <style>
        :root {
            --dna-blue: #00d2ff;
            --dna-purple: #9d50bb;
            --bg-dark: #0f172a;
        }
        body {
            margin: 0;
            font-family: 'Inter', sans-serif;
            background-color: var(--bg-dark);
            color: white;
            overflow-x: hidden;
        }
        header {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background: radial-gradient(circle at center, #1e293b 0%, #0f172a 100%);
            text-align: center;
        }
        .hero-title {
            font-size: 4rem;
            background: linear-gradient(to right, var(--dna-blue), var(--dna-purple));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 10px;
        }
        .tagline {
            font-size: 1.2rem;
            opacity: 0.8;
            max-width: 600px;
        }
        .dna-cta {
            margin-top: 30px;
            padding: 15px 40px;
            border-radius: 50px;
            border: none;
            background: linear-gradient(45deg, var(--dna-blue), var(--dna-purple));
            color: white;
            font-weight: bold;
            cursor: pointer;
            transition: transform 0.3s ease;
        }
        .dna-cta:hover {
            transform: scale(1.05);
            box-shadow: 0 0 20px rgba(0, 210, 255, 0.4);
        }
    </style>
</head>
<body>

    <header>
        <h1 class="hero-title">Helix & Heritage</h1>
        <p class="tagline">Unlock the secrets of your past. 2026 Whole Genome Sequencing (WGS) provides 100x more detail than traditional tests.</p>
        <button class="dna-cta">Upload Your Sequence</button>
    </header>

</body>
</html>

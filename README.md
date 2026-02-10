<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IWV Mesh Net | Community Connected</title>
    <style>
        :root {
            --bg-dark: #1a2a36;
            --accent-green: #00ff00;
            --sand: #e6d5b8;
            --clay: #b35a38;
            --text-light: #f4f4f4;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            background-color: var(--bg-dark);
            color: var(--text-light);
            line-height: 1.6;
        }

        header {
            padding: 2rem 1rem;
            text-align: center;
            background: linear-gradient(180deg, rgba(0,0,0,0.3) 0%, rgba(26,42,54,1) 100%);
        }

        .logo {
            max-width: 250px;
            height: auto;
            border-radius: 50%;
            box-shadow: 0 0 20px rgba(0, 255, 0, 0.2);
            margin-bottom: 1rem;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 2rem;
        }

        h1 {
            color: var(--sand);
            letter-spacing: 2px;
            text-transform: uppercase;
            margin-bottom: 0.5rem;
        }

        .status-badge {
            display: inline-block;
            padding: 0.25rem 1rem;
            border: 1px solid var(--accent-green);
            color: var(--accent-green);
            border-radius: 20px;
            font-size: 0.8rem;
            text-transform: uppercase;
            margin-bottom: 2rem;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 3rem;
        }

        .card {
            background: rgba(255, 255, 255, 0.05);
            padding: 1.5rem;
            border-radius: 8px;
            border-bottom: 3px solid var(--clay);
        }

        .card h3 {
            color: var(--accent-green);
            margin-top: 0;
        }

        .cta-button {
            display: inline-block;
            background-color: var(--clay);
            color: white;
            padding: 1rem 2rem;
            text-decoration: none;
            border-radius: 4px;
            font-weight: bold;
            margin-top: 2rem;
            transition: background 0.3s ease;
        }

        .cta-button:hover {
            background-color: #d36b45;
        }

        footer {
            text-align: center;
            padding: 4rem 1rem 2rem;
            font-size: 0.9rem;
            color: #777;
        }
    </style>
</head>
<body>

    <header>
        <img src="1000005908.png" alt="IWV Mesh Net Logo" class="logo">
        <h1>IWV MESH NET</h1>
        <div class="status-badge">● Network Online</div>
        <p>Building a resilient, community-owned communications network for the Indian Wells Valley.</p>
    </header>

    <div class="container">
        <section style="text-align: center;">
            <h2>Off-Grid. Decentralized. Together.</h2>
            <p>We are a group of enthusiasts dedicated to creating a robust mesh data network that works even when the traditional internet doesn't. From the mountains to the valley floor, we stay connected.</p>
            <a href="#" class="cta-button">Join the Network</a>
        </section>

        <div class="grid">
            <div class="card">
                <h3>Resilience</h3>
                <p>Designed to operate independently of major ISPs, ensuring communication during local emergencies or outages.</p>
            </div>
            <div class="card">
                <h3>Open Access</h3>
                <p>Built on open-source protocols. Our network is owned by the people who use it, not a corporation.</p>
            </div>
            <div class="card">
                <h3>Local Community</h3>
                <p>Connecting neighbors across the IWV through high-site nodes and home-based mesh points.</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2026 IWV Mesh Net. Located in the High Desert.</p>
    </footer>

</body>
</html>

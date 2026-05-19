<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mayank | Personal Portfolio & Resume</title>
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cloudflare.com">
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://googleapis.com">
    <link rel="preconnect" href="https://gstatic.com" crossorigin>
    <link href="https://googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --primary-color: #2563eb;
            --primary-dark: #1d4ed8;
            --text-dark: #1f2937;
            --text-muted: #4b5563;
            --bg-light: #f8fafc;
            --bg-white: #ffffff;
            --border-color: #e2e8f0;
            --shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--bg-light);
            color: var(--text-dark);
            line-height: 1.6;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        /* Profile Header Wrapper */
        header {
            background-color: var(--bg-white);
            padding: 40px;
            border-radius: 16px;
            box-shadow: var(--shadow);
            margin-bottom: 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .profile-info h1 {
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--text-dark);
            letter-spacing: -0.05em;
            margin-bottom: 5px;
        }

        .profile-info p {
            color: var(--primary-color);
            font-weight: 500;
            font-size: 1.1rem;
        }

        .contact-details {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .contact-item {
            display: flex;
            align-items: center;
            gap: 10px;
            color: var(--text-muted);
            text-decoration: none;
            font-size: 0.95rem;
            transition: color 0.2s ease;
        }

        .contact-item:hover {
            color: var(--primary-color);
        }

        .contact-item i {
            color: var(--primary-color);
            width: 16px;
        }

        /* Main Content Grid Layout */
        .main-layout {
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 30px;
        }

        @media (max-width: 768px) {
            .main-layout {
                grid-template-columns: 1fr;
            }
            header {
                flex-direction: column;
                align-items: flex-start;
                padding: 25px;
            }
        }

        /* Content Card Component */
        .card {
            background-color: var(--bg-white);
            padding: 35px;
            border-radius: 16px;
            box-shadow: var(--shadow);
            margin-bottom: 30px;
        }

        .card-title {
            font-size: 1.3rem;
            font-weight: 600;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid var(--border-color);
            display: flex;
            align-items: center;
            gap: 10px;
            color: var(--text-dark);
        }

        .card-title i {
            color: var(--primary-color);
        }

        .summary-text {
            color: var(--text-muted);
            font-size: 1.05rem;
            text-align: justify;
        }

        /* Education Timelines */
        .education-item {
            position: relative;
            padding-left: 20px;
            border-left: 2px solid var(--primary-color);
        }

        .education-item h3 {
            font-size: 1.15rem;
            font-weight: 600;
            color: var(--text-dark);
        }

        .institution {
            color: var(--text-muted);
            font-weight: 500;
            margin-bottom: 5px;
        }

        .duration {
            display: inline-block;
            background-color: #eff6ff;
            color: var(--primary-color);
            padding: 3px 10px;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: 600;
        }

        /* Dynamic Tags Sidebar */
        .tag-container {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
        }

        .tag {
            background-color: #f1f5f9;
            color: #334155;
            padding: 6px 12px;
            border-radius: 8px;
            font-size: 0.85rem;
            font-weight: 500;
            border: 1px solid var(--border-color);
        }

        footer {
            text-align: center;
            margin-top: 40px;
            color: var(--text-muted);
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Header Section -->
        <header>
            <div class="profile-info">
                <h1>MAYANK</h1>
                <p>Information Technology Student</p>
            </div>
            <div class="contact-details">
                <a href="mailto:mayankkumar40410@gmail.com" class="contact-item">
                    <i class="fa-regular fa-envelope"></i> mayankkumar40410@gmail.com
                </a>
                <a href="tel:+91991240017" class="contact-item">
                    <i class="fa-solid fa-phone"></i> +91 991240017
                </a>
                <span class="contact-item">
                    <i class="fa-solid fa-location-dot"></i> Durg, Chhattisgarh, India
                </span>
                <a href="#" target="_blank" class="contact-item">
                    <i class="fa-brands fa-linkedin"></i> LinkedIn Profile
                </a>
            </div>
        </header>

        <!-- Main Content Area -->
        <div class="main-layout">
            <!-- Left Column -->
            <div class="left-column">
                <!-- Professional Summary Card -->
                <section class="card">
                    <h2 class="card-title"><i class="fa-solid fa-user"></i> Professional Summary</h2>
                    <p class="summary-text">
                        Motivated and detail-oriented Information Technology student with strong knowledge in web development, Java programming, data visualization, and Microsoft Azure AI. Skilled in creating responsive web solutions, analyzing data using BI tools, and building cloud-integrated applications. Passionate about leveraging technology for real-world problem solving and continuous learning in both software and data domains.
                    </p>
                </section>

                <!-- Education Card -->
                <section class="card">
                    <h2 class="card-title"><i class="fa-solid fa-graduation-cap"></i> Education</h2>
                    <div class="education-item">
                        <h3>Bachelor of Technology (B.Tech)</h3>
                        <p class="institution">Information Technology</p>
                        <p class="institution">Rungta College of Engineering and Technology, Bhilai</p>
                        <span class="duration">2022 – Present</span>
                    </div>
                </section>
            </div>

            <!-- Right Column / Sidebar -->
            <div class="right-column">
                <!-- Highlighted Skills extracted from Summary -->
                <section class="card">
                    <h2 class="card-title"><i class="fa-solid fa-code"></i> Core Skills</h2>
                    <div class="tag-container">
                        <span class="tag">Web Development</span>
                        <span class="tag">Java Programming</span>
                        <span class="tag">Data Visualization</span>
                        <span class="tag">Microsoft Azure AI</span>
                        <span class="tag">BI Tools</span>
                        <span class="tag">Cloud Integration</span>
                        <span class="tag">Problem Solving</span>
                    </div>
                </section>
            </div>
        </div>

        <footer>
            <p>&copy; 2026 Mayank. All Rights Reserved.</p>
        </footer>
    </div>

</body>
</html><!

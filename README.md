<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hussain's Social Links</title>
    
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <style>
        :root {
            /* Light theme color variables */
            --bg-color: #f9fafb;
            --text-color: #1f2937;
            --btn-bg: #ffffff;
            --btn-hover: #f3f4f6;
            --btn-border: #e5e7eb;
            --accent-color: #8b5cf6;
        }

        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            width: 100%;
            max-width: 600px;
            padding: 40px 20px;
            box-sizing: border-box;
            text-align: center;
        }

        .links-wrapper {
            display: flex;
            flex-direction: column;
            gap: 16px;
        }

        .social-link {
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            background-color: var(--btn-bg);
            color: var(--text-color);
            text-decoration: none;
            /* Increased left/right padding (50px) to prevent text from overlapping the icon */
            padding: 18px 50px; 
            border-radius: 12px;
            font-size: 16px;
            font-weight: 600;
            transition: all 0.3s ease;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05); /* Softer shadow for light mode */
            border: 1px solid var(--btn-border);
        }

        .social-link:hover {
            background-color: var(--btn-hover);
            transform: translateY(-2px);
            border-color: var(--accent-color);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .social-link i {
            position: absolute;
            left: 20px;
            font-size: 22px;
            color: #4b5563; /* Default icon color in light mode */
            transition: color 0.3s ease;
        }

        /* Specific Icon Colors on Hover adjusted for a white background */
        .social-link:hover .fa-goodreads { color: #382110; }
        .social-link:hover .fa-film { color: #00e573; } /* Letterboxd */
        .social-link:hover .fa-imdb { color: #f5c518; }
        .social-link:hover .fa-tv { color: #2e51a2; } /* MyAnimeList */
        .social-link:hover .fa-twitter { color: #1DA1F2; } /* Twitter */
        .social-link:hover .fa-instagram { color: #E1306C; }
        .social-link:hover .fa-steam { color: #171a21; } /* Steam Dark Blue */
        .social-link:hover .fa-xbox { color: #107C10; }

    </style>
</head>
<body>

    <div class="container">

        <div class="links-wrapper">
            
            <!-- Goodreads -->
            <a href="https://www.goodreads.com/user/show/196007154-hussain" target="_blank" rel="noopener noreferrer" class="social-link">
                <i class="fa-brands fa-goodreads"></i>
                Goodreads
            </a>

            <!-- Letterboxd -->
            <a href="https://boxd.it/l0wPl" target="_blank" rel="noopener noreferrer" class="social-link">
                <i class="fa-solid fa-film"></i>
                Letterboxd
            </a>

            <!-- IMDb -->
            <a href="https://www.imdb.com/user/p.5edve44wtxjreffgmscsvlscvu/ratings/?ref_=ext_shr_lnk" target="_blank" rel="noopener noreferrer" class="social-link">
                <i class="fa-brands fa-imdb"></i>
                IMDb
            </a>

            <!-- MyAnimeList -->
            <a href="https://myanimelist.net/profile/aljarrash" target="_blank" rel="noopener noreferrer" class="social-link">
                <i class="fa-solid fa-tv"></i>
                MyAnimeList
            </a>
            
            <!-- Twitter / X -->
            <a href="https://x.com/floorcollapsing" target="_blank" rel="noopener noreferrer" class="social-link">
                <i class="fa-brands fa-twitter"></i>
                Twitter
            </a>

            <!-- Instagram -->
            <a href="https://www.instagram.com/synecdoche_new.york?igsh=MWw0Z2FzYTR5eGw4dw==" target="_blank" rel="noopener noreferrer" class="social-link">
                <i class="fa-brands fa-instagram"></i>
                Instagram
            </a>

            <!-- Steam -->
            <a href="https://steamcommunity.com/id/hussains/" target="_blank" rel="noopener noreferrer" class="social-link">
                <i class="fa-brands fa-steam"></i>
                Steam
            </a>

            <!-- Xbox -->
            <a href="https://www.xbox.com/en-GB/play/user/hjay232" target="_blank" rel="noopener noreferrer" class="social-link">
                <i class="fa-brands fa-xbox"></i>
                Xbox
            </a>

        </div>
    </div>

</body>
</html>

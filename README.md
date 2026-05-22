<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<style>
    :root {
        --bg-color: transparent; /* Let the platform's background show through */
        --text-color: #1f2937;
        --btn-bg: #ffffff;
        --btn-hover: #f3f4f6;
        --btn-border: #e5e7eb;
        --accent-color: #8b5cf6;
    }

    .social-links-container {
        width: 100%;
        max-width: 600px;
        margin: 0 auto;
        padding: 10px;
        box-sizing: border-box;
        text-align: center;
        font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
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
        /* Increased padding to give text a safe zone away from the icon */
        padding: 18px 64px; 
        border-radius: 12px;
        font-size: 16px;
        font-weight: 600;
        transition: all 0.3s ease;
        box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05); 
        border: 1px solid var(--btn-border);
    }

    .social-link:hover {
        background-color: var(--btn-hover);
        transform: translateY(-2px);
        border-color: var(--accent-color);
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        color: var(--text-color);
    }

    /* Target both FontAwesome icons and our custom IMDb icon */
    .social-link i, .imdb-custom-icon {
        position: absolute;
        left: 20px;
        top: 50%;
        transform: translateY(-50%);
        font-size: 22px;
        color: #4b5563; 
        transition: color 0.3s ease;
    }

    /* Custom IMDb Icon to remove the ugly box border */
    .imdb-custom-icon {
        font-family: Arial, Helvetica, sans-serif;
        font-weight: 900;
        font-size: 14px;
        letter-spacing: -0.5px;
    }

    /* Specific Icon Colors on Hover */
    .social-link:hover .fa-goodreads { color: #382110; }
    .social-link:hover .fa-film { color: #00e573; }
    .social-link:hover .imdb-custom-icon { color: #f5c518; }
    .social-link:hover .fa-tv { color: #2e51a2; }
    .social-link:hover .fa-twitter { color: #1DA1F2; }
    .social-link:hover .fa-spotify { color: #1DB954; }
    .social-link:hover .fa-steam { color: #171a21; }
    .social-link:hover .fa-xbox { color: #107C10; }
</style>

<div class="social-links-container">
    <div class="links-wrapper">
        
        <a href="https://www.goodreads.com/user/show/196007154-hussain" target="_blank" rel="noopener noreferrer" class="social-link">
            <i class="fa-brands fa-goodreads"></i>
            Goodreads
        </a>

        <a href="https://boxd.it/l0wPl" target="_blank" rel="noopener noreferrer" class="social-link">
            <i class="fa-solid fa-film"></i>
            Letterboxd
        </a>

        <a href="https://www.imdb.com/user/p.5edve44wtxjreffgmscsvlscvu/ratings/?ref_=ext_shr_lnk" target="_blank" rel="noopener noreferrer" class="social-link">
            <span class="imdb-custom-icon">IMDb</span>
            IMDb
        </a>

        <a href="https://myanimelist.net/profile/aljarrash" target="_blank" rel="noopener noreferrer" class="social-link">
            <i class="fa-solid fa-tv"></i>
            MyAnimeList
        </a>
        
        <a href="https://x.com/floorcollapsing" target="_blank" rel="noopener noreferrer" class="social-link">
            <i class="fa-brands fa-twitter"></i>
            Twitter
        </a>

        <a href="https://open.spotify.com/user/hussainjay?si=jPyltA-YQSG8MM1wB1Q69w" target="_blank" rel="noopener noreferrer" class="social-link">
            <i class="fa-brands fa-spotify"></i>
            Spotify
        </a>

        <a href="https://steamcommunity.com/id/hussains/" target="_blank" rel="noopener noreferrer" class="social-link">
            <i class="fa-brands fa-steam"></i>
            Steam
        </a>

        <a href="https://www.xbox.com/en-GB/play/user/hjay232" target="_blank" rel="noopener noreferrer" class="social-link">
            <i class="fa-brands fa-xbox"></i>
            Xbox
        </a>

    </div>
</div>

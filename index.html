<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Song</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&display=swap" rel="stylesheet">
    <style>
        /* --- ARCHITECTURE MINDSET: CSS Variables & Global Styles --- */
        :root {
            /* Color Palette */
            --primary-accent: #00ff7f; /* Neon Green/Control */
            --secondary-accent: #ff3366; /* Pink/Branding */
            --bg-deep: #0a0a0a; /* Deep Black Background */
            --bg-card: #141414; /* Elevated Card Surface */
            --text-high: #ffffff;
            --text-low: #b3b3b3;

            /* Spacing */
            --spacing-xs: 4px;
            --spacing-sm: 8px;
            --spacing-md: 16px;
            --spacing-lg: 24px;

            /* UI Elements */
            --border-radius-sm: 4px;
            --border-radius-lg: 10px;
        }

        /* Global Reset */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Poppins', sans-serif;
            -webkit-tap-highlight-color: transparent; 
            touch-action: manipulation;
            -ms-touch-action: pan-x pan-y;
        }
        body {
            background-color: var(--bg-deep);
            color: var(--text-high);
            /* Fixed Scene Lock */
            height: 100vh; 
            display: flex;
            flex-direction: column;
            overflow: hidden; 
            font-weight: 400;
        }

        /* --- APP TITLE ANIMATION --- */
        #appTitle {
            font-size: 1.5rem;
            font-weight: 800;
            text-align: center;
            padding: var(--spacing-md);
            background-color: var(--bg-deep);
            color: var(--text-high);
            position: sticky;
            top: 0;
            z-index: 10;
        }

        /* Animation for "Song" */
        .char {
            display: inline-block;
            opacity: 0;
            animation: fadeIn 0.8s forwards;
            animation-delay: calc(0.1s * var(--char-index));
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(10px) scale(0.8);
            }
            to {
                opacity: 1;
                transform: translateY(0) scale(1);
            }
        }
        #appTitle .char:nth-child(1) { color: var(--primary-accent); } /* S */
        #appTitle .char:nth-child(2) { color: var(--secondary-accent); } /* o */
        #appTitle .char:nth-child(3) { color: var(--primary-accent); } /* n */
        #appTitle .char:nth-child(4) { color: var(--secondary-accent); } /* g */
        
        /* --- NAVIGATION (Bottom Bar Style for Modern Mobile Apps) --- */
        .navigation {
            display: flex;
            justify-content: space-around;
            padding: var(--spacing-sm) 0;
            background-color: var(--bg-card);
            box-shadow: 0 -4px 10px rgba(0, 0, 0, 0.5);
            position: fixed; 
            bottom: 0;
            left: 0;
            right: 0;
            z-index: 30;
        }
        .nav-item {
            cursor: pointer;
            text-align: center;
            font-size: 0.75rem;
            font-weight: 600;
            color: var(--text-low);
            transition: color 0.2s;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .nav-item.active {
            color: var(--primary-accent);
        }
        .nav-item svg {
            width: 22px;
            height: 22px;
            fill: currentColor; 
            margin-bottom: 2px;
        }
        
        /* --- LAYOUT AND SCROLLABLE CONTENT --- */
        .main-container {
            /* Adjusted Height: Total Height - Nav Bar (60px) - Player Bar (approx 145px) - Title Bar (approx 50px) */
            height: calc(100vh - 60px - 145px - 50px); 
            flex-grow: 1;
            overflow-y: auto; 
            padding: 0 var(--spacing-md); /* Removed top padding, title is fixed */
        }
        .content-section {
            display: none;
        }
        .content-section.active {
            display: block;
        }
        .heading-module {
            font-size: 1.5rem;
            font-weight: 700;
            margin: var(--spacing-lg) 0 var(--spacing-md);
            border-left: 4px solid var(--secondary-accent);
            padding-left: var(--spacing-sm);
        }

        /* --- SEARCH BAR --- */
        .search-container-top {
            display: flex;
            gap: var(--spacing-sm);
            padding: var(--spacing-md) 0;
            position: sticky; 
            top: 0;
            background-color: var(--bg-deep);
            z-index: 5;
        }
        #searchInput {
            flex-grow: 1;
            padding: 10px var(--spacing-md);
            border-radius: 50px;
            border: none;
            background-color: var(--bg-card);
            color: var(--text-high);
            font-size: 1rem;
            outline: none;
            box-shadow: inset 0 0 5px rgba(0, 0, 0, 0.4);
        }
        .search-button {
            padding: 10px 20px;
            border-radius: 50px;
            border: none;
            background-color: var(--primary-accent);
            color: var(--bg-deep);
            cursor: pointer;
            font-weight: 700;
            transition: transform 0.1s, background-color 0.2s;
        }
        .search-button:active {
            transform: scale(0.95);
        }

        /* --- CARD MODULES (Home Grid) --- */
        .module-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(140px, 1fr));
            gap: var(--spacing-md);
            margin-bottom: var(--spacing-lg);
        }
        .card-module {
            background-color: var(--bg-card);
            padding: var(--spacing-md);
            border-radius: var(--border-radius-lg);
            text-align: center;
            cursor: pointer;
            transition: background-color 0.2s, transform 0.1s;
        }
        .card-module:hover {
            background-color: #222;
        }
        .card-module img {
            width: 100%;
            aspect-ratio: 1 / 1;
            border-radius: var(--border-radius-sm);
            margin-bottom: var(--spacing-sm);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
        }
        .card-module strong {
            display: block;
            font-size: 0.9rem;
            font-weight: 600;
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
        }
        .card-module span {
            font-size: 0.75rem;
            color: var(--text-low);
        }
        
        /* --- TRACK LIST (Search/Queue) --- */
        .track-list {
            display: flex;
            flex-direction: column;
            gap: var(--spacing-xs);
        }
        .track-item {
            display: flex;
            align-items: center;
            padding: var(--spacing-sm);
            background-color: transparent;
            border-radius: var(--border-radius-sm);
            cursor: pointer;
            transition: background-color 0.2s;
        }
        .track-item:hover {
            background-color: #1a1a1a;
        }
        .track-item.is-playing {
             border-left: 3px solid var(--primary-accent);
             background-color: #1a1a1a;
        }
        .track-item.is-playing .track-info strong {
            color: var(--primary-accent);
        }

        .track-item img {
            width: 40px;
            height: 40px;
            border-radius: var(--border-radius-sm);
            margin-right: var(--spacing-md);
            object-fit: cover;
        }
        .track-info {
            flex-grow: 1;
            overflow: hidden;
        }
        .track-info strong {
            display: block;
            font-size: 0.9em;
            font-weight: 600;
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
            color: var(--text-high);
            transition: color 0.2s;
        }
        .track-info span {
            display: block;
            font-size: 0.75em;
            color: var(--text-low);
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
        }
        .track-icon {
            width: 18px;
            height: 18px;
            fill: currentColor;
            margin-left: var(--spacing-sm);
            flex-shrink: 0;
        }
        .loading-state {
            color: var(--text-low);
            text-align: center;
            padding: var(--spacing-lg);
        }

        /* --- PLAYER BAR (Fixed Footer) --- */
        .player-bar-container {
            position: fixed; 
            bottom: 60px; 
            left: 0;
            right: 0;
            padding: var(--spacing-sm) var(--spacing-md);
            background-color: var(--bg-card);
            box-shadow: 0 -4px 15px rgba(0, 0, 0, 0.7);
            z-index: 20;
            display: flex;
            flex-direction: column;
            gap: var(--spacing-sm);
        }
        
        /* Player Info Row */
        .player-info-row {
            display: flex;
            align-items: center;
            gap: var(--spacing-md);
        }
        #playerAlbumArt {
            width: 55px;
            height: 55px;
            border-radius: var(--border-radius-sm);
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.5);
            flex-shrink: 0;
        }
        .player-controls-group {
            display: flex;
            align-items: center;
            gap: var(--spacing-sm);
            margin-left: auto;
        }
        .control-button {
            background: none;
            border: none;
            cursor: pointer;
            line-height: 0;
            padding: var(--spacing-xs);
        }
        .control-button svg {
            width: 28px;
            height: 28px;
            fill: var(--primary-accent);
            transition: fill 0.2s, transform 0.1s;
        }
        .control-button:active svg {
            transform: scale(0.9);
        }
        #playPauseButton svg {
             width: 38px;
             height: 38px;
        }

        /* Utility/Shuffle/Repeat Icons */
        .utility-icon {
            width: 20px;
            height: 20px;
            fill: var(--text-low);
            transition: fill 0.2s;
        }
        .utility-icon.active {
            fill: var(--primary-accent);
        }

        /* Seek and Time Display */
        .seek-container {
            display: flex;
            align-items: center;
            gap: var(--spacing-sm);
        }
        .time-display {
            font-size: 0.7rem;
            color: var(--text-low);
            width: 30px; 
            text-align: center;
        }
        #seekSlider {
            -webkit-appearance: none;
            appearance: none;
            flex-grow: 1;
            height: 4px;
            background: #444;
            border-radius: 5px;
            outline: none;
        }
        #seekSlider::-webkit-slider-thumb {
            -webkit-appearance: none;
            appearance: none;
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background: var(--secondary-accent);
            cursor: pointer;
        }
        
        /* Volume Slider (Hidden on small mobile screens to save space) */
        .volume-control-group {
            display: none;
        }
        @media (min-width: 600px) {
            .volume-control-group {
                display: flex;
                align-items: center;
                gap: var(--spacing-sm);
                margin-left: var(--spacing-md);
            }
            #volumeSlider {
                 width: 80px;
            }
        }
    </style>
</head>
<body>
    
    <div id="appTitle">
        <span class="char" style="--char-index: 0;">S</span>
        <span class="char" style="--char-index: 1;">o</span>
        <span class="char" style="--char-index: 2;">n</span>
        <span class="char" style="--char-index: 3;">g</span>
    </div>

    <div class="main-container">
        
        <div id="home-section" class="content-section active">
            <h2 class="heading-module" style="border-color: var(--primary-accent);">Discover Music</h2>
            <p class="loading-state" id="homeLoading">Loading categories...</p>

            <h2 class="heading-module" id="hindi-title">Hindi</h2>
            <div id="hindi-grid" class="module-grid"></div>

            <h2 class="heading-module" id="english-title">English</h2>
            <div id="english-grid" class="module-grid"></div>
                
            <h2 class="heading-module" id="bhojpuri-title">Bhojpuri</h2>
            <div id="bhojpuri-grid" class="module-grid"></div>
        </div>
        
        <div id="search-section" class="content-section">
            <div class="search-container-top">
                <input type="text" id="searchInput" placeholder="Search song, album, artist..." onkeypress="handleKeyPress(event)">
                <button class="search-button" onclick="searchSaavn()">Search</button>
            </div>

            <h2 class="heading-module" style="border-color: var(--secondary-accent);">Search Results / Tracks</h2>
            <div id="songResults" class="track-list">
                <p class="loading-state">Type above to start searching.</p>
            </div>
        </div>

        <div id="queue-section" class="content-section">
            <h2 class="heading-module" style="border-color: var(--secondary-accent);">Current Queue / Up Next</h2>
            <div id="queueList" class="track-list">
                <p class="loading-state">No songs in the queue.</p>
            </div>
        </div>

    </div>

    <div class="player-bar-container">
        
        <div class="player-info-row">
            <img id="playerAlbumArt" src="data:image/gif;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs=" alt="Album Art" style="background-color: #333;">
            
            <div class="player-info">
                <div id="nowPlayingName" style="font-weight: 700;">No song is playing.</div>
                <div id="nowPlayingArtist" style="font-size: 0.8em; color: var(--text-low);"></div>
            </div>
            
            <div class="player-controls-group">
                <button id="shuffleButton" class="control-button" onclick="toggleShuffle()" title="Shuffle">
                    <svg class="utility-icon" id="shuffleIcon" viewBox="0 0 24 24"><path d="M14 4H18V8H14V4M14 14H18V18H14V14M10 18V15.4L4.85 10.25L6.27 8.83L11.5 14.06V11.23L16.25 6.47L17.66 7.88L11.5 14.06L16.73 19.3L15.31 20.72L10 15.49V18Z" /></svg>
                </button>
                
                <button id="repeatButton" class="control-button" onclick="toggleRepeat()" title="Repeat">
                    <svg class="utility-icon" id="repeatIcon" viewBox="0 0 24 24"><path d="M17 17.5V14.5L20.5 18L17 21.5V18.5H15A4 4 0 0 1 11 14.5V10.5H13V14.5A2 2 0 0 0 15 16.5H17Z M7 6.5V9.5L3.5 6L7 2.5V5.5H9A4 4 0 0 1 13 9.5V13.5H11V9.5A2 2 0 0 0 9 7.5H7Z" /></svg>
                </button>

                <div class="volume-control-group">
                    <svg class="utility-icon" viewBox="0 0 24 24"><path d="M14 3.23V5.29C16.89 6.15 19 8.83 19 12C19 15.17 16.89 17.85 14 18.71V20.77C18 19.86 21 16.29 21 12C21 7.71 18 4.14 14 3.23M16.5 12C16.5 10.23 15.5 8.71 14 7.97V16.03C15.5 15.29 16.5 13.77 16.5 12M3 9V15H7L12 20V4L7 9H3Z" /></svg>
                    <input type="range" id="volumeSlider" min="0" max="1" step="0.01" value="0.7" style="height: 2px;">
                </div>
            </div>
        </div>

        <div class="seek-container">
            <span id="currentTime" class="time-display">0:00</span>
            <input type="range" id="seekSlider" min="0" max="100" value="0">
            <span id="totalDuration" class="time-display">0:00</span>
        </div>
        
        <div style="display: flex; justify-content: center; margin: var(--spacing-xs) 0;">
             <button id="prevButton" class="control-button" onclick="playPrev()" title="Previous">
                <svg viewBox="0 0 24 24" style="width:24px;height:24px;"><path d="M6 6H8V18H6V6M9.5 12L18 18V6L9.5 12Z" /></svg>
            </button>
            <button id="playPauseButton" class="control-button" onclick="togglePlayPause()" title="Play/Pause">
                <svg id="playIcon" viewBox="0 0 24 24"><path d="M8 5.14V19.14L19 12.14L8 5.14Z" /></svg>
                <svg id="pauseIcon" style="display:none;" viewBox="0 0 24 24"><path d="M14 19H18V5H14M6 19H10V5H6V19Z" /></svg>
            </button>
            <button id="nextButton" class="control-button" onclick="playNext()" title="Next">
                <svg viewBox="0 0 24 24" style="width:24px;height:24px;"><path d="M16 18H18V6H16V18M6 6V18L14.5 12L6 6Z" /></svg>
            </button>
        </div>

        <audio id="audioPlayer"></audio>
    </div>
    
    <div class="navigation">
        <div class="nav-item active" data-target="home-section" onclick="changeSection(this)">
            <svg viewBox="0 0 24 24"><path d="M10 20V14H14V20H19V12H22L12 3L2 12H5V20H10Z" /></svg>
            Home
        </div>
        <div class="nav-item" data-target="search-section" onclick="changeSection(this)">
            <svg viewBox="0 0 24 24"><path d="M9.5,3A6.5,6.5 0 0,1 16,9.5C16,11.11 15.41,12.59 14.44,13.73L19.71,19L18.29,20.41L12.97,15.14C11.85,15.77 10.55,16 9.5,16A6.5,6.5 0 0,1 3,9.5A6.5,6.5 0 0,1 9.5,3M9.5,5A4.5,4.5 0 0,0 5,9.5A4.5,4.5 0 0,0 9.5,14A4.5,4.5 0 0,0 14,9.5A4.5,4.5 0 0,0 9.5,5Z" /></svg>
            Search
        </div>
        <div class="nav-item" data-target="queue-section" onclick="changeSection(this)">
            <svg viewBox="0 0 24 24"><path d="M10,21H14V17H10V21M12,3A9,9 0 0,0 3,12A9,9 0 0,0 12,21A9,9 0 0,0 21,12A9,9 0 0,0 12,3M12,19A7,7 0 0,1 5,12A7,7 0 0,1 12,5A7,7 0 0,1 19,12A7,7 0 0,1 12,19Z" /></svg>
            Queue
        </div>
    </div>

    <script>
        // --- CONFIGURATION ---
        const API_BASE_URL = 'https://saavn.dev/api/search/songs'; 
        
        const CATEGORY_CONFIG = [
            { id: 'hindi-grid', title: 'Hindi', query: 'Latest Hindi Songs', primary: true }, 
            // UPDATED QUERY for more professional/top English songs
            { id: 'english-grid', title: 'English', query: 'Hollywood Top Hits' }, 
            { id: 'bhojpuri-grid', title: 'Bhojpuri', query: 'Bhojpuri Song' }
        ];

        // --- DOM Elements ---
        const audioPlayer = document.getElementById('audioPlayer');
        const songResultsDiv = document.getElementById('songResults');
        const queueListDiv = document.getElementById('queueList');
        const nowPlayingName = document.getElementById('nowPlayingName');
        const nowPlayingArtist = document.getElementById('nowPlayingArtist');
        const playerAlbumArt = document.getElementById('playerAlbumArt');
        const playIcon = document.getElementById('playIcon');
        const pauseIcon = document.getElementById('pauseIcon');
        const seekSlider = document.getElementById('seekSlider');
        const currentTimeDisplay = document.getElementById('currentTime');
        const totalDurationDisplay = document.getElementById('totalDuration');
        const volumeSlider = document.getElementById('volumeSlider');
        const shuffleIcon = document.getElementById('shuffleIcon');
        const repeatIcon = document.getElementById('repeatIcon');

        // --- State Variables ---
        let currentPlaylist = [];
        let originalPlaylist = [];
        let currentTrackIndex = -1;
        let isShuffling = false;
        let repeatMode = 0; // 0: None, 1: All, 2: Single

        // --- UTILITIES ---
        function formatTime(seconds) {
            const minutes = Math.floor(seconds / 60);
            const remainingSeconds = Math.floor(seconds % 60);
            return `${minutes}:${remainingSeconds < 10 ? '0' : ''}${remainingSeconds}`;
        }
        
        function changeSection(element) {
            document.querySelectorAll('.nav-item').forEach(nav => nav.classList.remove('active'));
            element.classList.add('active');
            
            document.querySelectorAll('.content-section').forEach(section => section.classList.remove('active'));
            document.getElementById(element.getAttribute('data-target')).classList.add('active');
            
            document.querySelector('.main-container').scrollTop = 0;

            if (element.getAttribute('data-target') === 'queue-section') {
                displayQueue();
            }
        }
        
        // --- PLAYER CONTROLS ---

        function updatePlayPauseIcons(isPaused) {
            playIcon.style.display = isPaused ? 'block' : 'none';
            pauseIcon.style.display = isPaused ? 'none' : 'block';
        }
        
        function updatePlayerUI(track) {
             const albumArtUrl = track.image.length > 0 ? track.image[0].url : '';
             nowPlayingName.textContent = track.name;
             nowPlayingArtist.textContent = track.artists.primary.map(a => a.name).join(', ');
             playerAlbumArt.src = albumArtUrl || 'data:image/gif;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs=';
        }

        function updateTrackHighlight(newIndex) {
            document.querySelectorAll('.track-item').forEach((trackDiv) => {
                trackDiv.classList.remove('is-playing');
            });
            
            const playingTrack = document.querySelector(`.track-item[data-index="${newIndex}"]`);
            if (playingTrack) {
                playingTrack.classList.add('is-playing');
                if (document.getElementById('queue-section').classList.contains('active')) {
                     playingTrack.scrollIntoView({ behavior: 'smooth', block: 'nearest' });
                }
            }
        }
        
        function playSong(index) {
            if (index < 0 || index >= currentPlaylist.length) return;

            const track = currentPlaylist[index];
            const streamUrlObject = track.downloadUrl.find(u => u.quality.includes('320')) || track.downloadUrl.slice(-1)[0];
            const streamUrl = streamUrlObject ? streamUrlObject.url : null;
            
            if (streamUrl) {
                updateTrackHighlight(index);
                currentTrackIndex = index;
                
                audioPlayer.pause(); 
                audioPlayer.src = streamUrl;
                audioPlayer.load();
                
                audioPlayer.play()
                    .then(() => {
                        updatePlayerUI(track);
                        updatePlayPauseIcons(false);
                        displayQueue(); 
                    })
                    .catch(error => {
                        console.error('Playback failed (Likely CORS/Unstable URL):', error);
                        alert('Playback failed. Check console for details. (URL unstable)');
                        updatePlayPauseIcons(true);
                    });
            } else {
                alert('Streaming URL not found for this track.');
            }
        }

        function togglePlayPause() {
            if (audioPlayer.paused) {
                if (currentTrackIndex === -1 && currentPlaylist.length > 0) {
                     playSong(0); 
                } else if (currentTrackIndex !== -1) {
                     audioPlayer.play().catch(e => console.error("Play failed:", e));
                }
            } else {
                audioPlayer.pause();
            }
        }
        
        function playNext() {
            if (currentPlaylist.length === 0) return;

            if (repeatMode === 2 && currentTrackIndex !== -1) { 
                audioPlayer.currentTime = 0;
                audioPlayer.play();
                return;
            }

            let nextIndex = (currentTrackIndex + 1) % currentPlaylist.length;
            
            if (repeatMode === 0 && nextIndex === 0 && currentTrackIndex === currentPlaylist.length - 1) { 
                audioPlayer.pause();
                updatePlayPauseIcons(true);
                return;
            }

            playSong(nextIndex);
        }

        function playPrev() {
            if (currentPlaylist.length === 0) return;
            
            if (audioPlayer.currentTime > 3) {
                audioPlayer.currentTime = 0;
                return;
            }
            
            let prevIndex = currentTrackIndex - 1;
            if (prevIndex < 0) {
                prevIndex = currentPlaylist.length - 1;
            }
            playSong(prevIndex);
        }
        
        function toggleShuffle() {
            isShuffling = !isShuffling;
            shuffleIcon.classList.toggle('active', isShuffling);
            
            if (isShuffling) {
                originalPlaylist = [...currentPlaylist];
                currentPlaylist.sort(() => Math.random() - 0.5);
                
                if (currentTrackIndex !== -1) {
                    const currentTrack = originalPlaylist[currentTrackIndex];
                    currentTrackIndex = currentPlaylist.findIndex(t => t.id === currentTrack.id);
                }
            } else {
                if (currentTrackIndex !== -1) {
                    const currentTrack = currentPlaylist[currentTrackIndex];
                    currentTrackIndex = originalPlaylist.findIndex(t => t.id === currentTrack.id);
                }
                currentPlaylist = [...originalPlaylist];
            }
            displayQueue();
            updateTrackHighlight(currentTrackIndex);
        }

        function toggleRepeat() {
            repeatMode = (repeatMode + 1) % 3;
            repeatIcon.classList.remove('active'); 
            
            if (repeatMode === 1) { 
                repeatIcon.classList.add('active');
                repeatIcon.innerHTML = '<path d="M17 17.5V14.5L20.5 18L17 21.5V18.5H15A4 4 0 0 1 11 14.5V10.5H13V14.5A2 2 0 0 0 15 16.5H17Z M7 6.5V9.5L3.5 6L7 2.5V5.5H9A4 4 0 0 1 13 9.5V13.5H11V9.5A2 2 0 0 0 9 7.5H7Z" />';
            } else if (repeatMode === 2) { 
                repeatIcon.classList.add('active');
                repeatIcon.innerHTML = '<path d="M17 17.5V14.5L20.5 18L17 21.5V18.5H15A4 4 0 0 1 11 14.5V10.5H13V14.5A2 2 0 0 0 15 16.5H17Z M7 6.5V9.5L3.5 6L7 2.5V5.5H9A4 4 0 0 1 13 9.5V13.5H11V9.5A2 2 0 0 0 9 7.5H7Z M10 10H14V14H10V10Z" />'; 
            } else { 
                repeatIcon.innerHTML = '<path d="M17 17.5V14.5L20.5 18L17 21.5V18.5H15A4 4 0 0 1 11 14.5V10.5H13V14.5A2 2 0 0 0 15 16.5H17Z M7 6.5V9.5L3.5 6L7 2.5V5.5H9A4 4 0 0 1 13 9.5V13.5H11V9.5A2 2 0 0 0 9 7.5H7Z" />';
            }
        }
        
        // --- RENDERING FUNCTIONS ---

        function createTrackElement(track, index) {
            const trackDiv = document.createElement('div');
            trackDiv.className = 'track-item';
            trackDiv.setAttribute('data-index', index);
            
            const albumArt = track.image.length > 0 ? track.image[0].url : ''; 
            
            trackDiv.innerHTML = `
                <img src="${albumArt}" alt="Album Art">
                <div class="track-info">
                    <strong>${track.name}</strong>
                    <span>${track.artists.primary.map(a => a.name).join(', ')} | ${track.album.name}</span>
                </div>
                <svg class="track-icon" viewBox="0 0 24 24"><path d="M12 3V13.55A4 4 0 1 0 14 17V7H18V3H12Z" /></svg>
            `;
            
            trackDiv.onclick = () => playSong(index); 
            return trackDiv;
        }

        function displaySearchResults(tracks) {
            songResultsDiv.innerHTML = '';
            currentPlaylist = tracks; 
            if (!isShuffling) originalPlaylist = [...currentPlaylist];
            currentTrackIndex = -1;
            
            tracks.forEach((track, index) => {
                songResultsDiv.appendChild(createTrackElement(track, index));
            });
        }

        function displayQueue() {
            queueListDiv.innerHTML = '';
            if (currentPlaylist.length === 0) {
                queueListDiv.innerHTML = '<p class="loading-state">No songs in the queue.</p>';
                return;
            }
            currentPlaylist.forEach((track, index) => {
                 queueListDiv.appendChild(createTrackElement(track, index));
            });
            updateTrackHighlight(currentTrackIndex);
        }

        function createModuleCard(item, index, categoryId) {
            const card = document.createElement('div');
            card.className = 'card-module';
            
            const image = item.image.length > 0 ? item.image[2].url : 'data:image/gif;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs=';
            
            card.innerHTML = `
                <img src="${image}" alt="${item.name}">
                <strong>${item.name}</strong>
                <span>${item.artists.primary.map(a => a.name).join(', ')}</span>
            `;
            
            // LOGIC CHANGE: Click on card loads full 50-song playlist and starts playing the clicked song.
            card.onclick = () => {
                // Find the full category configuration
                const category = CATEGORY_CONFIG.find(c => c.id === categoryId);
                
                // 1. Load the full 50-song list and set it as the current playlist
                loadCategoryTracks(category, true)
                    .then(fullList => {
                        // 2. Find the index of the clicked song in the new 50-song playlist
                        const trackIndex = fullList.findIndex(t => t.id === item.id);
                        
                        if (trackIndex !== -1) {
                            playSong(trackIndex);
                        } else {
                            // This shouldn't happen if the API returns consistent results, but is a safe fallback
                            playSong(0); 
                        }
                    })
                    .catch(error => {
                         alert('Could not set category playlist.');
                    });
            }; 
            
            return card;
        }

        // --- DATA FETCHING ---
        async function fetchTracks(query, limit = 5) {
            try {
                const response = await fetch(`${API_BASE_URL}?query=${encodeURIComponent(query)}&limit=${limit}`);
                if (!response.ok) throw new Error(`HTTP Error: ${response.status}`);
                
                const json = await response.json();
                return json.success && json.data && json.data.results ? json.data.results : [];

            } catch (error) {
                console.error(`Error fetching tracks for query "${query}":`, error);
                return null;
            }
        }

        async function loadCategoryTracks(category, forPlaylist = false) {
            const limit = forPlaylist ? 50 : 5; // 50 for playlist, 5 for home screen preview
            const tracks = await fetchTracks(category.query, limit);

            if (tracks === null) {
                if (!forPlaylist) {
                    document.getElementById(category.id).innerHTML = `<p class="loading-state" style="color:var(--secondary-accent);">API Error: Failed to load tracks for ${category.title}.</p>`;
                }
                return [];
            }

            if (forPlaylist) {
                // For playlist setting (limit 50)
                currentPlaylist = tracks;
                originalPlaylist = [...currentPlaylist];
                return tracks;
            } else {
                // For Home Screen display (limit 5)
                const grid = document.getElementById(category.id);
                grid.innerHTML = ''; 
                
                if (tracks.length === 0) {
                    grid.innerHTML = '<p class="loading-state">No songs found.</p>';
                } else {
                    tracks.forEach((item, index) => {
                         grid.appendChild(createModuleCard(item, index, category.id)); 
                    });
                }
                return tracks;
            }
        }

        async function searchSaavn() {
            const query = document.getElementById('searchInput').value.trim();
            if (!query) return;

            songResultsDiv.innerHTML = '<p class="loading-state">Searching...</p>';
            changeSection(document.querySelector('.nav-item[data-target="search-section"]'));

            const tracks = await fetchTracks(query, 50);

            if (tracks === null) {
                songResultsDiv.innerHTML = `<p class="loading-state" style="color:var(--secondary-accent);">API Error: Could not connect to streaming service.</p>`;
            } else if (tracks.length > 0) {
                displaySearchResults(tracks); 
            } else {
                songResultsDiv.innerHTML = '<p class="loading-state">No results found.</p>';
            }
        }

        // --- INITIALIZATION ---
        async function initializeApp() {
            document.getElementById('homeLoading').style.display = 'none';

            let initialPlaylistSet = false;
            for (const category of CATEGORY_CONFIG) {
                // 1. Load 5 tracks for the Home Screen UI
                const tracks = await loadCategoryTracks(category);
                
                // 2. Set the full (50 song) playlist for the primary category (e.g., Hindi) as the default queue
                if (category.primary && tracks.length > 0 && !initialPlaylistSet) {
                     await loadCategoryTracks(category, true); 
                     initialPlaylistSet = true;
                }
            }
        }

        // --- EVENT LISTENERS ---
        
        // Time and Seek Updates
        audioPlayer.addEventListener('timeupdate', () => {
            if (!isNaN(audioPlayer.duration) && audioPlayer.duration > 0) {
                const percentage = (audioPlayer.currentTime / audioPlayer.duration) * 100;
                seekSlider.value = percentage;
                currentTimeDisplay.textContent = formatTime(audioPlayer.currentTime);
            }
        });

        audioPlayer.addEventListener('loadedmetadata', () => {
             totalDurationDisplay.textContent = formatTime(audioPlayer.duration);
             seekSlider.max = 100;
        });

        seekSlider.addEventListener('input', () => {
            if (!isNaN(audioPlayer.duration) && audioPlayer.duration > 0) {
                const seekTime = (seekSlider.value / 100) * audioPlayer.duration;
                audioPlayer.currentTime = seekTime;
                currentTimeDisplay.textContent = formatTime(seekTime);
            }
        });

        // Other Player Events
        audioPlayer.addEventListener('ended', playNext);
        audioPlayer.volume = volumeSlider.value;
        volumeSlider.addEventListener('input', (e) => {
            audioPlayer.volume = e.target.value;
        });
        audioPlayer.addEventListener('play', () => {
             updatePlayPauseIcons(false);
             if (currentTrackIndex !== -1) updateTrackHighlight(currentTrackIndex);
        });
        audioPlayer.addEventListener('pause', () => {
             updatePlayPauseIcons(true);
        });
        
        function handleKeyPress(event) {
            if (event.key === 'Enter') {
                searchSaavn();
            }
        }

        // Start the application
        updatePlayPauseIcons(true);
        initializeApp();
    </script>
</body>
</html>

<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZolloRokuro | Official Live Stream & Gaming Hub</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&family=Rajdhani:wght@500;600;700&display=swap" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        cyber: {
                            dark: '#0a0d14',
                            card: '#121722',
                            cardLight: '#1b2232',
                            purple: '#9333ea',
                            magenta: '#e11d48',
                            cyan: '#06b6d4',
                            green: '#10b981',
                            border: '#242e42'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        display: ['Rajdhani', 'sans-serif'],
                    },
                    boxShadow: {
                        'neon-cyan': '0 0 20px rgba(6, 182, 212, 0.35)',
                        'neon-purple': '0 0 20px rgba(147, 51, 234, 0.35)',
                        'neon-magenta': '0 0 20px rgba(225, 29, 72, 0.35)'
                    }
                }
            }
        }
    </script>

    <style>
        .font-display { font-family: 'Rajdhani', sans-serif; }
        
        .glow-text-cyan { text-shadow: 0 0 12px rgba(6, 182, 212, 0.6); }
        .glow-text-purple { text-shadow: 0 0 12px rgba(147, 51, 234, 0.6); }

        @keyframes pulse-glow {
            0%, 100% { opacity: 0.2; transform: scale(1); }
            50% { opacity: 0.35; transform: scale(1.08); }
        }
        .animate-ambient {
            animation: pulse-glow 9s infinite ease-in-out;
        }

        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #0a0d14; }
        ::-webkit-scrollbar-thumb { background: #242e42; border-radius: 4px; }
        ::-webkit-scrollbar-thumb:hover { background: #06b6d4; }
    </style>
</head>
<body class="bg-cyber-dark text-slate-100 font-sans antialiased overflow-x-hidden selection:bg-cyber-cyan selection:text-black">

    <!-- Background Glow Canvas Layer -->
    <div class="fixed inset-0 pointer-events-none z-0 overflow-hidden">
        <div class="absolute -top-32 -left-32 w-[500px] h-[500px] bg-cyber-purple/30 rounded-full blur-[140px] animate-ambient"></div>
        <div class="absolute top-1/3 -right-32 w-[500px] h-[500px] bg-cyber-cyan/25 rounded-full blur-[150px] animate-ambient"></div>
        <div class="absolute -bottom-32 left-1/3 w-[500px] h-[500px] bg-cyber-magenta/20 rounded-full blur-[140px] animate-ambient"></div>
    </div>

    <!-- Header Navigation -->
    <header class="sticky top-0 z-50 backdrop-blur-md bg-cyber-dark/85 border-b border-cyber-border">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            
            <!-- Brand Logo -->
            <a href="#" class="flex items-center space-x-3 group">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-cyber-cyan via-cyber-purple to-cyber-magenta p-0.5 shadow-neon-cyan group-hover:scale-105 transition-transform duration-300">
                    <div class="w-full h-full bg-cyber-dark rounded-[10px] flex items-center justify-center">
                        <span class="font-display font-black text-xl text-transparent bg-clip-text bg-gradient-to-r from-cyber-cyan to-cyber-purple">ZR</span>
                    </div>
                </div>
                <span class="font-display font-black text-2xl tracking-wider text-white group-hover:text-cyber-cyan transition-colors">
                    ZOLLO<span class="text-cyber-cyan">ROKURO</span>
                </span>
            </a>

            <!-- Navigation Links -->
            <nav class="hidden md:flex items-center space-x-8 text-sm font-semibold tracking-wider text-slate-300">
                <a href="#stream" class="hover:text-cyber-cyan transition-colors">STREAM</a>
                <a href="#schedule" class="hover:text-cyber-cyan transition-colors">SCHEDULE</a>
                <a href="#about" class="hover:text-cyber-cyan transition-colors">ABOUT</a>
                <a href="#vods" class="hover:text-cyber-cyan transition-colors">CLIPS & VODS</a>
                <a href="#gear" class="hover:text-cyber-cyan transition-colors">GEAR SETUP</a>
                <a href="#contact" class="hover:text-cyber-cyan transition-colors">CONTACT</a>
            </nav>

            <!-- Action Buttons & Socials -->
            <div class="hidden lg:flex items-center space-x-3">
                <a href="https://twitch.tv/zollorokuro" target="_blank" class="w-9 h-9 rounded-lg bg-cyber-card border border-cyber-border flex items-center justify-center text-slate-300 hover:text-white hover:bg-cyber-purple hover:border-cyber-purple transition-all">
                    <i class="fa-brands fa-twitch"></i>
                </a>
                <a href="https://www.youtube.com/@GoldenLixir_" target="_blank" class="w-9 h-9 rounded-lg bg-cyber-card border border-cyber-border flex items-center justify-center text-slate-300 hover:text-white hover:bg-red-600 hover:border-red-600 transition-all">
                    <i class="fa-brands fa-youtube"></i>
                </a>
                <a href="https://discord.gg/Mx7MyfjKKC" target="_blank" class="w-9 h-9 rounded-lg bg-cyber-card border border-cyber-border flex items-center justify-center text-slate-300 hover:text-white hover:bg-indigo-600 hover:border-indigo-600 transition-all">
                    <i class="fa-brands fa-discord"></i>
                </a>
                <a href="#stream" class="ml-2 px-4 py-2 rounded-lg bg-gradient-to-r from-cyber-cyan to-cyber-purple hover:opacity-90 transition-opacity font-bold text-xs text-white tracking-widest uppercase shadow-neon-cyan flex items-center space-x-2">
                    <span class="w-2 h-2 rounded-full bg-white animate-ping"></span>
                    <span>WATCH LIVE</span>
                </a>
            </div>

            <!-- Mobile Menu Toggle -->
            <button id="mobileMenuBtn" class="md:hidden text-slate-300 hover:text-white p-2">
                <i class="fa-solid fa-bars text-2xl"></i>
            </button>
        </div>

        <!-- Mobile Navigation Drawer -->
        <div id="mobileMenu" class="hidden md:hidden bg-cyber-card border-b border-cyber-border px-4 py-4 space-y-3">
            <a href="#stream" class="block py-2 text-slate-200 hover:text-cyber-cyan font-semibold">STREAM</a>
            <a href="#schedule" class="block py-2 text-slate-200 hover:text-cyber-cyan font-semibold">SCHEDULE</a>
            <a href="#about" class="block py-2 text-slate-200 hover:text-cyber-cyan font-semibold">ABOUT</a>
            <a href="#vods" class="block py-2 text-slate-200 hover:text-cyber-cyan font-semibold">CLIPS & VODS</a>
            <a href="#gear" class="block py-2 text-slate-200 hover:text-cyber-cyan font-semibold">GEAR SETUP</a>
            <a href="#contact" class="block py-2 text-slate-200 hover:text-cyber-cyan font-semibold">CONTACT</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative z-10 pt-12 pb-16 lg:pt-20 lg:pb-24 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid lg:grid-cols-12 gap-12 items-center">
            
            <!-- Left Column Content -->
            <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                
                <!-- Live Status Pill Indicator -->
                <div class="inline-flex items-center space-x-3 px-4 py-2 rounded-full bg-cyber-card border border-cyber-cyan/40 shadow-neon-cyan backdrop-blur-md">
                    <span class="relative flex h-3 w-3">
                        <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-cyber-green opacity-75"></span>
                        <span class="relative inline-flex rounded-full h-3 w-3 bg-cyber-green"></span>
                    </span>
                    <span class="text-xs font-bold tracking-widest uppercase text-cyber-green">LIVE NOW ON TWITCH</span>
                    <span class="text-slate-600">|</span>
                    <span class="text-xs text-slate-300 font-semibold"><i class="fa-solid fa-gamepad text-cyber-cyan mr-1"></i>RainbowSixSiege / Variety</span>
                </div>

                <!-- Hero Title -->
                <h1 class="font-display text-5xl sm:text-7xl font-black tracking-tight text-white leading-none uppercase">
                    WELCOME TO THE <br>
                    <span class="text-transparent bg-clip-text bg-gradient-to-r from-cyber-cyan via-cyber-purple to-cyber-magenta glow-text-cyan">
                        ZOLLO DOMAIN
                    </span>
                </h1>

                <p class="text-slate-400 text-lg max-w-2xl mx-auto lg:mx-0 leading-relaxed">
                    Competitive FPS enthusiast, variety gaming streamer. Play with high-skill plays, good vibes, and community game nights.
                </p>

                <!-- CTA Actions -->
                <div class="flex flex-wrap justify-center lg:justify-start gap-4 pt-2">
                    <a href="#stream" class="px-8 py-4 rounded-xl bg-gradient-to-r from-cyber-cyan to-cyber-purple hover:opacity-90 font-bold text-white shadow-neon-cyan transition-all duration-300 hover:scale-105 flex items-center space-x-3">
                        <i class="fa-brands fa-twitch text-xl"></i>
                        <span>JOIN STREAM</span>
                    </a>
                    <button onclick="copyStreamLink()" class="px-6 py-4 rounded-xl bg-cyber-card border border-cyber-border hover:border-cyber-cyan text-slate-200 hover:text-white font-bold transition-all duration-300 flex items-center space-x-2">
                        <i class="fa-solid fa-share-nodes text-cyber-cyan"></i>
                        <span>SHARE STREAM</span>
                    </button>
                </div>

                <!-- Social Media Bar -->
                <div class="pt-6 border-t border-cyber-border/80 flex flex-wrap items-center justify-center lg:justify-start gap-6 text-sm text-slate-400">
                    <a href="https://twitch.tv/zollorokuro" target="_blank" class="hover:text-cyber-purple transition-colors flex items-center space-x-2">
                        <i class="fa-brands fa-twitch text-lg text-purple-400"></i>
                        <span>Twitch</span>
                    </a>
                    <a href="https://www.youtube.com/@GoldenLixir_" target="_blank" class="hover:text-red-500 transition-colors flex items-center space-x-2">
                        <i class="fa-brands fa-youtube text-lg text-red-500"></i>
                        <span>YouTube</span>
                    </a>
                    <a href="https://x.com/zollorokuro" target="_blank" class="hover:text-sky-400 transition-colors flex items-center space-x-2">
                        <i class="fa-brands fa-x-twitter text-lg text-slate-300"></i>
                        <span>Twitter/X</span>
                    </a>
                    <a href="https://discord.gg/Mx7MyfjKKC" target="_blank" class="hover:text-indigo-400 transition-colors flex items-center space-x-2">
                        <i class="fa-brands fa-discord text-lg text-indigo-400"></i>
                        <span>Discord</span>
                    </a>
                </div>

            </div>

            <!-- Right Column Profile Frame -->
            <div class="lg:col-span-5 relative">
                <div class="relative mx-auto max-w-md lg:max-w-none">
                    <div class="absolute -inset-1 rounded-3xl bg-gradient-to-r from-cyber-cyan via-cyber-purple to-cyber-magenta opacity-40 blur-xl"></div>
                    
                    <div class="relative bg-cyber-card border border-cyber-border rounded-2xl p-6 shadow-2xl">
                        <div class="relative h-88 rounded-xl overflow-hidden bg-slate-900">
                            <img src="C:\Users\golde\OneDrive\Pictures\4f2b0b94-dbc2-4179-aa88-52758b570aa4 - Copy.png" alt="ZolloRokuro Avatar" class="w-full h-88 object-cover">
                            <div class="absolute inset-0 bg-gradient-to-t from-cyber-card via-transparent to-transparent"></div>
                            
                            <div class="absolute bottom-4 left-4 right-4 flex items-center justify-between">
                                <span class="bg-cyber-dark/90 backdrop-blur-md px-3 py-1.5 rounded-lg border border-cyber-border text-xs font-bold text-cyber-cyan">
                                    <i class="fa-solid fa-crown text-amber-400 mr-1"></i> Diamond Ranked Player
                                </span>
                                <span class="bg-red-600 px-3 py-1.5 rounded-lg text-xs font-bold text-white uppercase tracking-wider">
                                    LIVE
                                </span>
                            </div>
                        </div>

                        <div class="mt-4 flex items-center justify-between">
                            <div>
                                <h3 class="font-display font-extrabold text-xl text-white">ZolloRokuro</h3>
                                <p class="text-xs text-cyber-cyan font-semibold">STREAMER & CONTENT CREATOR</p>
                            </div>
                            <div class="text-right">
                                <span class="text-xs text-slate-400 block">Twitch Community</span>
                                <span class="font-display font-bold text-cyber-purple text-lg">200</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </section>


    <!-- Schedule Section with Countdown -->
    <section id="schedule" class="py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
        
        <!-- Section Header -->
        <div class="text-center max-w-2xl mx-auto mb-12">
            <div class="flex items-center justify-center space-x-2 text-cyber-cyan font-bold text-xs uppercase tracking-widest mb-2">
                <i class="fa-solid fa-calendar-alt"></i>
                <span>Broadcast Routine</span>
            </div>
            <h2 class="font-display text-4xl font-black text-white uppercase">STREAMING SCHEDULE</h2>
            <p class="text-slate-400 text-sm mt-2">Catch ZolloRokuro live every week. All times in EST.</p>
        </div>
		<div style="text-align: center; font-size: 45px; font-weight: bold;">
  Coming Soon
</div>
       
    </section>

    <!-- About ZolloRokuro Section -->
    <section id="about" class="py-20 bg-cyber-card/30 border-y border-cyber-border relative z-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-12 gap-12 items-center">

                <!-- Bio Content -->
                <div class="lg:col-span-7 space-y-6">
                    <div class="flex items-center space-x-2 text-cyber-purple font-bold text-xs uppercase tracking-widest">
                        <i class="fa-solid fa-user-astronaut"></i>
                        <span>Who Is ZolloRokuro?</span>
                    </div>
                    <h2 class="font-display text-4xl font-black text-white uppercase">PASSIONATE GAMER & CONTENT CREATOR</h2>
                    <p class="text-slate-400 text-sm leading-relaxed">
                        ZolloRokuro is an energetic live streamer known for exceptional aim, tactical gameplay, and genuine community engagement. Streaming live on Twitch, Zollo has cultivated an inclusive, competitive, and hype environment where gamers of all skill levels meet up.
                    </p>
                    <p class="text-slate-400 text-sm leading-relaxed">
                        Whether pushing ranks in Rainbow Six Siege, clutching 1v4s in tactical shooters, or screaming through indie horror games on Sunday nights, every stream brings high energy and interactive chat engagement.
                    </p>

                    <!-- Favorite Games Badges -->
                    <div class="pt-2">
                        <span class="text-xs font-bold text-slate-300 uppercase tracking-wider block mb-3">MAIN FEATURED GAMES:</span>
                        <div class="flex flex-wrap gap-2">
                            <span class="px-3 py-1.5 rounded-lg bg-cyber-card border border-cyber-border text-xs font-semibold text-cyber-cyan">RainbowSixSiege</span>
                            <span class="px-3 py-1.5 rounded-lg bg-cyber-card border border-cyber-border text-xs font-semibold text-cyber-purple">Wardogs</span>
                            <span class="px-3 py-1.5 rounded-lg bg-cyber-card border border-cyber-border text-xs font-semibold text-cyber-magenta">Call of Duty</span>
                            <span class="px-3 py-1.5 rounded-lg bg-cyber-card border border-cyber-border text-xs font-semibold text-emerald-400">GuildWars 2</span>
                            <span class="px-3 py-1.5 rounded-lg bg-cyber-card border border-cyber-border text-xs font-semibold text-amber-400">Arma Reforger</span>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Clips & VODs Gallery Section -->
    <section id="vods" class="py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
        
        <div class="flex flex-col md:flex-row md:items-end justify-between mb-10 gap-4">
            <div>
                <div class="flex items-center space-x-2 text-cyber-magenta font-bold text-xs uppercase tracking-widest mb-1">
                    <i class="fa-solid fa-film"></i>
                    <span>Media Library</span>
                </div>
                <h2 class="font-display text-3xl sm:text-4xl font-black text-white uppercase">TOP CLIPS & RECENT VODS</h2>
            </div>

            <!-- Filter Buttons -->
            <div class="flex items-center space-x-2 bg-cyber-card p-1.5 rounded-xl border border-cyber-border">
                <button onclick="filterMedia('all')" class="media-filter-btn px-4 py-1.5 rounded-lg text-xs font-bold bg-cyber-cyan text-black" data-filter="all">ALL</button>
                <button onclick="filterMedia('clip')" class="media-filter-btn px-4 py-1.5 rounded-lg text-xs font-bold text-slate-400 hover:text-white" data-filter="clip">CLIPS</button>
                <button onclick="filterMedia('vod')" class="media-filter-btn px-4 py-1.5 rounded-lg text-xs font-bold text-slate-400 hover:text-white" data-filter="vod">FULL VODS</button>
            </div>
        </div>

        <!-- Video Gallery Grid -->
        <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
            
            <!-- Card 1 -->
            <div class="media-card clip bg-cyber-card border border-cyber-border rounded-2xl overflow-hidden group cursor-pointer hover:border-cyber-cyan transition-all" onclick="openMediaModal('CHEATS ENABLED FOR A DIAMOND', 'https://www.twitch.tv/zollorokuro/clip/FaintEndearingHorseCoolStoryBob-XzLKli8ucZCbGY9l?range=all')">
                <div class="relative h-48 bg-slate-900 overflow-hidden">
                    <img src="https://static-cdn.jtvnw.net/twitch-video-assets/twitch-vap-video-assets-prod-us-west-2/900869c5-b4f2-4c5c-bdf3-0ed87f7cb9c4/landscape/thumb/thumb-0000000000-1920x1080.jpg" alt="Clip 1" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                    <div class="absolute inset-0 bg-black/40 flex items-center justify-center">
                        <div class="w-12 h-12 rounded-full bg-cyber-cyan text-black flex items-center justify-center shadow-neon-cyan group-hover:scale-110 transition-transform">
                            <i class="fa-solid fa-play ml-0.5"></i>
                        </div>
                    </div>
                    <span class="absolute bottom-2 right-2 bg-black/80 text-white text-[10px] font-bold px-2 py-0.5 rounded">00:45</span>
                </div>
                <div class="p-4">
                    <span class="text-[10px] font-bold text-cyber-cyan uppercase">TWITCH CLIP</span>
                    <h3 class="font-display font-bold text-white text-base mt-0.5">CHEATS ENABLED FOR A DIAMOND</h3>
                    <p class="text-xs text-slate-400 mt-2"><i class="fa-regular fa-eye mr-1"></i> 45.2K Views</p>
                </div>
            </div>

            <!-- Card 2 -->
            <div class="media-card vod bg-cyber-card border border-cyber-border rounded-2xl overflow-hidden group cursor-pointer hover:border-cyber-purple transition-all" onclick="openMediaModal('FULL BROADCAST: RANKED RADIANT SESH', 'https://www.twitch.tv/videos/2818849530')">
                <div class="relative h-48 bg-slate-900 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1538481199705-c710c4e965fc?auto=format&fit=crop&w=600&q=80" alt="VOD 1" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                    <div class="absolute inset-0 bg-black/40 flex items-center justify-center">
                        <div class="w-12 h-12 rounded-full bg-cyber-purple text-white flex items-center justify-center shadow-neon-purple group-hover:scale-110 transition-transform">
                            <i class="fa-solid fa-play ml-0.5"></i>
                        </div>
                    </div>
                    <span class="absolute bottom-2 right-2 bg-black/80 text-white text-[10px] font-bold px-2 py-0.5 rounded">05:12:30</span>
                </div>
                <div class="p-4">
                    <span class="text-[10px] font-bold text-cyber-purple uppercase">FULL VOD</span>
                    <h3 class="font-display font-bold text-white text-base mt-0.5">FULL BROADCAST: RANKED SESH</h3>
                    <p class="text-xs text-slate-400 mt-2"><i class="fa-regular fa-eye mr-1"></i> 18.9K Views</p>
                </div>
            </div>

        </div>
    </section>

    <!-- Gaming Setup & Gear Section -->
    <section id="gear" class="py-20 bg-cyber-card/30 border-y border-cyber-border relative z-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="text-center max-w-2xl mx-auto mb-12">
                <div class="flex items-center justify-center space-x-2 text-cyber-cyan font-bold text-xs uppercase tracking-widest mb-2">
                    <i class="fa-solid fa-microchip"></i>
                    <span>Hardware Specifications</span>
                </div>
                <h2 class="font-display text-4xl font-black text-white uppercase">ZOLLO'S GAMING & STREAM RIG</h2>
                <p class="text-slate-400 text-sm mt-2">The complete hardware breakdown behind the 1080p 60fps broadcast.</p>
            </div>

            <!-- Gear Specs Grid -->
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                
                <!-- Spec Card 1 -->
                <div class="bg-cyber-card border border-cyber-border rounded-2xl p-6 hover:border-cyber-cyan transition-all">
                    <div class="w-10 h-10 rounded-xl bg-cyber-cyan/10 border border-cyber-cyan/30 flex items-center justify-center text-cyber-cyan mb-4">
                        <i class="fa-solid fa-desktop text-lg"></i>
                    </div>
                    <h3 class="font-display font-bold text-lg text-white">GAMING PC SPECS</h3>
                    <ul class="mt-3 space-y-2 text-xs text-slate-300">
                        <li class="flex justify-between border-b border-cyber-border/60 pb-1.5"><span class="text-slate-400">CPU</span> <span class="font-bold">AMD Ryzen 7 7800X3D</span></li>
                        <li class="flex justify-between border-b border-cyber-border/60 pb-1.5"><span class="text-slate-400">GPU</span> <span class="font-bold">NVIDIA RTX 5060TI</span></li>
                        <li class="flex justify-between border-b border-cyber-border/60 pb-1.5"><span class="text-slate-400">RAM</span> <span class="font-bold">64GB DDR4 6000MHz</span></li>
                        <li class="flex justify-between"><span class="text-slate-400">Storage</span> <span class="font-bold">2TB Gen4 NVMe SSD And More</span></li>
                    </ul>
                </div>

                <!-- Spec Card 2 -->
                <div class="bg-cyber-card border border-cyber-border rounded-2xl p-6 hover:border-cyber-purple transition-all">
                    <div class="w-10 h-10 rounded-xl bg-cyber-purple/10 border border-cyber-purple/30 flex items-center justify-center text-cyber-purple mb-4">
                        <i class="fa-solid fa-keyboard text-lg"></i>
                    </div>
                    <h3 class="font-display font-bold text-lg text-white">PERIPHERALS</h3>
                    <ul class="mt-3 space-y-2 text-xs text-slate-300">
                        <li class="flex justify-between border-b border-cyber-border/60 pb-1.5"><span class="text-slate-400">Mouse</span> <span class="font-bold">Logitech G Pro X Superlight</span></li>
                        <li class="flex justify-between border-b border-cyber-border/60 pb-1.5"><span class="text-slate-400">Keyboard</span> <span class="font-bold">RoyalKludge 75%</span></li>
                        <li class="flex justify-between border-b border-cyber-border/60 pb-1.5"><span class="text-slate-400">Headset</span> <span class="font-bold">MoonDrop Starfild Earbuds</span></li>
                        <li class="flex justify-between"><span class="text-slate-400">Monitor</span> <span class="font-bold">240Hz Preditor</span></li>
                    </ul>
                </div>

                <!-- Spec Card 3 -->
                <div class="bg-cyber-card border border-cyber-border rounded-2xl p-6 hover:border-cyber-magenta transition-all">
                    <div class="w-10 h-10 rounded-xl bg-cyber-magenta/10 border border-cyber-magenta/30 flex items-center justify-center text-cyber-magenta mb-4">
                        <i class="fa-solid fa-microphone text-lg"></i>
                    </div>
                    <h3 class="font-display font-bold text-lg text-white">STREAMING AUDIO & CAM</h3>
                    <ul class="mt-3 space-y-2 text-xs text-slate-300">
                        <li class="flex justify-between border-b border-cyber-border/60 pb-1.5"><span class="text-slate-400">Microphone</span> <span class="font-bold">TONOR Dynamic Microphone</span></li>
                        <li class="flex justify-between border-b border-cyber-border/60 pb-1.5"><span class="text-slate-400">Audio Interface</span> <span class="font-bold">MONO AudioMixer</span></li>
                        <li class="flex justify-between border-b border-cyber-border/60 pb-1.5"><span class="text-slate-400">Camera</span> <span class="font-bold">Logitech C920</span></li>
                        <li class="flex justify-between"><span class="text-slate-400">Lighting</span> <span class="font-bold">2 Smallrig P96's</span></li>
                    </ul>
                </div>

            </div>
        </div>
    </section>

    <!-- Contact / Business Inquiries Section -->
    <section id="contact" class="py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
        <div class="max-w-3xl mx-auto bg-cyber-card border border-cyber-border rounded-3xl p-8 sm:p-10 shadow-2xl">
            <div class="text-center mb-8">
                <span class="text-xs font-bold text-cyber-cyan uppercase tracking-widest block mb-1">BUSINESS & SPONSORSHIPS</span>
                <h2 class="font-display text-3xl font-black text-white uppercase">GET IN TOUCH WITH ZOLLO</h2>
                <p class="text-slate-400 text-xs mt-2">Interested in sponsorship opportunities, brand integrations, or tournament invites?</p>
            </div>

            <form onsubmit="handleContactSubmit(event)" class="space-y-4">
                <div class="grid sm:grid-cols-2 gap-4">
                    <div>
                        <label class="block text-xs font-bold text-slate-300 uppercase mb-1">Your Name</label>
                        <input type="text" required placeholder="John Doe" class="w-full bg-cyber-dark border border-cyber-border rounded-xl px-4 py-3 text-xs text-white focus:outline-none focus:border-cyber-cyan">
                    </div>
                    <div>
                        <label class="block text-xs font-bold text-slate-300 uppercase mb-1">Business Email</label>
                        <input type="email" required placeholder="business@company.com" class="w-full bg-cyber-dark border border-cyber-border rounded-xl px-4 py-3 text-xs text-white focus:outline-none focus:border-cyber-cyan">
                    </div>
                </div>

                <div>
                    <label class="block text-xs font-bold text-slate-300 uppercase mb-1">Subject</label>
                    <input type="text" required placeholder="Sponsorship Proposal / Event Booking" class="w-full bg-cyber-dark border border-cyber-border rounded-xl px-4 py-3 text-xs text-white focus:outline-none focus:border-cyber-cyan">
                </div>

                <div>
                    <label class="block text-xs font-bold text-slate-300 uppercase mb-1">Message</label>
                    <textarea rows="4" required placeholder="Details of your proposal..." class="w-full bg-cyber-dark border border-cyber-border rounded-xl px-4 py-3 text-xs text-white focus:outline-none focus:border-cyber-cyan"></textarea>
                </div>

                <button type="submit" class="w-full py-4 rounded-xl bg-gradient-to-r from-cyber-cyan to-cyber-purple font-bold text-white text-xs uppercase tracking-widest shadow-neon-cyan hover:opacity-90 transition-opacity">
                    SEND INQUIRY
                </button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-cyber-dark border-t border-cyber-border pt-12 pb-8 relative z-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center sm:text-left flex flex-col sm:flex-row items-center justify-between gap-6">
            <div>
                <span class="font-display font-black text-xl text-white">ZOLLO<span class="text-cyber-cyan">ROKURO</span></span>
                <p class="text-xs text-slate-400 mt-1">&copy; 2026 ZolloRokuro Gaming. All rights reserved.</p>
            </div>
            <div class="flex space-x-6 text-sm text-slate-400">
                <a href="https://twitch.tv/zollorokuro" target="_blank" class="hover:text-cyber-purple"><i class="fa-brands fa-twitch"></i></a>
                <a href="https://youtube.com" target="_blank" class="hover:text-red-500"><i class="fa-brands fa-youtube"></i></a>
                <a href="https://x.com" target="_blank" class="hover:text-sky-400"><i class="fa-brands fa-x-twitter"></i></a>
                <a href="https://discord.gg" target="_blank" class="hover:text-indigo-400"><i class="fa-brands fa-discord"></i></a>
            </div>
        </div>
    </footer>

    <!-- Video Modal Popup -->
    <div id="mediaModal" class="fixed inset-0 z-50 hidden bg-black/80 backdrop-blur-md flex items-center justify-center p-4">
        <div class="bg-cyber-card border border-cyber-border w-full max-w-4xl rounded-2xl overflow-hidden shadow-2xl">
            <div class="p-4 border-b border-cyber-border flex items-center justify-between">
                <h3 id="mediaModalTitle" class="font-display font-bold text-white text-sm">Media Player</h3>
                <button onclick="closeMediaModal()" class="text-slate-400 hover:text-white p-1">
                    <i class="fa-solid fa-xmark text-xl"></i>
                </button>
            </div>
            <div class="relative pb-[56.25%] h-0 bg-black">
                <iframe id="mediaIframe" class="absolute top-0 left-0 w-full h-full" src="" frameborder="0" allowfullscreen></iframe>
            </div>
        </div>
    </div>

    <!-- Notification Toast -->
    <div id="toast" class="fixed bottom-6 right-6 z-50 hidden bg-cyber-cyan text-black px-5 py-3 rounded-xl shadow-neon-cyan font-bold text-xs flex items-center space-x-2">
        <i class="fa-solid fa-circle-check"></i>
        <span id="toastMsg">Notification Message</span>
    </div>

    <script>
        // Mobile Navigation Drawer Toggle
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const mobileMenu = document.getElementById('mobileMenu');
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Simulated Twitch Chat Generator
        const mockChatUsers = [
            { name: 'RokuroSub_99', color: 'text-cyber-cyan' },
            { name: 'VortexApex', color: 'text-cyber-purple' },
            { name: 'GamerGirl2026', color: 'text-cyber-magenta' },
            { name: 'ProAimBot', color: 'text-emerald-400' },
            { name: 'HyperSlayer', color: 'text-amber-400' }
        ];

        const mockChatMessages = [
            "LET'S GO ZOLLO! 🔥",
            "What sensitivity are you playing on today?",
            "ROKURO CLAN ON TOP 🚀",
            "Insane movement in that last fight!",
            "GGs in chat everyone!",
            "Can we get viewer games after this match?"
        ];

        const chatFeed = document.getElementById('chatFeed');

        function pushChatMessage(user, message) {
            const chatEl = document.createElement('div');
            chatEl.className = 'leading-relaxed break-words';
            chatEl.innerHTML = `<span class="font-bold ${user.color}">${user.name}:</span> <span class="text-slate-300">${message}</span>`;
            chatFeed.appendChild(chatEl);
            chatFeed.scrollTop = chatFeed.scrollHeight;
        }

        // Initialize Chat
        mockChatMessages.slice(0, 4).forEach((msg, idx) => {
            pushChatMessage(mockChatUsers[idx % mockChatUsers.length], msg);
        });

        // Loop Chat Traffic
        setInterval(() => {
            const user = mockChatUsers[Math.floor(Math.random() * mockChatUsers.length)];
            const msg = mockChatMessages[Math.floor(Math.random() * mockChatMessages.length)];
            pushChatMessage(user, msg);
        }, 3200);

        function handleSendChat(e) {
            e.preventDefault();
            const input = document.getElementById('chatInput');
            if (input.value.trim() !== '') {
                pushChatMessage({ name: 'You (Clan Member)', color: 'text-cyber-cyan' }, input.value.trim());
                input.value = '';
            }
        }

        // Player Video Controls
        let isPlaying = true;
        function togglePauseState() {
            isPlaying = !isPlaying;
            const icon = document.getElementById('pauseIcon');
            const status = document.getElementById('streamStatusText');
            if (isPlaying) {
                icon.className = 'fa-solid fa-pause';
                status.innerText = 'Playing: Apex Legends - Ranked Solo Queue to Predator';
            } else {
                icon.className = 'fa-solid fa-play ml-1';
                status.innerText = 'Stream Stream Paused - Click to Resume';
            }
        }

        function toggleAudio() {
            const icon = document.getElementById('audioIcon');
            if (icon.classList.contains('fa-volume-high')) {
                icon.className = 'fa-solid fa-volume-xmark text-red-500';
            } else {
                icon.className = 'fa-solid fa-volume-high text-base';
            }
        }

        function toggleFullscreen() {
            const playerCol = document.getElementById('playerCol');
            if (!document.fullscreenElement) {
                playerCol.requestFullscreen().catch(() => {
                    showToast('Fullscreen unavailable in preview.');
                });
            } else {
                document.exitFullscreen();
            }
        }

        // Toggle Stream Source & Chat Sidebar
        function toggleStreamSource(type) {
            const chatCol = document.getElementById('chatCol');
            const playerCol = document.getElementById('playerCol');
            
            if (type === 'chat') {
                chatCol.classList.toggle('hidden');
                if (chatCol.classList.contains('hidden')) {
                    playerCol.classList.remove('lg:col-span-8');
                    playerCol.classList.add('lg:col-span-12');
                } else {
                    playerCol.classList.remove('lg:col-span-12');
                    playerCol.classList.add('lg:col-span-8');
                }
            } else {
                showToast('Twitch official stream player active.');
            }
        }

        // Copy Stream Share Link
        function copyStreamLink() {
            const dummy = document.createElement('input');
            document.body.appendChild(dummy);
            dummy.value = 'https://twitch.tv/zollorokuro';
            dummy.select();
            document.execCommand('copy');
            document.body.removeChild(dummy);
            showToast('Stream URL copied to clipboard!');
        }

        // Media Gallery Filters
        function filterMedia(category) {
            const buttons = document.querySelectorAll('.media-filter-btn');
            buttons.forEach(btn => {
                if (btn.getAttribute('data-filter') === category) {
                    btn.className = 'media-filter-btn px-4 py-1.5 rounded-lg text-xs font-bold bg-cyber-cyan text-black';
                } else {
                    btn.className = 'media-filter-btn px-4 py-1.5 rounded-lg text-xs font-bold text-slate-400 hover:text-white';
                }
            });

            const cards = document.querySelectorAll('.media-card');
            cards.forEach(card => {
                if (category === 'all' || card.classList.contains(category)) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        // Media Modal Handler
        function openMediaModal(title, url) {
            document.getElementById('mediaModalTitle').innerText = title;
            document.getElementById('mediaIframe').src = url;
            document.getElementById('mediaModal').classList.remove('hidden');
        }

        function closeMediaModal() {
            document.getElementById('mediaModal').classList.add('hidden');
            document.getElementById('mediaIframe').src = '';
        }

        // Contact Form Submission
        function handleContactSubmit(e) {
            e.preventDefault();
            showToast('Inquiry sent! Zollo\'s team will contact you soon.');
            e.target.reset();
        }

        // Toast Helper
        function showToast(msg) {
            const toast = document.getElementById('toast');
            const toastMsg = document.getElementById('toastMsg');
            toastMsg.innerText = msg;
            toast.classList.remove('hidden');
            setTimeout(() => {
                toast.classList.add('hidden');
            }, 3000);
        }

        // Countdown Timer Logic
        setInterval(() => {
            const secEl = document.getElementById('timerSecs');
            let secs = parseInt(secEl.innerText);
            if (secs > 0) {
                secEl.innerText = String(secs - 1).padStart(2, '0');
            } else {
                secEl.innerText = '59';
            }
        }, 1000);
    </script>
</body>
</html>

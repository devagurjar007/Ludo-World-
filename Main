<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Khelstar - Gaming & Esports Platform</title>
    <link rel="icon" type="image/x-icon" href="/static/favicon.ico">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <script src="https://cdn.jsdelivr.net/npm/vanta@latest/dist/vanta.globe.min.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #0f172a;
            color: #f8fafc;
        }
        .hero-gradient {
            background: linear-gradient(135deg, #1e293b 0%, #0f172a 100%);
        }
        .game-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        .nav-link:hover {
            color: #60a5fa;
        }
        .btn-primary {
            background: linear-gradient(90deg, #3b82f6 0%, #6366f1 100%);
        }
        .btn-primary:hover {
            background: linear-gradient(90deg, #2563eb 0%, #4f46e5 100%);
        }
    </style>
</head>
<body class="min-h-screen">
    <!-- Navbar -->
    <nav class="bg-gray-900/80 backdrop-blur-md fixed w-full z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <div class="flex items-center">
                    <div class="flex-shrink-0">
                        <span class="text-2xl font-bold text-blue-400">KHELSTAR</span>
                    </div>
                    <div class="hidden md:block">
                        <div class="ml-10 flex items-baseline space-x-4">
                            <a href="#" class="nav-link px-3 py-2 rounded-md text-sm font-medium text-white">Home</a>
                            <a href="#" class="nav-link px-3 py-2 rounded-md text-sm font-medium text-gray-300 hover:text-white">Tournaments</a>
                            <a href="#" class="nav-link px-3 py-2 rounded-md text-sm font-medium text-gray-300 hover:text-white">Leaderboards</a>
                            <a href="#" class="nav-link px-3 py-2 rounded-md text-sm font-medium text-gray-300 hover:text-white">Streams</a>
                            <a href="#" class="nav-link px-3 py-2 rounded-md text-sm font-medium text-gray-300 hover:text-white">Shop</a>
                        </div>
                    </div>
                </div>
                <div class="hidden md:block">
                    <div class="ml-4 flex items-center md:ml-6">
                        <button class="p-1 rounded-full text-gray-400 hover:text-white focus:outline-none">
                            <i data-feather="search"></i>
                        </button>
                        <button class="ml-3 p-1 rounded-full text-gray-400 hover:text-white focus:outline-none">
                            <i data-feather="bell"></i>
                        </button>
                        <button class="ml-3 flex items-center text-sm rounded-full focus:outline-none">
                            <img class="h-8 w-8 rounded-full" src="http://static.photos/gaming/200x200/42" alt="User profile">
                        </button>
                    </div>
                </div>
                <div class="-mr-2 flex md:hidden">
                    <button type="button" class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-white hover:bg-gray-700 focus:outline-none">
                        <i data-feather="menu"></i>
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <div id="vanta-bg" class="hero-gradient min-h-screen flex items-center justify-center pt-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-24">
            <div class="text-center">
                <h1 class="text-4xl md:text-6xl font-bold mb-6" data-aos="fade-up">
                    <span class="bg-clip-text text-transparent bg-gradient-to-r from-blue-400 to-purple-500">Compete. Win. Repeat.</span>
                </h1>
                <p class="text-xl md:text-2xl text-gray-300 max-w-3xl mx-auto mb-10" data-aos="fade-up" data-aos-delay="100">
                    Join India's fastest growing gaming platform. Participate in tournaments, watch live streams, and connect with gamers worldwide.
                </p>
                <div class="flex flex-col sm:flex-row justify-center gap-4" data-aos="fade-up" data-aos-delay="200">
                    <a href="#" class="btn-primary text-white font-medium py-3 px-8 rounded-lg transition duration-300">
                        Join Tournament
                    </a>
                    <a href="#" class="bg-gray-800 text-white font-medium py-3 px-8 rounded-lg hover:bg-gray-700 transition duration-300">
                        Watch Live
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- Trending Games -->
    <section class="py-16 bg-gray-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold mb-4" data-aos="fade-up">Trending Games</h2>
                <p class="text-gray-400 max-w-2xl mx-auto" data-aos="fade-up" data-aos-delay="100">
                    Compete in the most popular games with thousands of players worldwide
                </p>
            </div>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Game Card 1 -->
                <div class="game-card bg-gray-800 rounded-xl overflow-hidden transition duration-300" data-aos="fade-up">
                    <img src="http://static.photos/gaming/640x360/1" alt="BGMI" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <div class="flex items-center mb-3">
                            <img src="http://static.photos/gaming/200x200/1" alt="BGMI Logo" class="w-10 h-10 rounded-full mr-3">
                            <h3 class="font-bold text-lg">BGMI</h3>
                        </div>
                        <p class="text-gray-400 text-sm mb-4">Battle royale mobile game with millions of players</p>
                        <div class="flex justify-between items-center">
                            <span class="text-blue-400 text-sm font-medium">5 Tournaments</span>
                            <button class="text-xs bg-blue-600 hover:bg-blue-700 text-white py-1 px-3 rounded-full">
                                Join
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Game Card 2 -->
                <div class="game-card bg-gray-800 rounded-xl overflow-hidden transition duration-300" data-aos="fade-up" data-aos-delay="100">
                    <img src="http://static.photos/gaming/640x360/2" alt="Free Fire" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <div class="flex items-center mb-3">
                            <img src="http://static.photos/gaming/200x200/2" alt="Free Fire Logo" class="w-10 h-10 rounded-full mr-3">
                            <h3 class="font-bold text-lg">Free Fire</h3>
                        </div>
                        <p class="text-gray-400 text-sm mb-4">Fast-paced battle royale with 50 million daily players</p>
                        <div class="flex justify-between items-center">
                            <span class="text-blue-400 text-sm font-medium">3 Tournaments</span>
                            <button class="text-xs bg-blue-600 hover:bg-blue-700 text-white py-1 px-3 rounded-full">
                                Join
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Game Card 3 -->
                <div class="game-card bg-gray-800 rounded-xl overflow-hidden transition duration-300" data-aos="fade-up" data-aos-delay="200">
                    <img src="http://static.photos/gaming/640x360/3" alt="Valorant" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <div class="flex items-center mb-3">
                            <img src="http://static.photos/gaming/200x200/3" alt="Valorant Logo" class="w-10 h-10 rounded-full mr-3">
                            <h3 class="font-bold text-lg">Valorant</h3>
                        </div>
                        <p class="text-gray-400 text-sm mb-4">Tactical shooter with unique agent abilities</p>
                        <div class="flex justify-between items-center">
                            <span class="text-blue-400 text-sm font-medium">7 Tournaments</span>
                            <button class="text-xs bg-blue-600 hover:bg-blue-700 text-white py-1 px-3 rounded-full">
                                Join
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Game Card 4 -->
                <div class="game-card bg-gray-800 rounded-xl overflow-hidden transition duration-300" data-aos="fade-up" data-aos-delay="300">
                    <img src="http://static.photos/gaming/640x360/4" alt="Call of Duty" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <div class="flex items-center mb-3">
                            <img src="http://static.photos/gaming/200x200/4" alt="COD Logo" class="w-10 h-10 rounded-full mr-3">
                            <h3 class="font-bold text-lg">Call of Duty</h3>
                        </div>
                        <p class="text-gray-400 text-sm mb-4">Legendary FPS franchise with mobile and PC versions</p>
                        <div class="flex justify-between items-center">
                            <span class="text-blue-400 text-sm font-medium">4 Tournaments</span>
                            <button class="text-xs bg-blue-600 hover:bg-blue-700 text-white py-1 px-3 rounded-full">
                                Join
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Live Tournaments -->
    <section class="py-16 bg-gray-950">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row justify-between items-center mb-12">
                <div>
                    <h2 class="text-3xl font-bold mb-2" data-aos="fade-up">Live Tournaments</h2>
                    <p class="text-gray-400" data-aos="fade-up" data-aos-delay="100">
                        Don't miss these exciting competitions happening right now
                    </p>
                </div>
                <a href="#" class="mt-4 md:mt-0 text-blue-400 hover:text-blue-300 flex items-center" data-aos="fade-left">
                    View All <i data-feather="chevron-right" class="ml-1 w-5 h-5"></i>
                </a>
            </div>
            
            <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
                <!-- Tournament Card 1 -->
                <div class="bg-gray-800 rounded-xl overflow-hidden" data-aos="fade-up">
                    <div class="relative">
                        <img src="http://static.photos/gaming/640x360/5" alt="BGMI Tournament" class="w-full h-48 object-cover">
                        <div class="absolute top-4 left-4 bg-red-500 text-white text-xs font-bold px-2 py-1 rounded">
                            LIVE
                        </div>
                        <div class="absolute bottom-4 right-4 bg-black/70 text-white text-xs font-medium px-2 py-1 rounded">
                            12K Watching
                        </div>
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-4">
                            <div>
                                <h3 class="font-bold text-xl mb-1">BGMI Championship</h3>
                                <p class="text-gray-400 text-sm">Squad TPP | Prize: ₹5,00,000</p>
                            </div>
                            <div class="flex items-center text-yellow-400">
                                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                                <span class="ml-1 text-sm">4.9</span>
                            </div>
                        </div>
                        <div class="flex items-center justify-between">
                            <div class="flex -space-x-2">
                                <img class="w-8 h-8 rounded-full border-2 border-gray-800" src="http://static.photos/people/200x200/1" alt="Team 1">
                                <img class="w-8 h-8 rounded-full border-2 border-gray-800" src="http://static.photos/people/200x200/2" alt="Team 2">
                                <img class="w-8 h-8 rounded-full border-2 border-gray-800" src="http://static.photos/people/200x200/3" alt="Team 3">
                                <div class="w-8 h-8 rounded-full bg-gray-700 border-2 border-gray-800 flex items-center justify-center text-xs text-gray-400">
                                    +12
                                </div>
                            </div>
                            <button class="bg-blue-600 hover:bg-blue-700 text-white py-2 px-4 rounded-lg text-sm font-medium transition duration-300">
                                Watch Now
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Tournament Card 2 -->
                <div class="bg-gray-800 rounded-xl overflow-hidden" data-aos="fade-up" data-aos-delay="100">
                    <div class="relative">
                        <img src="http://static.photos/gaming/640x360/6" alt="Free Fire Tournament" class="w-full h-48 object-cover">
                        <div class="absolute top-4 left-4 bg-red-500 text-white text-xs font-bold px-2 py-1 rounded">
                            LIVE
                        </div>
                        <div class="absolute bottom-4 right-4 bg-black/70 text-white text-xs font-medium px-2 py-1 rounded">
                            8.5K Watching
                        </div>
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-4">
                            <div>
                                <h3 class="font-bold text-xl mb-1">Free Fire Clash</h3>
                                <p class="text-gray-400 text-sm">Squad | Prize: ₹2,50,000</p>
                            </div>
                            <div class="flex items-center text-yellow-400">
                                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                                <span class="ml-1 text-sm">4.7</span>
                            </div>
                        </div>
                        <div class="flex items-center justify-between">
                            <div class="flex -space-x-2">
                                <img class="w-8 h-8 rounded-full border-2 border-gray-800" src="http://static.photos/people/200x200/4" alt="Team 1">
                                <img class="w-8 h-8 rounded-full border-2 border-gray-800" src="http://static.photos/people/200x200/5" alt="Team 2">
                                <img class="w-8 h-8 rounded-full border-2 border-gray-800" src="http://static.photos/people/200x200/6" alt="Team 3">
                                <div class="w-8 h-8 rounded-full bg-gray-700 border-2 border-gray-800 flex items-center justify-center text-xs text-gray-400">
                                    +15
                                </div>
                            </div>
                            <button class="bg-blue-600 hover:bg-blue-700 text-white py-2 px-4 rounded-lg text-sm font-medium transition duration-300">
                                Watch Now
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Tournament Card 3 -->
                <div class="bg-gray-800 rounded-xl overflow-hidden" data-aos="fade-up" data-aos-delay="200">
                    <div class="relative">
                        <img src="http://static.photos/gaming/640x360/7" alt="Valorant Tournament" class="w-full h-48 object-cover">
                        <div class="absolute top-4 left-4 bg-red-500 text-white text-xs font-bold px-2 py-1 rounded">
                            LIVE
                        </div>
                        <div class="absolute bottom-4 right-4 bg-black/70 text-white text-xs font-medium px-2 py-1 rounded">
                            15K Watching
                        </div>
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-4">
                            <div>
                                <h3 class="font-bold text-xl mb-1">Valorant Showdown</h3>
                                <p class="text-gray-400 text-sm">5v5 | Prize: ₹7,50,000</p>
                            </div>
                            <div class="flex items-center text-yellow-400">
                                <i data-feather="star" class="w-4 h-4 fill-current"></i>
                                <span class="ml-1 text-sm">4.8</span>
                            </div>
                        </div>
                        <div class="flex items-center justify-between">
                            <div class="flex -space-x-2">
                                <img class="w-8 h-8 rounded-full border-2 border-gray-800" src="http://static.photos/people/200x200/7" alt="Team 1">
                                <img class="w-8 h-8 rounded-full border-2 border-gray-800" src="http://static.photos/people/200x200/8" alt="Team 2">
                                <img class="w-8 h-8 rounded-full border-2 border-gray-800" src="http://static.photos/people/200x200/9" alt="Team 3">
                                <div class="w-8 h-8 rounded-full bg-gray-700 border-2 border-gray-800 flex items-center justify-center text-xs text-gray-400">
                                    +18
                                </div>
                            </div>
                            <button class="bg-blue-600 hover:bg-blue-700 text-white py-2 px-4 rounded-lg text-sm font-medium transition duration-300">
                                Watch Now
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Features -->
    <section class="py-16 bg-gray-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold mb-4" data-aos="fade-up">Why Choose Khelstar?</h2>
                <p class="text-gray-400 max-w-2xl mx-auto" data-aos="fade-up" data-aos-delay="100">
                    The ultimate platform for gamers to compete, connect and grow
                </p>
           

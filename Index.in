```html
<!DOCTYPE html>
<html lang="en" class="h-full bg-slate-50">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NaukriSetu - Latest Government Jobs, Admit Cards & Results (नौकरी सेतु)</title>
    <meta name="description" content="NaukriSetu is India's leading portal for latest Sarkari Naukri, SSC, Railway, UPSC, Banking, Defence, and State Government job notifications.">
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        emerald: {
                            800: '#065F46',
                            700: '#047857',
                            600: '#059669',
                            50: '#ecfdf5',
                        },
                        royal: {
                            900: '#1E3A8A',
                            800: '#1e40af',
                            700: '#1d4ed8',
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'Noto Sans Devanagari', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=Noto+Sans+Devanagari:wght@400;600;700&display=swap" rel="stylesheet">
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        .ticker-wrap { width: 100%; overflow: hidden; white-space: nowrap; }
        .ticker-move { display: inline-block; animation: ticker 35s linear infinite; }
        .ticker-move:hover { animation-play-state: paused; }
        @keyframes ticker {
            0% { transform: translate3d(0, 0, 0); }
            100% { transform: translate3d(-50%, 0, 0); }
        }
        .adsense-box {
            background-image: repeating-linear-gradient(45deg, #f8fafc, #f8fafc 10px, #f1f5f9 10px, #f1f5f9 20px);
        }
        /* Hide scrollbars for clean UI while keeping scrollability */
        .no-scrollbar::-webkit-scrollbar { display: none; }
        .no-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
    </style>
</head>
<body class="font-sans antialiased text-slate-800 flex flex-col min-h-full">

    <!-- TOP ANNOUNCEMENT & TICKER HEADER -->
    <div class="bg-emerald-800 text-white text-xs sm:text-sm py-1.5 px-3 flex items-center justify-between border-b border-emerald-700">
        <div class="flex items-center space-x-2 overflow-hidden w-full max-w-7xl mx-auto">
            <span class="bg-red-600 text-white font-bold px-2 py-0.5 rounded text-[11px] tracking-wider uppercase shrink-0 flex items-center gap-1 animate-pulse">
                <i data-lucide="flame" class="w-3.5 h-3.5">="w-3.5 h-3.5"></i> LIVE UPDATES
            </span>
            <div class="ticker-wrap flex-1">
                <div id="tickerContent" class="ticker-move text-emerald-100 font-medium">
                    <!-- Dynamic Ticker JS -->
                </div>
            </div>
        </div>
    </div>

    <!-- MAIN BRAND HEADER -->
    <header class="bg-white border-b border-slate-200 shadow-sm sticky top-0 z-30">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16 sm:h-20">
                <!-- Logo & Brand -->
                <div class="flex items-center space-x-3 cursor-pointer" onclick="switchTab('home')">
                    <div class="w-10 h-10 sm:w-12 sm:h-12 bg-gradient-to-tr from-emerald-800 to-emerald-600 rounded-xl flex items-center justify-center text-white font-extrabold text-xl shadow-md border-2 border-emerald-400">
                        N
                    </div>
                    <div>
                        <div class="flex items-center gap-2">
                            <span class="text-xl sm:text-2xl font-black text-emerald-800 tracking-tight" id="headerSiteName">NaukriSetu</span>
                            <span class="text-xs bg-royal-900 text-white px-1.5 py-0.5 rounded font-bold">नौकरी सेतु</span>
                        </div>
                        <p class="text-xs text-slate-500 font-medium hidden sm:block" id="headerTagline">Official Portal for Indian Government Jobs & Admissions</p>
                    </div>
                </div>

                <!-- Desktop Navigation Links -->
                <nav class="hidden md:flex items-center space-x-1 lg:space-x-4 text-sm font-semibold text-slate-700">
                    <button onclick="switchTab('home')" class="hover:text-emerald-700 px-3 py-2 rounded-lg hover:bg-emerald-50 transition">Home</button>
                    <button onclick="scrollToSection('latest-jobs')" class="hover:text-emerald-700 px-3 py-2 rounded-lg hover:bg-emerald-50 transition">Latest Jobs</button>
                    <button onclick="filterByCat('Admit Cards')" class="hover:text-emerald-700 px-3 py-2 rounded-lg hover:bg-emerald-50 transition">Admit Card</button>
                    <button onclick="filterByCat('Results')" class="hover:text-emerald-700 px-3 py-2 rounded-lg hover:bg-emerald-50 transition">Results</button>
                    <button onclick="filterByCat('Answer Keys')" class="hover:text-emerald-700 px-3 py-2 rounded-lg hover:bg-emerald-50 transition">Answer Key</button>
                </nav>

                <!-- Action Buttons & Admin Portal Trigger -->
                <div class="flex items-center space-x-2 sm:space-x-3">
                    <button onclick="toggleSeoModal()" title="SEO & Indexing Tools" class="hidden sm:flex items-center gap-1 text-xs bg-slate-100 hover:bg-slate-200 text-slate-700 font-medium px-2.5 py-2 rounded-lg border border-slate-300 transition">
                        <i data-lucide="file-code" class="w-4 h-4 text-royal-900"></i> SEO Tools
                    </button>
                    <button onclick="openAdminModal()" class="flex items-center gap-1.5 bg-gradient-to-r from-royal-900 to-royal-800 text-white text-xs sm:text-sm font-semibold px-3 sm:px-4 py-2 rounded-lg shadow-sm hover:from-royal-800 hover:to-royal-700 transition">
                        <i data-lucide="shield-check" class="w-4 h-4"></i> Admin CMS
                    </button>
                </div>
            </div>
        </div>
    </header>

    <!-- MAIN BODY CONTENT CONTAINER -->
    <main class="flex-grow max-w-7xl w-full mx-auto px-4 sm:px-6 lg:px-8 py-4 sm:py-6 space-y-6">

        <!-- ADSENSE BANNER TOP SLOT -->
        <div id="adTopSlot" class="w-full adsense-box border-2 border-dashed border-slate-300 rounded-xl p-3 text-center transition">
            <div class="flex items-center justify-between text-[11px] text-slate-400 font-semibold tracking-wider uppercase mb-1">
                <span>Advertisement - Sponsored Link</span>
                <span>Google AdSense Slot #1</span>
            </div>
            <div class="py-3 flex flex-col sm:flex-row items-center justify-center gap-4 text-slate-600">
                <i data-lucide="layout-template" class="w-8 h-8 text-slate-400"></i>
                <div class="text-left">
                    <p class="font-bold text-sm text-slate-700">Prepare for SSC & Railway Exams 2026 - Free Mock Tests</p>
                    <p class="text-xs text-slate-500">Sponsored by Certified Educational Partners. Ad-free practice series.</p>
                </div>
                <button class="bg-royal-900 text-white text-xs px-3 py-1.5 rounded font-semibold hover:bg-royal-800">Learn More</button>
            </div>
        </div>

        <!-- SEARCH & ADVANCED FILTER BAR -->
        <section class="bg-white rounded-2xl shadow-sm border border-slate-200 p-4 sm:p-6">
            <div class="flex flex-col md:flex-row gap-3">
                <div class="relative flex-grow">
                    <i data-lucide="search" class="w-5 h-5 absolute left-3.5 top-3.5 text-slate-400"></i>
                    <input type="text" id="searchInput" oninput="applyFilters()" placeholder="Search by Job Title, Department, SSC, RRB, UPSC, Defence..." class="w-full pl-11 pr-4 py-3 bg-slate-50 border border-slate-300 rounded-xl focus:bg-white focus:ring-2 focus:ring-emerald-600 focus:outline-none text-sm font-medium">
                </div>
                <div class="grid grid-cols-2 sm:grid-cols-4 gap-2">
                    <select id="qualificationFilter" onchange="applyFilters()" class="bg-slate-50 border border-slate-300 text-slate-700 text-xs sm:text-sm rounded-xl p-2.5 focus:ring-2 focus:ring-emerald-600 focus:outline-none">
                        <option value="">All Qualifications</option>
                        <option value="10th">10th Pass</option>
                        <option value="12th">12th Pass</option>
                        <option value="Graduate">Graduate Degree</option>
                        <option value="Diploma">Diploma / ITI</option>
                        <option value="Post Graduate">Post Graduate</option>
                    </select>

                    <select id="deptFilter" onchange="applyFilters()" class="bg-slate-50 border border-slate-300 text-slate-700 text-xs sm:text-sm rounded-xl p-2.5 focus:ring-2 focus:ring-emerald-600 focus:outline-none">
                        <option value="">All Departments</option>
                        <option value="SSC">SSC (Staff Selection)</option>
                        <option value="Railway">Indian Railways (RRB)</option>
                        <option value="UPSC">UPSC / Civil Services</option>
                        <option value="Banking">Banking (IBPS/SBI)</option>
                        <option value="Defence">Police & Defence</option>
                        <option value="Teaching">Teaching & Education</option>
                    </select>

                    <select id="stateFilter" onchange="applyFilters()" class="bg-slate-50 border border-slate-300 text-slate-700 text-xs sm:text-sm rounded-xl p-2.5 focus:ring-2 focus:ring-emerald-600 focus:outline-none">
                        <option value="">All States / All India</option>
                        <option value="All India">All India Level</option>
                        <option value="Uttar Pradesh">Uttar Pradesh</option>
                        <option value="Bihar">Bihar</option>
                        <option value="Madhya Pradesh">Madhya Pradesh</option>
                        <option value="Delhi">Delhi / NCR</option>
                        <option value="Rajasthan">Rajasthan</option>
                        <option value="Maharashtra">Maharashtra</option>
                    </select>

                    <button onclick="resetFilters()" class="bg-slate-200 hover:bg-slate-300 text-slate-700 font-semibold text-xs sm:text-sm rounded-xl p-2.5 flex items-center justify-center gap-1 transition">
                        <i data-lucide="rotate-ccw" class="w-4 h-4"></i> Reset
                    </button>
                </div>
            </div>
            
            <!-- Quick Category Pill Chips -->
            <div class="mt-4 flex flex-wrap gap-2 text-xs">
                <span class="text-slate-500 font-bold self-center mr-1">Popular:</span>
                <button onclick="quickFilter('10th')" class="bg-slate-100 hover:bg-emerald-50 hover:text-emerald-700 text-slate-700 font-semibold px-3 py-1.5 rounded-full border border-slate-200 transition">🎓 10th Pass Jobs</button>
                <button onclick="quickFilter('12th')" class="bg-slate-100 hover:bg-emerald-50 hover:text-emerald-700 text-slate-700 font-semibold px-3 py-1.5 rounded-full border border-slate-200 transition">📜 12th Pass Jobs</button>
                <button onclick="quickFilter('Railway')" class="bg-slate-100 hover:bg-emerald-50 hover:text-emerald-700 text-slate-700 font-semibold px-3 py-1.5 rounded-full border border-slate-200 transition">🚆 Railway Recruitment</button>
                <button onclick="quickFilter('SSC')" class="bg-slate-100 hover:bg-emerald-50 hover:text-emerald-700 text-slate-700 font-semibold px-3 py-1.5 rounded-full border border-slate-200 transition">🏛️ SSC CGL & CHSL</button>
                <button onclick="quickFilter('Defence')" class="bg-slate-100 hover:bg-emerald-50 hover:text-emerald-700 text-slate-700 font-semibold px-3 py-1.5 rounded-full border border-slate-200 transition">🛡️ Police & Defence</button>
                <button onclick="quickFilter('Closing Soon')" class="bg-red-50 hover:bg-red-100 text-red-700 font-semibold px-3 py-1.5 rounded-full border border-red-200 transition">⏰ Closing Soon!</button>
            </div>
        </section>

        <!-- PORTAL LIVE COUNTERS & STATS -->
        <div class="grid grid-cols-2 md:grid-cols-4 gap-3 sm:gap-4">
            <div class="bg-white border border-slate-200 rounded-xl p-3.5 sm:p-4 flex items-center space-x-3 shadow-sm">
                <div class="w-10 h-10 rounded-lg bg-emerald-100 text-emerald-800 flex items-center justify-center font-bold">
                    <i data-lucide="briefcase" class="w-5 h-5"></i>
                </div>
                <div>
                    <div id="statTotalJobs" class="text-xl sm:text-2xl font-black text-slate-800">0</div>
                    <div class="text-xs text-slate-500 font-medium">Active Vacancies</div>
                </div>
            </div>
            <div class="bg-white border border-slate-200 rounded-xl p-3.5 sm:p-4 flex items-center space-x-3 shadow-sm">
                <div class="w-10 h-10 rounded-lg bg-royal-100 text-royal-900 flex items-center justify-center font-bold">
                    <i data-lucide="ticket" class="w-5 h-5"></i>
                </div>
                <div>
                    <div id="statAdmitCards" class="text-xl sm:text-2xl font-black text-slate-800">0</div>
                    <div class="text-xs text-slate-500 font-medium">Admit Cards Out</div>
                </div>
            </div>
            <div class="bg-white border border-slate-200 rounded-xl p-3.5 sm:p-4 flex items-center space-x-3 shadow-sm">
                <div class="w-10 h-10 rounded-lg bg-amber-100 text-amber-800 flex items-center justify-center font-bold">
                    <i data-lucide="award" class="w-5 h-5"></i>
                </div>
                <div>
                    <div id="statResults" class="text-xl sm:text-2xl font-black text-slate-800">0</div>
                    <div class="text-xs text-slate-500 font-medium">Declared Results</div>
                </div>
            </div>
            <div class="bg-white border border-slate-200 rounded-xl p-3.5 sm:p-4 flex items-center space-x-3 shadow-sm">
                <div class="w-10 h-10 rounded-lg bg-purple-100 text-purple-800 flex items-center justify-center font-bold">
                    <i data-lucide="clock" class="w-5 h-5"></i>
                </div>
                <div>
                    <div id="statClosingSoon" class="text-xl sm:text-2xl font-black text-red-600">0</div>
                    <div class="text-xs text-slate-500 font-medium">Closing This Week</div>
                </div>
            </div>
        </div>

        <!-- 3-COLUMN HIGHLIGHT MATRIX (SARKARI STYLE HOME GRID) -->
        <section class="grid grid-cols-1 lg:grid-cols-3 gap-6">
            
            <!-- COLUMN 1: LATEST JOBS -->
            <div class="bg-white rounded-2xl shadow-sm border border-slate-200 overflow-hidden flex flex-col">
                <div class="bg-gradient-to-r from-emerald-800 to-emerald-700 p-3.5 sm:p-4 text-white flex justify-between items-center">
                    <h2 class="font-bold text-base sm:text-lg flex items-center gap-2">
                        <i data-lucide="sparkles" class="w-5 h-5 text-amber-300"></i> Latest Government Jobs
                    </h2>
                    <span class="text-xs bg-emerald-900/50 px-2 py-0.5 rounded font-semibold text-emerald-200">New Updates</span>
                </div>
                <div id="colLatestJobs" class="divide-y divide-slate-100 p-2 overflow-y-auto max-h-[520px] flex-grow no-scrollbar">
                    <!-- JS Injected List -->
                </div>
            </div>

            <!-- COLUMN 2: ADMIT CARDS -->
            <div class="bg-white rounded-2xl shadow-sm border border-slate-200 overflow-hidden flex flex-col">
                <div class="bg-gradient-to-r from-royal-900 to-royal-800 p-3.5 sm:p-4 text-white flex justify-between items-center">
                    <h2 class="font-bold text-base sm:text-lg flex items-center gap-2">
                        <i data-lucide="ticket" class="w-5 h-5 text-blue-300"></i> Admit Cards 2026
                    </h2>
                    <span class="text-xs bg-royal-950/50 px-2 py-0.5 rounded font-semibold text-royal-200">Hall Tickets</span>
                </div>
                <div id="colAdmitCards" class="divide-y divide-slate-100 p-2 overflow-y-auto max-h-[520px] flex-grow no-scrollbar">
                    <!-- JS Injected List -->
                </div>
            </div>

            <!-- COLUMN 3: RESULTS & ANSWER KEYS -->
            <div class="bg-white rounded-2xl shadow-sm border border-slate-200 overflow-hidden flex flex-col">
                <div class="bg-gradient-to-r from-slate-800 to-slate-700 p-3.5 sm:p-4 text-white flex justify-between items-center">
                    <h2 class="font-bold text-base sm:text-lg flex items-center gap-2">
                        <i data-lucide="check-circle-2" class="w-5 h-5 text-emerald-400"></i> Results & Answer Keys
                    </h2>
                    <span class="text-xs bg-slate-900/50 px-2 py-0.5 rounded font-semibold text-slate-300">Declared</span>
                </div>
                <div id="colResults" class="divide-y divide-slate-100 p-2 overflow-y-auto max-h-[520px] flex-grow no-scrollbar">
                    <!-- JS Injected List -->
                </div>
            </div>

        </section>

        <!-- CATEGORIZED JOB BOARDS SECTION -->
        <section class="space-y-6" id="latest-jobs">
            <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 border-b border-slate-200 pb-3">
                <div>
                    <h2 class="text-xl sm:text-2xl font-black text-slate-900 flex items-center gap-2">
                        <i data-lucide="layers" class="w-6 h-6 text-emerald-700"></i> Explore Job Categories
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-500">Filter jobs by educational qualifications, departments, and government sector</p>
                </div>
                <div class="flex items-center gap-2 text-xs font-semibold">
                    <span class="text-slate-400">Sort by:</span>
                    <select id="sortBy" onchange="applyFilters()" class="bg-white border border-slate-300 text-slate-700 rounded-lg px-2.5 py-1.5 focus:outline-none">
                        <option value="newest">Latest Released</option>
                        <option value="closingSoon">Closing Soon Date</option>
                        <option value="vacancies">Highest Vacancies</option>
                    </select>
                </div>
            </div>

            <!-- CARDS GRID -->
            <div id="allJobsGrid" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-5">
                <!-- JS Populated Job Cards -->
            </div>

            <div id="noResultsMsg" class="hidden text-center py-12 bg-white rounded-2xl border border-slate-200">
                <i data-lucide="search-x" class="w-12 h-12 text-slate-300 mx-auto mb-3"></i>
                <h3 class="text-lg font-bold text-slate-700">No Matching Notifications Found</h3>
          

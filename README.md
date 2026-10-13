<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mior Nazrin Private Music Class</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        .gradient-bg {
            background: linear-gradient(135deg, #0f172a 0%, #1e1b4b 50%, #311042 100%);
        }
        .card-glow:hover {
            box-shadow: 0 0 25px rgba(168, 85, 247, 0.25);
        }
    </style>
</head>
<body class="bg-slate-950 text-slate-100 font-sans antialiased selection:bg-purple-500 selection:text-white min-h-screen flex flex-col">

    <!-- Navigation -->
    <nav class="sticky top-0 z-50 backdrop-blur-md bg-slate-950/80 border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <div class="flex items-center space-x-3">
                    <div class="bg-gradient-to-tr from-purple-600 to-indigo-500 p-2 rounded-lg text-white">
                        <i class="fa-solid fa-music text-xl"></i>
                    </div>
                    <span class="font-bold text-lg sm:text-xl tracking-tight bg-gradient-to-r from-purple-400 to-indigo-300 bg-clip-text text-transparent">
                        Mior Nazrin
                    </span>
                </div>
                
                <div class="hidden md:flex items-center space-x-8 text-sm font-medium">
                    <a href="#instruments" class="hover:text-purple-400 transition-colors">Instruments</a>
                    <a href="#calendar" class="hover:text-purple-400 transition-colors">Schedule</a>
                    <a href="#instructor" class="hover:text-purple-400 transition-colors">About Instructor</a>
                    <a href="#booking" class="bg-gradient-to-r from-purple-600 to-indigo-600 hover:from-purple-500 hover:to-indigo-500 text-white px-4 py-2 rounded-full transition-all duration-200 shadow-md hover:shadow-purple-500/25">Book Class</a>
                </div>

                <!-- Admin Toggle Button -->
                <div class="flex items-center">
                    <button id="adminToggleBtn" onclick="toggleAdminMode()" class="text-xs bg-slate-800 hover:bg-slate-700 text-slate-300 border border-slate-700 px-3 py-1.5 rounded-full transition">
                        <i class="fa-solid fa-lock text-purple-400 mr-1"></i> Admin View
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="gradient-bg py-20 px-4 sm:px-6 lg:px-8 text-center relative overflow-hidden border-b border-slate-800">
        <div class="max-w-4xl mx-auto space-y-6 relative z-10">
            <div class="flex flex-wrap justify-center gap-2">
                <span class="inline-flex items-center gap-2 bg-purple-500/10 border border-purple-500/20 text-purple-300 px-4 py-1.5 rounded-full text-xs font-semibold uppercase tracking-wider">
                    <i class="fa-solid fa-award"></i> Award-Winning Music Education
                </span>
                <span class="inline-flex items-center gap-2 bg-emerald-500/10 border border-emerald-500/20 text-emerald-300 px-4 py-1.5 rounded-full text-xs font-semibold uppercase tracking-wider">
                    <i class="fa-solid fa-tag"></i> RM 130 / Lesson
                </span>
            </div>
            
            <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight text-white">
                Mior Nazrin <br class="hidden sm:inline"/>
                <span class="bg-gradient-to-r from-purple-400 via-pink-400 to-indigo-400 bg-clip-text text-transparent">
                    Private Music Class
                </span>
            </h1>
            <p class="text-slate-300 text-base sm:text-lg max-w-2xl mx-auto leading-relaxed">
                Elevate your sound with personalized instruction across multiple instruments and ensemble performance directing at just <strong class="text-white">RM 130 per lesson</strong>.
            </p>
            <div class="flex flex-wrap justify-center gap-4 pt-4">
                <a href="#booking" class="bg-purple-600 hover:bg-purple-500 text-white px-6 py-3 rounded-xl font-semibold shadow-lg shadow-purple-900/40 transition">
                    Book a Lesson (RM 130)
                </a>
                <a href="#calendar" class="bg-slate-900/80 hover:bg-slate-800 text-slate-200 border border-slate-700 px-6 py-3 rounded-xl font-semibold transition">
                    Check Calendar
                </a>
            </div>
        </div>
    </header>

    <!-- Instruments Offered Section -->
    <section id="instruments" class="py-16 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
        <div class="text-center max-w-2xl mx-auto mb-12">
            <h2 class="text-3xl font-bold text-white mb-3">Instruments & Classes Offered</h2>
            <p class="text-slate-400">Tailored music instruction designed for all skill levels at <span class="text-emerald-400 font-semibold">RM 130</span> per session.</p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
            <!-- Guitar -->
            <div class="bg-slate-900 border border-slate-800 rounded-2xl p-6 transition duration-300 card-glow flex flex-col justify-between">
                <div>
                    <div class="w-12 h-12 bg-purple-900/40 text-purple-400 rounded-xl flex items-center justify-center text-xl mb-4">
                        <i class="fa-solid fa-guitar"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">Guitar</h3>
                    <p class="text-slate-400 text-sm mb-4">Acoustic & Electric guitar techniques, chord theory, solos, and performance styles.</p>
                </div>
                <div class="pt-4 border-t border-slate-800/80 flex items-center justify-between text-xs">
                    <span class="text-slate-400">Rate:</span>
                    <span class="text-emerald-400 font-bold">RM 130 / lesson</span>
                </div>
            </div>

            <!-- Bass -->
            <div class="bg-slate-900 border border-slate-800 rounded-2xl p-6 transition duration-300 card-glow flex flex-col justify-between">
                <div>
                    <div class="w-12 h-12 bg-indigo-900/40 text-indigo-400 rounded-xl flex items-center justify-center text-xl mb-4">
                        <i class="fa-solid fa-sliders"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">Bass</h3>
                    <p class="text-slate-400 text-sm mb-4">Groove development, rhythm locking, fretboard navigation, and dynamic basslines.</p>
                </div>
                <div class="pt-4 border-t border-slate-800/80 flex items-center justify-between text-xs">
                    <span class="text-slate-400">Rate:</span>
                    <span class="text-emerald-400 font-bold">RM 130 / lesson</span>
                </div>
            </div>

            <!-- Piano -->
            <div class="bg-slate-900 border border-slate-800 rounded-2xl p-6 transition duration-300 card-glow flex flex-col justify-between">
                <div>
                    <div class="w-12 h-12 bg-pink-900/40 text-pink-400 rounded-xl flex items-center justify-center text-xl mb-4">
                        <i class="fa-solid fa-keyboard"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">Piano</h3>
                    <p class="text-slate-400 text-sm mb-4">Keyboard fundamentals, music reading, harmony, ear training, and accompaniment.</p>
                </div>
                <div class="pt-4 border-t border-slate-800/80 flex items-center justify-between text-xs">
                    <span class="text-slate-400">Rate:</span>
                    <span class="text-emerald-400 font-bold">RM 130 / lesson</span>
                </div>
            </div>

            <!-- Ukulele -->
            <div class="bg-slate-900 border border-slate-800 rounded-2xl p-6 transition duration-300 card-glow flex flex-col justify-between">
                <div>
                    <div class="w-12 h-12 bg-emerald-900/40 text-emerald-400 rounded-xl flex items-center justify-center text-xl mb-4">
                        <i class="fa-solid fa-music"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">Ukulele</h3>
                    <p class="text-slate-400 text-sm mb-4">Fun and engaging strumming patterns, basic fingerpicking, and song accompaniment.</p>
                </div>
                <div class="pt-4 border-t border-slate-800/80 flex items-center justify-between text-xs">
                    <span class="text-slate-400">Rate:</span>
                    <span class="text-emerald-400 font-bold">RM 130 / lesson</span>
                </div>
            </div>

            <!-- Drums -->
            <div class="bg-slate-900 border border-slate-800 rounded-2xl p-6 transition duration-300 card-glow flex flex-col justify-between">
                <div>
                    <div class="w-12 h-12 bg-amber-900/40 text-amber-400 rounded-xl flex items-center justify-center text-xl mb-4">
                        <i class="fa-solid fa-drum"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">Drums</h3>
                    <p class="text-slate-400 text-sm mb-4">Rhythmic control, limb independence, timekeeping, and various musical grooves.</p>
                </div>
                <div class="pt-4 border-t border-slate-800/80 flex items-center justify-between text-xs">
                    <span class="text-slate-400">Rate:</span>
                    <span class="text-emerald-400 font-bold">RM 130 / lesson</span>
                </div>
            </div>

            <!-- Band Directing -->
            <div class="bg-slate-900 border border-slate-800 rounded-2xl p-6 transition duration-300 card-glow flex flex-col justify-between">
                <div>
                    <div class="w-12 h-12 bg-blue-900/40 text-blue-400 rounded-xl flex items-center justify-center text-xl mb-4">
                        <i class="fa-solid fa-users"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">Band Directing</h3>
                    <p class="text-slate-400 text-sm mb-4">Group dynamics, arrangement, stage performance polish, and band harmony setup.</p>
                </div>
                <div class="pt-4 border-t border-slate-800/80 flex items-center justify-between text-xs">
                    <span class="text-slate-400">Rate:</span>
                    <span class="text-emerald-400 font-bold">RM 130 / lesson</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Calendar Section -->
    <section id="calendar" class="py-16 px-4 sm:px-6 lg:px-8 max-w-5xl mx-auto">
        <div class="bg-slate-900 border border-slate-800 rounded-3xl p-6 sm:p-8 shadow-2xl">
            <div class="flex flex-col sm:flex-row items-start sm:items-center justify-between mb-6 gap-4">
                <div>
                    <h2 class="text-2xl font-bold text-white">Monthly Availability Calendar</h2>
                    <p class="text-slate-400 text-sm mt-1">Select dates marked <span class="text-emerald-400 font-semibold">Available</span> to request a slot.</p>
                </div>
                
                <div class="flex items-center space-x-3">
                    <button onclick="changeMonth(-1)" class="p-2 bg-slate-800 hover:bg-slate-700 text-slate-200 rounded-lg transition"><i class="fa-solid fa-chevron-left"></i></button>
                    <span id="currentMonthYear" class="font-bold text-slate-200 min-w-[140px] text-center"></span>
                    <button onclick="changeMonth(1)" class="p-2 bg-slate-800 hover:bg-slate-700 text-slate-200 rounded-lg transition"><i class="fa-solid fa-chevron-right"></i></button>
                </div>
            </div>

            <!-- Admin Banner -->
            <div id="adminBanner" class="hidden mb-4 p-3 bg-purple-900/40 border border-purple-500/40 rounded-xl text-purple-200 text-xs flex items-center justify-between">
                <span><i class="fa-solid fa-triangle-exclamation mr-1"></i> <strong>Admin Mode Active:</strong> Click any date on the calendar to toggle its status between Available and Occupied.</span>
                <span class="text-purple-400 font-mono text-[10px]">Changes Auto-Saved</span>
            </div>

            <!-- Calendar Grid -->
            <div class="grid grid-cols-7 gap-1 sm:gap-2 text-center text-xs sm:text-sm mb-2 text-slate-400 font-semibold">
                <div>Sun</div><div>Mon</div><div>Tue</div><div>Wed</div><div>Thu</div><div>Fri</div><div>Sat</div>
            </div>

            <div id="calendarDays" class="grid grid-cols-7 gap-1 sm:gap-2">
                <!-- Generated dynamically via JS -->
            </div>

            <div class="flex flex-wrap items-center justify-center gap-6 mt-6 pt-6 border-t border-slate-800 text-xs text-slate-400">
                <div class="flex items-center space-x-2">
                    <span class="w-3 h-3 rounded-full bg-emerald-500/20 border border-emerald-500"></span>
                    <span>Available</span>
                </div>
                <div class="flex items-center space-x-2">
                    <span class="w-3 h-3 rounded-full bg-rose-500/20 border border-rose-500"></span>
                    <span>Occupied</span>
                </div>
                <div class="flex items-center space-x-2">
                    <span class="w-3 h-3 rounded-full bg-slate-800 border border-slate-700"></span>
                    <span>Passed Date</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Instructor Information -->
    <section id="instructor" class="py-16 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto border-t border-slate-800/60">
        <div class="bg-gradient-to-r from-slate-900 to-indigo-950/40 border border-slate-800 rounded-3xl p-8 sm:p-12">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 items-center">
                <div class="flex flex-col items-center text-center md:text-left md:items-start space-y-4">
                    <img src="profile.jpg" alt="Mior Nazrin Shah" class="w-32 h-32 rounded-full object-cover shadow-xl">
                    <div>
                        <h2 class="text-2xl font-bold text-white">Mior Nazrin Shah</h2>
                        <p class="text-purple-400 text-sm font-medium">Head Instructor & Musician</p>
                    </div>
                </div>

                <div class="md:col-span-2 space-y-4">
                    <h3 class="text-xl font-semibold text-slate-200">Qualifications & Experience</h3>
                    <ul class="space-y-3 text-slate-300 text-sm">
                        <li class="flex items-start space-x-3">
                            <i class="fa-solid fa-star text-amber-400 mt-1"></i>
                            <span><strong>Best Guitarist National Level 2024:</strong> Recognized nationally for guitar performance and mastery.</span>
                        </li>
                        <li class="flex items-start space-x-3">
                            <i class="fa-solid fa-graduation-cap text-purple-400 mt-1"></i>
                            <span><strong>5 Years Formal Music Education:</strong> Comprehensive background in musical performance, theory, and arrangement.</span>
                        </li>
                        <li class="flex items-start space-x-3">
                            <i class="fa-solid fa-award text-indigo-400 mt-1"></i>
                            <span><strong>Trained by UPBM JPN Selangor:</strong> High-standard music coaching and performance development.</span>
                        </li>
                        <li class="flex items-start space-x-3">
                            <i class="fa-solid fa-clock text-blue-400 mt-1"></i>
                            <span><strong>9 Years Learning Guitar:</strong> Extensive practical experience across various genres and techniques.</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Booking Form & Receipt Screen -->
    <section id="booking" class="py-16 px-4 sm:px-6 lg:px-8 max-w-4xl mx-auto">
        <div class="bg-slate-900 border border-slate-800 rounded-3xl p-6 sm:p-10 shadow-xl">
            
            <!-- Booking Form Container -->
            <div id="formContainer">
                <div class="text-center mb-8">
                    <h2 class="text-3xl font-bold text-white">Book a Lesson</h2>
                    <p class="text-slate-400 text-sm mt-2">Standard rate: <span class="text-emerald-400 font-semibold">RM 130 per session</span>. Fill out details below to request your slot.</p>
                </div>

                <form id="bookingForm" onsubmit="handleFormSubmit(event)" class="space-y-6">
                    <div>
                        <label class="block text-xs font-semibold uppercase tracking-wider text-slate-300 mb-2">Your Name</label>
                        <input type="text" id="clientName" name="name" required placeholder="Full Name" 
                            class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-slate-100 focus:outline-none focus:border-purple-500 focus:ring-1 focus:ring-purple-500">
                    </div>

                    <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
                        <div>
                            <label class="block text-xs font-semibold uppercase tracking-wider text-slate-300 mb-2">Instrument</label>
                            <select id="clientInstrument" name="instrument" required 
                                class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-slate-100 focus:outline-none focus:border-purple-500">
                                <option value="">Select...</option>
                                <option value="Guitar">Guitar</option>
                                <option value="Bass">Bass</option>
                                <option value="Piano">Piano</option>
                                <option value="Ukulele">Ukulele</option>
                                <option value="Drums">Drums</option>
                                <option value="Band Directing">Band Directing</option>
                            </select>
                        </div>

                        <div>
                            <label class="block text-xs font-semibold uppercase tracking-wider text-slate-300 mb-2">Preferred Date</label>
                            <input type="date" id="bookingDate" name="date" required 
                                class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-slate-100 focus:outline-none focus:border-purple-500">
                        </div>

                        <div>
                            <label class="block text-xs font-semibold uppercase tracking-wider text-slate-300 mb-2">Preferred Time</label>
                            <input type="time" id="clientTime" name="time" required 
                                class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-slate-100 focus:outline-none focus:border-purple-500">
                        </div>
                    </div>

                    <div>
                        <label class="block text-xs font-semibold uppercase tracking-wider text-slate-300 mb-2">Reference</label>
  

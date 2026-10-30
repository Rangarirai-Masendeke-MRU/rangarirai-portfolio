<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rangarirai (Ranga) Masendeke | Smart Manufacturing & Data Analytics Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            dark: '#0B1120',
                            card: '#1E293B',
                            border: '#334155',
                            cyan: '#06B6D4',
                            blue: '#3B82F6',
                            text: '#94A3B8',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #0B1120;
        }
        ::-webkit-scrollbar-thumb {
            background: #334155;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #06B6D4;
        }
        
        .gradient-text {
            background: linear-gradient(135deg, #38BDF8 0%, #06B6D4 50%, #3B82F6 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .glass-nav {
            background: rgba(11, 17, 32, 0.85);
            backdrop-filter: blur(12px);
        }
    </style>
</head>
<body class="bg-brand-dark text-slate-100 font-sans antialiased selection:bg-cyan-500 selection:text-white">

    <!-- Navigation Header -->
    <header class="fixed top-0 left-0 w-full z-50 glass-nav border-b border-brand-border/50 transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <!-- Brand Logo -->
            <a href="#hero" class="flex items-center gap-3 group">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-cyan-500 to-blue-600 flex items-center justify-center font-bold text-lg text-white shadow-lg shadow-cyan-500/20 group-hover:scale-105 transition-transform">
                    RM
                </div>
                <div class="flex flex-col">
                    <span class="font-bold text-lg tracking-tight text-white group-hover:text-cyan-400 transition-colors">Rangarirai Masendeke</span>
                    <span class="text-xs text-brand-text font-medium">Smart Mfg & Data Analytics</span>
                </div>
            </a>

            <!-- Desktop Nav Links -->
            <nav class="hidden md:flex items-center gap-8 text-sm font-medium">
                <a href="#about" class="text-slate-300 hover:text-cyan-400 transition-colors">About</a>
                <a href="#skills" class="text-slate-300 hover:text-cyan-400 transition-colors">Skills</a>
                <a href="#projects" class="text-slate-300 hover:text-cyan-400 transition-colors">Projects</a>
                <a href="#education" class="text-slate-300 hover:text-cyan-400 transition-colors">Education</a>
                <a href="#athletics" class="text-slate-300 hover:text-cyan-400 transition-colors">Athletics</a>
                <a href="#contact" class="px-5 py-2.5 rounded-lg bg-gradient-to-r from-cyan-500 to-blue-600 text-white font-semibold shadow-lg shadow-cyan-500/20 hover:shadow-cyan-500/40 hover:scale-[1.02] transition-all">
                    Get in Touch
                </a>
            </nav>

            <!-- Mobile Menu Toggle Button -->
            <button id="mobile-menu-btn" class="md:hidden text-slate-300 hover:text-cyan-400 p-2 focus:outline-none" aria-label="Toggle Navigation">
                <i class="fa-solid fa-bars text-2xl"></i>
            </button>
        </div>

        <!-- Mobile Navigation Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-slate-900 border-b border-brand-border px-4 pt-2 pb-6 space-y-3">
            <a href="#about" class="block py-2 text-slate-300 hover:text-cyan-400 transition-colors">About</a>
            <a href="#skills" class="block py-2 text-slate-300 hover:text-cyan-400 transition-colors">Skills</a>
            <a href="#projects" class="block py-2 text-slate-300 hover:text-cyan-400 transition-colors">Projects</a>
            <a href="#education" class="block py-2 text-slate-300 hover:text-cyan-400 transition-colors">Education</a>
            <a href="#athletics" class="block py-2 text-slate-300 hover:text-cyan-400 transition-colors">Athletics</a>
            <a href="#contact" class="block py-2 text-cyan-400 font-semibold">Get in Touch &rarr;</a>
        </div>
    </header>

    <main class="pt-20">
        <!-- HERO SECTION -->
        <section id="hero" class="relative min-h-[90vh] flex items-center justify-center py-20 px-4 sm:px-6 lg:px-8 overflow-hidden">
            <!-- Background Glow Elements -->
            <div class="absolute top-1/4 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[600px] h-[600px] bg-cyan-500/10 rounded-full blur-[120px] pointer-events-none"></div>
            <div class="absolute bottom-10 right-10 w-96 h-96 bg-blue-600/10 rounded-full blur-[100px] pointer-events-none"></div>

            <div class="max-w-5xl mx-auto text-center z-10">
                <div class="inline-flex items-center gap-2 px-4 py-2 rounded-full bg-slate-800/80 border border-brand-border mb-8 text-xs font-semibold tracking-wide text-cyan-400 uppercase shadow-inner">
                    <span class="w-2 h-2 rounded-full bg-cyan-400 animate-ping"></span>
                    Smart Manufacturing & Engineering Specialist
                </div>

                <h1 class="text-4xl sm:text-6xl lg:text-7xl font-extrabold tracking-tight text-white mb-6 leading-tight">
                    Engineering Precision. <br class="hidden sm:inline"/>
                    <span class="gradient-text">Driven by Data Analytics.</span>
                </h1>

                <p class="text-lg sm:text-xl text-slate-300 max-w-3xl mx-auto mb-10 font-normal leading-relaxed">
                    Hello, I'm <strong class="text-white">Rangarirai (Ranga) Masendeke</strong> — a Mechanical Engineer specializing in Smart Manufacturing, Machine Learning Predictive Maintenance, and Systems Automation at Manav Rachna University.
                </p>

                <!-- Key Badges -->
                <div class="flex flex-wrap justify-center gap-3 mb-10 text-xs sm:text-sm font-medium text-slate-300">
                    <span class="bg-slate-800/90 border border-slate-700/80 px-4 py-2 rounded-lg flex items-center gap-2">
                        <i class="fa-solid fa-microchip text-cyan-400"></i> Smart Mfg & Automation
                    </span>
                    <span class="bg-slate-800/90 border border-slate-700/80 px-4 py-2 rounded-lg flex items-center gap-2">
                        <i class="fa-solid fa-chart-line text-blue-400"></i> Data Analytics Minor
                    </span>
                    <span class="bg-slate-800/90 border border-slate-700/80 px-4 py-2 rounded-lg flex items-center gap-2">
                        <i class="fa-solid fa-futbol text-emerald-400"></i> Forward, Manav Rachna FC
                    </span>
                </div>

                <!-- Call to Actions -->
                <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                    <a href="#projects" class="w-full sm:w-auto px-8 py-4 rounded-xl bg-gradient-to-r from-cyan-500 to-blue-600 text-white font-bold shadow-xl shadow-cyan-500/25 hover:shadow-cyan-500/40 hover:scale-105 transition-all">
                        Explore My Projects
                    </a>
                    <a href="#contact" class="w-full sm:w-auto px-8 py-4 rounded-xl bg-slate-800/90 hover:bg-slate-700 text-slate-200 border border-slate-700 font-semibold transition-all hover:scale-105">
                        Contact Me
                    </a>
                </div>
            </div>
        </section>

        <!-- ABOUT ME SECTION -->
        <section id="about" class="py-24 bg-slate-900/50 border-y border-brand-border/60">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <h2 class="text-3xl sm:text-4xl font-bold text-white mb-4">About Me</h2>
                    <div class="w-16 h-1 bg-gradient-to-r from-cyan-500 to-blue-600 mx-auto rounded-full"></div>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                    <!-- Bio Content -->
                    <div class="lg:col-span-7 space-y-6 text-slate-300 leading-relaxed text-base sm:text-lg">
                        <p>
                            I am a <strong class="text-white">B.Tech Mechanical Engineering student at Manav Rachna University</strong>, specializing in Smart Manufacturing & Automation with a minor in Data Analytics. My core interest lies at the intersection of traditional physical engineering and modern digital intelligence.
                        </p>
                        <p>
                            My professional journey began with hands-on operational work at <strong class="text-white">OKMART Gweru in Zimbabwe</strong>, where I developed an acute understanding of operational efficiency, resource logistics, and practical problem-solving. Transitioning into advanced engineering studies in India expanded my capacity to solve complex industrial problems using mathematical modeling, computer-aided design, and predictive data science.
                        </p>
                        <p>
                            Whether generating multi-variable regression models in Python, executing 3D assembly models in SolidWorks, or authoring research in LaTeX, I am dedicated to engineering high-efficiency solutions for the next era of industrial automation.
                        </p>
                    </div>

                    <!-- Highlight Cards -->
                    <div class="lg:col-span-5 grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div class="bg-slate-800/80 p-6 rounded-2xl border border-slate-700 hover:border-cyan-500/50 transition-colors">
                            <div class="w-12 h-12 rounded-xl bg-cyan-500/10 flex items-center justify-center text-cyan-400 text-xl font-bold mb-4">
                                <i class="fa-solid fa-earth-africa"></i>
                            </div>
                            <h3 class="text-white font-bold text-lg mb-1">Global Perspective</h3>
                            <p class="text-sm text-brand-text">Rooted in Zimbabwe (Gweru) with operational experience, trained academically in India.</p>
                        </div>

                        <div class="bg-slate-800/80 p-6 rounded-2xl border border-slate-700 hover:border-blue-500/50 transition-colors">
                            <div class="w-12 h-12 rounded-xl bg-blue-500/10 flex items-center justify-center text-blue-400 text-xl font-bold mb-4">
                                <i class="fa-solid fa-industry"></i>
                            </div>
                            <h3 class="text-white font-bold text-lg mb-1">Smart Industry</h3>
                            <p class="text-sm text-brand-text">Integrating IoT sensor workflows, predictive algorithms, and smart factory design.</p>
                        </div>

                        <div class="bg-slate-800/80 p-6 rounded-2xl border border-slate-700 hover:border-cyan-500/50 transition-colors sm:col-span-2">
                            <div class="w-12 h-12 rounded-xl bg-emerald-500/10 flex items-center justify-center text-emerald-400 text-xl font-bold mb-4">
                                <i class="fa-solid fa-lightbulb"></i>
                            </div>
                            <h3 class="text-white font-bold text-lg mb-1">Core Engineering Philosophy</h3>
                            <p class="text-sm text-brand-text">"Bridging physical mechanical systems with real-time data analytics to eliminate operational downtime and elevate precision."</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- CORE COMPETENCIES & SKILLS SECTION -->
        <section id="skills" class="py-24 px-4 sm:px-6 lg:px-8">
            <div class="max-w-7xl mx-auto">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <h2 class="text-3xl sm:text-4xl font-bold text-white mb-4">Core Competencies & Skills</h2>
                    <p class="text-brand-text text-base sm:text-lg">Select a domain to explore my technical toolset and technical methodologies.</p>
                    <div class="w-16 h-1 bg-gradient-to-r from-cyan-500 to-blue-600 mx-auto rounded-full mt-4"></div>
                </div>

                <!-- Skill Category Tabs -->
                <div class="flex flex-wrap justify-center gap-3 mb-12">
                    <button onclick="switchTab('mechanical')" id="tab-mechanical" class="skill-tab active px-6 py-3 rounded-xl font-semibold text-sm transition-all bg-gradient-to-r from-cyan-500 to-blue-600 text-white shadow-lg shadow-cyan-500/20">
                        <i class="fa-solid fa-gears mr-2"></i> Mechanical & Smart Mfg
                    </button>
                    <button onclick="switchTab('analytics')" id="tab-analytics" class="skill-tab px-6 py-3 rounded-xl font-semibold text-sm transition-all bg-slate-800 text-slate-300 hover:bg-slate-700 border border-slate-700">
                        <i class="fa-solid fa-chart-pie mr-2"></i> Data Analytics & AI
                    </button>
                    <button onclick="switchTab('design')" id="tab-design" class="skill-tab px-6 py-3 rounded-xl font-semibold text-sm transition-all bg-slate-800 text-slate-300 hover:bg-slate-700 border border-slate-700">
                        <i class="fa-solid fa-laptop-code mr-2"></i> Web & UI Architecture
                    </button>
                </div>

                <!-- Tab Content Grid -->
                <div id="skills-container" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                    <!-- Dynamic skills injected via JavaScript -->
                </div>
            </div>
        </section>

        <!-- FEATURED PROJECTS SECTION -->
        <section id="projects" class="py-24 bg-slate-900/50 border-t border-brand-border/60">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <h2 class="text-3xl sm:text-4xl font-bold text-white mb-4">Featured Engineering Projects</h2>
                    <p class="text-brand-text text-base sm:text-lg">Research, machine learning models, and strategic engineering analysis.</p>
                    <div class="w-16 h-1 bg-gradient-to-r from-cyan-500 to-blue-600 mx-auto rounded-full mt-4"></div>
                </div>

                <!-- Filter Controls -->
                <div class="flex flex-wrap justify-center gap-2 mb-12">
                    <button onclick="filterProjects('all')" class="proj-filter active-filter px-4 py-2 rounded-lg text-xs font-semibold bg-cyan-500 text-white">All Projects</button>
                    <button onclick="filterProjects('ai-mfg')" class="proj-filter px-4 py-2 rounded-lg text-xs font-semibold bg-slate-800 text-slate-300 hover:bg-slate-700 border border-slate-700">Smart Mfg & AI</button>
                    <button onclick="filterProjects('analytics')" class="proj-filter px-4 py-2 rounded-lg text-xs font-semibold bg-slate-800 text-slate-300 hover:bg-slate-700 border border-slate-700">Data Analytics</button>
                    <button onclick="filterProjects('strategy')" class="proj-filter px-4 py-2 rounded-lg text-xs font-semibold bg-slate-800 text-slate-300 hover:bg-slate-700 border border-slate-700">Entrepreneurship</button>
                </div>

                <!-- Projects Grid -->
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8" id="projects-grid">
                    <!-- Project Card 1 -->
                    <div class="project-card bg-slate-800/90 border border-slate-700 rounded-2xl overflow-hidden hover:border-cyan-500/60 transition-all hover:-translate-y-1 shadow-lg" data-category="ai-mfg">
                        <div class="p-8">
                            <div class="flex items-center justify-between mb-4">
                                <span class="px-3 py-1 rounded-full text-xs font-semibold bg-cyan-500/10 text-cyan-400 border border-cyan-500/30">Research Paper</span>
                                <i class="fa-solid fa-microscope text-slate-500 text-xl"></i>
                            </div>
                            <h3 class="text-xl font-bold text-white mb-3">AI-Driven Material Defect Detection</h3>
                            <p class="text-brand-text text-sm leading-relaxed mb-6">
                                Compiled an academic research framework in LaTeX analyzing computer vision algorithms for real-time defect identification in high-speed industrial manufacturing lines.
                            </p>
                            <div class="flex flex-wrap gap-2 mb-6">
                                <span class="text-xs bg-slate-900/80 text-slate-300 px-3 py-1 rounded-md border border-slate-700">LaTeX</span>
                                <span class="text-xs bg-slate-900/80 text-slate-300 px-3 py-1 rounded-md border border-slate-700">Computer Vision</span>
                                <span class="text-xs bg-slate-900/80 text-slate-300 px-3 py-1 rounded-md border border-slate-700">Quality Control</span>
                            </div>
                            <div class="border-t border-slate-700/60 pt-4 flex justify-between items-center text-xs text-brand-text">
                                <span>Focus: Smart Factory QA</span>
                                <span class="text-cyan-400 font-semibold flex items-center gap-1 cursor-pointer hover:underline" onclick="openModal('AI-Driven Material Defect Detection', 'Developed a theoretical framework and LaTeX documentation analyzing AI-integrated industrial optical cameras for automated material flaw classification. Evaluates computational overhead, dynamic lighting, and edge deployment.')">Details <i class="fa-solid fa-arrow-right"></i></span>
                            </div>
                        </div>
                    </div>

                    <!-- Project Card 2 -->
                    <div class="project-card bg-slate-800/90 border border-slate-700 rounded-2xl overflow-hidden hover:border-blue-500/60 transition-all hover:-translate-y-1 shadow-lg" data-category="ai-mfg analytics">
                        <div class="p-8">
                            <div class="flex items-center justify-between mb-4">
                                <span class="px-3 py-1 rounded-full text-xs font-semibold bg-blue-500/10 text-blue-400 border border-blue-500/30">Machine Learning</span>
                                <i class="fa-solid fa-wrench text-slate-500 text-xl"></i>
                            </div>
                            <h3 class="text-xl font-bold text-white mb-3">Predictive Maintenance on AI4I 2020 Dataset</h3>
                            <p class="text-brand-text text-sm leading-relaxed mb-6">
                                Built predictive classification algorithms using Python (Scikit-Learn) to forecast equipment failures and operational downtime in industrial machinery setups.
                            </p>
                            <div class="flex flex-wrap gap-2 mb-6">
                                <span class="text-xs bg-slate-900/80 text-slate-300 px-3 py-1 rounded-md border border-slate-700">Python</span>
                                <span class="text-xs bg-slate-900/80 text-slate-300 px-3 py-1 rounded-md border border-slate-700">Scikit-Learn</span>
                                <span class="text-xs bg-slate-900/80 text-slate-300 px-3 py-1 rounded-md border border-slate-700">Predictive Analytics</span>
                            </div>
                            <div class="border-t border-slate-700/60 pt-4 flex justify-between items-center text-xs text-brand-text">
                                <span>Focus: Downtime Reduction</span>
                                <span class="text-blue-400 font-semibold flex items-center gap-1 cursor-pointer hover:underline" onclick="openModal('Predictive Maintenance ML Model', 'Analyzed tool wear, heat dissipation, and torque failure modes using the AI4I 2020 dataset. Applied synthetic oversampling and Random Forest/Decision Tree classifiers to optimize recall for industrial failure modes.')">Details <i class="fa-solid fa-arrow-right"></i></span>
                            </div>
                        </div>
                    </div>

                    <!-- Project Card 3 -->
                    <div class="project-card bg-slate-800/90 border border-slate-700 rounded-2xl overflow-hidden hover:border-cyan-500/60 transition-all hover:-translate-y-1 shadow-lg" data-category="analytics">
                        <div class="p-8">
                            <div class="flex items-center justify-between mb-4">
                                <span class="px-3 py-1 rounded-full text-xs font-semibold bg-emerald-500/10 text-emerald-400 border border-emerald-500/30">Data Science</span>
                                <i class="fa-solid fa-chart-column text-slate-500 text-xl"></i>
                            </div>
                            <h3 class="text-xl font-bold text-white mb-3">Academic Student Performance Modeling</h3>
                            <p class="text-brand-text text-sm leading-relaxed mb-6">
                                Conducted exploratory data analysis, generated Seaborn correlation heatmaps, and fitted multi-variable linear regression models to isolate key indicators of academic success.
                            </p>
                            <div class="flex flex-wrap gap-2 mb-6">
                                <span class="text-xs bg-slate-900/80 text-slate-300 px-3 py-1 rounded-md border border-slate-700">Pandas / NumPy</span>
                                <span class="text-xs bg-slate-900/80 text-slate-300 px-3 py-1 rounded-md border border-slate-700">Seaborn Heatmaps</span>
                                <span class="text-xs bg-slate-900/80 text-slate-300 px-3 py-1 rounded-md border border-slate-700">Regression</span>
                            </div>
                            <div class="border-t border-slate-700/60 pt-4 flex justify-between items-center text-xs text-brand-text">
                                <span>Focus: Statistical Modeling</span>
                                <span class="text-cyan-400 font-semibold flex items-center gap-1 cursor-pointer hover:underline" onclick="openModal('Student Performance Analytics', 'Engineered feature sets and evaluated multi-variable regression equations. Generated statistical matrix visualizers to identify dominant factors affecting student performance outcomes.')">Details <i class="fa-solid fa-arrow-right"></i></span>
                            </div>
                        </div>
                    </div>

                    <!-- Project Card 4 -->
                    <div class="project-card bg-slate-800/90 border border-slate-700 rounded-2xl overflow-hidden hover:border-blue-500/60 transition-all hover:-translate-y-1 shadow-lg" data-category="strategy">
                        <div class="p-8">
                            <div class="flex items-center justify-between mb-4">
                                <span class="px-3 py-1 rounded-full text-xs font-semibold bg-amber-500/10 text-amber-400 border border-amber-500/30">Engineering Entrepreneurship</span>
                                <i class="fa-solid fa-fire text-slate-500 text-xl"></i>
                            </div>
                            <h3 class="text-xl font-bold text-white mb-3">Domestic LPG Retail Infrastructure Analysis</h3>
                            <p class="text-brand-text text-sm leading-relaxed mb-6">
                                Conducted technical feasibility studies, unit economics modeling, and distribution logistics design for establishing reliable energy infrastructure in Zimbabwe.
                            </p>
                            <div class="flex flex-wrap gap-2 mb-6">
                                <span class="text-xs bg-slate-900/80 text-slate-300 px-3 py-1 rounded-md border border-slate-700">Feasibility Analysis</span>
                                <span class="text-xs bg-slate-900/80 text-slate-300 px-3 py-1 rounded-md border border-slate-700">Supply Chain</span>
                                <span class="text-xs bg-slate-900/80 text-slate-300 px-3 py-1 rounded-md border border-slate-700">Market Research</span>
                            </div>
                            <div class="border-t border-slate-700/60 pt-4 flex justify-between items-center text-xs text-brand-text">
                                <span>Focus: Energy Logistics</span>
                                <span class="text-blue-400 font-semibold flex items-center gap-1 cursor-pointer hover:underline" onclick="openModal('LPG Infrastructure Analysis', 'Synthesized logistics frameworks, safety standards compliance, and financial unit models for clean domestic energy solutions in regional African markets.')">Details <i class="fa-solid fa-arrow-right"></i></span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- EDUCATION & BACKGROUND SECTION -->
        <section id="education" class="py-24 px-4 sm:px-6 lg:px-8">
            <div class="max-w-7xl mx-auto">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <h2 class="text-3xl sm:text-4xl font-bold text-white mb-4">Education & Operational Background</h2>
                    <p class="text-brand-text text-base sm:text-lg">Academic credentials and foundational practical experience.</p>
                    <div class="w-16 h-1 bg-gradient-to-r from-cyan-500 to-blue-600 mx-auto rounded-full mt-4"></div>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <!-- Academic Education Card -->
                    <div class="bg-slate-800/80 border border-slate-700 rounded-2xl p-8 relative overflow-hidden">
                        <div class="absolute top-0 left-0 w-2 h-full bg-gradient-to-b from-cyan-500 to-blue-600"></div>
                        <div class="flex justify-between items-start mb-6">
                            <div>
                                <span class="text-xs font-semibold text-cyan-400 uppercase tracking-wider">Higher Education</span>
                                <h3 class="text-2xl font-bold text-white mt-1">Manav Rachna University</h3>
                                <p class="text-brand-text font-medium text-sm">Faridabad, India</p>
                            </div>
                            <div class="w-12 h-12 rounded-xl bg-slate-900 flex items-center justify-center text-cyan-400 text-xl font-bold">
                                <i class="fa-solid fa-graduation-cap"></i>
                            </div>
                        </div>

                        <div class="space-y-4 text-slate-300 text-sm">
                            <p class="font-bold text-base text-white">B.Tech in Mechanical Engineering</p>
                            <ul class="space-y-2 border-l border-slate-700 pl-4">
                                <li><strong class="text-slate-200">Specialization:</strong> Smart Manufacturing & Automation</li>
                                <li><strong class="text-slate-200">Minor Discipline:</strong> Data Analytics</li>
                                <li><strong class="text-slate-200">Roll Number:</strong> <code class="bg-slate-900 px-2 py-0.5 rounded text-cyan-300 font-mono">2K25MEUNO1176</code></li>
                                <li><strong class="text-slate-200">Batch:</strong> Batch 05</li>
                            </ul>
                        </div>
                    </div>

                    <!-- Work / Background Experience Card -->
                    <div class="bg-slate-800/80 border border-slate-700 rounded-2xl p-8 relative overflow-hidden">
                        <div class="absolute top-0 left-0 w-2 h-full bg-gradient-to-b from-blue-500 to-emerald-500"></div>
                        <div class="flex justify-between items-start mb-6">
                            <div>
                                <span class="text-xs font-semibold text-blue-400 uppercase tracking-wider">Operational Experience</span>
                                <h3 class="text-2xl font-bold text-white mt-1">OKMART Gweru</h3>
                                <p class="text-brand-text font-medium text-sm">Gweru, Zimbabwe</p>
                            </div>
                            <div class="w-12 h-12 rounded-xl bg-slate-900 flex items-center justify-center text-blue-400 text-xl font-bold">
                                <i class="fa-solid fa-boxes-stacked"></i>
                            </div>
                        </div>

                        <div class="space-y-4 text-slate-300 text-sm">
                            <p class="font-bold text-base text-white">Retail Operations & Stock Logistics</p>
                            <p class="leading-relaxed">
                                Managed practical retail logistics, stock integrity, and inventory throughput in a fast-paced environment. This foundational operational work instilled structured discipline, supply chain awareness, and practical problem-solving capabilities prior to university engineering studies.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ATHLETICS & LEADERSHIP SECTION -->
        <section id="athletics" class="py-24 bg-slate-900/50 border-t border-brand-border/60">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="bg-gradient-to-r from-slate-800 to-slate-900 border border-slate-700 rounded-3xl p-8 sm:p-12 overflow-hidden relative">
                    <div class="absolute -right-10 -bottom-10 w-80 h-80 bg-emerald-500/10 rounded-full blur-3xl pointer-events-none"></div>

                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                        <div class="lg:col-span-8 space-y-6">
                            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-emerald-500/10 border border-emerald-500/30 text-emerald-400 text-xs font-semibold">
                                <i class="fa-solid fa-trophy"></i> University Athletic Leadership
                            </div>
                            <h2 class="text-3xl sm:text-4xl font-extrabold text-white">Forward, Manav Rachna FC</h2>
                            <p class="text-slate-300 text-base sm:text-lg leading-relaxed">
                                As a starting forward on the varsity college team, I represent Manav Rachna University in competitive collegiate matches. Playing high-level soccer demands quick tactical decision-making under pressure, physical endurance, and team synergy — values that translate directly into my engineering and analytics work.
                            </p>

                            <div class="grid grid-cols-2 sm:grid-cols-3 gap-4 pt-4 text-xs sm:text-sm">
                                <div class="bg-slate-900/70 p-4 rounded-xl border border-slate-700">
                                    <p class="text-brand-text">Role</p>
                                    <p class="font-bold text-white text-base">Forward (Attacker)</p>
                                </div>
                                <div class="bg-slate-900/70 p-4 rounded-xl border border-slate-700">
                                    <p class="text-brand-text">Team</p>
                                    <p class="font-bold text-white text-base">Manav Rachna FC</p>
                                </div>
                                <div class="bg-slate-900/70 p-4 rounded-xl border border-slate-700 col-span-2 sm:col-span-1">
                                    <p class="text-brand-text">Core Competency</p>
                                    <p class="font-bold text-white text-base">Tactical Discipline</p>
                                </div>
                            </div>
                        </div>

                        <div class="lg:col-span-4 flex justify-center">
                            <div class="w-48 h-48 sm:w-56 sm:h-56 rounded-full bg-gradient-to-tr from-emerald-500 to-cyan-500 p-1 flex items-center justify-center shadow-2xl shadow-emerald-500/20">
                                <div class="w-full h-full bg-slate-900 rounded-full flex flex-col items-center justify-center p-6 text-center">
                                    <i class="fa-solid fa-futbol text-5xl text-emerald-400 mb-3 animate-bounce"></i>
                                    <span class="font-bold text-white text-lg">Athletic & Academic Balance</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- CONTACT SECTION -->
        <section id="contact" class="py-24 px-4 sm:px-6 lg:px-8 relative">
            <div class="max-w-7xl mx-auto">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <h2 class="text-3xl sm:text-4xl font-bold text-white mb-4">Connect & Collaborate</h2>
                    <p class="text-brand-text text-base sm:text-lg">Have an engineering project, research query, or professional inquiry?</p>
                    <div class="w-16 h-1 bg-gradient-to-r from-cyan-500 to-blue-600 mx-auto rounded-full mt-4"></div>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
                    <!-- Direct Info Cards -->
                    <div class="lg:col-span-5 space-y-6">
                        <div class="bg-slate-800/80 p-6 rounded-2xl border border-slate-700 flex items-start gap-4">
                            <div class="w-12 h-12 rounded-xl bg-cyan-500/10 flex items-center justify-center text-cyan-400 shrink-0 text-lg">
                                <i class="fa-solid fa-envelope"></i>
                            </div>
                            <div>
                                <h3 class="text-white font-bold text-base">Direct Email</h3>
                                <p class="text-brand-text text-sm mb-1">Official University Mail</p>
                                <a href="mailto:rangarirai.masendeke@mru.edu.in" class="text-cyan-400 hover:underline font-semibold text-sm">rangarirai.masendeke@mru.edu.in</a>
                            </div>
                        </div>

                        <div class="bg-slate-800/80 p-6 rounded-2xl border border-slate-700 flex items-start gap-4">
                            <div class="w-12 h-12 rounded-xl bg-blue-500/10 flex items-center justify-center text-blue-400 shrink-0 text-lg">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <h3 class="text-white font-bold text-base">Location</h3>
                                <p class="text-brand-text text-sm">Faridabad, Haryana, India (University)</p>
                                <p class="text-brand-text text-xs text-slate-400 mt-1">Origin: Gweru, Zimbabwe</p>
                            </div>
                        </div>

                        <div class="bg-slate-800/80 p-6 rounded-2xl border border-slate-700 flex items-start gap-4">
                            <div class="w-12 h-12 rounded-xl bg-emerald-500/10 flex items-center justify-center text-emerald-400 shrink-0 text-lg">
                                <i class="fa-solid fa-link"></i>
                            </div>
                            <div>
                                <h3 class="text-white font-bold text-base">Professional Networks</h3>
                                <div class="flex gap-4 mt-3">
                                    <a href="https://linkedin.com" target="_blank" rel="noopener noreferrer" title="LinkedIn Profile" class="w-10 h-10 rounded-lg bg-slate-900 flex items-center justify-center text-slate-300 hover:text-cyan-400 hover:border hover:border-cyan-400 transition-all">
                                        <i class="fa-brands fa-linkedin-in"></i>
                                    </a>
                                    <a href="https://github.com" target="_blank" rel="noopener noreferrer" title="GitHub Repository" class="w-10 h-10 rounded-lg bg-slate-900 flex items-center justify-center text-slate-300 hover:text-cyan-400 hover:border hover:border-cyan-400 transition-all">
                                        <i class="fa-brands fa-github"></i>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Interactive Contact Form -->
                    <div class="lg:col-span-7 bg-slate-800/90 border border-slate-700 p-8 rounded-2xl shadow-xl">
                        <form id="contact-form" onsubmit="handleFormSubmit(event)" class="space-y-6">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                                <div>
                                    <label class="block text-sm font-semibold text-slate-200 mb-2">Your Name</label>
                                    <input type="text" required placeholder="e.g. John Doe" class="w-full bg-slate-900 border border-slate-700 rounded-xl px-4 py-3 text-slate-100 placeholder-slate-500 focus:outline-none focus:border-cyan-500 transition-colors">
                                </div>
                                <div>
                                    <label class="block text-sm font-semibold text-slate-200 mb-2">Your Email</label>
                                    <input type="email" required placeholder="e.g. john@example.com" class="w-full bg-slate-900 border border-slate-700 rounded-xl px-4 py-3 text-slate-100 placeholder-slate-500 focus:outline-none focus:border-cyan-500 transition-colors">
                                </div>
                            </div>

                            <div>
                                <label class="block text-sm font-semibold text-slate-200 mb-2">Subject</label>
                                <input type="text" required placeholder="Project Collaboration / Academic Query" class="w-full bg-slate-900 border border-slate-700 rounded-xl px-4 py-3 text-slate-100 placeholder-slate-500 focus:outline-none focus:border-cyan-500 transition-colors">
                            </div>

                            <div>
                                <label class="block text-sm font-semibold text-slate-200 mb-2">Message</label>
                                <textarea rows="5" required placeholder="Write your message here..." class="w-full bg-slate-900 border border-slate-700 rounded-xl px-4 py-3 text-slate-100 placeholder-slate-500 focus:outline-none focus:border-cyan-500 transition-colors resize-none"></textarea>
                            </div>

                            <button type="submit" class="w-full py-4 rounded-xl bg-gradient-to-r from-cyan-500 to-blue-600 text-white font-bold shadow-lg shadow-cyan-500/20 hover:shadow-cyan-500/40 hover:scale-[1.01] transition-all">
                                Send Message
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- FOOTER -->
    <footer class="bg-slate-950 border-t border-brand-border py-8 text-center text-sm text-brand-text">
        <div class="max-w-7xl mx-auto px-4 flex flex-col sm:flex-row justify-between items-center gap-4">
            <p>&copy; Rangarirai (Ranga) Masendeke. All rights reserved.</p>
            <p class="text-xs">B.Tech Smart Manufacturing & Automation | Manav Rachna University</p>
        </div>
    </footer>

    <!-- INTERACTIVE MODAL FOR DETAILS -->
    <div id="modal" class="fixed inset-0 z-50 flex items-center justify-center bg-black/70 backdrop-blur-sm hidden p-4">
        <div class="bg-slate-800 border border-slate-700 rounded-2xl max-w-lg w-full p-6 shadow-2xl relative">
            <h3 id="modal-title" class="text-xl font-bold text-white mb-3">Project Overview</h3>
            <p id="modal-body" class="text-slate-300 text-sm leading-relaxed mb-6"></p>
            <button onclick="closeModal()" class="w-full py-2.5 bg-cyan-500 hover:bg-cyan-600 text-white font-semibold rounded-xl transition-colors">
                Close View
            </button>
        </div>
    </div>

    <!-- JAVASCRIPT FOR INTERACTIVITY -->
    <script>
        // Data for Skills
        const skillsData = {
            mechanical: [
                { name: "SolidWorks (3D CAD)", desc: "Component design, assembly modeling, and engineering draft standards.", icon: "fa-cube" },
                { name: "Sensor Data Processing", desc: "Interfacing physical IoT sensors into analytical data streams.", icon: "fa-wave-square" },
                { name: "Predictive Maintenance", desc: "Machine failure modeling and preventive tool-wear scheduling.", icon: "fa-sliders" },
                { name: "Wolfram Mathematica", desc: "Symbolic computation, fluid mechanics, and differential equation modeling.", icon: "fa-calculator" },
                { name: "LaTeX Typesetting", desc: "Professional technical paper drafting and academic mathematical formatting.", icon: "fa-file-lines" },
                { name: "Fluid Mechanics & Thermo", desc: "Thermal analysis, pressure dynamic evaluation, and flow modeling.", icon: "fa-fire-flame-simple" }
            ],
            analytics: [
                { name: "Python (NumPy & Pandas)", desc: "Complex dataset cleaning, transformation, and numerical array processing.", icon: "fa-brands fa-python" },
                { name: "Matplotlib & Seaborn", desc: "Exploratory visualization, correlation heatmaps, and trend distribution.", icon: "fa-chart-line" },
                { name: "Scikit-Learn Machine Learning", desc: "Supervised regression models, classification trees, and feature scaling.", icon: "fa-brain" },
                { name: "R Programming", desc: "Statistical modeling, probability distributions, and hypothesis evaluation.", icon: "fa-r" },
                { name: "Data Pipeline Modeling", desc: "ETL structures for turning raw operational logs into actionable metrics.", icon: "fa-database" }
            ],
            design: [
                { name: "HTML5 & Tailwind CSS", desc: "Responsive, sleek web interfaces and portfolio platforms.", icon: "fa-code" },
                { name: "Figma UI/UX Mockups", desc: "Wireframing user-centric dashboards and interactive system prototypes.", icon: "fa-figma" },
                { name: "Lucidchart Architecture", desc: "Process flowcharting, data flow diagrams, and system mapping.", icon: "fa-diagram-project" }
            ]
        };

        // Render Skills Card Function
        function renderSkills(category) {
            const container = document.getElementById('skills-container');
            const list = skillsData[category] || [];
            
            container.innerHTML = list.map(s => `
                <div class="bg-slate-800/80 border border-slate-700 p-6 rounded-2xl hover:border-cyan-500/50 transition-all hover:-translate-y-1">
                    <div class="w-12 h-12 rounded-xl bg-slate-900 border border-slate-700/80 flex items-center justify-center text-cyan-400 text-xl font-bold mb-4">
                        <i class="${s.icon.includes('fa-') ? s.icon : 'fa-solid ' + s.icon}"></i>
                    </div>
                    <h3 class="text-white font-bold text-lg mb-2">${s.name}</h3>
                    <p class="text-brand-text text-sm leading-relaxed">${s.desc}</p>
                </div>
            `).join('');
        }

        // Tab Switching Logic
        function switchTab(tabKey) {
            document.querySelectorAll('.skill-tab').forEach(btn => {
                btn.classList.remove('bg-gradient-to-r', 'from-cyan-500', 'to-blue-600', 'text-white', 'shadow-lg');
                btn.classList.add('bg-slate-800', 'text-slate-300');
            });

            const activeBtn = document.getElementById(`tab-${tabKey}`);
            if (activeBtn) {
                activeBtn.classList.remove('bg-slate-800', 'text-slate-300');
                activeBtn.classList.add('bg-gradient-to-r', 'from-cyan-500', 'to-blue-600', 'text-white', 'shadow-lg');
            }

            renderSkills(tabKey);
        }

        // Project Filter Logic
        function filterProjects(cat) {
            document.querySelectorAll('.proj-filter').forEach(btn => {
                btn.classList.remove('bg-cyan-500', 'text-white');
                btn.classList.add('bg-slate-800', 'text-slate-300');
            });

            event.target.classList.remove('bg-slate-800', 'text-slate-300');
            event.target.classList.add('bg-cyan-500', 'text-white');

            const cards = document.querySelectorAll('.project-card');
            cards.forEach(card => {
                const categories = card.getAttribute('data-category');
                if (cat === 'all' || categories.includes(cat)) {
                    card.style.display = 'block';
                } else {
                    card.style.display = 'none';
                }
            });
        }

        // Modal Functions
        function openModal(title, body) {
            document.getElementById('modal-title').innerText = title;
            document.getElementById('modal-body').innerText = body;
            document.getElementById('modal').classList.remove('hidden');
        }

        function closeModal() {
            document.getElementById('modal').classList.add('hidden');
        }

        // Form Submit Handler
        function handleFormSubmit(e) {
            e.preventDefault();
            openModal(
                "Message Sent Successfully!",
                "Thank you for reaching out. Your inquiry has been logged, and Rangarirai Masendeke will respond shortly."
            );
            document.getElementById('contact-form').reset();
        }

        // Mobile Nav Toggle
        const menuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Initialize default tab on page load
        window.onload = function() {
            renderSkills('mechanical');
        };
    </script>
</body>
</html>
```
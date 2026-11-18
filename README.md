Brian Opondo
This my detailed career portfolio showing my professional journey from education, projects, to experience.
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Brian Otieno Opondo | Insurance Underwriter, Bancassurance & Economist</title>
  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Chart.js for Interactive Career Diagrams -->
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <!-- Lucide Icons -->
  <script src="https://unpkg.com/lucide@latest"></script>
  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Plus+Jakarta+Sans:wght@600;700;800&display=swap" rel="stylesheet">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
            display: ['Plus Jakarta Sans', 'sans-serif'],
          },
          colors: {
            navy: {
              900: '#0A192F',
              800: '#112240',
              700: '#1D3557',
            },
            teal: {
              600: '#0D9488',
              500: '#14B8A6',
              50: '#F0FDFA',
            }
          }
        }
      }
    }
  </script>

  <style>
    .glass-nav {
      background: rgba(255, 255, 255, 0.92);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
    }
  </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-teal-500 selection:text-white">

  <!-- Sticky Navigation -->
  <header class="fixed top-0 inset-x-0 z-50 glass-nav border-b border-slate-200/80">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
      <a href="#top" class="flex items-center gap-2.5 group">
        <div class="w-9 h-9 rounded-lg bg-navy-900 text-white font-display font-bold flex items-center justify-center text-sm tracking-wider group-hover:bg-teal-600 transition-colors">
          BO
        </div>
        <div>
          <span class="font-display font-bold text-navy-900 text-base block leading-none">Brian Opondo</span>
          <span class="text-[11px] text-slate-500 font-medium">Underwriting &bull; Bancassurance &bull; Economics</span>
        </div>
      </a>

      <!-- Desktop Menu -->
      <nav class="hidden md:flex items-center gap-7 text-sm font-medium text-slate-600">
        <a href="#about" class="hover:text-teal-600 transition-colors">About</a>
        <a href="#analytics" class="hover:text-teal-600 transition-colors">Career Metrics</a>
        <a href="#experience" class="hover:text-teal-600 transition-colors">Experience</a>
        <a href="#education" class="hover:text-teal-600 transition-colors">Education & Certs</a>
        <a href="#projects" class="hover:text-teal-600 transition-colors">Projects</a>
        <a href="#contact" class="px-4 py-2 rounded-lg bg-navy-900 text-white hover:bg-teal-600 transition-colors">Contact</a>
      </nav>

      <!-- Mobile Menu Button -->
      <button id="mobile-menu-btn" class="md:hidden p-2 rounded-lg text-slate-700 hover:bg-slate-100" aria-label="Open Menu">
        <i data-lucide="menu" class="w-6 h-6"></i>
      </button>
    </div>

    <!-- Mobile Dropdown -->
    <div id="mobile-menu" class="hidden md:hidden bg-white border-b border-slate-200 px-4 pt-2 pb-4 space-y-2 text-sm font-medium">
      <a href="#about" class="block py-2 text-slate-700 hover:text-teal-600">About</a>
      <a href="#analytics" class="block py-2 text-slate-700 hover:text-teal-600">Career Metrics & Diagrams</a>
      <a href="#experience" class="block py-2 text-slate-700 hover:text-teal-600">Work Experience</a>
      <a href="#education" class="block py-2 text-slate-700 hover:text-teal-600">Education & Certifications</a>
      <a href="#projects" class="block py-2 text-slate-700 hover:text-teal-600">Projects & Leadership</a>
      <a href="#contact" class="block py-2 text-teal-600 font-semibold">Contact & References</a>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="top" class="pt-28 pb-16 md:pt-36 md:pb-24 bg-gradient-to-br from-navy-900 via-navy-800 to-slate-900 text-white relative overflow-hidden">
    <div class="absolute inset-0 opacity-10" style="background-image: radial-gradient(#14B8A6 1px, transparent 1px); background-size: 28px 28px;"></div>

    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
        <!-- Left Text Column -->
        <div class="lg:col-span-8 space-y-6">
          <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-teal-500/15 border border-teal-400/30 text-teal-300 text-xs font-semibold tracking-wide uppercase">
            <span class="w-2 h-2 rounded-full bg-teal-400 animate-pulse"></span>
            Nairobi, Kenya &bull; 3+ Years Active Industry Experience
          </div>

          <h1 class="font-display text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight leading-tight">
            Brian Otieno <span class="text-teal-400">Opondo</span>
          </h1>

          <p class="text-lg sm:text-xl text-slate-200 font-medium">
            Insurance Underwriter &bull; Bancassurance Specialist &bull; BSc. Economics
          </p>

          <p class="text-slate-300 text-base leading-relaxed max-w-2xl">
            Results-oriented professional specializing in general insurance underwriting, bancassurance operations, risk assessment, claims processing, and economic data analysis. Proven track record of managing high-volume daily policy portfolios while maintaining strict regulatory compliance.
          </p>

          <!-- Key KPI Strip -->
          <div class="grid grid-cols-3 gap-4 pt-2 max-w-xl">
            <div class="bg-white/5 border border-white/10 rounded-xl p-3.5">
              <div class="font-display text-2xl sm:text-3xl font-bold text-teal-400">30+</div>
              <div class="text-xs text-slate-300 mt-0.5">Daily Client On-boardings & Inquiries</div>
            </div>
            <div class="bg-white/5 border border-white/10 rounded-xl p-3.5">
              <div class="font-display text-2xl sm:text-3xl font-bold text-teal-400">15+</div>
              <div class="text-xs text-slate-300 mt-0.5">Daily Quotations & Risk Proposals</div>
            </div>
            <div class="bg-white/5 border border-white/10 rounded-xl p-3.5">
              <div class="font-display text-2xl sm:text-3xl font-bold text-teal-400">100%</div>
              <div class="text-xs text-slate-300 mt-0.5">KYC / AML & Audit Accuracy</div>
            </div>
          </div>

          <!-- Action Buttons -->
          <div class="flex flex-wrap items-center gap-4 pt-2">
            <a href="#experience" class="px-6 py-3 rounded-xl bg-teal-600 hover:bg-teal-500 text-white font-semibold text-sm shadow-lg shadow-teal-900/40 transition-all flex items-center gap-2">
              Explore Career Timeline
              <i data-lucide="arrow-down-right" class="w-4 h-4"></i>
            </a>
            <a href="https://www.linkedin.com/in/brian-opondo001" target="_blank" rel="noopener noreferrer" class="px-6 py-3 rounded-xl bg-white/10 hover:bg-white/15 border border-white/20 text-white font-semibold text-sm transition-all flex items-center gap-2">
              <i data-lucide="linkedin" class="w-4 h-4 text-teal-300"></i>
              LinkedIn Profile
            </a>
          </div>
        </div>

        <!-- Right Quick Badge Column -->
        <div class="lg:col-span-4 flex justify-center">
          <div class="w-full max-w-sm bg-white/5 border border-white/10 rounded-2xl p-6 backdrop-blur-sm space-y-4">
            <div class="flex items-center gap-3">
              <div class="w-10 h-10 rounded-xl bg-teal-500/20 text-teal-300 flex items-center justify-center font-bold">
                BO
              </div>
              <div>
                <h3 class="font-display font-bold text-white text-base">Professional Focus</h3>
                <p class="text-xs text-slate-300">Risk, Banking & Macroeconomics</p>
              </div>
            </div>
            <p class="text-xs text-slate-300 leading-relaxed">
              Equipped with robust risk management frameworks, quantitative research capabilities, and enterprise software execution.
            </p>
            <div class="pt-3 border-t border-white/10 flex items-center justify-between text-xs text-teal-300">
              <span>Status: Active Professional</span>
              <span class="inline-flex items-center gap-1 font-semibold"><i data-lucide="shield-check" class="w-3.5 h-3.5"></i> Verified</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-16 md:py-24 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="max-w-3xl space-y-6 mx-auto text-center">
      <div>
        <span class="text-xs font-bold uppercase tracking-widest text-teal-600">Professional Profile</span>
        <h2 class="font-display text-3xl sm:text-4xl font-bold text-navy-900 mt-1">
          Bridging Economic Analysis with Precision Risk Underwriting
        </h2>
      </div>

      <p class="text-slate-600 leading-relaxed text-base">
        With a Bachelor of Science in Economics (Second Class Honors, Upper Division) from Maasai Mara University[cite: 11] and three years of hands-on experience in Kenya’s insurance and financial sector[cite: 11], I bring quantitative rigor to risk evaluation, premium negotiation, and bancassurance operations[cite: 11].
      </p>

      <p class="text-slate-600 leading-relaxed text-base">
        From evaluating risk exposures at <strong>Reica Insurance Brokers</strong>[cite: 11] and managing high-volume bancassurance workflows in the <strong>Inspro system</strong> at <strong>Consolidated Bancassurance Intermediary</strong>[cite: 11], to conducting national policy research at <strong>The National Treasury</strong>[cite: 11] and field data mapping for <strong>UNICEF</strong>, my career is built on accuracy, integrity, and client-centric delivery.
      </p>

      <!-- 3 Core Competency Cards -->
      <div class="grid grid-cols-1 sm:grid-cols-3 gap-6 pt-6 text-left">
        <div class="p-5 rounded-2xl bg-white border border-slate-200 shadow-sm hover:border-teal-500 transition-colors">
          <div class="w-10 h-10 rounded-xl bg-teal-50 text-teal-600 flex items-center justify-center mb-4">
            <i data-lucide="file-check-2" class="w-5 h-5"></i>
          </div>
          <h3 class="font-display font-bold text-navy-900 text-base">Underwriting & Risk</h3>
          <p class="text-xs text-slate-500 mt-1 leading-relaxed">Loss history evaluation, cover notes, premium pricing & insurer negotiations[cite: 11].</p>
        </div>

        <div class="p-5 rounded-2xl bg-white border border-slate-200 shadow-sm hover:border-teal-500 transition-colors">
          <div class="w-10 h-10 rounded-xl bg-blue-50 text-blue-600 flex items-center justify-center mb-4">
            <i data-lucide="building-2" class="w-5 h-5"></i>
          </div>
          <h3 class="font-display font-bold text-navy-900 text-base">Bancassurance Ops</h3>
          <p class="text-xs text-slate-500 mt-1 leading-relaxed">Inspro system onboarding, policy renewals, claims tracking & KYC/AML compliance[cite: 11].</p>
        </div>

        <div class="p-5 rounded-2xl bg-white border border-slate-200 shadow-sm hover:border-teal-500 transition-colors">
          <div class="w-10 h-10 rounded-xl bg-amber-50 text-amber-600 flex items-center justify-center mb-4">
            <i data-lucide="bar-chart-3" class="w-5 h-5"></i>
          </div>
          <h3 class="font-display font-bold text-navy-900 text-base">Economics & Data</h3>
          <p class="text-xs text-slate-500 mt-1 leading-relaxed">Macroeconomic policy research[cite: 11], SAP business analysis[cite: 11] & electronic survey mapping.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Interactive Career Diagrams & Analytics Section -->
  <section id="analytics" class="py-16 md:py-24 bg-white border-y border-slate-200">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="max-w-3xl">
        <span class="text-xs font-bold uppercase tracking-widest text-teal-600">Interactive Career Diagrams</span>
        <h2 class="font-display text-3xl sm:text-4xl font-bold text-navy-900 mt-1">
          Operational Throughput & Competency Architecture
        </h2>
        <p class="text-slate-600 mt-2">
          Visualizing daily operational benchmarks across bancassurance and underwriting roles alongside cross-functional domain expertise.
        </p>
      </div>

      <!-- Two Interactive Charts Grid -->
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 mt-10">
        <!-- Bar Chart: Daily Operational Volume -->
        <div class="lg:col-span-7 bg-slate-50 rounded-2xl p-6 border border-slate-200 shadow-sm">
          <div class="flex flex-wrap items-center justify-between gap-2 mb-4">
            <div>
              <h3 class="font-display font-bold text-navy-900 text-lg">Daily Operational Volume Benchmarks</h3>
              <p class="text-xs text-slate-500">Average daily transactions processed across insurance roles</p>
            </div>
            <span class="px-3 py-1 rounded-full bg-teal-100 text-teal-800 text-xs font-semibold">Interactive Chart</span>
          </div>
          <div class="relative h-72 w-full">
            <canvas id="throughputChart"></canvas>
          </div>
        </div>

        <!-- Radar Chart: Domain Competency Matrix -->
        <div class="lg:col-span-5 bg-slate-50 rounded-2xl p-6 border border-slate-200 shadow-sm">
          <div class="mb-4">
            <h3 class="font-display font-bold text-navy-900 text-lg">Core Competency Matrix</h3>
            <p class="text-xs text-slate-500">Multi-disciplinary balance of technical, analytical & client skills</p>
          </div>
          <div class="relative h-72 w-full">
            <canvas id="skillsRadarChart"></canvas>
          </div>
        </div>
      </div>

      <!-- Process Workflow Diagram -->
      <div class="mt-10 bg-navy-900 text-white rounded-2xl p-6 sm:p-8 shadow-lg">
        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-6">
          <div>
            <span class="text-xs font-semibold uppercase tracking-wider text-teal-400">End-

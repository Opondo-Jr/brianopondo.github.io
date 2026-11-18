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
    .hd-photo {
      image-rendering: -webkit-optimize-contrast;
      filter: contrast(1.04) saturate(1.05);
      transition: transform 0.4s ease, filter 0.4s ease;
    }
    .hd-photo:hover {
      transform: scale(1.02);
      filter: contrast(1.07) saturate(1.08);
    }
    .hd-logo {
      image-rendering: -webkit-optimize-contrast;
      filter: contrast(1.06) saturate(1.08);
      object-fit: contain;
    }
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
        <div class="lg:col-span-7 space-y-6">
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

        <!-- Right Portrait Card -->
        <div class="lg:col-span-5 flex justify-center">
          <div class="relative w-72 sm:w-80 md:w-96">
            <div class="absolute -inset-2 rounded-2xl bg-gradient-to-tr from-teal-500 to-blue-500 opacity-30 blur-lg"></div>
            <div class="relative rounded-2xl overflow-hidden bg-white p-2 shadow-2xl border border-white/20">
              <img
                src="Screenshot_20241116-104240_Gallery.jpg"
                alt="Brian Otieno Opondo - Professional Portrait"
                class="w-full h-[380px] sm:h-[420px] object-cover object-top rounded-xl hd-photo bg-slate-100"
              />
              <div class="p-3 bg-white flex items-center justify-between">
                <div>
                  <p class="text-xs font-bold text-navy-900">Bancassurance & Underwriting</p>
                  <p class="text-[11px] text-slate-500">Consolidated Bancassurance Intermediary</p>
                </div>
                <span class="inline-flex items-center gap-1 px-2.5 py-1 rounded-full bg-teal-50 text-teal-700 text-[11px] font-semibold">
                  <i data-lucide="shield-check" class="w-3.5 h-3.5"></i> Verified
                </span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- About & Visual Journey Section -->
  <section id="about" class="py-16 md:py-24 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
      <!-- Photo Collage -->
      <div class="lg:col-span-5 grid grid-cols-2 gap-4">
        <div class="space-y-4">
          <div class="rounded-2xl overflow-hidden shadow-md border border-slate-200 bg-white">
            <img
              src="IMG-20240621-WA0101.jpg"
              alt="Brian Opondo in a professional training and policy session"
              class="w-full h-56 object-cover object-center hd-photo"
            />
            <div class="p-2.5 text-[11px] text-slate-600 font-medium bg-slate-50 border-t border-slate-100">
              Stakeholder & Field Research Forum
            </div>
          </div>
          <div class="p-4 rounded-2xl bg-navy-900 text-white shadow-md">
            <div class="text-xs text-teal-400 font-semibold uppercase tracking-wider">Languages</div>
            <p class="text-sm font-semibold mt-1">English &bull; Kiswahili &bull; Dholuo</p>
            <p class="text-xs text-slate-400 mt-0.5">Full Professional Proficiency</p>
          </div>
        </div>

        <div class="pt-6">
          <div class="rounded-2xl overflow-hidden shadow-md border border-slate-200 bg-white">
            <img
              src="RKD_9861.jpg"
              alt="Brian Opondo Graduation Portrait - BSc Economics"
              class="w-full h-72 object-cover object-top hd-photo"
            />
            <div class="p-2.5 text-[11px] text-slate-600 font-medium bg-slate-50 border-t border-slate-100">
              BSc. Economics &bull; Maasai Mara University
            </div>
          </div>
        </div>
      </div>

      <!-- Narrative & Core Pillars -->
      <div class="lg:col-span-7 space-y-6">
        <div>
          <span class="text-xs font-bold uppercase tracking-widest text-teal-600">Professional Profile</span>
          <h2 class="font-display text-3xl sm:text-4xl font-bold text-navy-900 mt-1">
            Bridging Economic Analysis with Precision Risk Underwriting
          </h2>
        </div>

        <p class="text-slate-600 leading-relaxed">
          With a Bachelor of Science in Economics (Second Class Honors, Upper Division) from Maasai Mara University and three years of hands-on experience in Kenya’s insurance and financial sector, I bring quantitative rigor to risk evaluation, premium negotiation, and bancassurance operations.
        </p>

        <p class="text-slate-600 leading-relaxed">
          From evaluating risk exposures at <strong>Reica Insurance Brokers</strong> and managing high-volume bancassurance workflows in the <strong>Inspro system</strong> at <strong>Consolidated Bancassurance Intermediary</strong>, to conducting national policy research at <strong>The National Treasury</strong> and field data mapping for <strong>UNICEF</strong>, my career is built on accuracy, integrity, and client-centric delivery.
        </p>

        <!-- 3 Core Competency Cards -->
        <div class="grid grid-cols-1 sm:grid-cols-3 gap-4 pt-2">
          <div class="p-4 rounded-xl bg-white border border-slate-200 shadow-sm hover:border-teal-500 transition-colors">
            <div class="w-9 h-9 rounded-lg bg-teal-50 text-teal-600 flex items-center justify-center mb-3">
              <i data-lucide="file-check-2" class="w-5 h-5"></i>
            </div>
            <h3 class="font-display font-bold text-navy-900 text-sm">Underwriting & Risk</h3>
            <p class="text-xs text-slate-500 mt-1">Loss history evaluation, cover notes, premium pricing & insurer negotiations.</p>
          </div>

          <div class="p-4 rounded-xl bg-white border border-slate-200 shadow-sm hover:border-teal-500 transition-colors">
            <div class="w-9 h-9 rounded-lg bg-blue-50 text-blue-600 flex items-center justify-center mb-3">
              <i data-lucide="building-2" class="w-5 h-5"></i>
            </div>
            <h3 class="font-display font-bold text-navy-900 text-sm">Bancassurance Ops</h3>
            <p class="text-xs text-slate-500 mt-1">Inspro system onboarding, policy renewals, claims tracking & KYC/AML compliance.</p>
          </div>

          <div class="p-4 rounded-xl bg-white border border-slate-200 shadow-sm hover:border-teal-500 transition-colors">
            <div class="w-9 h-9 rounded-lg bg-amber-50 text-amber-600 flex items-center justify-center mb-3">
              <i data-lucide="bar-chart-3" class="w-5 h-5"></i>
            </div>
            <h3 class="font-display font-bold text-navy-900 text-sm">Economics & Data</h3>
            <p class="text-xs text-slate-500 mt-1">Macroeconomic policy research, SAP business analysis & electronic survey mapping.</p>
          </div>
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
            <span class="text-xs font-semibold uppercase tracking-wider text-teal-400">End-to-End Workflow Diagram</span>
            <h3 class="font-display text-xl font-bold mt-0.5">Bancassurance & Underwriting Execution Pipeline</h3>
          </div>
          <span class="text-xs text-slate-400">Click any stage to inspect operational standards</span>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-5 gap-4" id="workflow-steps">
          <button onclick="selectWorkflow(0)" class="workflow-btn text-left p-4 rounded-xl bg-teal-600/20 border-2 border-teal-400 transition-all">
            <div class="text-xs font-bold text-teal-300">01 &bull; INTAKE</div>
            <div class="font-display font-bold text-sm mt-1">Client & Risk Assessment</div>
            <p class="text-[11px] text-slate-300 mt-1">30 daily applications & loss record reviews</p>
          </button>

          <button onclick="selectWorkflow(1)" class="workflow-btn text-left p-4 rounded-xl bg-white/5 border border-white/15 hover:border-teal-400/60 transition-all">
            <div class="text-xs font-bold text-slate-400">02 &bull; PRICING</div>
            <div class="font-display font-bold text-sm mt-1">Quotation & Negotiation</div>
            <p class="text-[11px] text-slate-300 mt-1">15 competitive quotes & insurer terms daily</p>
          </button>

          <button onclick="selectWorkflow(2)" class="workflow-btn text-left p-4 rounded-xl bg-white/5 border border-white/15 hover:border-teal-400/60 transition-all">
            <div class="text-xs font-bold text-slate-400">03 &bull; COMPLIANCE</div>
            <div class="font-display font-bold text-sm mt-1">Inspro Onboarding & KYC</div>
            <p class="text-[11px] text-slate-300 mt-1">AML verification & policy record entry</p>
          </button>

          <button onclick="selectWorkflow(3)" class="workflow-btn text-left p-4 rounded-xl bg-white/5 border border-white/15 hover:border-teal-400/60 transition-all">
            <div class="text-xs font-bold text-slate-400">04 &bull; RETENTION</div>
            <div class="font-display font-bold text-sm mt-1">Policy Renewals</div>
            <p class="text-[11px] text-slate-300 mt-1">30 renewal invitations managed daily</p>
          </button>

          <button onclick="selectWorkflow(4)" class="workflow-btn text-left p-4 rounded-xl bg-white/5 border border-white/15 hover:border-teal-400/60 transition-all">
            <div class="text-xs font-bold text-slate-400">05 &bull; RESOLUTION</div>
            <div class="font-display font-bold text-sm mt-1">Claims & Reporting</div>
            <p class="text-[11px] text-slate-300 mt-1">Weekly claims filing & executive reports</p>
          </button>
        </div>

        <div id="workflow-detail" class="mt-5 p-4 rounded-xl bg-white/10 border border-white/10 text-sm text-slate-200 flex items-start gap-3">
          <i data-lucide="info" class="w-5 h-5 text-teal-400 shrink-0 mt-0.5"></i>
          <div>
            <strong class="text-white">Stage 01 — Client & Risk Assessment:</strong> Gathering applicant data, evaluating loss records, claims history, and financial exposures across 10–30 daily cases to establish accurate risk eligibility before policy structuring.
          </div>
        </div>
      </div>

      <!-- Skill Filter Pills -->
      <div class="mt-10">
        <div class="flex flex-wrap items-center justify-between gap-4 mb-4">
          <h3 class="font-display font-bold text-navy-900 text-lg">Core Competencies & Technical Toolkit</h3>
          <div class="flex flex-wrap gap-2">
            <button onclick="filterSkills('all')" class="skill-tab px-3 py-1 rounded-full text-xs font-semibold bg-navy-900 text-white">All Skills (18)</button>
            <button onclick="filterSkills('insurance')" class="skill-tab px-3 py-1 rounded-full text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200">Insurance & Risk</button>
            <button onclick="filterSkills('analytics')" class="skill-tab px-3 py-1 rounded-full text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200">Data & Economics</button>
            <button onclick="filterSkills('leadership')" class="skill-tab px-3 py-1 rounded-full text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200">Leadership & Soft Skills</button>
          </div>
        </div>
        <div id="skills-container" class="flex flex-wrap gap-2.5"></div>
      </div>
    </div>
  </section>

  <!-- Work Experience Timeline Section (With Exact Matched Logos) -->
  <section id="experience" class="py-16 md:py-24 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex flex-col md:flex-row md:items-end justify-between gap-4 mb-12">
      <div>
        <span class="text-xs font-bold uppercase tracking-widest text-teal-600">Career Progression</span>
        <h2 class="font-display text-3xl sm:text-4xl font-bold text-navy-900 mt-1">
          Professional Work Experience
        </h2>
      </div>

      <div class="inline-flex rounded-xl bg-slate-200/70 p-1 self-start">
        <button onclick="filterExperience('all')" class="exp-filter px-4 py-2 rounded-lg text-xs font-semibold bg-white text-navy-900 shadow-sm transition-all">All Roles (4)</button>
        <button onclick="filterExperience('insurance')" class="exp-filter px-4 py-2 rounded-lg text-xs font-semibold text-slate-600 hover:text-navy-900 transition-all">Insurance & Banking</button>
        <button onclick="filterExperience('research')" class="exp-filter px-4 py-2 rounded-lg text-xs font-semibold text-slate-600 hover:text-navy-900 transition-all">Economics & Field Data</button>
      </div>
    </div>

    <div class="space-y-8" id="experience-list">

      <!-- Role 1: Bancassurance Assistant (Consolidated Bancassurance Logo) -->
      <article data-category="insurance" class="exp-card bg-white rounded-2xl border border-slate-200 p-6 sm:p-8 shadow-sm hover:shadow-md transition-shadow">
        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 pb-5 border-b border-slate-100">
          <div class="flex items-center gap-4">
            <div class="w-16 h-14 rounded-xl bg-white border border-slate-200 p-1 flex items-center justify-center shrink-0 shadow-xs">
              <img src="Consolidated bancasurance.jpg" alt="Consolidated Bank Logo" class="w-full h-full hd-logo" />
            </div>
            <div>
              <div class="flex flex-wrap items-center gap-2">
                <h3 class="font-display text-xl font-bold text-navy-900">Bancassurance Assistant</h3>
                <span class="px-2.5 py-0.5 rounded-full bg-teal-50 text-teal-700 text-xs font-semibold">Current Role</span>
              </div>
              <p class="text-sm font-semibold text-slate-700 mt-0.5">Consolidated Bancassurance Intermediary Limited &bull; Nairobi</p>
            </div>
          </div>
          <div class="text-xs font-bold text-navy-900 bg-slate-100 px-3.5 py-1.5 rounded-lg self-start sm:self-center">
            Jul 2026 – Present
          </div>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-x-8 gap-y-2.5 pt-5 text-sm text-slate-600">
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Handling <strong>30 daily client and internal agent inquiries</strong> regarding insurance products, premiums, policy benefits, claims, and policy servicing.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Preparing and processing an average of <strong>15 insurance quotations daily</strong> while liaising with underwriters to secure competitive premiums.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Facilitating on-boarding of <strong>30 new and repeat clients daily</strong> in the <strong>Inspro bancassurance system</strong> with accurate verification.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Managing <strong>30 policy renewal invitations daily</strong>, following up on expiring policies to maintain uninterrupted client coverage.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Receiving, reviewing, and submitting <strong>3 insurance claims weekly</strong> while guiding clients and tracking progress with insurers.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Ensuring strict compliance with <strong>KYC, AML, data protection</strong>, and preparing weekly/monthly operational performance reports.</span>
          </div>
        </div>
      </article>

      <!-- Role 2: General Insurance Underwriter (Reica Insurance Logo) -->
      <article data-category="insurance" class="exp-card bg-white rounded-2xl border border-slate-200 p-6 sm:p-8 shadow-sm hover:shadow-md transition-shadow">
        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 pb-5 border-b border-slate-100">
          <div class="flex items-center gap-4">
            <div class="w-20 h-14 rounded-xl bg-white border border-slate-200 p-1 flex items-center justify-center shrink-0 shadow-xs">
              <img src="reica-logo-300x97.png" alt="Reica Insurance Brokers Logo" class="w-full h-full hd-logo" />
            </div>
            <div>
              <h3 class="font-display text-xl font-bold text-navy-900">General Insurance Underwriter</h3>
              <p class="text-sm font-semibold text-slate-700 mt-0.5">Reica Insurance Brokers Limited &bull; Nairobi</p>
            </div>
          </div>
          <div class="text-xs font-bold text-navy-900 bg-slate-100 px-3.5 py-1.5 rounded-lg self-start sm:self-center">
            Dec 2023 – Jun 2026
          </div>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-x-8 gap-y-2.5 pt-5 text-sm text-slate-600">
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Evaluated an average of <strong>30 insurance applications daily</strong>, gathering applicant information to facilitate sound underwriting decisions.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Reviewed <strong>15 insurance proposals daily</strong> for completeness, accuracy, and compliance with insurer underwriting guidelines.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Analyzed financial data, risk exposures, and loss records for <strong>10 cases daily</strong> and prepared weekly preliminary risk assessment reports.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Generated <strong>15 competitive insurance quotations and cover notes daily</strong> across multiple classes for new business and renewals.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Processed <strong>20 client policy records daily</strong> into underwriting systems, ensuring data accuracy, confidentiality, and timely issuance.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Coordinated across claims, finance, and customer service teams to resolve policy discrepancies and negotiate competitive terms.</span>
          </div>
        </div>
      </article>

      <!-- Role 3: Enumerator - UNICEF School Mapping Program -->
      <article data-category="research" class="exp-card bg-white rounded-2xl border border-slate-200 p-6 sm:p-8 shadow-sm hover:shadow-md transition-shadow">
        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 pb-5 border-b border-slate-100">
          <div class="flex items-center gap-4">
            <div class="w-20 h-14 rounded-xl bg-white border border-slate-200 p-1.5 flex items-center justify-center shrink-0 shadow-xs">
              <img src="unicef.png" alt="UNICEF Logo" class="w-full h-full hd-logo" />
            </div>
            <div>
              <div class="flex flex-wrap items-center gap-2">
                <h3 class="font-display text-xl font-bold text-navy-900">Enumerator</h3>
                <span class="px-2.5 py-0.5 rounded-full bg-sky-50 text-sky-700 text-xs font-semibold">Field Data & Mapping</span>
              </div>
              <p class="text-sm font-semibold text-slate-700 mt-0.5">UNICEF School Mapping Program &bull; Nairobi</p>
            </div>
          </div>
          <div class="text-xs font-bold text-navy-900 bg-slate-100 px-3.5 py-1.5 rounded-lg self-start sm:self-center">
            Oct 2024
          </div>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-x-8 gap-y-2.5 pt-5 text-sm text-slate-600">
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-sky-600 shrink-0 mt-1"></i>
            <span>Collected primary institutional data by conducting structured interviews with school head teachers using standardized survey instruments.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-sky-600 shrink-0 mt-1"></i>
            <span>Verified the accuracy and completeness of collected data during interviews, ensuring valid responses and resolving inconsistencies on-site.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-sky-600 shrink-0 mt-1"></i>
            <span>Accurately inputted validated records into the electronic data collection system immediately following each school interview.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-sky-600 shrink-0 mt-1"></i>
            <span>Submitted completed data collection forms and field progress reports to the project supervisor within strict designated deadlines.</span>
          </div>
        </div>
      </article>

      <!-- Role 4: Economist Attaché (The National Treasury Logo) -->
      <article data-category="research" class="exp-card bg-white rounded-2xl border border-slate-200 p-6 sm:p-8 shadow-sm hover:shadow-md transition-shadow">
        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 pb-5 border-b border-slate-100">
          <div class="flex items-center gap-4">
            <div class="w-24 h-14 rounded-xl bg-white border border-slate-200 p-1 flex items-center justify-center shrink-0 shadow-xs">
              <img src="The National Treasury.png" alt="The National Treasury Logo" class="w-full h-full hd-logo" />
            </div>
            <div>
              <h3 class="font-display text-xl font-bold text-navy-900">Economist Attaché</h3>
              <p class="text-sm font-semibold text-slate-700 mt-0.5">The National Treasury and Economic Planning &bull; Nairobi</p>
            </div>
          </div>
          <div class="text-xs font-bold text-navy-900 bg-slate-100 px-3.5 py-1.5 rounded-lg self-start sm:self-center">
            May 2023 – Aug 2023
          </div>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-x-8 gap-y-2.5 pt-5 text-sm text-slate-600">
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-amber-600 shrink-0 mt-1"></i>
            <span>Carried out monitoring and evaluation of macroeconomic trends and conducted topical policy research, including food security and hunger implications in Kenya.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-amber-600 shrink-0 mt-1"></i>
            <span>Contributed to <strong>three economic policy formulation and implementation guidelines</strong> alongside national statistics management.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-amber-600 shrink-0 mt-1"></i>
            <span>Assessed potential fiscal and economic impacts of proposed government policies for national and sectoral development planning.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-amber-600 shrink-0 mt-1"></i>
            <span>Synthesized complex economic datasets into clear, concise analytical reports for policymakers and key stakeholders.</span>
          </div>
        </div>
      </article>

    </div>
  </section>

  <!-- Education & Verified Certifications Section (With Maasai Mara & Ambira Logos) -->
  <section id="education" class="py-16 md:py-24 bg-white border-y border-slate-200">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="max-w-3xl mb-12">
        <span class="text-xs font-bold uppercase tracking-widest text-teal-600">Academic & Technical Credentials</span>
        <h2 class="font-display text-3xl sm:text-4xl font-bold text-navy-900 mt-1">
          Education & Professional Certifications
        </h2>
        <p class="text-slate-600 mt-2">
          Formal university training in Economics paired with enterprise SAP technology, digital data management, and corporate leadership credentials.
        </p>
      </div>

      <!-- Featured Degree Card with Maasai Mara University Logo -->
      <div class="bg-gradient-to-r from-navy-900 to-navy-800 text-white rounded-2xl p-6 sm:p-8 mb-8 shadow-md flex flex-col md:flex-row md:items-center justify-between gap-6">
        <div class="flex items-center gap-4">
          <div class="w-16 h-16 rounded-2xl bg-white p-1.5 flex items-center justify-center shrink-0 shadow-md">
            <img src="Maasai mara university.jpg" alt="Maasai Mara University Logo" class="w-full h-full hd-logo" />
          </div>
          <div>
            <span class="text-xs font-bold uppercase tracking-wider text-teal-300">University Degree</span>
            <h3 class="font-display text-2xl font-bold mt-0.5">Bachelor of Science in Economics</h3>
            <p class="text-slate-300 font-medium text-sm mt-1">Maasai Mara University &bull; Second Class Honors (Upper Division)</p>
          </div>
        </div>
        <div class="px-4 py-2 rounded-xl bg-white/10 border border-white/15 text-xs font-bold tracking-wide self-start md:self-center">
          Sep 2019 – Dec 2023
        </div>
      </div>

      <!-- Certifications Grid with Matched Logos -->
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">

        <!-- Coursera -->
        <div class="bg-slate-50 rounded-2xl border border-slate-200 p-6 flex flex-col justify-between hover:border-blue-500 transition-colors">
          <div>
            <div class="h-14 w-32 rounded-xl bg-white border border-slate-200 p-2 flex items-center justify-center mb-4 shadow-xs">
              <img src="coursera.png" alt="Coursera Logo" class="w-full h-full hd-logo" />
            </div>
            <span class="text-[11px] font-bold uppercase tracking-wider text-blue-700">Coursera</span>
            <h4 class="font-display font-bold text-navy-900 text-lg mt-1">SAP Business Analyst Certificate</h4>
            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
              Enterprise business process modeling, SAP system workflows, requirements analysis, and data-driven operational reporting.
            </p>
          </div>
          <div class="mt-5 pt-3 border-t border-slate-200 flex items-center justify-between text-xs font-semibold text-slate-500">
            <span>Issued via Coursera</span>
            <span class="text-navy-900">Jun 2025 – Aug 2025</span>
          </div>
        </div>

        <!-- Ajira Digital Program -->
        <div class="bg-slate-50 rounded-2xl border border-slate-200 p-6 flex flex-col justify-between hover:border-green-600 transition-colors">
          <div>
            <div class="h-14 w-36 rounded-xl bg-white border border-slate-200 p-2 flex items-center justify-center mb-4 shadow-xs">
              <img src="ajira.jpg" alt="Ajira Digital Program Logo" class="w-full h-full hd-logo" />
            </div>
            <span class="text-[11px] font-bold uppercase tracking-wider text-green-700">Ajira Digital Program</span>
            <h4 class="font-display font-bold text-navy-900 text-lg mt-1">Data Entry & Management Certificate</h4>
            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
              Structured database administration, high-speed accurate data capture, spreadsheet modeling, and digital record integrity.
            </p>
          </div>
          <div class="mt-5 pt-3 border-t border-slate-200 flex items-center justify-between text-xs font-semibold text-slate-500">
            <span>ajiradigital.go.ke</span>
            <span class="text-navy-900">Mar 2023</span>
          </div>
        </div>

        <!-- Corporate Career Academy -->
        <div class="bg-slate-50 rounded-2xl border border-slate-200 p-6 flex flex-col justify-between hover:border-red-500 transition-colors">
          <div>
            <div class="h-14 w-40 rounded-xl bg-white border border-slate-200 p-2 flex items-center justify-center mb-4 shadow-xs">
              <img src="coporate career academy.png" alt="Corporate Career Academy Logo" class="w-full h-full hd-logo" />
            </div>
            <span class="text-[11px] font-bold uppercase tracking-wider text-red-600">Corporate Career Academy</span>
            <h4 class="font-display font-bold text-navy-900 text-lg mt-1">Career, Leadership & Employability Skills</h4>
            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
              Executive workplace readiness, corporate ethics, team leadership, stakeholder communication, and organizational problem-solving.
            </p>
          </div>
          <div class="mt-5 pt-3 border-t border-slate-200 flex items-center justify-between text-xs font-semibold text-slate-500">
            <span>Nurturing for Industry</span>
            <span class="text-navy-900">Nov 2022</span>
          </div>
        </div>

        <!-- SAP Educate to Employ -->
        <div class="bg-slate-50 rounded-2xl border border-slate-200 p-6 flex flex-col justify-between hover:border-teal-500 transition-colors">
          <div>
            <div class="h-14 w-14 rounded-xl bg-navy-900 text-teal-400 flex items-center justify-center mb-4 font-display font-bold text-sm">
              SAP
            </div>
            <span class="text-[11px] font-bold uppercase tracking-wider text-teal-700">SAP Educate to Employ</span>
            <h4 class="font-display font-bold text-navy-900 text-lg mt-1">SAP General Tech Consultant</h4>
            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
              Enterprise ERP configuration, cloud architecture fundamentals, and technical consulting best practices.
            </p>
          </div>
          <div class="mt-5 pt-3 border-t border-slate-200 flex items-center justify-between text-xs font-semibold text-slate-500">
            <span>In Progress</span>
            <span class="text-navy-900">Jul 2025 – Present</span>
          </div>
        </div>

        <!-- Ambira High School (With Ambira Logo) -->
        <div class="bg-slate-50 rounded-2xl border border-slate-200 p-6 flex flex-col justify-between hover:border-red-600 transition-colors">
          <div>
            <div class="h-14 w-14 rounded-xl bg-white border border-slate-200 p-1 flex items-center justify-center mb-4 shadow-xs">
              <img src="Ambira high school.jpg" alt="Ambira High School Logo" class="w-full h-full hd-logo" />
            </div>
            <span class="text-[11px] font-bold uppercase tracking-wider text-red-600">Ambira High School</span>
            <h4 class="font-display font-bold text-navy-900 text-lg mt-1">Secondary Education</h4>
            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
              Foundational academic training centered on analytical problem solving, discipline, and academic excellence.
            </p>
          </div>
          <div class="mt-5 pt-3 border-t border-slate-200 flex items-center justify-between text-xs font-semibold text-slate-500">
            <span>United for Excellence</span>
            <span class="text-navy-900">Secondary</span>
          </div>
        </div>

        <!-- Computer Literacy -->
        <div class="bg-slate-50 rounded-2xl border border-slate-200 p-6 flex flex-col justify-between hover:border-teal-500 transition-colors">
          <div>
            <div class="h-14 w-14 rounded-xl bg-slate-800 text-white flex items-center justify-center mb-4">
              <i data-lucide="monitor" class="w-6 h-6"></i>
            </div>
            <span class="text-[11px] font-bold uppercase tracking-wider text-slate-600">Elementary College of Computer Studies</span>
            <h4 class="font-display font-bold text-navy-900 text-lg mt-1">Computer Digital Literacy</h4>
            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
              Core office productivity suites, digital documentation, information management, and computer operations.
            </p>
          </div>
          <div class="mt-5 pt-3 border-t border-slate-200 flex items-center justify-between text-xs font-semibold text-slate-500">
            <span>Certificate</span>
            <span class="text-navy-900">May 2019 – Jul 2019</span>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- Projects & Community Leadership Section -->
  <section id="projects" class="py-16 md:py-24 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="max-w-3xl mb-12">
      <span class="text-xs font-bold uppercase tracking-widest text-teal-600">Entrepreneurship & Governance</span>
      <h2 class="font-display text-3xl sm:text-4xl font-bold text-navy-900 mt-1">
        Projects & Youth Leadership
      </h2>
      <p class="text-slate-600 mt-2">
        Demonstrated financial stewardship, capital management, and conflict resolution in community enterprise.
      </p>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
      <!-- Project Card 1 -->
      <div class="bg-white rounded-2xl border border-slate-200 p-6 sm:p-8 shadow-sm">
        <div class="flex items-center justify-between gap-2 mb-4">
          <span class="px-3 py-1 rounded-full bg-amber-50 text-amber-800 text-xs font-bold">Agribusiness Enterprise</span>
          <span class="text-xs font-semibold text-slate-500">Jun 2020 – Feb 2021</span>
        </div>
        <h3 class="font-display text-xl font-bold text-navy-900">Commercial Poultry Rearing Project</h3>
        <p class="text-sm font-medium text-teal-700 mt-0.5">Furahaa Entertainment Youth Group</p>
        <p class="text-sm text-slate-600 mt-4 leading-relaxed">
          Initiated, budgeted, and managed a youth group chicken rearing enterprise with a starting capital of <strong>Kshs. 100,000</strong> to generate sustainable group revenue and strengthen financial stability during my tenure.
        </p>
        <div class="mt-6 pt-4 border-t border-slate-100 grid grid-cols-2 gap-4 text-xs">
          <div>
            <span class="text-slate-400 block">Initial Capital Managed</span>
            <span class="font-bold text-navy-900 text-sm">Kshs. 100,000</span>
          </div>
          <div>
            <span class="text-slate-400 block">Primary Outcome</span>
            <span class="font-bold text-teal-700 text-sm">Sustainable Group Income</span>
          </div>
        </div>
      </div>

      <!-- Leadership Card 2 -->
      <div class="bg-white rounded-2xl border border-slate-200 p-6 sm:p-8 shadow-sm">
        <div class="flex items-center justify-between gap-2 mb-4">
          <span class="px-3 py-1 rounded-full bg-teal-50 text-teal-800 text-xs font-bold">Executive Leadership</span>
          <span class="text-xs font-semibold text-slate-500">Feb 2020 – Mar 2021</span>
        </div>
        <h3 class="font-display text-xl font-bold text-navy-900">Chairperson (Volunteer)</h3>
        <p class="text-sm font-medium text-teal-700 mt-0.5">Furahaa Entertainment Youth Group</p>
        <ul class="mt-4 space-y-2 text-sm text-slate-600">
          <li class="flex items-start gap-2">
            <i data-lucide="check" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Oversaw expanded poultry enterprise operations valued at <strong>Kshs. 250,000</strong> starting capital.</span>
          </li>
          <li class="flex items-start gap-2">
            <i data-lucide="check" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Delegated operational duties, represented the organization externally, and ensured execution of group resolutions.</span>
          </li>
          <li class="flex items-start gap-2">
            <i data-lucide="check" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Fostered cohesion and successfully mediated <strong>five internal conflicts</strong> during tenure.</span>
          </li>
        </ul>
      </div>
    </div>
  </section>

  <!-- References & Contact Section -->
  <section id="contact" class="py-16 md:py-24 bg-navy-900 text-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
        <!-- Direct Contact Info -->
        <div class="lg:col-span-5 space-y-6">
          <span class="text-xs font-bold uppercase tracking-widest text-teal-400">Get In Touch</span>
          <h2 class="font-display text-3xl sm:text-4xl font-bold">
            Let’s Connect
          </h2>
          <p class="text-slate-300 text-sm leading-relaxed">
            Available for opportunities in Insurance Underwriting, Bancassurance Operations, Risk Management, and Economic/Business Analysis.
          </p>

          <div class="space-y-4 pt-2 text-sm">
            <a href="mailto:ba.opondo@hotmail.com" class="flex items-center gap-3.5 p-3.5 rounded-xl bg-white/5 border border-white/10 hover:border-teal-400 transition-colors">
              <i data-lucide="mail" class="w-5 h-5 text-teal-400"></i>
              <div>
                <div class="text-xs text-slate-400">Email Address</div>
                <div class="font-semibold">ba.opondo@hotmail.com</div>
              </div>
            </a>

            <a href="tel:+254742583408" class="flex items-center gap-3.5 p-3.5 rounded-xl bg-white/5 border border-white/10 hover:border-teal-400 transition-colors">
              <i data-lucide="phone" class="w-5 h-5 text-teal-400"></i>
              <div>
                <div class="text-xs text-slate-400">Phone / WhatsApp</div>
                <div class="font-semibold">+254 742 583 408</div>
              </div>
            </a>

            <a href="https://www.linkedin.com/in/brian-opondo001" target="_blank" rel="noopener noreferrer" class="flex items-center gap-3.5 p-3.5 rounded-xl bg-white/5 border border-white/10 hover:border-teal-400 transition-colors">
              <i data-lucide="linkedin" class="w-5 h-5 text-teal-400"></i>
              <div>
                <div class="text-xs text-slate-400">LinkedIn</div>
                <div class="font-semibold">linkedin.com/in/brian-opondo001</div>
              </div>
            </a>

            <div class="flex items-center gap-3.5 p-3.5 rounded-xl bg-white/5 border border-white/10">
              <i data-lucide="map-pin" class="w-5 h-5 text-teal-400"></i>
              <div>
                <div class="text-xs text-slate-400">Postal & Location</div>
                <div class="font-semibold">P.O Box 51133-00200, Nairobi, Kenya</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Professional Referees -->
        <div class="lg:col-span-7">
          <div class="bg-white/5 border border-white/10 rounded-2xl p-6 sm:p-8">
            <h3 class="font-display text-xl font-bold text-white mb-1">Professional References</h3>
            <p class="text-xs text-slate-400 mb-6">Verified industry and leadership referees</p>

            <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
              <!-- Referee 1 -->
              <div class="p-4 rounded-xl bg-navy-800 border border-white/10 space-y-2">
                <div class="w-9 h-9 rounded-lg bg-teal-500/20 text-teal-300 flex items-center justify-center font-bold text-xs">
                  AO
                </div>
                <div class="font-display font-bold text-sm text-white">Alvin Ochola</div>
                <div class="text-xs text-teal-400 font-medium">Bancassurance Officer</div>
                <div class="text-xs text-slate-300">Consolidated Bancassurance</div>
                <div class="pt-2 border-t border-white/10 text-[11px] text-slate-400 space-y-1 break-all">
                  <div>aochola@consolidated-bank.com</div>
                  <div class="text-slate-200 font-medium">+254 795 075 560</div>
                </div>
              </div>

              <!-- Referee 2 -->
              <div class="p-4 rounded-xl bg-navy-800 border border-white/10 space-y-2">
                <div class="w-9 h-9 rounded-lg bg-teal-500/20 text-teal-300 flex items-center justify-center font-bold text-xs">
                  NO
                </div>
                <div class="font-display font-bold text-sm text-white">Nathaniel Opanga</div>
                <div class="text-xs text-teal-400 font-medium">Director</div>
                <div class="text-xs text-slate-300">Reica Insurance Brokers Ltd</div>
                <div class="pt-2 border-t border-white/10 text-[11px] text-slate-400 space-y-1 break-all">
                  <div>nathanielowiti@gmail.com</div>
                  <div class="text-slate-200 font-medium">+254 715 198 221</div>
                </div>
              </div>

              <!-- Referee 3 -->
              <div class="p-4 rounded-xl bg-navy-800 border border-white/10 space-y-2">
                <div class="w-9 h-9 rounded-lg bg-teal-500/20 text-teal-300 flex items-center justify-center font-bold text-xs">
                  SO
                </div>
                <div class="font-display font-bold text-sm text-white">Stephen Okoko</div>
                <div class="text-xs text-teal-400 font-medium">Telecommunications Engineer</div>
                <div class="text-xs text-slate-300">Xiaomi Technologies Kenya</div>
                <div class="pt-2 border-t border-white/10 text-[11px] text-slate-400 space-y-1 break-all">
                  <div>okokostephen@gmail.com</div>
                  <div class="text-slate-200 font-medium">+254 797 867 048</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="mt-14 pt-8 border-t border-white/10 flex flex-col sm:flex-row items-center justify-between text-xs text-slate-400 gap-4">
        <p>&copy; 2026 Brian Otieno Opondo. All rights reserved.</p>
        <p>Insurance Underwriting &bull; Bancassurance Operations &bull; Economic Analysis</p>
      </div>
    </div>
  </section>

  <!-- Interactive Scripts -->
  <script>
    lucide.createIcons();

    const menuBtn = document.getElementById('mobile-menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');
    menuBtn.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });

    const workflowDescriptions = [
      "<strong>Stage 01 — Client & Risk Assessment:</strong> Gathering applicant data, evaluating loss records, claims history, and financial exposures across 10–30 daily cases to establish accurate risk eligibility before policy structuring.",
      "<strong>Stage 02 — Quotation & Negotiation:</strong> Preparing 15 competitive insurance quotations and cover notes daily across general insurance classes while negotiating favorable terms with partner underwriters.",
      "<strong>Stage 03 — Inspro Onboarding & Compliance:</strong> Executing 30 daily client on-boardings in the Inspro bancassurance system with full KYC, AML, and data protection verification.",
      "<strong>Stage 04 — Policy Renewals & Retention:</strong> Proactively tracking 30 renewal invitations daily and coordinating with clients and insurers to prevent lapses in coverage.",
      "<strong>Stage 05 — Claims & Executive Reporting:</strong> Submitting and tracking 3 claims weekly, resolving discrepancies across finance/claims teams, and producing weekly/monthly operational reports."
    ];

    function selectWorkflow(index) {
      const buttons = document.querySelectorAll('.workflow-btn');
      buttons.forEach((btn, idx) => {
        if (idx === index) {
          btn.className = "workflow-btn text-left p-4 rounded-xl bg-teal-600/20 border-2 border-teal-400 transition-all";
          btn.querySelector('div').className = "text-xs font-bold text-teal-300";
        } else {
          btn.className = "workflow-btn text-left p-4 rounded-xl bg-white/5 border border-white/15 hover:border-teal-400/60 transition-all";
          btn.querySelector('div').className = "text-xs font-bold text-slate-400";
        }
      });
      document.getElementById('workflow-detail').innerHTML = `
        <i data-lucide="info" class="w-5 h-5 text-teal-400 shrink-0 mt-0.5"></i>
        <div>${workflowDescriptions[index]}</div>
      `;
      lucide.createIcons();
    }

    const allSkills = [
      { name: "Insurance Underwriting", cat: "insurance" },
      { name: "Bancassurance Operations", cat: "insurance" },
      { name: "Claims Processing", cat: "insurance" },
      { name: "Client Relationship Management", cat: "insurance" },
      { name: "KYC & AML Compliance", cat: "insurance" },
      { name: "Data Management & Analysis", cat: "analytics" },
      { name: "Financial Acumen", cat: "analytics" },
      { name: "Economic Research", cat: "analytics" },
      { name: "SAP Business Analysis", cat: "analytics" },
      { name: "Analytical & Critical Thinking", cat: "analytics" },
      { name: "Computer Skills", cat: "analytics" },
      { name: "Leadership", cat: "leadership" },
      { name: "Growth Management", cat: "leadership" },
      { name: "Planning & Coordination", cat: "leadership" },
      { name: "Interpersonal Skills", cat: "leadership" },
      { name: "Time Management", cat: "leadership" },
      { name: "Teamwork & Networking", cat: "leadership" },
      { name: "Adaptability & Communication", cat: "leadership" }
    ];

    function renderSkills(filter) {
      const container = document.getElementById('skills-container');
      const filtered = filter === 'all' ? allSkills : allSkills.filter(s => s.cat === filter);
      container.innerHTML = filtered.map(skill => `
        <span class="px-3.5 py-2 rounded-xl bg-slate-100 hover:bg-teal-50 hover:text-teal-800 border border-slate-200 text-xs font-semibold text-navy-900 transition-colors">
          ${skill.name}
        </span>
      `).join('');
    }

    function filterSkills(category) {
      document.querySelectorAll('.skill-tab').forEach(btn => {
        btn.className = "skill-tab px-3 py-1 rounded-full text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200";
      });
      event.target.className = "skill-tab px-3 py-1 rounded-full text-xs font-semibold bg-navy-900 text-white";
      renderSkills(category);
    }

    renderSkills('all');

    function filterExperience(category) {
      document.querySelectorAll('.exp-filter').forEach(btn => {
        btn.className = "exp-filter px-4 py-2 rounded-lg text-xs font-semibold text-slate-600 hover:text-navy-900 transition-all";
      });
      event.target.className = "exp-filter px-4 py-2 rounded-lg text-xs font-semibold bg-white text-navy-900 shadow-sm transition-all";

      document.querySelectorAll('.exp-card').forEach(card => {
        if (category === 'all' || card.dataset.category === category) {
          card.style.display = 'block';
        } else {
          card.style.display = 'none';
        }
      });
    }

    const ctxBar = document.getElementById('throughputChart').getContext('2d');
    new Chart(ctxBar, {
      type: 'bar',
      data: {
        labels: [
          'Client Inquiries',
          'Inspro On-boardings',
          'Policy Renewals',
          'App Evaluations',
          'Policy Records',
          'Quotes & Cover Notes',
          'Risk Case Reviews'
        ],
        datasets: [{
          label: 'Average Daily Volume (Cases / Transactions)',
          data: [30, 30, 30, 30, 20, 15, 10],
          backgroundColor: [
            '#0A192F',
            '#0D9488',
            '#14B8A6',
            '#1D3557',
            '#2563EB',
            '#0284C7',
            '#D97706'
          ],
          borderRadius: 8,
          barPercentage: 0.6
        }]
      },
      options: {
        responsive: true,
        maintainAspectRatio: false,
        plugins: {
          legend: { display: false },
          tooltip: {
            callbacks: {
              label: (ctx) => ` ${ctx.raw} units processed per day`
            }
          }
        },
        scales: {
          y: {
            beginAtZero: true,
            max: 35,
            grid: { color: '#E2E8F0' },
            ticks: { font: { size: 11 } }
          },
          x: {
            grid: { display: false },
            ticks: { font: { size: 10 } }
          }
        }
      }
    });

    const ctxRadar = document.getElementById('skillsRadarChart').getContext('2d');
    new Chart(ctxRadar, {
      type: 'radar',
      data: {
        labels: [
          'Insurance Underwriting',
          'Bancassurance Ops',
          'Economic Research',
          'Data & SAP Analysis',
          'Claims & Servicing',
          'KYC/AML Compliance'
        ],
        datasets: [{
          label: 'Proficiency Index',
          data: [95, 96, 90, 92, 93, 98],
          backgroundColor: 'rgba(13, 148, 136, 0.2)',
          borderColor: '#0D9488',
          pointBackgroundColor: '#0A192F',
          pointBorderColor: '#fff',
          borderWidth: 2
        }]
      },
      options: {
        responsive: true,
        maintainAspectRatio: false,
        plugins: {
          legend: { display: false }
        },
        scales: {
          r: {
            min: 50,
            max: 100,
            ticks: { display: false },
            pointLabels: {
              font: { size: 11, weight: '600' },
              color: '#1E293B'
            },
            grid: { color: '#CBD5E1' }
          }
        }
      }
    });
  </script>
</body>
</html>

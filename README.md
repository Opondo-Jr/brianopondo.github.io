

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

  <!-- Work Experience Timeline Section -->
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

      <!-- Role 1: Bancassurance Assistant -->
      <article data-category="insurance" class="exp-card bg-white rounded-2xl border border-slate-200 p-6 sm:p-8 shadow-sm hover:shadow-md transition-shadow">
        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 pb-5 border-b border-slate-100">
          <div class="flex items-center gap-4">
            <div class="w-12 h-12 rounded-xl bg-navy-900 text-teal-400 flex items-center justify-center shrink-0 font-display font-bold text-sm">
              CB
            </div>
            <div>
              <div class="flex flex-wrap items-center gap-2">
                <h3 class="font-display text-xl font-bold text-navy-900">Bancassurance Assistant</h3>
                <span class="px-2.5 py-0.5 rounded-full bg-teal-50 text-teal-700 text-xs font-semibold">Current Role</span>
              </div>
              <p class="text-sm font-semibold text-slate-700 mt-0.5">Consolidated Bancassurance Intermediary Limited &bull; Nairobi[cite: 11]</p>
            </div>
          </div>
          <div class="text-xs font-bold text-navy-900 bg-slate-100 px-3.5 py-1.5 rounded-lg self-start sm:self-center">
            Jul 2026 – Present[cite: 11]
          </div>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-x-8 gap-y-2.5 pt-5 text-sm text-slate-600">
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Handling <strong>30 daily client and internal agent inquiries</strong> regarding insurance products, premiums, policy benefits, claims, and policy servicing[cite: 11].</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Preparing and processing an average of <strong>15 insurance quotations daily</strong> while liaising with underwriters to secure competitive premiums and appropriate coverage[cite: 11].</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Facilitating on-boarding of <strong>30 new and repeat clients daily</strong> in the <strong>Inspro bancassurance system</strong>[cite: 11], ensuring accurate documentation and verification.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Managing <strong>30 policy renewal invitations daily</strong>, following up on expiring policies and coordinating with insurers to maintain uninterrupted coverage[cite: 11].</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Receiving, reviewing, and submitting <strong>3 insurance claims weekly</strong> while guiding clients through documentation and monitoring pending claims[cite: 11].</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Supporting compliance with <strong>KYC, AML, data protection</strong>, and preparing weekly/monthly operational performance reports[cite: 11].</span>
          </div>
        </div>
      </article>

      <!-- Role 2: General Insurance Underwriter -->
      <article data-category="insurance" class="exp-card bg-white rounded-2xl border border-slate-200 p-6 sm:p-8 shadow-sm hover:shadow-md transition-shadow">
        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 pb-5 border-b border-slate-100">
          <div class="flex items-center gap-4">
            <div class="w-12 h-12 rounded-xl bg-teal-600 text-white flex items-center justify-center shrink-0 font-display font-bold text-sm">
              RI
            </div>
            <div>
              <h3 class="font-display text-xl font-bold text-navy-900">General Insurance Underwriter</h3>
              <p class="text-sm font-semibold text-slate-700 mt-0.5">Reica Insurance Brokers Limited &bull; Nairobi[cite: 11]</p>
            </div>
          </div>
          <div class="text-xs font-bold text-navy-900 bg-slate-100 px-3.5 py-1.5 rounded-lg self-start sm:self-center">
            Dec 2023 – Jun 2026[cite: 11]
          </div>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-x-8 gap-y-2.5 pt-5 text-sm text-slate-600">
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Evaluated an average of <strong>30 insurance applications daily</strong>, gathering applicant information to facilitate sound underwriting decisions[cite: 11].</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Reviewed <strong>15 insurance proposals daily</strong> for completeness, accuracy, and compliance with insurer underwriting requirements[cite: 11].</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Analyzed financial data, risk exposures, and loss records for <strong>10 cases daily</strong> to determine risk eligibility and prepared weekly risk assessment reports[cite: 11].</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Generated <strong>15 competitive insurance quotations and cover notes daily</strong> across various insurance classes for new business and renewals[cite: 11].</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Processed <strong>20 client policy records daily</strong> into underwriting systems, ensuring data accuracy, completeness, confidentiality, and timely issuance[cite: 11].</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Coordinated with claims, finance, and customer service departments to resolve policy discrepancies and negotiate competitive terms with insurers[cite: 11].</span>
          </div>
        </div>
      </article>

      <!-- Role 3: Enumerator - UNICEF School Mapping Program -->
      <article data-category="research" class="exp-card bg-white rounded-2xl border border-slate-200 p-6 sm:p-8 shadow-sm hover:shadow-md transition-shadow">
        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 pb-5 border-b border-slate-100">
          <div class="flex items-center gap-4">
            <div class="w-12 h-12 rounded-xl bg-sky-600 text-white flex items-center justify-center shrink-0 font-display font-bold text-sm">
              UN
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
            <span>Collected data by conducting structured interviews with school head teachers using provided survey instruments.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-sky-600 shrink-0 mt-1"></i>
            <span>Verified the accuracy and completeness of collected data during the interview process, ensuring proper responses and addressing inconsistencies.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-sky-600 shrink-0 mt-1"></i>
            <span>Accurately inputted collected data into electronic data collection systems after each interview.</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-sky-600 shrink-0 mt-1"></i>
            <span>Reported by submitting completed data collection forms and relevant reports to the project supervisor within designated deadlines.</span>
          </div>
        </div>
      </article>

      <!-- Role 4: Economist Attaché -->
      <article data-category="research" class="exp-card bg-white rounded-2xl border border-slate-200 p-6 sm:p-8 shadow-sm hover:shadow-md transition-shadow">
        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 pb-5 border-b border-slate-100">
          <div class="flex items-center gap-4">
            <div class="w-12 h-12 rounded-xl bg-amber-600 text-white flex items-center justify-center shrink-0 font-display font-bold text-sm">
              NT
            </div>
            <div>
              <h3 class="font-display text-xl font-bold text-navy-900">Economist Attaché</h3>
              <p class="text-sm font-semibold text-slate-700 mt-0.5">The National Treasury and Economic Planning &bull; Nairobi[cite: 11]</p>
            </div>
          </div>
          <div class="text-xs font-bold text-navy-900 bg-slate-100 px-3.5 py-1.5 rounded-lg self-start sm:self-center">
            May 2023 – Aug 2023[cite: 11]
          </div>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-x-8 gap-y-2.5 pt-5 text-sm text-slate-600">
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-amber-600 shrink-0 mt-1"></i>
            <span>Carried out monitoring and evaluation of economic trends and research on topical issues such as hunger implications in Kenya[cite: 11].</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-amber-600 shrink-0 mt-1"></i>
            <span>Helped in <strong>three economic policy formulation and implementation guidelines</strong> and national statistics management[cite: 11].</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-amber-600 shrink-0 mt-1"></i>
            <span>Assessed the potential economic impacts of proposed policies at the government level for sectoral planning[cite: 11].</span>
          </div>
          <div class="flex items-start gap-2.5">
            <i data-lucide="check-circle-2" class="w-4 h-4 text-amber-600 shrink-0 mt-1"></i>
            <span>Conducted in-depth research on specific economic topics and presented findings in clear, concise reports to stakeholders[cite: 11].</span>
          </div>
        </div>
      </article>

    </div>
  </section>

  <!-- Education & Verified Certifications Section -->
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

      <!-- Featured Degree Card -->
      <div class="bg-gradient-to-r from-navy-900 to-navy-800 text-white rounded-2xl p-6 sm:p-8 mb-8 shadow-md flex flex-col md:flex-row md:items-center justify-between gap-6">
        <div class="flex items-center gap-4">
          <div class="w-14 h-14 rounded-2xl bg-teal-500/20 border border-teal-400/30 flex items-center justify-center shrink-0">
            <i data-lucide="graduation-cap" class="w-7 h-7 text-teal-300"></i>
          </div>
          <div>
            <span class="text-xs font-bold uppercase tracking-wider text-teal-300">University Degree</span>
            <h3 class="font-display text-2xl font-bold mt-0.5">Bachelor of Science in Economics[cite: 11]</h3>
            <p class="text-slate-300 font-medium text-sm mt-1">Maasai Mara University &bull; Second Class Honors (Upper Division)[cite: 11]</p>
          </div>
        </div>
        <div class="px-4 py-2 rounded-xl bg-white/10 border border-white/15 text-xs font-bold tracking-wide self-start md:self-center">
          Sep 2019 – Dec 2023[cite: 11]
        </div>
      </div>

      <!-- Certifications Grid -->
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">

        <!-- Coursera -->
        <div class="bg-slate-50 rounded-2xl border border-slate-200 p-6 flex flex-col justify-between hover:border-blue-500 transition-colors">
          <div>
            <div class="h-12 w-12 rounded-xl bg-blue-600 text-white flex items-center justify-center mb-4 font-bold text-xs">
              CRS
            </div>
            <span class="text-[11px] font-bold uppercase tracking-wider text-blue-700">Coursera[cite: 11]</span>
            <h4 class="font-display font-bold text-navy-900 text-lg mt-1">SAP Business Analyst Certificate[cite: 11]</h4>
            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
              Enterprise business process modeling, SAP system workflows, requirements analysis, and data-driven operational reporting.
            </p>
          </div>
          <div class="mt-5 pt-3 border-t border-slate-200 flex items-center justify-between text-xs font-semibold text-slate-500">
            <span>Issued via Coursera[cite: 11]</span>
            <span class="text-navy-900">Jun 2025 – Aug 2025[cite: 11]</span>
          </div>
        </div>

        <!-- Ajira Digital Program -->
        <div class="bg-slate-50 rounded-2xl border border-slate-200 p-6 flex flex-col justify-between hover:border-green-600 transition-colors">
          <div>
            <div class="h-12 w-12 rounded-xl bg-green-600 text-white flex items-center justify-center mb-4 font-bold text-xs">
              AJI
            </div>
            <span class="text-[11px] font-bold uppercase tracking-wider text-green-700">Ajira Digital Program[cite: 11]</span>
            <h4 class="font-display font-bold text-navy-900 text-lg mt-1">Data Entry & Management Certificate[cite: 11]</h4>
            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
              Structured database administration, high-speed accurate data capture, spreadsheet modeling, and digital record integrity.
            </p>
          </div>
          <div class="mt-5 pt-3 border-t border-slate-200 flex items-center justify-between text-xs font-semibold text-slate-500">
            <span>ajiradigital.go.ke[cite: 11]</span>
            <span class="text-navy-900">Mar 2023[cite: 11]</span>
          </div>
        </div>

        <!-- Corporate Career Academy -->
        <div class="bg-slate-50 rounded-2xl border border-slate-200 p-6 flex flex-col justify-between hover:border-red-500 transition-colors">
          <div>
            <div class="h-12 w-12 rounded-xl bg-red-600 text-white flex items-center justify-center mb-4 font-bold text-xs">
              CCA
            </div>
            <span class="text-[11px] font-bold uppercase tracking-wider text-red-600">Corporate Career Academy[cite: 11]</span>
            <h4 class="font-display font-bold text-navy-900 text-lg mt-1">Career, Leadership & Employability Skills[cite: 11]</h4>
            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
              Executive workplace readiness, corporate ethics, team leadership, stakeholder communication, and organizational problem-solving.
            </p>
          </div>
          <div class="mt-5 pt-3 border-t border-slate-200 flex items-center justify-between text-xs font-semibold text-slate-500">
            <span>Nurturing for Industry[cite: 11]</span>
            <span class="text-navy-900">Nov 2022[cite: 11]</span>
          </div>
        </div>

        <!-- SAP Educate to Employ -->
        <div class="bg-slate-50 rounded-2xl border border-slate-200 p-6 flex flex-col justify-between hover:border-teal-500 transition-colors">
          <div>
            <div class="h-12 w-12 rounded-xl bg-navy-900 text-teal-400 flex items-center justify-center mb-4 font-display font-bold text-sm">
              SAP
            </div>
            <span class="text-[11px] font-bold uppercase tracking-wider text-teal-700">SAP Educate to Employ[cite: 11]</span>
            <h4 class="font-display font-bold text-navy-900 text-lg mt-1">SAP General Tech Consultant[cite: 11]</h4>
            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
              Enterprise ERP configuration, cloud architecture fundamentals, and technical consulting best practices.
            </p>
          </div>
          <div class="mt-5 pt-3 border-t border-slate-200 flex items-center justify-between text-xs font-semibold text-slate-500">
            <span>In Progress[cite: 11]</span>
            <span class="text-navy-900">Jul 2025 – Present[cite: 11]</span>
          </div>
        </div>

        <!-- Ambira High School -->
        <div class="bg-slate-50 rounded-2xl border border-slate-200 p-6 flex flex-col justify-between hover:border-red-600 transition-colors">
          <div>
            <div class="h-12 w-12 rounded-xl bg-red-600 text-white flex items-center justify-center mb-4 font-bold text-xs">
              AMB
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
            <div class="h-12 w-12 rounded-xl bg-slate-800 text-white flex items-center justify-center mb-4">
              <i data-lucide="monitor" class="w-6 h-6"></i>
            </div>
            <span class="text-[11px] font-bold uppercase tracking-wider text-slate-600">Elementary College of Computer Studies[cite: 11]</span>
            <h4 class="font-display font-bold text-navy-900 text-lg mt-1">Computer Digital Literacy[cite: 11]</h4>
            <p class="text-xs text-slate-600 mt-2 leading-relaxed">
              Core office productivity suites, digital documentation, information management, and computer operations.
            </p>
          </div>
          <div class="mt-5 pt-3 border-t border-slate-200 flex items-center justify-between text-xs font-semibold text-slate-500">
            <span>Certificate[cite: 11]</span>
            <span class="text-navy-900">May 2019 – Jul 2019[cite: 11]</span>
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
          <span class="text-xs font-semibold text-slate-500">Jun 2020 – Feb 2021[cite: 11]</span>
        </div>
        <h3 class="font-display text-xl font-bold text-navy-900">Commercial Poultry Rearing Project[cite: 11]</h3>
        <p class="text-sm font-medium text-teal-700 mt-0.5">Furahaa Entertainment Youth Group[cite: 11]</p>
        <p class="text-sm text-slate-600 mt-4 leading-relaxed">
          Started and managed a group project for Furahaa Entertainment Youth Group of chicken rearing with a starting capital of <strong>Kshs. 100,000</strong> to generate income for the group and ensure financial stability for the period I served[cite: 11].
        </p>
        <div class="mt-6 pt-4 border-t border-slate-100 grid grid-cols-2 gap-4 text-xs">
          <div>
            <span class="text-slate-400 block">Initial Capital Managed</span>
            <span class="font-bold text-navy-900 text-sm">Kshs. 100,000[cite: 11]</span>
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
          <span class="text-xs font-semibold text-slate-500">Feb 2020 – Mar 2021[cite: 11]</span>
        </div>
        <h3 class="font-display text-xl font-bold text-navy-900">Chairperson (Volunteer)[cite: 11]</h3>
        <p class="text-sm font-medium text-teal-700 mt-0.5">Furahaa Entertainment Youth Group[cite: 11]</p>
        <ul class="mt-4 space-y-2 text-sm text-slate-600">
          <li class="flex items-start gap-2">
            <i data-lucide="check" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Managed a group project of chicken rearing with a starting capital of <strong>Kshs. 250,000</strong> to generate income and ensure financial stability[cite: 11].</span>
          </li>
          <li class="flex items-start gap-2">
            <i data-lucide="check" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Delegated duties and represented the group in outside activities and functions, ensuring decisions are carried out[cite: 11].</span>
          </li>
          <li class="flex items-start gap-2">
            <i data-lucide="check" class="w-4 h-4 text-teal-600 shrink-0 mt-1"></i>
            <span>Built unity among members and successfully managed <strong>five internal conflicts</strong> during my tenure[cite: 11].</span>
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
            Available for opportunities in Insurance Underwriting, Bancassurance Operations, Risk Management, and Economic/Business Analysis[cite: 11].
          </p>

          <div class="space-y-4 pt-2 text-sm">
            <a href="mailto:ba.opondo@hotmail.com" class="flex items-center gap-3.5 p-3.5 rounded-xl bg-white/5 border border-white/10 hover:border-teal-400 transition-colors">
              <i data-lucide="mail" class="w-5 h-5 text-teal-400"></i>
              <div>
                <div class="text-xs text-slate-400">Email Address</div>
                <div class="font-semibold">ba.opondo@hotmail.com[cite: 11]</div>
              </div>
            </a>

            <a href="tel:+254742583408" class="flex items-center gap-3.5 p-3.5 rounded-xl bg-white/5 border border-white/10 hover:border-teal-400 transition-colors">
              <i data-lucide="phone" class="w-5 h-5 text-teal-400"></i>
              <div>
                <div class="text-xs text-slate-400">Phone / WhatsApp</div>
                <div class="font-semibold">+254 742 583 408[cite: 11]</div>
              </div>
            </a>

            <a href="https://www.linkedin.com/in/brian-opondo001" target="_blank" rel="noopener noreferrer" class="flex items-center gap-3.5 p-3.5 rounded-xl bg-white/5 border border-white/10 hover:border-teal-400 transition-colors">
              <i data-lucide="linkedin" class="w-5 h-5 text-teal-400"></i>
              <div>
                <div class="text-xs text-slate-400">LinkedIn</div>
                <div class="font-semibold">linkedin.com/in/brian-opondo001[cite: 11]</div>
              </div>
            </a>

            <div class="flex items-center gap-3.5 p-3.5 rounded-xl bg-white/5 border border-white/10">
              <i data-lucide="map-pin" class="w-5 h-5 text-teal-400"></i>
              <div>
                <div class="text-xs text-slate-400">Postal & Location</div>
                <div class="font-semibold">P.O Box 51133-00200, Nairobi, Kenya[cite: 11]</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Professional Referees -->
        <div class="lg:col-span-7">
          <div class="bg-white/5 border border-white/10 rounded-2xl p-6 sm:p-8">
            <h3 class="font-display text-xl font-bold text-white mb-1">Professional References</h3>
            <p class="text-xs text-slate-400 mb-6">Verified industry and leadership referees[cite: 11]</p>

            <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
              <!-- Referee 1 -->
              <div class="p-4 rounded-xl bg-navy-800 border border-white/10 space-y-2">
                <div class="w-9 h-9 rounded-lg bg-teal-500/20 text-teal-300 flex items-center justify-center font-bold text-xs">
                  AO
                </div>
                <div class="font-display font-bold text-sm text-white">Alvin Ochola[cite: 11]</div>
                <div class="text-xs text-teal-400 font-medium">Bancassurance Officer[cite: 11]</div>
                <div class="text-xs text-slate-300">Consolidated Bancassurance[cite: 11]</div>
                <div class="pt-2 border-t border-white/10 text-[11px] text-slate-400 space-y-1 break-all">
                  <div>aochola@consolidated-bank.com[cite: 11]</div>
                  <div class="text-slate-200 font-medium">+254 795 075 560[cite: 11]</div>
                </div>
              </div>

              <!-- Referee 2 -->
              <div class="p-4 rounded-xl bg-navy-800 border border-white/10 space-y-2">
                <div class="w-9 h-9 rounded-lg bg-teal-500/20 text-teal-300 flex items-center justify-center font-bold text-xs">
                  NO
                </div>
                <div class="font-display font-bold text-sm text-white">Nathaniel Opanga[cite: 11]</div>
                <div class="text-xs text-teal-400 font-medium">Director[cite: 11]</div>
                <div class="text-xs text-slate-300">Reica Insurance Brokers Ltd[cite: 11]</div>
                <div class="pt-2 border-t border-white/10 text-[11px] text-slate-400 space-y-1 break-all">
                  <div>nathanielowiti@gmail.com[cite: 11]</div>
                  <div class="text-slate-200 font-medium">+254 715 198 221[cite: 11]</div>
                </div>
              </div>

              <!-- Referee 3 -->
              <div class="p-4 rounded-xl bg-navy-800 border border-white/10 space-y-2">
                <div class="w-9 h-9 rounded-lg bg-teal-500/20 text-teal-300 flex items-center justify-center font-bold text-xs">
                  SO
                </div>
                <div class="font-display font-bold text-sm text-white">Stephen Okoko[cite: 11]</div>
                <div class="text-xs text-teal-400 font-medium">Telecommunications Engineer[cite: 11]</div>
                <div class="text-xs text-slate-300">Xiaomi Technologies Kenya[cite: 11]</div>
                <div class="pt-2 border-t border-white/10 text-[11px] text-slate-400 space-y-1 break-all">
                  <div>okokostephen@gmail.com[cite: 11]</div>
                  <div class="text-slate-200 font-medium">+254 797 867 048[cite: 11]</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="mt-14 pt-8 border-t border-white/10 flex flex-col sm:flex-row items-center justify-between text-xs text-slate-400 gap-4">
        <p>&copy; 2026 Brian Otieno Opondo. All rights reserved.</p>
        <p>Insurance Underwriting &bull; Bancassurance Operations &bull; Economic Analysis[cite: 11]</p>
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

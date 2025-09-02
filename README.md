# kontol-website
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kenzo | Ethical Hacker</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
  <style>
    body {
      background: linear-gradient(to bottom, #0f172a, #0a0a0a);
      font-family: 'Courier New', monospace;
      color: #e2e8f0;
    }
    .star {
      width: 14px;
      height: 14px;
      display: inline-block;
      margin-right: 2px;
      clip-path: polygon(50% 0%, 61% 35%, 98% 35%, 
                        68% 57%, 79% 91%, 50% 70%, 
                        21% 91%, 32% 57%, 2% 35%, 39% 35%);
    }
    .star.filled { background: #facc15; } /* Kuning */
    .star.empty { background: #475569; }  /* Abu */
  </style>
</head>
<body class="px-4">

  <!-- HEADER -->
  <header class="py-6 text-center" data-aos="fade-down">
    <h1 class="text-xl font-bold text-cyan-400">Kenzo — Ethical Hacker</h1>
    <p class="text-sm text-slate-400">Security Researcher & Pentester</p>
  </header>

  <!-- ABOUT -->
  <section class="bg-white/5 rounded-lg p-4 mb-6 shadow" data-aos="fade-up">
    <h2 class="text-base font-bold mb-2">About Me</h2>
    <p class="text-xs text-slate-300 mb-2">
      Saya Kenzo, fokus dalam keamanan siber dan ethical hacking. 
      Tujuan saya adalah mengamankan sistem dan berbagi pengetahuan dengan komunitas.
    </p>
    <div class="text-xs text-slate-400">
      <div><strong>Email:</strong> <a href="mailto:pykcyber@gmail.com" class="underline">pykcyber@gmail.com</a></div>
      <div><strong>WA:</strong> <a href="https://wa.me/6283143490913" class="underline">+62 831-4349-0913</a></div>
    </div>
  </section>

  <!-- SKILLS -->
  <section data-aos="fade-right">
    <h3 class="text-base font-bold mb-3">Skills</h3>
    <div class="space-y-2">
      <div class="p-2 bg-white/5 rounded border border-slate-700 flex justify-between">
        <span class="text-xs">Web App Pentesting</span>
        <div>
          <span class="star filled"></span><span class="star filled"></span><span class="star filled"></span><span class="star filled"></span><span class="star filled"></span>
        </div>
      </div>
      <div class="p-2 bg-white/5 rounded border border-slate-700 flex justify-between">
        <span class="text-xs">API Security</span>
        <div>
          <span class="star filled"></span><span class="star filled"></span><span class="star filled"></span><span class="star filled"></span><span class="star empty"></span>
        </div>
      </div>
      <div class="p-2 bg-white/5 rounded border border-slate-700 flex justify-between">
        <span class="text-xs">OSINT & Threat Intel</span>
        <div>
          <span class="star filled"></span><span class="star filled"></span><span class="star filled"></span><span class="star filled"></span><span class="star filled"></span>
        </div>
      </div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section class="mt-6" data-aos="fade-left">
    <h3 class="text-base font-bold mb-3">Projects</h3>
    <div class="space-y-2">
      <div class="p-2 bg-white/5 rounded border border-slate-700 flex justify-between">
        <span class="text-xs">Enterprise Audit</span>
        <div>
          <span class="star filled"></span><span class="star filled"></span><span class="star filled"></span><span class="star filled"></span><span class="star filled"></span>
        </div>
      </div>
      <div class="p-2 bg-white/5 rounded border border-slate-700 flex justify-between">
        <span class="text-xs">Bug Bounty Findings</span>
        <div>
          <span class="star filled"></span><span class="star filled"></span><span class="star filled"></span><span class="star filled"></span><span class="star filled"></span>
        </div>
      </div>
      <div class="p-2 bg-white/5 rounded border border-slate-700 flex justify-between">
        <span class="text-xs">API Security Hardening</span>
        <div>
          <span class="star filled"></span><span class="star filled"></span><span class="star filled"></span><span class="star filled"></span><span class="star empty"></span>
        </div>
      </div>
    </div>
  </section>

  <!-- CERTIFICATES -->
  <section class="mt-6" data-aos="zoom-in">
    <h3 class="text-base font-bold mb-3">Certificates</h3>
    <div class="space-y-2">
      <div class="p-2 bg-white/5 rounded border border-slate-700">
        <p class="text-xs">Sertifikat ini saya berikan kepada: <span class="text-cyan-400 font-bold">Kenzo</span></p>
        <p class="text-[10px] text-slate-400">Certified Web Pentesting</p>
        <div class="mt-1">
          <span class="star filled"></span><span class="star filled"></span><span class="star filled"></span><span class="star filled"></span><span class="star filled"></span>
        </div>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section class="mt-6 bg-white/5 rounded-lg p-4 shadow" data-aos="fade-up">
    <h3 class="text-base font-bold mb-2">Contact</h3>
    <a href="mailto:pykcyber@gmail.com" class="block text-xs underline">pykcyber@gmail.com</a>
    <a href="https://wa.me/6283143490913" target="_blank" class="block text-xs underline mt-1">+62 831-4349-0913</a>
  </section>

  <!-- FOOTER -->
  <footer class="text-center text-[10px] text-slate-500 mt-6 pb-6" data-aos="fade-up">
    <div>Website ini dibuat oleh <strong>Kenzo</strong></div>
    <div>© 2025 Kenzo. Semua hak cipta dilindungi.</div>
  </footer>

  <!-- AOS Script -->
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>AOS.init({ duration: 800, once: true });</script>
</body>
</html>

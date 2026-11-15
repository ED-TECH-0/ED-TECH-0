<!--
  VISHAL V — GitHub Profile README
  Glassmorphism • 3D depth • Black / White / Silver only
  Works on GitHub profile: no <style>, no <script>, only inline HTML + SVG (SMIL) + <details>
  Create a PUBLIC repo named exactly "ED-TECH-0" and put this as its README.md
-->
<div align="center" style="max-width:720px;margin:0 auto;padding:24px 16px 40px;background:radial-gradient(ellipse 80% 60% at 50% 0%,rgba(255,255,255,0.06) 0%,transparent 60%),#050508">

  <!-- ===== 3D ROTATING ORB (SVG + SMIL) ===== -->
  <svg viewBox="0 0 360 360" width="260" height="260" style="margin-bottom:16px;filter:drop-shadow(0 0 40px rgba(255,255,255,0.08))">
    <defs>
      <radialGradient id="orb" cx="50%" cy="30%" r="70%">
        <stop offset="0%" stop-color="#ffffff"/>
        <stop offset="40%" stop-color="#c8ccd4"/>
        <stop offset="75%" stop-color="#7a7f8a"/>
        <stop offset="100%" stop-color="#1a1d23"/>
      </radialGradient>
      <radialGradient id="glow" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stop-color="#ffffff" stop-opacity="0.25"/>
        <stop offset="60%" stop-color="#ffffff" stop-opacity="0"/>
      </radialGradient>
      <linearGradient id="ring" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#ffffff"/>
        <stop offset="50%" stop-color="#b0b5c0"/>
        <stop offset="100%" stop-color="#ffffff"/>
      </linearGradient>
    </defs>
    <!-- ambient glow -->
    <circle cx="180" cy="180" r="160" fill="url(#glow)"/>
    <!-- rotating shell -->
    <g>
      <animateTransform attributeName="transform" type="rotate" from="0 180 180" to="360 180 180" dur="20s" repeatCount="indefinite"/>
      <!-- core sphere -->
      <circle cx="180" cy="180" r="110" fill="url(#orb)"/>
      <!-- equator ring -->
      <ellipse cx="180" cy="180" rx="118" ry="22" fill="none" stroke="url(#ring)" stroke-width="1.5" opacity="0.35"/>
      <!-- meridian ring -->
      <ellipse cx="180" cy="180" rx="22" ry="118" fill="none" stroke="url(#ring)" stroke-width="1.5" opacity="0.25"/>
      <!-- inner highlight -->
      <ellipse cx="150" cy="140" rx="35" ry="22" fill="#ffffff" opacity="0.12"/>
    </g>
    <!-- pulsing outer ring -->
    <circle cx="180" cy="180" r="135" fill="none" stroke="#ffffff" stroke-width="0.5" opacity="0.15">
      <animate attributeName="r" values="135;150;135" dur="4s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.15;0;0.15" dur="4s" repeatCount="indefinite"/>
    </circle>
  </svg>

  <!-- ===== NAME ===== -->
  <h1 style="margin:8px 0 4px;font-family:'Geist',system-ui,sans-serif;font-weight:300;font-size:42px;letter-spacing:-1.2px;line-height:1.05;color:#ffffff;background:linear-gradient(135deg,#ffffff 0%,#d0d4dc 40%,#8a8f9a 70%,#ffffff 100%);-webkit-background-clip:text;background-clip:text;-webkit-text-fill-color:transparent">
    Vishal V
  </h1>
  <p style="margin:0 0 18px;color:#7a7f8a;font-family:'Geist',system-ui,sans-serif;font-size:15px;letter-spacing:0.2px;max-width:540px">
    I build Linux systems & security tools. Creator of <strong style="color:#c8ccd4">Sydra OS</strong>. Think in layers, question defaults, learn by building.
  </p>

  <!-- ===== BADGES ROW ===== -->
  <div style="display:flex;flex-wrap:wrap;gap:10px;justify-content:center;margin-bottom:24px">
    <span style="background:rgba(255,255,255,0.05);border:1px solid rgba(255,255,255,0.1);padding:6px 14px;border-radius:100px;font:500 11px/1 'Geist Mono',monospace;letter-spacing:0.5px;text-transform:uppercase;color:#c8ccd4">Arch Linux</span>
    <span style="background:rgba(255,255,255,0.05);border:1px solid rgba(255,255,255,0.1);padding:6px 14px;border-radius:100px;font:500 11px/1 'Geist Mono',monospace;letter-spacing:0.5px;text-transform:uppercase;color:#c8ccd4">Rust</span>
    <span style="background:rgba(255,255,255,0.05);border:1px solid rgba(255,255,255,0.1);padding:6px 14px;border-radius:100px;font:500 11px/1 'Geist Mono',monospace;letter-spacing:0.5px;text-transform:uppercase;color:#c8ccd4">Python</span>
    <span style="background:rgba(255,255,255,0.05);border:1px solid rgba(255,255,255,0.1);padding:6px 14px;border-radius:100px;font:500 11px/1 'Geist Mono',monospace;letter-spacing:0.5px;text-transform:uppercase;color:#c8ccd4">KDE Plasma</span>
    <span style="background:rgba(255,255,255,0.05);border:1px solid rgba(255,255,255,0.1);padding:6px 14px;border-radius:100px;font:500 11px/1 'Geist Mono',monospace;letter-spacing:0.5px;text-transform:uppercase;color:#c8ccd4">Ollama</span>
    <span style="background:rgba(255,255,255,0.05);border:1px solid rgba(255,255,255,0.1);padding:6px 14px;border-radius:100px;font:500 11px/1 'Geist Mono',monospace;letter-spacing:0.5px;text-transform:uppercase;color:#c8ccd4">Hermes</span>
  </div>

  <!-- ===== LINKS ===== -->
  <div style="display:flex;flex-wrap:wrap;gap:10px;justify-content:center;margin-bottom:28px">
    <a href="https://github.com/ED-TECH-0" target="_blank" rel="noopener" style="background:#ffffff;color:#050508;padding:10px 22px;border-radius:100px;text-decoration:none;font:500 13px 'Geist',system-ui,sans-serif;box-shadow:0 4px 24px rgba(255,255,255,0.15);transition:transform .15s,box-shadow .15s" onmouseover="this.style.transform='translateY(-2px)';this.style.boxShadow='0 8px 32px rgba(255,255,255,0.25)'" onmouseout="this.style.transform='';this.style.boxShadow=''">GitHub</a>
    <a href="https://instagram.com/0731_vengence" target="_blank" rel="noopener" style="background:rgba(255,255,255,0.05);color:#ffffff;border:1px solid rgba(255,255,255,0.12);padding:10px 22px;border-radius:100px;text-decoration:none;font:500 13px 'Geist',system-ui,sans-serif" onmouseover="this.style.background='rgba(255,255,255,0.1)';this.style.borderColor='rgba(255,255,255,0.25)'" onmouseout="this.style.background='';this.style.borderColor=''">Instagram</a>
    <a href="mailto:vishal.0731.v@gmail.com" style="background:rgba(255,255,255,0.05);color:#ffffff;border:1px solid rgba(255,255,255,0.12);padding:10px 22px;border-radius:100px;text-decoration:none;font:500 13px 'Geist',system-ui,sans-serif" onmouseover="this.style.background='rgba(255,255,255,0.1)';this.style.borderColor='rgba(255,255,255,0.25)'" onmouseout="this.style.background='';this.style.borderColor=''">Email</a>
  </div>

  <!-- ===== 3D CARDS SECTIONS (glassmorphism) ===== -->
  <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:16px;text-align:left">

    <!-- WHAT I CAN DO -->
    <details open style="background:rgba(255,255,255,0.03);border:1px solid rgba(255,255,255,0.08);border-radius:16px;overflow:hidden;backdrop-filter:blur(20px);transition:border-color .2s,background .2s" onmouseover="this.style.borderColor='rgba(255,255,255,0.18)';this.style.background='rgba(255,255,255,0.05)'" onmouseout="this.style.borderColor='';this.style.background=''">
      <summary style="padding:16px 20px;cursor:pointer;display:flex;align-items:center;gap:10px;background:linear-gradient(180deg,rgba(255,255,255,0.04),transparent);border-bottom:1px solid rgba(255,255,255,0.05)">
        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><polygon points="12 2 22 8.5 22 15.5 12 22 2 15.5 2 8.5 12 2"/><line x1="12" y1="22" x2="12" y2="15.5"/><polyline points="22 8.5 12 15.5 2 8.5"/></svg>
        <span style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:15px;color:#ffffff;letter-spacing:-0.2px">What I Can Do</span>
      </summary>
      <div style="padding:16px 20px 20px;display:grid;gap:10px">
        <div style="background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px">Build Operating Systems</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">Custom Arch-based distros: bootable ISOs, installers, desktop environments, welcome apps, system tweak tools.</div>
        </div>
        <div style="background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px">Create Security Tools</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">Pentesting fundamentals, hardening, scripts that start from how an attacker thinks.</div>
        </div>
        <div style="background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px">Run AI Locally</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">Private offline workflows with Ollama & GGUF. Agents: Hermes, Antigravity.</div>
        </div>
        <div style="background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px">Write Low-Level Code</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">Rust, Python, shell. Going deeper: assembly, syscalls, how the machine runs.</div>
        </div>
        <div style="background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px">Design the Experience</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">Glass interfaces, design tokens, visual identity. Also draw, illustrate, write.</div>
        </div>
        <div style="background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px">Learn Fast, In Public</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">Pick up fields by building real things, then record what I learned for others.</div>
        </div>
      </div>
    </details>

    <!-- HOW I THINK -->
    <details style="background:rgba(255,255,255,0.03);border:1px solid rgba(255,255,255,0.08);border-radius:16px;overflow:hidden;backdrop-filter:blur(20px)" onmouseover="this.style.borderColor='rgba(255,255,255,0.18)';this.style.background='rgba(255,255,255,0.05)'" onmouseout="this.style.borderColor='';this.style.background=''">
      <summary style="padding:16px 20px;cursor:pointer;display:flex;align-items:center;gap:10px;background:linear-gradient(180deg,rgba(255,255,255,0.04),transparent);border-bottom:1px solid rgba(255,255,255,0.05)">
        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/><path d="M17 11l-4 4-4-4"/></svg>
        <span style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:15px;color:#ffffff;letter-spacing:-0.2px">How I Think</span>
      </summary>
      <div style="padding:16px 20px 20px;display:grid;gap:10px">
        <div style="background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px">Question the Default</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">Keep asking why something is built the way it is; test if there's a simpler, stronger way.</div>
        </div>
        <div style="background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px">Think in Layers</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">Split problems into instinctive, analytical, and explainable — clean systems from clear boundaries.</div>
        </div>
        <div style="background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px">Watch People First</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">Study behavior before choosing tools. Interfaces that explain themselves.</div>
        </div>
        <div style="background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px">Stay with Big Questions</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">Space, the mind, societies. First-principles reasoning that pushes the work.</div>
        </div>
        <div style="background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px">Write Ideas Down</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">Poetry and philosophy as thinking tools. Notes that evolve into engineering.</div>
        </div>
      </div>
    </details>

    <!-- CYBERSECURITY -->
    <details style="background:rgba(255,255,255,0.03);border:1px solid rgba(255,255,255,0.08);border-radius:16px;overflow:hidden;backdrop-filter:blur(20px)" onmouseover="this.style.borderColor='rgba(255,255,255,0.18)';this.style.background='rgba(255,255,255,0.05)'" onmouseout="this.style.borderColor='';this.style.background=''">
      <summary style="padding:16px 20px;cursor:pointer;display:flex;align-items:center;gap:10px;background:linear-gradient(180deg,rgba(255,255,255,0.04),transparent);border-bottom:1px solid rgba(255,255,255,0.05)">
        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/><path d="M9 12l2 2 4-4"/></svg>
        <span style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:15px;color:#ffffff;letter-spacing:-0.2px">Cybersecurity</span>
      </summary>
      <div style="padding:16px 20px 20px;display:grid;gap:10px">
        <p style="margin:0 0 8px;font-size:13px;color:#8a8f9a;line-height:1.5">Security decides how far we can trust software and AI. Core craft, not add-on.</p>
        <div style="background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px">Think Like an Attacker</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">Pentesting methodology, Linux labs, Termux — study breaks to build better defenses.</div>
        </div>
        <div style="background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px">Harden the System</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">Secure defaults, least privilege, snapshot rollback (Sydra OS). Safety built into base.</div>
        </div>
        <div style="background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px">Guard AI Itself</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">As agents gain power, someone must secure them. AI for security; security for AI.</div>
        </div>
      </div>
    </details>

    <!-- PROJECTS -->
    <details style="background:rgba(255,255,255,0.03);border:1px solid rgba(255,255,255,0.08);border-radius:16px;overflow:hidden;backdrop-filter:blur(20px)" onmouseover="this.style.borderColor='rgba(255,255,255,0.18)';this.style.background='rgba(255,255,255,0.05)'" onmouseout="this.style.borderColor='';this.style.background=''">
      <summary style="padding:16px 20px;cursor:pointer;display:flex;align-items:center;gap:10px;background:linear-gradient(180deg,rgba(255,255,255,0.04),transparent);border-bottom:1px solid rgba(255,255,255,0.05)">
        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="3" width="20" height="14" rx="2"/><path d="M8 21h8M12 17v4"/></svg>
        <span style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:15px;color:#ffffff;letter-spacing:-0.2px">Projects</span>
      </summary>
      <div style="padding:16px 20px 20px;display:grid;gap:10px">
        <a href="https://github.com/ED-TECH-0/sydra-os" target="_blank" rel="noopener" style="text-decoration:none;background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px;display:block;color:inherit" onmouseover="this.style.borderColor='rgba(255,255,255,0.18)';this.style.background='rgba(255,255,255,0.05)'" onmouseout="this.style.borderColor='';this.style.background=''">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px;display:flex;align-items:center;gap:8px"><span style="background:rgba(255,255,255,0.08);padding:2px 8px;border-radius:4px;font:500 10px 'Geist Mono',monospace;color:#c8ccd4">GPL-3.0</span> Sydra OS</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">Arch-based, KDE Plasma 6, glassmorphism desktop, Calamares installer, gaming stack, Btrfs + Snapper.</div>
        </a>
        <a href="https://github.com/ED-TECH-0/agan" target="_blank" rel="noopener" style="text-decoration:none;background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px;display:block;color:inherit" onmouseover="this.style.borderColor='rgba(255,255,255,0.18)';this.style.background='rgba(255,255,255,0.05)'" onmouseout="this.style.borderColor='';this.style.background=''">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px;display:flex;align-items:center;gap:8px"><span style="background:rgba(255,255,255,0.08);padding:2px 8px;border-radius:4px;font:500 10px 'Geist Mono',monospace;color:#c8ccd4">Apache-2.0</span> agan</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">Retrieval-first AI assistant. Router→Planner→Privacy Firewall→Retriever→Reranker→Reasoner→Verifier→Writer. Scales from 0.6B to 32B.</div>
        </a>
      </div>
    </details>

    <!-- BUILD LOOP / TOOLS -->
    <details style="background:rgba(255,255,255,0.03);border:1px solid rgba(255,255,255,0.08);border-radius:16px;overflow:hidden;backdrop-filter:blur(20px)" onmouseover="this.style.borderColor='rgba(255,255,255,0.18)';this.style.background='rgba(255,255,255,0.05)'" onmouseout="this.style.borderColor='';this.style.background=''">
      <summary style="padding:16px 20px;cursor:pointer;display:flex;align-items:center;gap:10px;background:linear-gradient(180deg,rgba(255,255,255,0.04),transparent);border-bottom:1px solid rgba(255,255,255,0.05)">
        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><path d="M12 6v6l4 2"/></svg>
        <span style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:15px;color:#ffffff;letter-spacing:-0.2px">Build Loop</span>
      </summary>
      <div style="padding:16px 20px 20px;display:grid;gap:10px">
        <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:8px">
          <span style="background:rgba(255,255,255,0.04);border:1px solid rgba(255,255,255,0.08);border-radius:8px;padding:10px 12px;text-align:center;font:500 12px 'Geist',system-ui,sans-serif;color:#ffffff">Hermes</span>
          <span style="background:rgba(255,255,255,0.04);border:1px solid rgba(255,255,255,0.08);border-radius:8px;padding:10px 12px;text-align:center;font:500 12px 'Geist',system-ui,sans-serif;color:#ffffff">Antigravity</span>
          <span style="background:rgba(255,255,255,0.04);border:1px solid rgba(255,255,255,0.08);border-radius:8px;padding:10px 12px;text-align:center;font:500 12px 'Geist',system-ui,sans-serif;color:#ffffff">Ollama</span>
          <span style="background:rgba(255,255,255,0.04);border:1px solid rgba(255,255,255,0.08);border-radius:8px;padding:10px 12px;text-align:center;font:500 12px 'Geist',system-ui,sans-serif;color:#ffffff">Agathiyan AI</span>
          <span style="background:rgba(255,255,255,0.04);border:1px solid rgba(255,255,255,0.08);border-radius:8px;padding:10px 12px;text-align:center;font:500 12px 'Geist',system-ui,sans-serif;color:#ffffff">Pentest SML</span>
          <span style="background:rgba(255,255,255,0.04);border:1px solid rgba(255,255,255,0.08);border-radius:8px;padding:10px 12px;text-align:center;font:500 12px 'Geist',system-ui,sans-serif;color:#ffffff">C-V Processor</span>
        </div>
      </div>
    </details>

    <!-- ART & WORDS -->
    <details style="background:rgba(255,255,255,0.03);border:1px solid rgba(255,255,255,0.08);border-radius:16px;overflow:hidden;backdrop-filter:blur(20px)" onmouseover="this.style.borderColor='rgba(255,255,255,0.18)';this.style.background='rgba(255,255,255,0.05)'" onmouseout="this.style.borderColor='';this.style.background=''">
      <summary style="padding:16px 20px;cursor:pointer;display:flex;align-items:center;gap:10px;background:linear-gradient(180deg,rgba(255,255,255,0.04),transparent);border-bottom:1px solid rgba(255,255,255,0.05)">
        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M4 19.5A2.5 2.5 0 0 1 6.5 17H20"/><path d="M6.5 2H20v20H6.5A2.5 2.5 0 0 1 4 19.5v-15A2.5 2.5 0 0 1 6.5 2z"/><path d="M9 9.5h6"/><path d="M9 13h4"/><path d="M9 16.5h2"/></svg>
        <span style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:15px;color:#ffffff;letter-spacing:-0.2px">Art & Words</span>
      </summary>
      <div style="padding:16px 20px 20px;display:grid;gap:10px">
        <div style="background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px">Ballads</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">Story-carrying verse. Private writing became how I put hard thoughts into words.</div>
        </div>
        <div style="background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px">Philosophy</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">Cosmology, the mind, societies. What empty space is, why people act, what that means for building.</div>
        </div>
        <div style="background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px">Dialogue</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5">Think through ideas as conversations between viewpoints. Write them to test every side.</div>
        </div>
        <div style="background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.06);border-radius:10px;padding:14px 16px">
          <div style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:14px;color:#ffffff;margin-bottom:4px">Typography Here</div>
          <div style="font-size:12px;color:#8a8f9a;line-height:1.5"><code style="font-family:'Geist Mono',monospace;background:rgba(255,255,255,0.08);padding:1px 4px;border-radius:3px">Geist</code> + <code style="font-family:'Geist Mono',monospace;background:rgba(255,255,255,0.08);padding:1px 4px;border-radius:3px">Geist Mono</code> — precise, futuristic voice matching the work.</div>
        </div>
      </div>
    </details>

    <!-- CONTACT -->
    <details style="background:rgba(255,255,255,0.03);border:1px solid rgba(255,255,255,0.08);border-radius:16px;overflow:hidden;backdrop-filter:blur(20px)" onmouseover="this.style.borderColor='rgba(255,255,255,0.18)';this.style.background='rgba(255,255,255,0.05)'" onmouseout="this.style.borderColor='';this.style.background=''">
      <summary style="padding:16px 20px;cursor:pointer;display:flex;align-items:center;gap:10px;background:linear-gradient(180deg,rgba(255,255,255,0.04),transparent);border-bottom:1px solid rgba(255,255,255,0.05)">
        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>
        <span style="font-family:'Geist',system-ui,sans-serif;font-weight:500;font-size:15px;color:#ffffff;letter-spacing:-0.2px">Contact</span>
      </summary>
      <div style="padding:16px 20px 20px;display:grid;gap:10px">
        <p style="margin:0 0 8px;font-size:13px;color:#8a8f9a">Open to roles & consulting on Linux, local AI, security tooling.</p>
        <a href="mailto:vishal.0731.v@gmail.com" style="background:rgba(255,255,255,0.05);border:1px solid rgba(255,255,255,0.1);padding:10px 16px;border-radius:100px;text-decoration:none;font:500 13px 'Geist',system-ui,sans-serif;color:#ffffff;display:inline-block;text-align:center" onmouseover="this.style.background='rgba(255,255,255,0.1)';this.style.borderColor='rgba(255,255,255,0.25)'" onmouseout="this.style.background='';this.style.borderColor=''">vishal.0731.v@gmail.com</a>
        <div style="display:flex;flex-wrap:wrap;gap:10px;justify-content:center">
          <a href="https://github.com/ED-TECH-0" target="_blank" rel="noopener" style="background:#ffffff;color:#050508;padding:10px 20px;border-radius:100px;text-decoration:none;font:500 13px 'Geist',system-ui,sans-serif;box-shadow:0 4px 24px rgba(255,255,255,0.15)" onmouseover="this.style.transform='translateY(-2px)'" onmouseout="this.style.transform=''">GitHub</a>
          <a href="https://instagram.com/0731_vengence" target="_blank" rel="noopener" style="background:rgba(255,255,255,0.05);color:#ffffff;border:1px solid rgba(255,255,255,0.12);padding:10px 20px;border-radius:100px;text-decoration:none;font:500 13px 'Geist',system-ui,sans-serif" onmouseover="this.style.background='rgba(255,255,255,0.1)';this.style.borderColor='rgba(255,255,255,0.25)'" onmouseout="this.style.background='';this.style.borderColor=''">Instagram</a>
        </div>
      </div>
    </details>

  </div>

  <!-- ===== FOOTER ===== -->
  <div style="margin-top:32px;padding-top:20px;border-top:1px solid rgba(255,255,255,0.06);display:flex;flex-wrap:wrap;gap:16px;justify-content:center;align-items:center">
    <p style="margin:0;font-size:12px;color:#5a5e66;font-family:'Geist Mono',monospace;letter-spacing:0.5px">© 2026 Vishal V</p>
    <a href="https://ed-tech-0.github.io/" target="_blank" rel="noopener" style="color:#7a7f8a;font-size:12px;font-family:'Geist Mono',monospace;text-decoration:none;letter-spacing:0.5px" onmouseover="this.style.color='#ffffff'" onmouseout="this.style.color=''">Portfolio</a>
    <a href="https://github.com/ED-TECH-0" target="_blank" rel="noopener" style="color:#7a7f8a;font-size:12px;font-family:'Geist Mono',monospace;text-decoration:none;letter-spacing:0.5px" onmouseover="this.style.color='#ffffff'" onmouseout="this.style.color=''">GitHub</a>
    <a href="https://instagram.com/0731_vengence" target="_blank" rel="noopener" style="color:#7a7f8a;font-size:12px;font-family:'Geist Mono',monospace;text-decoration:none;letter-spacing:0.5px" onmouseover="this.style.color='#ffffff'" onmouseout="this.style.color=''">Instagram</a>
  </div>

</div>

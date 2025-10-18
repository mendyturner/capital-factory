<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Tech Week @ Capital Factory — Beta Access & Compliance Whitepaper</title>
  <meta name="description" content="Join us during Tech Week at Capital Factory. Get Beta access and download the Industry Compliance Playbook whitepaper.">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800;900&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg-0:#07090c; --bg-1:#0b0f14; --card:#0f141b; --stroke:#192230;
      --text:#eef6ff; --muted:#9fb2c7;
      --blue:#157aff; --blue-2:#45a1ff; --cyan:#37e6ff;
      --r:16px; --r-lg:22px;
      --container:1120px;
      --pad: clamp(16px, 3vw, 28px);
      --shadow: 0 10px 40px rgba(21,122,255,.35);
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0; font-family:Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, "Noto Sans", sans-serif;
      color:var(--text); background:
        radial-gradient(900px 600px at 80% -10%, rgba(0,160,255,.35), transparent 60%),
        radial-gradient(700px 600px at 8% 5%, rgba(0,255,255,.18), transparent 60%),
        linear-gradient(180deg,#06080c 0%,#0a0e14 100%);
    }
    a{color:inherit;text-decoration:none}
    .container{width:min(100% - 2*var(--pad), var(--container)); margin-inline:auto}

    header{
      position:sticky; top:0; z-index:50;
      background:linear-gradient(180deg, rgba(7,11,17,.9), rgba(7,11,17,.6) 60%, transparent);
      backdrop-filter: blur(8px);
      border-bottom:1px solid rgba(255,255,255,.06);
    }
    .nav{display:flex; align-items:center; justify-content:space-between; padding:12px 0}
    .brand{display:flex; align-items:center; gap:10px; font-weight:800; letter-spacing:.2px}
    .logo{
      width:28px; height:28px; border-radius:8px; display:grid; place-items:center;
      background: radial-gradient(80% 80% at 30% 20%, var(--cyan), var(--blue));
      box-shadow:var(--shadow);
    }
    .nav-links{display:flex; gap:20px; align-items:center; color:#cfe4ff}
    .btn{
      display:inline-flex; align-items:center; justify-content:center; gap:8px;
      padding:12px 16px; border-radius:12px; font-weight:700; border:1px solid rgba(255,255,255,.08);
      background:#0e141c; color:#e7f2ff;
    }
    .btn:hover{background:#121a24}
    .btn.primary{
      background:linear-gradient(135deg, var(--blue), var(--cyan));
      border:none; color:#082339; box-shadow:var(--shadow);
    }
    .btn.primary strong{color:#fff; mix-blend-mode:overlay}
    .menu{display:none}
    @media (max-width:900px){ .nav-links{display:none} .menu{display:inline-flex} }

    .hero{padding: clamp(56px, 10vw, 120px) 0 24px}
    .eyebrow{
      display:inline-flex; gap:10px; align-items:center;
      background:linear-gradient(135deg, rgba(0,150,255,.16), rgba(0,255,255,.10));
      border:1px solid rgba(0,170,255,.35); color:#9ad3ff;
      padding:6px 12px; border-radius:999px; font-size:12px; letter-spacing:.4px;
    }
    h1{
      margin:16px 0 10px; line-height:.95; letter-spacing:-.02em;
      font-size:clamp(40px, 9.5vw, 96px); font-weight:900;
    }
    .lead{color:#c7d6ea; font-size:clamp(16px, 2.2vw, 20px); max-width:60ch}
    .hero-ctas{display:flex; gap:12px; margin-top:24px; flex-wrap:wrap}

    .features{
      display:grid; grid-template-columns:repeat(3, 1fr); gap:18px;
      margin: clamp(40px, 8vw, 72px) 0;
    }
    @media (max-width:980px){ .features{grid-template-columns:1fr} }
    .card{
      background:linear-gradient(180deg, rgba(255,255,255,.02), transparent), var(--card);
      border:1px solid var(--stroke); border-radius:var(--r); padding:20px 18px;
      box-shadow:0 10px 30px rgba(0,0,0,.35);
    }
    .card-head{display:flex; align-items:center; gap:12px; margin-bottom:8px}
    .icon{
      width:52px; height:52px; border-radius:14px; display:grid; place-items:center;
      background:linear-gradient(135deg, rgba(0,149,255,.25), rgba(0,255,255,.16));
      border:1px solid rgba(0,162,255,.35); box-shadow:var(--shadow);
    }
    .card p{color:var(--muted); margin:8px 0 0; line-height:1.6}

    /* CTA banner */
    .cta{
      background:linear-gradient(135deg, var(--blue), var(--cyan));
      border-radius:var(--r-lg); border:1px solid rgba(255,255,255,.08);
      box-shadow:var(--shadow); overflow:hidden; margin: clamp(40px, 8vw, 90px) 0;
    }
    .cta-inner{display:grid; grid-template-columns:1fr auto; gap:24px; align-items:center; padding: clamp(28px, 6vw, 48px)}
    @media (max-width:760px){ .cta-inner{grid-template-columns:1fr} }
    .cta h2{margin:0; color:#0b1e2d; font-size: clamp(26px, 5vw, 44px); letter-spacing:-.01em; font-weight:800}

    /* Modal */
    dialog{
      width:min(100% - 2*var(--pad), 560px); border:none; border-radius:16px;
      background:#0c1219; color:var(--text); padding:0; box-shadow:0 40px 80px rgba(0,0,0,.55);
    }
    dialog::backdrop{background:rgba(3,6,10,.6); backdrop-filter: blur(3px)}
    .modal-head{display:flex; align-items:center; justify-content:space-between; padding:16px 18px; border-bottom:1px solid rgba(255,255,255,.06)}
    .modal-body{padding:18px}
    .close{background:#0f141c; border:1px solid rgba(255,255,255,.1); color:#cfe4ff; border-radius:10px; padding:8px 10px}
    form{display:grid; gap:12px}
    label{font-weight:600}
    input, select, textarea{
      width:100%; padding:12px 14px; border-radius:12px; border:1px solid #1a2533; background:#0a1017; color:#e6f0ff;
    }
    .row{display:grid; grid-template-columns:1fr 1fr; gap:12px}
    @media (max-width:560px){ .row{grid-template-columns:1fr} }
    .hint{color:#9fb2c7; font-size:12px}
    .toast{
      position:fixed; right:16px; bottom:16px; display:none; padding:12px 14px; border-radius:12px;
      background:#0f1722; color:#e7f1ff; border:1px solid #1a2533; box-shadow:0 20px 40px rgba(0,0,0,.5);
    }
    .toast.show{display:block}
    footer{border-top:1px solid rgba(255,255,255,.06); color:#9fb2c7; padding:22px 0 56px}
    .foot{display:flex; align-items:center; justify-content:space-between; gap:10px; flex-wrap:wrap}
    .focus-ring:focus-visible{outline:2px solid var(--cyan); outline-offset:2px; border-radius:12px}
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="brand">
        <span class="logo" aria-hidden="true"></span>
        <span>Tech Week @ Capital Factory</span>
      </div>
      <nav class="nav-links" aria-label="Primary">
        <a href="#about">About</a>
        <a href="#agenda">Agenda</a>
        <a href="#faq">FAQ</a>
        <a class="btn primary focus-ring" href="#cta"><strong>Get Beta</strong></a>
      </nav>
      <button class="btn menu focus-ring menu" id="menuBtn">Menu</button>
    </div>
  </header>

  <main>
    <section class="container hero" id="top">
      <span class="eyebrow">Live during Tech Week • Austin • Capital Factory</span>
      <h1>Launch, Learn, and Lock Down Compliance</h1>
      <p class="lead">
        Meet the team during Tech Week at Capital Factory. Join our private Beta and grab the
        <em>Industry Compliance Playbook</em> to see requirements by sector with practical checklists.
      </p>
      <div class="hero-ctas">
        <button class="btn primary focus-ring" data-open="betaModal"><strong>Request Beta Access</strong></button>
        <button class="btn focus-ring" data-open="paperModal">Download Whitepaper</button>
      </div>

      <div class="features" id="about">
        <article class="card">
          <div class="card-head">
            <div class="icon">
              <svg width="26" height="26" viewBox="0 0 24 24" fill="none">
                <rect x="2.5" y="3" width="19" height="14" rx="3" stroke="#7fd3ff" fill="rgba(94,206,255,.12)"/>
                <path d="M9 8.5v3l3-1.5-3-1.5Z" fill="#a8e6ff"/>
              </svg>
            </div>
            <h3 style="margin:0">Hands-on Sessions</h3>
          </div>
          <p>Short demos, office hours, and rapid-fire audits to map your current compliance posture.</p>
        </article>

        <article class="card">
          <div class="card-head">
            <div class="icon">
              <svg width="26" height="26" viewBox="0 0 24 24" fill="none">
                <circle cx="12" cy="12" r="9" stroke="#7fd3ff" fill="rgba(94,206,255,.12)"/>
                <path d="M8.5 12.5l2.2 2.1 4.8-5.2" stroke="#a8e6ff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
            <h3 style="margin:0">Beta Access</h3>
          </div>
          <p>Early access to features that automate policy management, training, and gap tracking.</p>
        </article>

        <article class="card">
          <div class="card-head">
            <div class="icon">
              <svg width="26" height="26" viewBox="0 0 24 24" fill="none">
                <path d="M12 3l7 3v5c0 5-3.5 8-7 10-3.5-2-7-5-7-10V6l7-3Z" stroke="#7fd3ff" fill="rgba(94,206,255,.12)"/>
                <path d="M9 12l2 2 4-4" stroke="#a8e6ff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
            <h3 style="margin:0">Compliance by Industry</h3>
          </div>
          <p>Sector-specific breakdowns (SaaS, Health, Fintech, Gov, Manufacturing) with controls mapped to frameworks.</p>
        </article>
      </div>
    </section>

    <section class="container cta" id="cta" aria-labelledby="cta-title">
      <div class="cta-inner">
        <h2 id="cta-title">Be first. Be compliant. Be boring to auditors.</h2>
        <div style="display:flex; gap:10px; flex-wrap:wrap">
          <button class="btn primary focus-ring" data-open="betaModal"><strong>Join the Beta</strong></button>
          <button class="btn focus-ring" data-open="paperModal">Get the Playbook</button>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container foot">
      <div class="brand">
        <span class="logo" aria-hidden="true"></span>
        <span>Capital Factory • Tech Week</span>
      </div>
      <div>© <span id="year"></span> All rights reserved.</div>
    </div>
  </footer>

  <!-- Beta Modal -->
  <dialog id="betaModal" aria-labelledby="betaTitle">
    <div class="modal-head">
      <strong id="betaTitle">Request Beta Access</strong>
      <button class="close focus-ring" data-close>Close</button>
    </div>
    <div class="modal-body">
      <form id="betaForm" novalidate>
        <div class="row">
          <div>
            <label for="betaFirst">First name</label>
            <input id="betaFirst" name="first_name" autocomplete="given-name" required>
          </div>
          <div>
            <label for="betaLast">Last name</label>
            <input id="betaLast" name="last_name" autocomplete="family-name" required>
          </div>
        </div>
        <label for="betaEmail">Work email</label>
        <input id="betaEmail" name="email" type="email" autocomplete="email" required>
        <label for="betaCompany">Company</label>
        <input id="betaCompany" name="company" autocomplete="organization" required>
        <div class="row">
          <div>
            <label for="betaRole">Role</label>
            <input id="betaRole" name="role" placeholder="CISO, Head of Eng, …">
          </div>
          <div>
            <label for="betaIndustry">Industry</label>
            <select id="betaIndustry" name="industry">
              <option value="">Select…</option>
              <option>SaaS</option><option>Healthcare</option><option>Fintech</option>
              <option>Gov/Defense</option><option>Manufacturing</option><option>Other</option>
            </select>
          </div>
        </div>
        <label for="betaNotes">What are you hoping to solve?</label>
        <textarea id="betaNotes" name="notes" rows="3" placeholder="30 sec brain dump welcome."></textarea>
        <label class="hint">
          <input type="checkbox" name="consent" required>
          I agree to be contacted about Beta participation and product updates.
        </label>
        <button class="btn primary focus-ring" type="submit"><strong>Request Access</strong></button>
        <div class="hint">We’ll confirm by email and schedule a quick fit check.</div>
      </form>
    </div>
  </dialog>

  <!-- Whitepaper Modal -->
  <dialog id="paperModal" aria-labelledby="paperTitle">
    <div class="modal-head">
      <strong id="paperTitle">Get the “Industry Compliance Playbook”</strong>
      <button class="close focus-ring" data-close>Close</button>
    </div>
    <div class="modal-body">
      <form id="paperForm" novalidate>
        <div class="row">
          <div>
            <label for="paperFirst">First name</label>
            <input id="paperFirst" name="first_name" required autocomplete="given-name">
          </div>
          <div>
            <label for="paperLast">Last name</label>
            <input id="paperLast" name="last_name" required autocomplete="family-name">
          </div>
        </div>
        <label for="paperEmail">Work email</label>
        <input id="paperEmail" name="email" type="email" required autocomplete="email">
        <label for="paperCompany">Company</label>
        <input id="paperCompany" name="company" required autocomplete="organization">
        <label class="hint">
          <input type="checkbox" name="consent" required>
          Send me the whitepaper and follow-up resources.
        </label>
        <button class="btn primary focus-ring" type="submit"><strong>Download Now</strong></button>
        <div class="hint">We’ll also email you a link, because Murphy’s Law.</div>
      </form>
    </div>
  </dialog>

  <!-- Toast -->
  <div id="toast" class="toast" role="status" aria-live="polite"></div>

  <!-- jsPDF for client-side PDF creation after form submit -->
  <script src="https://cdn.jsdelivr.net/npm/jspdf@2.5.1/dist/jspdf.umd.min.js" integrity="sha384-9wnmQ1bG2m9uN1l8l0n3mLQX8p6cX8ncnQ0Eo6a0H2p4L1wT8h0m7P8Vd2b2O5xA" crossorigin="anonymous"></script>

  <script>
    // ======= CONFIG (swap this with your Make.com webhook) =======
    const MAKE_WEBHOOK_URL = 'https://hook.make.com/REPLACE_WITH_YOURS'; // <-- put your Make webhook URL here
    // ============================================================

    // Basic UI helpers
    const $ = (sel, root=document) => root.querySelector(sel);
    const $$ = (sel, root=document) => Array.from(root.querySelectorAll(sel));
    const toast = (msg, ms=3000) => {
      const el = $('#toast');
      el.textContent = msg; el.classList.add('show');
      setTimeout(()=> el.classList.remove('show'), ms);
    };

    // Mobile menu (simple jump to CTA)
    $('#menuBtn')?.addEventListener('click', () => {
      document.getElementById('cta').scrollIntoView({behavior:'smooth'});
    });

    // Open/Close modals
    $$('[data-open]').forEach(btn=>{
      btn.addEventListener('click', ()=> document.getElementById(btn.dataset.open).showModal());
    });
    $$('[data-close]').forEach(btn=>{
      btn.addEventListener('click', (e)=> e.target.closest('dialog').close());
    });

    // Common form -> payload serialization
    function serializeForm(form, type){
      const fd = new FormData(form);
      const data = Object.fromEntries(fd.entries());
      // Infer boolean for consent
      data.consent = fd.get('consent') ? true : false;

      // Enrich for CRM attribution
      const params = Object.fromEntries(new URLSearchParams(location.search).entries());
      return {
        submit_type: type,                       // 'beta_signup' | 'whitepaper_request'
        person: {
          first_name: data.first_name || '',
          last_name : data.last_name || '',
          email     : data.email || '',
          company   : data.company || '',
          role      : data.role || '',
          industry  : data.industry || '',
          notes     : data.notes || ''
        },
        consent: data.consent,
        context: {
          page_title : document.title,
          page_url   : location.href,
          referrer   : document.referrer,
          user_agent : navigator.userAgent,
          ts_iso     : new Date().toISOString(),
          utm        : {
            source: params.utm_source || '',
            medium: params.utm_medium || '',
            campaign: params.utm_campaign || '',
            term: params.utm_term || '',
            content: params.utm_content || ''
          }
        }
      };
    }

    // POST to Make.com webhook
    async function postToMake(payload){
      if(!MAKE_WEBHOOK_URL || MAKE_WEBHOOK_URL.includes('https://hook.us2.make.com/i8skkg44ybq6vptrr1bblxuks1j63vti')){
        console.warn('Make webhook not configured.');
        throw new Error('Webhook not configured');
      }
      const res = await fetch(MAKE_WEBHOOK_URL, {
        method: 'POST',
        mode: 'cors',
        headers: {'Content-Type':'application/json'},
        body: JSON.stringify(payload)
      });
      if(!res.ok) throw new Error('Webhook error ' + res.status);
      return await res.json().catch(()=> ({})); // Make often returns empty body; that's okay
    }

    // Whitepaper generation (client-side) using jsPDF
    async function generateWhitepaperPDF({first_name='', last_name='', company='', industry=''}) {
      const { jsPDF } = window.jspdf;
      const doc = new jsPDF({ unit:'pt', format:'a4' });
      const margin = 56;
      const title = 'Industry Compliance Playbook';
      const subtitle = 'Capital Factory • Tech Week Edition';
      const byline = `${first_name || 'Reader'} ${last_name || ''} — ${company || ''}`;

      doc.setFillColor(8, 20, 40);
      doc.rect(0,0,doc.internal.pageSize.getWidth(), 120,'F');

      doc.setTextColor(255,255,255);
      doc.setFont('helvetica','bold'); doc.setFontSize(26);
      doc.text(title, margin, 72);
      doc.setFontSize(14); doc.setFont('helvetica','normal');
      doc.text(subtitle, margin, 96);

      doc.setTextColor(20,40,70);
      doc.setFontSize(10);
      doc.text(`Prepared for: ${byline}`, margin, 130);

      // Body
      doc.setTextColor(15,15,18);
      doc.setFontSize(12);
      const body =
`What to expect:
• High-level requirements by sector
• Common control families and quick wins
• Crosswalk to popular frameworks (SOC 2, ISO 27001, HIPAA, PCI)
• Audit-readiness checklist

By Industry (sampling)
SaaS: Access control, secure SDLC, vendor risk, data retention.
Healthcare: HIPAA Security Rule admin/physical/technical safeguards, BAA tracking.
Fintech: PCI scope reductions, encryption in transit/at rest, incident response drills.
Gov/Defense: NIST 800-171, CMMC maturity practices, asset inventory hygiene.

Checklist (short)
□ Asset inventory accurate
□ MFA everywhere
□ Centralized logging
□ Vendor risk reviewed
□ Incident plan tested
□ Training complete
`;
      doc.setDrawColor(220, 232, 255);
      doc.line(margin, 150, doc.internal.pageSize.getWidth()-margin, 150);
      doc.setTextColor(30, 40, 80);
      doc.setFont('times','italic'); doc.text('Practical controls. No fluff. Fewer audits that hurt.', margin, 170);

      doc.setTextColor(20,20,22); doc.setFont('helvetica','normal');
      doc.text(body, margin, 210, {maxWidth: doc.internal.pageSize.getWidth()-margin*2, lineHeightFactor:1.35});

      // Footer
      const w = doc.internal.pageSize.getWidth();
      doc.setFontSize(9); doc.setTextColor(120,130,150);
      doc.text('© ' + new Date().getFullYear() + ' Capital Factory — Tech Week', margin, 810);
      doc.text('Generated from landing page submission', w - margin - 230, 810);

      return doc.output('blob');
    }

    // Form handlers
    function attachHandler(formId, type, onSuccess){
      const form = document.getElementById(formId);
      form.addEventListener('submit', async (e)=>{
        e.preventDefault();
        if(!form.reportValidity()) return;

        const payload = serializeForm(form, type);
        try{
          await postToMake(payload); // send to Make -> HubSpot
        }catch(err){
          // still allow the user to proceed; log for debugging
          console.error(err);
          toast('Saved locally. Webhook not configured.');
        }
        await onSuccess(payload);
      });
    }

    attachHandler('betaForm', 'beta_signup', async (payload)=>{
      toast('Thanks! We’ll reach out with Beta details.');
      document.getElementById('betaModal').close();
    });

    attachHandler('paperForm', 'whitepaper_request', async (payload)=>{
      toast('Generating your whitepaper…');
      const blob = await generateWhitepaperPDF(payload.person);
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a');
      a.href = url;
      a.download = 'Industry-Compliance-Playbook.pdf';
      document.body.appendChild(a);
      a.click();
      a.remove();
      URL.revokeObjectURL(url);
      document.getElementById('paperModal').close();
      toast('Whitepaper download started.');
    });

    // Accessibility niceties: ESC closes dialogs
    document.addEventListener('keydown', (e)=>{
      if(e.key === 'Escape') $$('dialog').forEach(d=> d.open && d.close());
    });

    // Smooth-scroll for internal anchors
    document.addEventListener('click', (e)=>{
      const a = e.target.closest('a[href^="#"]');
      if(!a) return;
      const id = a.getAttribute('href').slice(1);
      const el = document.getElementById(id);
      if(el){
        e.preventDefault();
        el.scrollIntoView({behavior:'smooth', block:'start'});
        history.pushState(null,'',`#${id}`);
      }
    });

    // Year
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>

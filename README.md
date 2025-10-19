<!doctype html>
<html lang="en-GB">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Key Programming — Car Key & Remote Programming | Mobile & Garage</title>
  <meta name="description" content="Key programming, key cloning, lost remote, immobilizer reprogramming — mobile and garage service. Fast quote & booking." />
  <meta name="theme-color" content="#0b63a5" />
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Ccircle cx='50' cy='50' r='45' fill='%230b63a5'/%3E%3Ctext x='50' y='58' font-size='40' text-anchor='middle' fill='white' font-family='Arial, sans-serif'%3EK%3C/text%3E%3C/svg%3E">
  <style>
    :root{
      --bg:#f7fbfd; --card:#ffffff; --accent:#0b63a5; --muted:#6b7280; --success:#087f5b;
      --maxw:1100px; --radius:12px; --shadow: 0 6px 18px rgba(11,99,165,0.08);
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0; background:linear-gradient(180deg,#f7fbfd 0%, #eef7fb 100%);
      color:#0f1724; -webkit-font-smoothing:antialiased; -moz-osx-font-smoothing:grayscale;
      line-height:1.45; padding:24px; display:flex; justify-content:center;
      font-size:16px;
    }

    .site{
      width:100%; max-width:var(--maxw);
      margin:20px; border-radius:16px; overflow:hidden; box-shadow: var(--shadow);
      background:linear-gradient(180deg, rgba(255,255,255,0.9), rgba(255,255,255,0.98));
      display:grid; grid-template-columns: 1fr 420px; gap:28px; padding:28px;
    }

    header{
      grid-column: 1 / -1; display:flex; align-items:center; gap:16px;
    }
    .brand{
      display:flex; gap:12px; align-items:center;
    }
    .logo{
      width:56px; height:56px; border-radius:12px; background:var(--accent);
      display:flex; align-items:center; justify-content:center; color:white; font-weight:700;
      font-size:22px;
    }
    h1{margin:0; font-size:20px}
    p.lead{margin:0; color:var(--muted); font-size:14px}

    .main{
      padding:10px 0;
    }
    .hero{
      background:linear-gradient(90deg, rgba(11,99,165,0.06), rgba(8,127,91,0.03));
      border-radius:12px; padding:18px; display:flex; gap:18px; align-items:center;
    }
    .hero-left{flex:1}
    .kpi{display:flex; gap:12px; margin-top:12px}
    .kpi .item{
      background:var(--card); padding:10px 12px; border-radius:10px; box-shadow:0 6px 14px rgba(12,40,80,0.04);
      min-width:110px; text-align:center;
    }
    .kpi strong{display:block; font-size:18px}
    .services{margin-top:18px; display:grid; gap:12px}
    .service{
      background:var(--card); padding:14px; border-radius:10px; box-shadow:0 6px 12px rgba(8,20,40,0.03);
      display:flex; gap:12px; align-items:flex-start;
    }
    .service svg{flex-shrink:0; width:44px; height:44px}
    .service h3{margin:0; font-size:16px}
    .service p{margin:6px 0 0; color:var(--muted); font-size:14px}

    /* Sidebar / Booking */
    .sidebar{
      background:linear-gradient(180deg,#fff,#fbfeff); border-radius:12px; padding:18px; box-shadow:0 10px 30px rgba(11,99,165,0.05);
      height:100%;
      display:flex; flex-direction:column; gap:12px;
    }
    form .field{display:flex; flex-direction:column; gap:6px; margin-bottom:8px}
    label{font-size:13px; color:#213547}
    input[type="text"], input[type="email"], input[type="tel"], select, textarea, input[type="datetime-local"]{
      padding:10px 12px; border-radius:10px; border:1px solid #e6eef6; background:white; font-size:14px;
    }
    textarea{min-height:90px; resize:vertical}
    .btn{
      display:inline-block; border:none; padding:12px 14px; border-radius:10px; cursor:pointer;
      background:var(--accent); color:white; font-weight:600; font-size:15px;
      box-shadow: 0 8px 20px rgba(11,99,165,0.18);
    }
    .note{font-size:13px; color:var(--muted)}

    /* Pricing table */
    .pricing{display:flex; gap:12px; margin-top:12px; flex-wrap:wrap}
    .price-card{flex:1; min-width:140px; background:linear-gradient(180deg,#fff,#f8feff); padding:12px; border-radius:10px; text-align:center}
    .price-card h4{margin:8px 0 4px}
    .price-card strong{font-size:18px}

    footer{grid-column:1/-1; padding-top:12px; border-top:1px solid #eef6fb; display:flex; justify-content:space-between; align-items:center; gap:12px}
    .social{display:flex; gap:10px}

    /* responsive */
    @media (max-width:980px){
      .site{grid-template-columns:1fr; padding:18px}
      .sidebar{order:2}
      header{flex-direction:column; align-items:flex-start; gap:8px}
    }

    /* small helper */
    .pill{display:inline-block; padding:6px 10px; border-radius:999px; font-size:13px; background:#eef6fb; color:var(--accent)}
    .success{color:var(--success)}
    .hidden{display:none !important}
    .error{color:#9b2c2c; font-size:13px}
  </style>
</head>
<body>
  <main class="site" role="main" aria-labelledby="site-title">
    <header>
      <div class="brand" aria-hidden="false">
        <div class="logo" aria-hidden="true">K</div>
        <div>
          <h1 id="site-title">Key Programming — Car Key Programming</h1>
          <p class="lead">Mobile & garage service · Key programming, remotes and immobilizers</p>
        </div>
      </div>
      <div style="margin-left:auto; display:flex; gap:12px; align-items:center">
        <span class="pill" title="24/7 Mobile Service">24/7 Mobile</span>
        <span class="pill" title="Garage Service Available">Garage Available</span>
      </div>
    </header>

    <section class="main" aria-label="Main information">
      <div class="hero" role="region" aria-labelledby="hero-title">
        <div class="hero-left">
          <h2 id="hero-title">Need a new key or reprogramming?</h2>
          <p class="lead">Fast response — we come to you. We program smart keys, remotes, transponder keys and reconfigure immobilizers.</p>

          <div class="kpi" aria-hidden="true">
            <div class="item"><strong>10–45 min</strong><span style="font-size:13px;color:var(--muted)">Average time</span></div>
            <div class="item"><strong>5k+</strong><span style="font-size:13px;color:var(--muted)">Keys programmed</span></div>
            <div class="item"><strong>12 mo warranty</strong><span style="font-size:13px;color:var(--muted)">Parts & programming</span></div>
          </div>

          <div class="services" aria-label="Services">
            <article class="service">
              <svg viewBox="0 0 24 24" fill="none" aria-hidden="true" focusable="false"><path d="M12 2v6" stroke="#0b63a5" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/><path d="M6 10l6 6 6-6" stroke="#0b63a5" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/></svg>
              <div>
                <h3>Transponder key programming</h3>
                <p>Chip keys/immobilizer — services for most makes (VW, BMW, Audi, Ford, Toyota, etc.).</p>
              </div>
            </article>

            <article class="service">
              <svg viewBox="0 0 24 24" fill="none" aria-hidden="true" focusable="false"><rect x="3" y="5" width="18" height="14" rx="2" stroke="#087f5b" stroke-width="1.6"/><path d="M8 9h8" stroke="#087f5b" stroke-width="1.6" stroke-linecap="round"/></svg>
              <div>
                <h3>Remotes / key fobs</h3>
                <p>Replacement and programming of remotes (includes batteries and shells when needed).</p>
              </div>
            </article>

            <article class="service">
              <svg viewBox="0 0 24 24" fill="none" aria-hidden="true" focusable="false"><path d="M4 7h16M4 12h16M4 17h16" stroke="#6b7280" stroke-width="1.6" stroke-linecap="round"/></svg>
              <div>
                <h3>Advanced scope / ECU work</h3>
                <p>Diagnostics and reprogramming when required (immobilizer issues or ECU replacement).</p>
              </div>
            </article>
          </div>
        </div>

        <aside class="sidebar" aria-label="Book service">
          <h3>Book or request a quote</h3>

          <form id="bookingForm" novalidate>
            <div class="field">
              <label for="name">Name</label>
              <input id="name" name="name" type="text" required placeholder="John Smith" />
              <div id="err-name" class="error hidden">Please enter your name.</div>
            </div>

            <div class="field">
              <label for="phone">Phone (WhatsApp preferred)</label>
              <input id="phone" name="phone" type="tel" required placeholder="+44 7xxx xxxxxx" />
              <div id="err-phone" class="error hidden">Invalid phone number.</div>
            </div>

            <div class="field">
              <label for="email">Email (optional)</label>
              <input id="email" name="email" type="email" placeholder="email@example.com" />
              <div id="err-email" class="error hidden">Invalid email address.</div>
            </div>

            <div class="field">
              <label for="service">Service</label>
              <select id="service" name="service" required>
                <option value="">Choose a service…</option>
                <option>Transponder programming (new key)</option>
                <option>Remote reprogramming</option>
                <option>Total key loss (no keys available)</option>
                <option>Immobilizer / ECU diagnostic</option>
              </select>
              <div id="err-service" class="error hidden">Please choose a service.</div>
            </div>

            <div class="field">
              <label for="when">Preferred date/time</label>
              <input id="when" name="when" type="datetime-local" />
              <div class="note">If urgent, write "URGENT" in the message field.</div>
            </div>

            <div class="field">
              <label for="address">Address / Location</label>
              <input id="address" name="address" type="text" placeholder="Street, city, postcode" required />
              <div id="err-address" class="error hidden">Please provide the address.</div>
            </div>

            <div class="field">
              <label for="msg">Details / Make and model</label>
              <textarea id="msg" name="msg" placeholder="Make, model, year, do you have a spare key, immobilizer light..."></textarea>
            </div>

            <button type="submit" class="btn" id="submitBtn" aria-live="polite">Request quote / Book</button>
            <div id="formResult" class="note" role="status" style="margin-top:8px"></div>
          </form>

          <div style="margin-top:auto">
            <h4 style="margin:8px 0 6px">Indicative pricing</h4>
            <div class="pricing">
              <div class="price-card">
                <h4>Basic</h4>
                <div><strong>£45–£80</strong></div>
                <div style="font-size:13px;color:var(--muted)">Simple key programming</div>
              </div>
              <div class="price-card">
                <h4>Remote</h4>
                <div><strong>£60–£150</strong></div>
                <div style="font-size:13px;color:var(--muted)">Includes shell & battery</div>
              </div>
              <div class="price-card">
                <h4>Total Loss</h4>
                <div><strong>£120–£400</strong></div>
                <div style="font-size:13px;color:var(--muted)">Depends on make / ECU</div>
              </div>
            </div>
          </div>
        </aside>
      </div>

      <footer>
        <div>
          <strong>Key Programming</strong><br>
          <span class="note">Mobile service across the city • Garage workshop available</span>
        </div>
        <div style="text-align:right">
          <div class="social" aria-hidden="true">
            <a href="#" title="WhatsApp">WhatsApp</a>
            <a href="#" title="Call">Call</a>
            <a href="#" title="Email">Email</a>
          </div>
          <div class="note" style="margin-top:6px">Warranty on parts & programming • VAT included where applicable</div>
        </div>
      </footer>
    </section>
  </main>

  <script>
    // Simple client-side form handling (no backend). Replace with real API integration.
    (function(){
      const form = document.getElementById('bookingForm');
      const result = document.getElementById('formResult');

      function showError(id, show){
        const el = document.getElementById(id);
        if(!el) return;
        el.className = show ? 'error' : 'error hidden';
      }

      form.addEventListener('submit', function(e){
        e.preventDefault();
        // basic validation
        const name = form.name.value.trim();
        const phone = form.phone.value.trim();
        const service = form.service.value;
        const address = form.address.value.trim();

        let ok = true;
        showError('err-name', !name);
        showError('err-phone', !phone);
        showError('err-service', !service);
        showError('err-address', !address);

        if(!name || !phone || !service || !address) ok = false;

        if(!ok){
          result.textContent = 'Please check the highlighted fields.';
          result.style.color = '#9b2c2c';
          return;
        }

        // simulate sending
        result.textContent = 'Sending request...';
        result.style.color = 'var(--muted)';

        // Simulate a successful submission (replace with actual fetch to your backend)
        setTimeout(function(){
          result.textContent = 'Thank you! We received your request. We will contact you shortly.';
          result.style.color = 'var(--success)';
          form.reset();
        }, 900);
      });
    })();
  </script>
</body>
</html>
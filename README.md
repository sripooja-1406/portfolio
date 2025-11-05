<!doctype html>

<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Telluri Sripooja reddy — Cybersecurity Portfolio</title>
  <meta name="description" content="Portfolio of Telluri Sripooja reddy — Cybersecurity student focusing on networking and OS security." />  <style>
    :root{
      --bg:#071021;
      --card:#0b1624;
      --accent:#00d1ff;
      --muted:#9aa8b3;
      --glow: 0 8px 32px rgba(0,209,255,0.08);
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,ui-sans-serif,system-ui,-apple-system,'Segoe UI',Roboto,'Helvetica Neue',Arial;color:#e6f3ff;background:linear-gradient(180deg,var(--bg),#02101a);}
    a{color:var(--accent);text-decoration:none}

    /* container */
    .wrap{max-width:1100px;margin:32px auto;padding:28px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:14px;padding:24px;margin-bottom:22px;box-shadow:var(--glow);border:1px solid rgba(255,255,255,0.02)}

    /* hero */
    .hero{display:flex;gap:24px;align-items:center}
    .hero-left{flex:1}
    .name{font-size:28px;margin:0}
    .title{font-weight:600;color:var(--accent);letter-spacing:0.6px;margin:6px 0}
    .lead{color:var(--muted);margin:12px 0;font-size:15px;line-height:1.5}
    .cta{display:inline-flex;gap:10px}
    .btn{background:transparent;border:1px solid rgba(255,255,255,0.06);padding:10px 14px;border-radius:10px;cursor:pointer;color:#dff7ff}
    .btn.primary{background:linear-gradient(90deg,var(--accent),#6be7ff);color:#00182a;border:none;box-shadow:0 6px 18px rgba(0,209,255,0.12)}

    /* profile card */
    .profile{width:220px;padding:18px;border-radius:12px;text-align:center}
    .avatar{width:96px;height:96px;border-radius:50%;display:inline-block;background:linear-gradient(135deg,#093b4b,#012028);margin-bottom:10px;box-shadow:inset 0 -6px 24px rgba(255,255,255,0.02)}
    .small{font-size:13px;color:var(--muted)}

    /* sections */
    h2{margin:0 0 12px 0;color:#dff7ff}
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}
    .skills{display:flex;gap:12px;flex-wrap:wrap}
    .chip{background:rgba(255,255,255,0.02);padding:8px 12px;border-radius:999px;font-size:13px;border:1px solid rgba(255,255,255,0.02)}

    /* projects */
    .projects{display:grid;grid-template-columns:repeat(3,1fr);gap:12px}
    .proj{background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.00));padding:14px;border-radius:12px;border:1px solid rgba(255,255,255,0.02)}
    .proj h3{margin:0 0 8px 0}
    .proj p{color:var(--muted);font-size:13px}
    .links{display:flex;gap:8px;margin-top:12px}

    /* contact */
    .contact-form{display:flex;flex-direction:column;gap:10px}
    input,textarea{background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.03);padding:10px;border-radius:8px;color:#e6f3ff}
    textarea{min-height:110px}

    /* modal */
    .modal{position:fixed;inset:0;display:none;align-items:center;justify-content:center;background:linear-gradient(180deg,rgba(0,0,0,0.55),rgba(0,0,0,0.7));z-index:60}
    .modal .box{background:var(--card);padding:18px;border-radius:12px;max-width:720px;width:92%;}

    /* responsive */
    @media (max-width:900px){
      .hero{flex-direction:column;align-items:flex-start}
      .projects,.grid{grid-template-columns:repeat(2,1fr)}
      .profile{width:100%}
    }
    @media (max-width:600px){
      .projects,.grid{grid-template-columns:1fr}
    }

    /* tiny animations */
    .glowText{background:linear-gradient(90deg,var(--accent),#7df3ff);-webkit-background-clip:text;background-clip:text;color:transparent}

  </style></head>
<body>
  <main class="wrap"><section class="card hero">
  <div class="hero-left">
    <p class="small">Portfolio</p>
    <h1 class="name">Telluri Sripooja reddy</h1>
    <div class="title">Cybersecurity Student • Networking & OS Security</div>
    <p class="lead">I explore how operating systems provide networking services — sockets, firewalls, packet filtering and secure system calls — and build small tools to visualize and defend networks.</p>
    <div class="cta">
      <a class="btn primary" href="/resume.pdf" download>Download Resume</a>
      <button class="btn" id="contactBtn">Contact</button>
      <a class="btn" href="mailto:poojatelluri28@gmail.com">Email Me</a>
    </div>
  </div>

  <aside class="profile">
    <div class="avatar"></div>
    <div style="font-weight:600">Telluri Sripooja reddy</div>
    <div class="small">Cybersecurity • Networking</div>
    <div style="margin-top:8px;font-size:13px;color:var(--muted)">poojatelluri28@gmail.com</div>
    <div style="margin-top:12px" class="skills">
      <span class="chip">TCP/IP</span>
      <span class="chip">Linux</span>
      <span class="chip">Packet Analysis</span>
    </div>
  </aside>
</section>

<section class="card">
  <h2>About</h2>
  <p style="color:var(--muted);margin-top:10px">I am a cybersecurity student focused on networking and operating system services. I enjoy analyzing how system calls, socket APIs, and kernel networking stacks behave — and creating visual, educational demos that help explain complex concepts to others.</p>
  <div style="margin-top:14px" class="grid">
    <div>
      <h3 style="margin-bottom:6px">Core Interests</h3>
      <p class="small">Network monitoring, OS syscall behavior, firewall concepts, secure file transfer, and defensive automation.</p>
    </div>
    <div>
      <h3 style="margin-bottom:6px">Tools & Technologies</h3>
      <div class="skills">
        <span class="chip">Wireshark</span>
        <span class="chip">Nmap</span>
        <span class="chip">Burp Suite</span>
        <span class="chip">Linux</span>
        <span class="chip">HTML/CSS/JS</span>
      </div>
    </div>
    <div>
      <h3 style="margin-bottom:6px">OS Networking Services</h3>
      <p class="small">Socket APIs, firewall/iptables, DNS/DHCP services, routing, network namespaces.</p>
    </div>
  </div>
</section>

<section class="card">
  <h2>Projects</h2>
  <div class="projects" style="margin-top:12px">

    <article class="proj">
      <h3>Packet Analyzer (Demo)</h3>
      <p>Interactive simulation that demonstrates captured packet fields and simple filtering logic — educational frontend that mimics a packet sniffer output.</p>
      <div class="links">
        <button class="btn" onclick="openModal('p1')">View Demo</button>
        <a class="btn" href="#">GitHub</a>
      </div>
    </article>

    <article class="proj">
      <h3>Secure File Transfer Simulator</h3>
      <p>Web demo showing client-side encryption, chunking and simulated transfer visualized inside the browser.</p>
      <div class="links">
        <button class="btn" onclick="openModal('p2')">View Demo</button>
        <a class="btn" href="#">GitHub</a>
      </div>
    </article>

    <article class="proj">
      <h3>Firewall Rule Visualizer</h3>
      <p>A JavaScript tool that visually evaluates firewall rules against sample packets and explains why traffic is allowed/blocked.</p>
      <div class="links">
        <button class="btn" onclick="openModal('p3')">Try</button>
        <a class="btn" href="#">GitHub</a>
      </div>
    </article>

  </div>
</section>

<section class="card">
  <h2>Skills</h2>
  <div style="margin-top:12px" class="skills">
    <span class="chip">Network Protocols (TCP/UDP)</span>
    <span class="chip">Packet Analysis</span>
    <span class="chip">Socket Programming</span>
    <span class="chip">Firewall / iptables</span>
    <span class="chip">Linux Kernel Basics</span>
    <span class="chip">HTML / CSS / JS</span>
  </div>
</section>

<section class="card">
  <h2>Contact</h2>
  <div style="display:grid;grid-template-columns:1fr 360px;gap:18px;margin-top:10px">
    <div>
      <p class="small">Prefer email — I typically respond within a few days.</p>
      <p style="color:var(--muted)"><strong>Email:</strong> <a href="mailto:poojatelluri28@gmail.com">poojatelluri28@gmail.com</a></p>
      <p style="color:var(--muted)"><strong>LinkedIn:</strong> <a href="#">(add your LinkedIn)</a></p>
      <p style="color:var(--muted)"><strong>GitHub:</strong> <a href="#">(add your GitHub)</a></p>
    </div>

    <form id="contactForm" class="contact-form" onsubmit="return sendMail(event)">
      <input id="name" placeholder="Your name" required />
      <input id="email" placeholder="Your email" type="email" required />
      <textarea id="message" placeholder="Message (brief)" required></textarea>
      <div style="display:flex;gap:8px">
        <button class="btn primary" type="submit">Send</button>
        <button class="btn" type="button" onclick="resetForm()">Reset</button>
      </div>
    </form>
  </div>
</section>

  </main>  <!-- modal area -->  <div id="modal" class="modal" onclick="closeModal(event)">
    <div class="box" id="modalBox">
      <!-- content injected by JS -->
    </div>
  </div>  <script>
    // Simple modal content for project demos
    const modalContents = {
      p1: `
        <h3>Packet Analyzer — Demo</h3>
        <p style="color:var(--muted)">This demo simulates packet capture and filtering. Use the controls below to filter by protocol or source IP.</p>
        <div style="margin-top:12px">
          <label>Filter by protocol: <select id="pktProto"><option>ALL</option><option>TCP</option><option>UDP</option><option>ICMP</option></select></label>
          <button class="btn" onclick="generatePackets()">Generate Sample Packets</button>
        </div>
        <pre id="pktOut" style="background:rgba(255,255,255,0.02);padding:12px;border-radius:8px;margin-top:12px;color:var(--muted);max-height:260px;overflow:auto">No packets yet. Click 'Generate Sample Packets'.</pre>`,
  p2: `
    <h3>Secure File Transfer Simulator</h3>
    <p style="color:var(--muted)">This is a frontend-only simulation: a file is split into chunks and each chunk is 'encrypted' (simulated). No real backend is used.</p>
    <div style="margin-top:12px">
      <input id="fakeFile" placeholder="Fake filename.txt" />
      <button class="btn" onclick="simulateTransfer()">Start Transfer</button>
    </div>
    <pre id="xferOut" style="background:rgba(255,255,255,0.02);padding:12px;border-radius:8px;margin-top:12px;color:var(--muted);max-height:260px;overflow:auto">No transfer yet.</pre>
  `,
  p3: `
    <h3>Firewall Rule Visualizer</h3>
    <p style="color:var(--muted)">Try a sample packet against simple allow/deny rules.</p>
    <div style="margin-top:12px">
      <label>Src IP: <input id="fwSrc" placeholder="192.168.1.5" /></label>
      <label>Dst Port: <input id="fwPort" placeholder="80" /></label>
      <button class="btn" onclick="evalFw()">Evaluate</button>
    </div>
    <div id="fwOut" style="margin-top:12px;color:var(--muted)"></div>
  `
};

function openModal(id){
  document.getElementById('modalBox').innerHTML = modalContents[id] || '<p>Demo coming soon</p>';
  document.getElementById('modal').style.display = 'flex';
}
function closeModal(e){
  if(e.target.id === 'modal') document.getElementById('modal').style.display = 'none';
}

// Demo generators
function randIP(){return 192.168.${Math.floor(Math.random()*5)}.${Math.floor(Math.random()*254)+1}}
function generatePackets(){
  const proto = document.getElementById('pktProto').value;
  const out = [];
  for(let i=0;i<12;i++){
    const p = {src:randIP(),dst:randIP(),proto:['TCP','UDP','ICMP'][Math.floor(Math.random()*3)],len:Math.floor(Math.random()*1400)+60};
    if(proto==='ALL' || p.proto===proto) out.push(p);
  }
  document.getElementById('pktOut').textContent = out.map(x=>JSON.stringify(x)).join('\n');
}

function simulateTransfer(){
  const file = document.getElementById('fakeFile').value||'demo.bin';
  const out = document.getElementById('xferOut');
  out.textContent = '';
  const chunks = 6;
  for(let i=1;i<=chunks;i++){
    out.textContent += Chunk ${i}/${chunks} encrypted and sent...\n;
  }
  out.textContent += '\nTransfer complete (simulated).';
}

function evalFw(){
  const src = document.getElementById('fwSrc').value||'192.168.1.5';
  const port = Number(document.getElementById('fwPort').value||'80');
  // Simple rule set (demo): block port 23 (telnet) and block src 192.168.1.100
  const blockedIPs = ['192.168.1.100'];
  const blockedPorts = [23];
  const out = document.getElementById('fwOut');
  if(blockedIPs.includes(src)){
    out.innerHTML = <strong>Result:</strong> BLOCKED — source ${src} is on the blocklist.;
    return;
  }
  if(blockedPorts.includes(port)){
    out.innerHTML = <strong>Result:</strong> BLOCKED — destination port ${port} is denied by policy.;
    return;
  }
  out.innerHTML = <strong>Result:</strong> ALLOWED — packet matches no deny rules.;
}

// contact form -> open local mail client via mailto
function sendMail(e){
  e.preventDefault();
  const name = document.getElementById('name').value.trim();
  const email = document.getElementById('email').value.trim();
  const msg = document.getElementById('message').value.trim();
  if(!name||!email||!msg){alert('Please complete the form');return false}
  const subject = encodeURIComponent('Portfolio contact from '+name);
  const body = encodeURIComponent('Name: '+name+'\nEmail: '+email+'\n\n'+msg);
  window.location.href = mailto:poojatelluri28@gmail.com?subject=${subject}&body=${body};
  return false;
}
function resetForm(){document.getElementById('contactForm').reset()}

// quick hook for hero contact button
document.getElementById('contactBtn').addEventListener('click',()=>{document.querySelector('html,body').scrollTop=99999;document.getElementById('name').focus();})

  </script>
</body>
</html>

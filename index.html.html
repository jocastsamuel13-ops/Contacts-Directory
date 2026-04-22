<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Key People Directory</title>
  <link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet" />
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --bg: #0f0e0c;
      --surface: #1a1915;
      --surface2: #242220;
      --border: #2e2c28;
      --gold: #c9a84c;
      --gold-dim: #8a6f2f;
      --text: #ede8df;
      --text-muted: #8a8070;
      --text-faint: #4a4640;
      --red: #c94c4c;
    }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: 'DM Sans', sans-serif;
      min-height: 100vh;
      padding: 0;
    }

    /* Header */
    header {
      padding: 48px 48px 32px;
      border-bottom: 1px solid var(--border);
      display: flex;
      align-items: flex-end;
      justify-content: space-between;
      gap: 24px;
      flex-wrap: wrap;
    }

    .header-left h1 {
      font-family: 'DM Serif Display', serif;
      font-size: clamp(2rem, 4vw, 3.2rem);
      font-weight: 400;
      line-height: 1;
      letter-spacing: -0.02em;
      color: var(--text);
    }

    .header-left h1 em {
      font-style: italic;
      color: var(--gold);
    }

    .header-left p {
      margin-top: 8px;
      color: var(--text-muted);
      font-size: 0.9rem;
      font-weight: 300;
    }

    .header-right {
      display: flex;
      gap: 12px;
      align-items: center;
    }

    /* Search */
    .search-bar {
      position: relative;
    }

    .search-bar input {
      background: var(--surface);
      border: 1px solid var(--border);
      color: var(--text);
      padding: 10px 16px 10px 40px;
      border-radius: 8px;
      font-family: 'DM Sans', sans-serif;
      font-size: 0.875rem;
      width: 240px;
      outline: none;
      transition: border-color 0.2s;
    }

    .search-bar input::placeholder { color: var(--text-faint); }
    .search-bar input:focus { border-color: var(--gold-dim); }

    .search-bar svg {
      position: absolute;
      left: 12px;
      top: 50%;
      transform: translateY(-50%);
      color: var(--text-faint);
      pointer-events: none;
    }

    /* Add button */
    .btn-add {
      background: var(--gold);
      color: #0f0e0c;
      border: none;
      padding: 10px 20px;
      border-radius: 8px;
      font-family: 'DM Sans', sans-serif;
      font-size: 0.875rem;
      font-weight: 600;
      cursor: pointer;
      display: flex;
      align-items: center;
      gap: 6px;
      transition: opacity 0.15s, transform 0.15s;
      white-space: nowrap;
    }
    .btn-add:hover { opacity: 0.85; transform: translateY(-1px); }
    .btn-add:active { transform: translateY(0); }

    /* Filter tabs */
    .filter-bar {
      padding: 20px 48px;
      display: flex;
      gap: 8px;
      align-items: center;
      border-bottom: 1px solid var(--border);
      flex-wrap: wrap;
    }

    .filter-tab {
      background: none;
      border: 1px solid var(--border);
      color: var(--text-muted);
      padding: 6px 14px;
      border-radius: 20px;
      font-family: 'DM Sans', sans-serif;
      font-size: 0.8rem;
      cursor: pointer;
      transition: all 0.15s;
    }
    .filter-tab:hover { border-color: var(--gold-dim); color: var(--text); }
    .filter-tab.active { background: var(--gold); border-color: var(--gold); color: #0f0e0c; font-weight: 600; }

    .count-badge {
      margin-left: auto;
      color: var(--text-faint);
      font-size: 0.8rem;
    }

    /* Grid */
    main {
      padding: 32px 48px 64px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
      gap: 16px;
    }

    /* Card */
    .card {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 24px;
      position: relative;
      transition: border-color 0.2s, transform 0.2s;
      animation: fadeIn 0.3s ease both;
    }
    .card:hover { border-color: var(--gold-dim); transform: translateY(-2px); }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(12px); }
      to   { opacity: 1; transform: translateY(0); }
    }

    .card-actions {
      position: absolute;
      top: 16px;
      right: 16px;
      display: flex;
      gap: 4px;
      opacity: 0;
      transition: opacity 0.15s;
    }
    .card:hover .card-actions { opacity: 1; }

    .icon-btn {
      background: var(--surface2);
      border: 1px solid var(--border);
      color: var(--text-muted);
      width: 28px;
      height: 28px;
      border-radius: 6px;
      cursor: pointer;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: color 0.15s, border-color 0.15s;
    }
    .icon-btn:hover { color: var(--text); border-color: var(--text-muted); }
    .icon-btn.delete:hover { color: var(--red); border-color: var(--red); }

    .avatar {
      width: 52px;
      height: 52px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'DM Serif Display', serif;
      font-size: 1.2rem;
      font-weight: 400;
      margin-bottom: 14px;
      flex-shrink: 0;
    }

    .card h3 {
      font-family: 'DM Serif Display', serif;
      font-size: 1.1rem;
      font-weight: 400;
      color: var(--text);
      margin-bottom: 4px;
    }

    .card .role {
      font-size: 0.8rem;
      color: var(--gold);
      font-weight: 500;
      text-transform: uppercase;
      letter-spacing: 0.06em;
      margin-bottom: 12px;
    }

    .card .org {
      font-size: 0.83rem;
      color: var(--text-muted);
      margin-bottom: 14px;
    }

    .card-divider {
      border: none;
      border-top: 1px solid var(--border);
      margin-bottom: 14px;
    }

    .contact-row {
      display: flex;
      align-items: center;
      gap: 8px;
      font-size: 0.8rem;
      color: var(--text-muted);
      margin-bottom: 6px;
    }
    .contact-row:last-child { margin-bottom: 0; }
    .contact-row svg { flex-shrink: 0; color: var(--text-faint); }
    .contact-row a { color: var(--text-muted); text-decoration: none; transition: color 0.15s; }
    .contact-row a:hover { color: var(--gold); }

    .tag {
      display: inline-block;
      background: var(--surface2);
      border: 1px solid var(--border);
      color: var(--text-muted);
      font-size: 0.72rem;
      padding: 2px 8px;
      border-radius: 4px;
      margin-top: 12px;
      margin-right: 4px;
    }

    /* Empty state */
    .empty {
      grid-column: 1/-1;
      text-align: center;
      padding: 80px 20px;
      color: var(--text-faint);
    }
    .empty svg { margin-bottom: 16px; opacity: 0.3; }
    .empty p { font-size: 0.9rem; }

    /* Modal */
    .modal-overlay {
      position: fixed;
      inset: 0;
      background: rgba(0,0,0,0.7);
      backdrop-filter: blur(4px);
      display: flex;
      align-items: center;
      justify-content: center;
      z-index: 100;
      padding: 20px;
      opacity: 0;
      pointer-events: none;
      transition: opacity 0.2s;
    }
    .modal-overlay.open { opacity: 1; pointer-events: all; }

    .modal {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 32px;
      width: 100%;
      max-width: 480px;
      transform: translateY(16px);
      transition: transform 0.2s;
    }
    .modal-overlay.open .modal { transform: translateY(0); }

    .modal h2 {
      font-family: 'DM Serif Display', serif;
      font-size: 1.5rem;
      font-weight: 400;
      margin-bottom: 24px;
      color: var(--text);
    }

    .form-row {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
    }

    .form-group {
      margin-bottom: 14px;
    }
    .form-group.full { grid-column: 1/-1; }

    .form-group label {
      display: block;
      font-size: 0.78rem;
      font-weight: 500;
      color: var(--text-muted);
      text-transform: uppercase;
      letter-spacing: 0.05em;
      margin-bottom: 6px;
    }

    .form-group input, .form-group select {
      width: 100%;
      background: var(--bg);
      border: 1px solid var(--border);
      color: var(--text);
      padding: 10px 12px;
      border-radius: 8px;
      font-family: 'DM Sans', sans-serif;
      font-size: 0.875rem;
      outline: none;
      transition: border-color 0.2s;
    }
    .form-group input:focus, .form-group select:focus { border-color: var(--gold-dim); }
    .form-group select option { background: var(--surface); }

    .modal-footer {
      display: flex;
      justify-content: flex-end;
      gap: 10px;
      margin-top: 24px;
    }

    .btn-cancel {
      background: none;
      border: 1px solid var(--border);
      color: var(--text-muted);
      padding: 10px 20px;
      border-radius: 8px;
      font-family: 'DM Sans', sans-serif;
      font-size: 0.875rem;
      cursor: pointer;
      transition: border-color 0.15s, color 0.15s;
    }
    .btn-cancel:hover { border-color: var(--text-muted); color: var(--text); }

    .btn-save {
      background: var(--gold);
      color: #0f0e0c;
      border: none;
      padding: 10px 24px;
      border-radius: 8px;
      font-family: 'DM Sans', sans-serif;
      font-size: 0.875rem;
      font-weight: 600;
      cursor: pointer;
      transition: opacity 0.15s;
    }
    .btn-save:hover { opacity: 0.85; }

    @media (max-width: 600px) {
      header, .filter-bar, main { padding-left: 20px; padding-right: 20px; }
      .search-bar input { width: 160px; }
      .form-row { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>

<header>
  <div class="header-left">
    <h1>Key <em>People</em></h1>
    <p>Your personal contacts directory</p>
  </div>
  <div class="header-right">
    <div class="search-bar">
      <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.35-4.35"/></svg>
      <input type="text" id="searchInput" placeholder="Search people…" oninput="render()" />
    </div>
    <button class="btn-add" onclick="openModal()">
      <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M12 5v14M5 12h14"/></svg>
      Add Person
    </button>
  </div>
</header>

<div class="filter-bar">
  <button class="filter-tab active" onclick="setFilter('All', this)">All</button>
  <button class="filter-tab" onclick="setFilter('Leadership', this)">Leadership</button>
  <button class="filter-tab" onclick="setFilter('Technical', this)">Technical</button>
  <button class="filter-tab" onclick="setFilter('Operations', this)">Operations</button>
  <button class="filter-tab" onclick="setFilter('External', this)">External</button>
  <span class="count-badge" id="countBadge"></span>
</div>

<main>
  <div class="grid" id="grid"></div>
</main>

<!-- Modal -->
<div class="modal-overlay" id="modalOverlay">
  <div class="modal">
    <h2 id="modalTitle">Add Person</h2>
    <div class="form-row">
      <div class="form-group"><label>First Name *</label><input id="f_first" placeholder="Jane" /></div>
      <div class="form-group"><label>Last Name *</label><input id="f_last" placeholder="Smith" /></div>
    </div>
    <div class="form-row">
      <div class="form-group"><label>Role / Title</label><input id="f_role" placeholder="Director of Engineering" /></div>
      <div class="form-group"><label>Organization</label><input id="f_org" placeholder="Company Ltd." /></div>
    </div>
    <div class="form-row">
      <div class="form-group"><label>Email</label><input id="f_email" type="email" placeholder="jane@example.com" /></div>
      <div class="form-group"><label>Phone</label><input id="f_phone" placeholder="+1 555 000 0000" /></div>
    </div>
    <div class="form-row">
      <div class="form-group"><label>Category</label>
        <select id="f_cat">
          <option value="Leadership">Leadership</option>
          <option value="Technical">Technical</option>
          <option value="Operations">Operations</option>
          <option value="External">External</option>
        </select>
      </div>
      <div class="form-group"><label>Tags (comma-separated)</label><input id="f_tags" placeholder="finance, board" /></div>
    </div>
    <div class="modal-footer">
      <button class="btn-cancel" onclick="closeModal()">Cancel</button>
      <button class="btn-save" onclick="saveContact()">Save</button>
    </div>
  </div>
</div>

<script>
  const AVATAR_COLORS = [
    ['#3b2f1a','#c9a84c'],['#1a2c3b','#4c9ac9'],['#1a3b2a','#4cc97a'],
    ['#3b1a2f','#c94ca8'],['#2f3b1a','#9ac94c'],['#3b1a1a','#c94c4c'],
  ];

  let contacts = [
    { id:1, first:'Amara', last:'Diallo', role:'Chief Executive Officer', org:'Novatek Group', email:'a.diallo@novatek.io', phone:'+1 415 200 1001', cat:'Leadership', tags:['board','strategy'] },
    { id:2, first:'Liam', last:'Osei', role:'Head of Engineering', org:'Novatek Group', email:'l.osei@novatek.io', phone:'+1 415 200 1002', cat:'Technical', tags:['backend','infra'] },
    { id:3, first:'Sofia', last:'Reyes', role:'CFO', org:'Novatek Group', email:'s.reyes@novatek.io', phone:'+1 415 200 1003', cat:'Leadership', tags:['finance'] },
    { id:4, first:'James', last:'Nkrumah', role:'DevOps Engineer', org:'Novatek Group', email:'j.nkrumah@novatek.io', phone:'+1 415 200 1004', cat:'Technical', tags:['cloud','devops'] },
    { id:5, first:'Yuki', last:'Tanaka', role:'Operations Manager', org:'Novatek Group', email:'y.tanaka@novatek.io', phone:'+1 415 200 1005', cat:'Operations', tags:['logistics'] },
    { id:6, first:'Carlos', last:'Ferreira', role:'Legal Counsel', org:'BrightLaw Partners', email:'c.ferreira@brightlaw.com', phone:'+1 212 300 2200', cat:'External', tags:['legal','contracts'] },
  ];

  let nextId = 7;
  let activeFilter = 'All';
  let editingId = null;

  function initials(c) { return (c.first[0]||'') + (c.last[0]||''); }
  function avatarStyle(id) {
    const [bg, fg] = AVATAR_COLORS[id % AVATAR_COLORS.length];
    return `background:${bg};color:${fg};`;
  }

  function setFilter(f, el) {
    activeFilter = f;
    document.querySelectorAll('.filter-tab').forEach(t => t.classList.remove('active'));
    el.classList.add('active');
    render();
  }

  function render() {
    const q = document.getElementById('searchInput').value.toLowerCase();
    let list = contacts.filter(c => {
      const match = (activeFilter === 'All' || c.cat === activeFilter);
      const search = !q || [c.first, c.last, c.role, c.org, c.email, ...c.tags].join(' ').toLowerCase().includes(q);
      return match && search;
    });

    document.getElementById('countBadge').textContent = `${list.length} ${list.length === 1 ? 'person' : 'people'}`;

    const grid = document.getElementById('grid');
    if (!list.length) {
      grid.innerHTML = `<div class="empty">
        <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87M16 3.13a4 4 0 0 1 0 7.75"/></svg>
        <p>No contacts found.</p>
      </div>`;
      return;
    }

    grid.innerHTML = list.map((c, i) => `
      <div class="card" style="animation-delay:${i * 40}ms">
        <div class="card-actions">
          <button class="icon-btn" title="Edit" onclick="editContact(${c.id})">
            <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M11 4H4a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-7"/><path d="M18.5 2.5a2.121 2.121 0 0 1 3 3L12 15l-4 1 1-4 9.5-9.5z"/></svg>
          </button>
          <button class="icon-btn delete" title="Delete" onclick="deleteContact(${c.id})">
            <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="3 6 5 6 21 6"/><path d="M19 6l-1 14H6L5 6"/><path d="M10 11v6M14 11v6"/><path d="M9 6V4h6v2"/></svg>
          </button>
        </div>
        <div class="avatar" style="${avatarStyle(c.id)}">${initials(c)}</div>
        <h3>${c.first} ${c.last}</h3>
        ${c.role ? `<div class="role">${c.role}</div>` : ''}
        ${c.org ? `<div class="org">${c.org}</div>` : ''}
        <hr class="card-divider" />
        ${c.email ? `<div class="contact-row"><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg><a href="mailto:${c.email}">${c.email}</a></div>` : ''}
        ${c.phone ? `<div class="contact-row"><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22 16.92v3a2 2 0 0 1-2.18 2A19.79 19.79 0 0 1 11.61 19a19.5 19.5 0 0 1-6-6A19.79 19.79 0 0 1 3.07 4.18 2 2 0 0 1 5.07 2h3a2 2 0 0 1 2 1.72c.127.96.361 1.903.7 2.81a2 2 0 0 1-.45 2.11L9.09 9.91A16 16 0 0 0 15 15.91l1.27-1.27a2 2 0 0 1 2.11-.45c.907.339 1.85.573 2.81.7A2 2 0 0 1 22 16.92z"/></svg>${c.phone}</div>` : ''}
        ${c.tags && c.tags.length ? `<div>${c.tags.map(t=>`<span class="tag">${t}</span>`).join('')}</div>` : ''}
      </div>
    `).join('');
  }

  function openModal(contact) {
    editingId = contact ? contact.id : null;
    document.getElementById('modalTitle').textContent = contact ? 'Edit Person' : 'Add Person';
    document.getElementById('f_first').value = contact?.first || '';
    document.getElementById('f_last').value = contact?.last || '';
    document.getElementById('f_role').value = contact?.role || '';
    document.getElementById('f_org').value = contact?.org || '';
    document.getElementById('f_email').value = contact?.email || '';
    document.getElementById('f_phone').value = contact?.phone || '';
    document.getElementById('f_cat').value = contact?.cat || 'Leadership';
    document.getElementById('f_tags').value = contact?.tags?.join(', ') || '';
    document.getElementById('modalOverlay').classList.add('open');
  }

  function closeModal() {
    document.getElementById('modalOverlay').classList.remove('open');
    editingId = null;
  }

  function saveContact() {
    const first = document.getElementById('f_first').value.trim();
    const last = document.getElementById('f_last').value.trim();
    if (!first || !last) { alert('First and last name are required.'); return; }
    const data = {
      first, last,
      role: document.getElementById('f_role').value.trim(),
      org: document.getElementById('f_org').value.trim(),
      email: document.getElementById('f_email').value.trim(),
      phone: document.getElementById('f_phone').value.trim(),
      cat: document.getElementById('f_cat').value,
      tags: document.getElementById('f_tags').value.split(',').map(t=>t.trim()).filter(Boolean),
    };
    if (editingId) {
      const idx = contacts.findIndex(c=>c.id===editingId);
      if (idx > -1) contacts[idx] = { ...contacts[idx], ...data };
    } else {
      contacts.push({ id: nextId++, ...data });
    }
    closeModal();
    render();
  }

  function editContact(id) {
    const c = contacts.find(c=>c.id===id);
    if (c) openModal(c);
  }

  function deleteContact(id) {
    if (!confirm('Remove this person from your directory?')) return;
    contacts = contacts.filter(c=>c.id!==id);
    render();
  }

  document.getElementById('modalOverlay').addEventListener('click', function(e) {
    if (e.target === this) closeModal();
  });

  render();
</script>
</body>
</html>

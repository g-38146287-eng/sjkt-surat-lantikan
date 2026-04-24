{\rtf1\ansi\ansicpg1252\cocoartf2870
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 <!-- /index.html -->\
<!doctype html>\
<html lang="ms">\
<head>\
  <meta charset="UTF-8" />\
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />\
  <title>Sistem Surat Lantikan Kurikulum & Pentadbiran - SJKT Kuala Lipis</title>\
  <link rel="stylesheet" href="style.css" />\
</head>\
<body>\
  <div class="app">\
    <div class="topbar">\
      <h1>Sistem Surat Lantikan Kurikulum & Pentadbiran</h1>\
      <p>SJKT Kuala Lipis \'95 Tetapan logo sekolah, isi data guru, tetapkan jawatan, semak semula, buka preview surat di tab baru, dan cetak satu-satu atau semua sekali.</p>\
    </div>\
\
    <div class="notice">\
      <strong>Makluman:</strong> Kod ini telah dikemaskini dengan nama Guru Besar dalam tetapan header, pemilihan jawatan menggunakan checkbox grid, dan butang Select All / Clear All.\
    </div>\
\
    <div class="tabs">\
      <button class="tab-btn active" data-tab="tab0">Tab 0 \'95 Logo & Tetapan</button>\
      <button class="tab-btn" data-tab="tab1">Tab 1 \'95 Isi Jawatan Guru</button>\
      <button class="tab-btn" data-tab="tab2">Tab 2 \'95 Semak / Kemaskini / Delete</button>\
      <button class="tab-btn" data-tab="tab3">Tab 3 \'95 Senarai Guru & Cetakan</button>\
    </div>\
\
    <section class="panel active" id="tab0">\
      <div class="subcard">\
        <h3>Upload logo sekolah / lambang</h3>\
        <div class="grid">\
          <div class="field col-6">\
            <label>Logo kiri (Jata Malaysia)</label>\
            <input type="file" id="logoLeftInput" accept="image/png,image/jpeg,image/webp,image/jpg">\
            <div class="help">Upload sekali sahaja. Disimpan dalam browser ini.</div>\
          </div>\
          <div class="field col-6">\
            <label>Logo kanan (Logo sekolah)</label>\
            <input type="file" id="logoRightInput" accept="image/png,image/jpeg,image/webp,image/jpg">\
            <div class="help">Upload sekali sahaja. Disimpan dalam browser ini.</div>\
          </div>\
          <div class="field col-4">\
            <label>Email sekolah header</label>\
            <input type="text" id="schoolEmail" value="cbd3047@moe.edu.my" />\
          </div>\
          <div class="field col-4">\
            <label>Nota header (pilihan)</label>\
            <input type="text" id="headerNote" placeholder="Pilihan sahaja" />\
          </div>\
          <div class="field col-4">\
            <label>Nama Guru Besar</label>\
            <input type="text" id="principalName" value="JEYAKANTAN PATHMANABAN" />\
          </div>\
        </div>\
\
        <div class="logo-preview-wrap">\
          <div class="logo-box-ui">\
            <div><strong>Preview logo kiri</strong></div>\
            <img id="logoLeftPreview" alt="Logo kiri" />\
          </div>\
          <div class="logo-box-ui">\
            <div><strong>Preview logo kanan</strong></div>\
            <img id="logoRightPreview" alt="Logo kanan" />\
          </div>\
        </div>\
\
        <div class="actions">\
          <button class="primary" type="button" id="saveLogoSettingsBtn">Simpan Tetapan Header</button>\
          <button class="secondary" type="button" id="clearLogoSettingsBtn">Padam Logo / Reset Header</button>\
        </div>\
      </div>\
    </section>\
\
    <section class="panel" id="tab1">\
      <div class="grid">\
        <div class="field col-6">\
          <label>Pilih nama guru</label>\
          <select id="teacherSelect"></select>\
        </div>\
\
        <div class="field col-6">\
          <label>Atau taip nama guru baru</label>\
          <div class="inline">\
            <input id="newTeacherName" placeholder="Contoh: Pn. Nitya Sree A/P Dorai Singam" />\
            <button class="success" id="addTeacherBtn" type="button">Tambah Guru</button>\
          </div>\
        </div>\
\
        <div class="field col-3">\
          <label>Ruj. Kami</label>\
          <input id="rujKami" value="CBD3047.100.6/1/3( )" />\
        </div>\
\
        <div class="field col-3">\
          <label>Tarikh surat</label>\
          <input id="tarikhSurat" type="date" />\
        </div>\
\
        <div class="field col-3">\
          <label>Tahun buku pengurusan</label>\
          <input id="tahunBuku" placeholder="Contoh: 2026/2027" />\
        </div>\
\
        <div class="field col-3">\
          <label>Sesi akademik</label>\
          <input id="sesiAkademik" placeholder="Contoh: 2026/2027" />\
        </div>\
\
        <div class="field col-6">\
          <label>Tajuk surat</label>\
          <input id="tajukSurat" value="PERLANTIKAN SEBAGAI JAWATANKUASA UNIT PENGURUSAN KURIKULUM DAN PENTADBIRAN SEKOLAH JENIS KEBANGSAAN (TAMIL) KUALA LIPIS" />\
        </div>\
\
        <div class="field col-3">\
          <label>Tarikh berkuat kuasa mulai</label>\
          <input id="tarikhMula" type="date" />\
        </div>\
\
        <div class="field col-3">\
          <label>Tarikh berkuat kuasa hingga</label>\
          <input id="tarikhHingga" type="date" />\
        </div>\
\
        <div class="field col-8">\
          <label>Pilih jawatan yang dipegang guru (boleh pilih banyak)</label>\
          <div class="inline checkbox-actions">\
            <button class="ghost" type="button" id="selectAllPositionsBtn">Select All</button>\
            <button class="secondary" type="button" id="clearAllPositionsBtn">Clear All</button>\
          </div>\
          <div id="positionCheckboxContainer" class="checkbox-grid"></div>\
          <div class="small muted">Tick checkbox untuk pilih banyak jawatan.</div>\
        </div>\
\
        <div class="field col-4">\
          <label>Tambah jawatan baru</label>\
          <textarea id="newPositionText" placeholder="Taip satu jawatan bagi setiap baris&#10;Contoh:&#10;Penyelaras PBD&#10;AJK Jadual Waktu"></textarea>\
          <div class="actions">\
            <button class="success" type="button" id="addPositionBtn">Tambah ke Senarai Jawatan</button>\
          </div>\
        </div>\
      </div>\
\
      <div class="actions">\
        <button class="primary" type="button" id="saveAssignmentBtn">Simpan / Kemaskini Rekod Guru</button>\
        <button class="secondary" type="button" id="resetFormBtn">Reset Borang</button>\
      </div>\
\
      <div class="subcard">\
        <h3>Jawatan guru yang dipilih</h3>\
        <div id="selectedTeacherPositions" class="muted">Belum ada data dipilih.</div>\
      </div>\
    </section>\
\
    <section class="panel" id="tab2">\
      <div class="toolbar">\
        <div style="min-width:260px;flex:1;">\
          <label>Cari nama guru</label>\
          <input id="searchTeacher" placeholder="Taip nama guru..." />\
        </div>\
        <div class="count-box" id="recordCount">0 rekod</div>\
        <button class="secondary" type="button" id="exportJsonBtn">Export Data JSON</button>\
        <label class="secondary import-label">\
          Import Data JSON\
          <input type="file" id="importJsonInput" accept="application/json" hidden>\
        </label>\
      </div>\
\
      <div class="table-wrap">\
        <table>\
          <thead>\
            <tr>\
              <th style="width:60px;">Bil.</th>\
              <th>Nama Guru</th>\
              <th>Jawatan</th>\
              <th style="width:120px;">Tahun</th>\
              <th style="width:160px;">Tarikh Kuat Kuasa</th>\
              <th style="width:180px;">Tindakan</th>\
            </tr>\
          </thead>\
          <tbody id="recordTableBody"></tbody>\
        </table>\
      </div>\
    </section>\
\
    <section class="panel" id="tab3">\
      <div class="toolbar">\
        <div style="min-width:260px;flex:1;">\
          <label>Pilih guru untuk preview / cetak</label>\
          <select id="printTeacherSelect"></select>\
        </div>\
        <button class="primary" type="button" id="previewOneBtn">Preview di Tab Baru</button>\
        <button class="secondary" type="button" id="printOneBtn">Cetak Guru Ini</button>\
        <button class="success" type="button" id="previewAllBtn">Preview Semua</button>\
        <button class="ghost" type="button" id="printAllBtn">Cetak Semua</button>\
      </div>\
\
      <div class="subcard">\
        <h3>Senarai nama guru yang telah diisi</h3>\
        <div id="teacherListView"></div>\
      </div>\
    </section>\
  </div>\
\
  <script src="app.js"></script>\
</body>\
</html>\
\
<!-- /style.css -->\
:root\{\
  --brand:#0f4c81;\
  --brand2:#1f6fb2;\
  --bg:#f4f7fb;\
  --card:#ffffff;\
  --text:#1f2937;\
  --muted:#6b7280;\
  --line:#d1d5db;\
  --ok:#166534;\
  --danger:#b91c1c;\
  --shadow:0 10px 30px rgba(15,76,129,.08);\
\}\
\
*\{box-sizing:border-box\}\
html,body\{margin:0;padding:0\}\
body\{font-family:Arial,Helvetica,sans-serif;background:var(--bg);color:var(--text)\}\
.app\{max-width:1400px;margin:0 auto;padding:20px\}\
.topbar\{background:linear-gradient(135deg,var(--brand),var(--brand2));color:#fff;border-radius:18px;padding:22px 24px;box-shadow:var(--shadow);margin-bottom:18px\}\
.topbar h1\{margin:0 0 8px;font-size:28px\}\
.topbar p\{margin:0;opacity:.95;line-height:1.5\}\
.notice\{background:#fff7ed;border:1px solid #fdba74;color:#9a3412;padding:14px 16px;border-radius:12px;margin:16px 0 18px;line-height:1.5\}\
.tabs\{display:flex;flex-wrap:wrap;gap:10px;margin-bottom:16px\}\
.tab-btn\{border:none;background:#dbeafe;color:#1e3a8a;padding:12px 16px;border-radius:12px;cursor:pointer;font-weight:700\}\
.tab-btn.active\{background:var(--brand);color:#fff\}\
.panel\{display:none;background:var(--card);border-radius:18px;padding:20px;box-shadow:var(--shadow)\}\
.panel.active\{display:block\}\
.grid\{display:grid;grid-template-columns:repeat(12,minmax(0,1fr));gap:14px\}\
.field\{grid-column:span 12\}\
.field.col-6\{grid-column:span 6\}\
.field.col-4\{grid-column:span 4\}\
.field.col-3\{grid-column:span 3\}\
.field.col-8\{grid-column:span 8\}\
.field label\{display:block;font-weight:700;margin-bottom:6px\}\
input,select,textarea\{width:100%;padding:11px 12px;border:1px solid var(--line);border-radius:10px;font-size:14px;background:#fff\}\
textarea\{min-height:90px;resize:vertical\}\
.actions\{display:flex;flex-wrap:wrap;gap:10px;margin-top:18px\}\
button\{border:none;border-radius:10px;padding:11px 14px;cursor:pointer;font-weight:700\}\
.primary\{background:var(--brand);color:#fff\}\
.secondary\{background:#e5e7eb;color:#111827\}\
.success\{background:#dcfce7;color:var(--ok)\}\
.danger\{background:#fee2e2;color:var(--danger)\}\
.ghost\{background:#eff6ff;color:#1d4ed8\}\
.subcard\{background:#f8fafc;border:1px solid #e5e7eb;border-radius:14px;padding:16px;margin-top:14px\}\
.subcard h3\{margin:0 0 10px\}\
.inline\{display:flex;gap:10px;align-items:center;flex-wrap:wrap\}\
.pill\{display:inline-block;white-space:nowrap;background:#dbeafe;color:#1d4ed8;padding:6px 10px;border-radius:999px;font-size:12px;margin:4px 6px 0 0;font-weight:700\}\
table\{width:100%;border-collapse:collapse;margin-top:12px;background:#fff\}\
th,td\{border:1px solid #e5e7eb;padding:10px;text-align:left;vertical-align:top;font-size:14px;word-break:break-word;max-width:300px\}\
th\{background:#eff6ff\}\
.muted\{color:var(--muted)\}\
.toolbar\{display:flex;gap:10px;flex-wrap:wrap;align-items:end;margin-bottom:10px\}\
.count-box\{background:#eff6ff;padding:10px 14px;border-radius:10px;color:#1e40af;font-weight:700\}\
.small\{font-size:12px\}\
.logo-preview-wrap\{display:flex;gap:20px;flex-wrap:wrap;margin-top:10px\}\
.logo-box-ui\{border:1px solid #d1d5db;border-radius:12px;padding:12px;background:#fff;min-width:220px\}\
.logo-box-ui img\{max-width:120px;max-height:120px;display:block;margin-top:10px;object-fit:contain;background:#fff;border:1px solid #f0f0f0\}\
.help\{font-size:12px;color:var(--muted);margin-top:6px\}\
.table-wrap\{overflow:auto\}\
.import-label\{display:inline-flex;align-items:center;gap:8px;padding:11px 14px;cursor:pointer\}\
.checkbox-actions\{margin:0 0 10px 0\}\
\
.position-item\{\
  display:block;\
  padding:8px 12px;\
  font-size:14px;\
  border-radius:8px;\
  margin-bottom:6px;\
  background:#fff;\
  border:1px solid #e5e7eb;\
  transition:all 0.2s;\
\}\
.position-item:hover\{\
  background:#f0f9ff;\
  border-color:#3b82f6;\
\}\
.position-item input[type="checkbox"]\{\
  width:auto;\
  margin-right:10px;\
  transform:scale(1.2);\
  cursor:pointer;\
\}\
.position-item label\{\
  cursor:pointer;\
  user-select:none;\
  display:inline;\
  font-weight:400;\
\}\
.checkbox-grid\{\
  display:grid;\
  grid-template-columns:repeat(auto-fill,minmax(280px,1fr));\
  gap:8px;\
  max-height:400px;\
  overflow-y:auto;\
  padding:10px;\
  background:#f9fafb;\
  border-radius:10px;\
  border:1px solid #e5e7eb;\
\}\
\
@media (max-width:900px)\{\
  .field.col-6,.field.col-4,.field.col-3,.field.col-8\{grid-column:span 12\}\
\}\
\
<!-- /app.js -->\
const STORAGE_KEY = 'sjkt_kuala_lipis_surat_lantikan_final_v6';\
const GLOBAL_RUJ_KEY = 'sjkt_kuala_lipis_global_ruj_v6';\
const HEADER_SETTINGS_KEY = 'sjkt_kuala_lipis_header_settings_v6';\
\
const DEFAULT_TEACHERS = [\
  "Pn. Nitya Sree A/P Dorai Singam",\
  "Pn. Yogeshwary A/P Subramaniam",\
  "Pn. Vejayah A/P Muthiah",\
  "Cik. Indirani A/P Subramaniam",\
  "Cik. P Thilagaavaty A/P Perumal",\
  "En. Mohd Heilmie Bin Hasim",\
  "Cik. Loggana A/P Assokumar",\
  "Pn. Kanchanaah A/P Rajenthiran",\
  "En. Palaganesh A/L Rajendran",\
  "Pn. Moganambal Selvi A/P Kunasigaran"\
];\
\
const DEFAULT_POSITIONS = [\
  "Guru Data & Maklumat Sekolah (EMIS)",\
  "Guru ICT / Penyelaras Bestari",\
  "Guru Perpustakaan & Media (GPM)",\
  "Penyelaras Latihan Dalam Perkhidmatan (LDP / CPD)",\
  "Penyelaras SKPM Kualiti@Sekolah",\
  "Pegawai Aset Sekolah",\
  "Pegawai Pemeriksa Aset & Pelupusan",\
  "Penyelaras Program Transformasi Sekolah 2025 (TS25)",\
  "Penyelaras Kajian Tindakan & Inovasi",\
  "Setiausaha Kurikulum",\
  "Setiausaha Peperiksaan Dalaman",\
  "Penyelaras Pentaksiran Berasaskan Sekolah (PBS)",\
  "Penyelaras Pentaksiran Bilik Darjah (PBD)",\
  "Penyelaras Jadual Waktu & Guru Ganti",\
  "Ketua Panitia Mata Pelajaran (BM, BI, Matematik, Sains, dll.)",\
  "Penyelaras Program NILAM",\
  "Penyelaras Pemulihan Khas & ProPIM",\
  "Penyelaras KBAT & i-THINK",\
  "Penyelaras STEM",\
  "Penyelaras Pembangunan Profesionalisme Guru (Professional Learning Community- PLC)",\
  "Penyelaras MBMMBI (Memartabatkan Bahasa Malaysia Memperkukuh Bahasa Inggeris)",\
  "Penyelaras Program Highly Immersive Programme (HIP)",\
  "Penyelaras Program Literasi dan Numerasi (PLaN)",\
  "Ketua Panitia Bahasa Melayu",\
  "Ketua Panitia Bahasa Tamil",\
  "Ketua Panitia Bahasa Inggeris",\
  "Ketua Panitia Matematik",\
  "Ketua Panitia Sains",\
  "Ketua Panitia Pendidikan Moral",\
  "Ketua Panitia Sejarah",\
  "Ketua Panitia Reka Bentuk dan Teknologi (RBT)",\
  "Ketua Panitia Pendidikan Seni Visual",\
  "Ketua Panitia Pendidikan Muzik",\
  "Ketua Panitia Teknologi Maklumat dan Komunikasi (TMK)",\
  "Ketua Panitia Pendidikan Jasmani dan Kesihatan (PJK)",\
  "Guru Prasekolah",\
  "Guru Kelas Tahun 1",\
  "Guru Kelas Tahun 2",\
  "Guru Kelas Tahun 3",\
  "Guru Kelas Tahun 4",\
  "Guru Kelas Tahun 5",\
  "Guru Kelas Tahun 6"\
];\
\
let GLOBAL_RUJ = 'CBD3047.100.6/1/3( )';\
\
let headerSettings = \{\
  leftLogo: '',\
  rightLogo: '',\
  schoolEmail: 'cbd3047@moe.edu.my',\
  note: '',\
  principalName: 'JEYAKANTAN PATHMANABAN'\
\};\
\
const state = \{\
  teachers: [],\
  positions: [],\
  letters: \{\}\
\};\
\
const el = (id) => document.getElementById(id);\
\
function saveState() \{\
  localStorage.setItem(STORAGE_KEY, JSON.stringify(state));\
  localStorage.setItem(GLOBAL_RUJ_KEY, GLOBAL_RUJ);\
  localStorage.setItem(HEADER_SETTINGS_KEY, JSON.stringify(headerSettings));\
\}\
\
function loadState() \{\
  const raw = localStorage.getItem(STORAGE_KEY);\
  const savedRuj = localStorage.getItem(GLOBAL_RUJ_KEY);\
  const savedHeader = localStorage.getItem(HEADER_SETTINGS_KEY);\
\
  if (savedRuj && savedRuj.trim()) \{\
    GLOBAL_RUJ = savedRuj.trim();\
  \}\
\
  if (savedHeader) \{\
    try \{\
      headerSettings = \{ ...headerSettings, ...JSON.parse(savedHeader) \};\
    \} catch (error) \{\}\
  \}\
\
  if (raw) \{\
    try \{\
      const parsed = JSON.parse(raw);\
      state.teachers = Array.isArray(parsed.teachers) ? parsed.teachers : [];\
      state.positions = Array.isArray(parsed.positions) ? parsed.positions : [];\
      state.letters = parsed.letters && typeof parsed.letters === 'object' ? parsed.letters : \{\};\
    \} catch (error) \{\}\
  \}\
\
  if (!state.teachers.length) \{\
    state.teachers = [...DEFAULT_TEACHERS];\
  \}\
\
  if (!state.positions.length) \{\
    state.positions = [...DEFAULT_POSITIONS];\
  \}\
\}\
\
function todayISO() \{\
  return new Date().toISOString().slice(0, 10);\
\}\
\
function formatMalayDate(iso) \{\
  if (!iso) return '';\
  const months = ['Januari', 'Februari', 'Mac', 'April', 'Mei', 'Jun', 'Julai', 'Ogos', 'September', 'Oktober', 'November', 'Disember'];\
  const date = new Date(`$\{iso\}T00:00:00`);\
  if (Number.isNaN(date.getTime())) return iso;\
  return `$\{date.getDate()\} $\{months[date.getMonth()]\} $\{date.getFullYear()\}`;\
\}\
\
function escapeHtml(str = '') \{\
  return String(str)\
    .replace(/&/g, '&amp;')\
    .replace(/</g, '&lt;')\
    .replace(/>/g, '&gt;')\
    .replace(/"/g, '&quot;')\
    .replace(/'/g, '&#39;');\
\}\
\
function roman(num) \{\
  const values = ['', 'i', 'ii', 'iii', 'iv', 'v', 'vi', 'vii', 'viii', 'ix', 'x', 'xi', 'xii', 'xiii', 'xiv', 'xv', 'xvi', 'xvii', 'xviii', 'xix', 'xx', 'xxi', 'xxii'];\
  return values[num] || `$\{num\}.`;\
\}\
\
function updateLogoPreviews() \{\
  const left = el('logoLeftPreview');\
  const right = el('logoRightPreview');\
\
  left.src = headerSettings.leftLogo || '';\
  right.src = headerSettings.rightLogo || '';\
  left.style.display = headerSettings.leftLogo ? 'block' : 'none';\
  right.style.display = headerSettings.rightLogo ? 'block' : 'none';\
\
  el('schoolEmail').value = headerSettings.schoolEmail || 'cbd3047@moe.edu.my';\
  el('headerNote').value = headerSettings.note || '';\
  el('principalName').value = headerSettings.principalName || 'JEYAKANTAN PATHMANABAN';\
\}\
\
function handleLogoUpload(file, side) \{\
  if (!file) return;\
  const reader = new FileReader();\
  reader.onload = function () \{\
    headerSettings[side] = reader.result;\
    updateLogoPreviews();\
  \};\
  reader.readAsDataURL(file);\
\}\
\
function saveHeaderSettings(showAlert = true) \{\
  headerSettings.schoolEmail = el('schoolEmail').value.trim() || 'cbd3047@moe.edu.my';\
  headerSettings.note = el('headerNote').value.trim();\
  headerSettings.principalName = el('principalName').value.trim() || 'JEYAKANTAN PATHMANABAN';\
  saveState();\
  updateLogoPreviews();\
\
  if (showAlert) \{\
    alert('Tetapan header berjaya disimpan.');\
  \}\
\}\
\
function clearHeaderSettings() \{\
  if (!confirm('Padam semua tetapan logo/header?')) return;\
\
  headerSettings = \{\
    leftLogo: '',\
    rightLogo: '',\
    schoolEmail: 'cbd3047@moe.edu.my',\
    note: '',\
    principalName: 'JEYAKANTAN PATHMANABAN'\
  \};\
\
  saveState();\
  updateLogoPreviews();\
  alert('Tetapan header telah direset.');\
\}\
\
function showTab(tabId) \{\
  document.querySelectorAll('.tab-btn').forEach((btn) => \{\
    btn.classList.toggle('active', btn.dataset.tab === tabId);\
  \});\
\
  document.querySelectorAll('.panel').forEach((panel) => \{\
    panel.classList.toggle('active', panel.id === tabId);\
  \});\
\}\
\
function teacherOptionsHTML(selected = '') \{\
  const options = ['<option value="">-- Pilih guru --</option>'];\
  [...state.teachers].sort().forEach((name) => \{\
    options.push(`<option value="$\{escapeHtml(name)\}" $\{name === selected ? 'selected' : ''\}>$\{escapeHtml(name)\}</option>`);\
  \});\
  return options.join('');\
\}\
\
function renderTeacherDropdowns(selected = '') \{\
  el('teacherSelect').innerHTML = teacherOptionsHTML(selected);\
  el('printTeacherSelect').innerHTML = teacherOptionsHTML(selected);\
\}\
\
function getPositionCheckboxes() \{\
  return Array.from(document.querySelectorAll('#positionCheckboxContainer input[type="checkbox"]'));\
\}\
\
function getSelectedPositions() \{\
  return getPositionCheckboxes()\
    .filter((checkbox) => checkbox.checked)\
    .map((checkbox) => checkbox.value);\
\}\
\
function setSelectedPositions(positions) \{\
  const selected = new Set(positions);\
  getPositionCheckboxes().forEach((checkbox) => \{\
    checkbox.checked = selected.has(checkbox.value);\
  \});\
  renderSelectedTeacherPositions();\
\}\
\
function renderPositions(selectedPositions) \{\
  const container = el('positionCheckboxContainer');\
  const current = Array.isArray(selectedPositions) ? selectedPositions : getSelectedPositions();\
\
  container.innerHTML = [...state.positions]\
    .sort()\
    .map((pos) => \{\
      const id = `pos_$\{Math.random().toString(36).slice(2, 11)\}`;\
      const checked = current.includes(pos) ? 'checked' : '';\
      return `<div class="position-item">\
        <input type="checkbox" id="$\{id\}" value="$\{escapeHtml(pos)\}" $\{checked\}>\
        <label for="$\{id\}">$\{escapeHtml(pos)\}</label>\
      </div>`;\
    \})\
    .join('');\
\
  getPositionCheckboxes().forEach((checkbox) => \{\
    checkbox.addEventListener('change', renderSelectedTeacherPositions);\
  \});\
\}\
\
function selectAllPositions() \{\
  getPositionCheckboxes().forEach((checkbox) => \{\
    checkbox.checked = true;\
  \});\
  renderSelectedTeacherPositions();\
\}\
\
function clearAllPositions() \{\
  getPositionCheckboxes().forEach((checkbox) => \{\
    checkbox.checked = false;\
  \});\
  renderSelectedTeacherPositions();\
\}\
\
function renderSelectedTeacherPositions() \{\
  const values = getSelectedPositions();\
  el('selectedTeacherPositions').innerHTML = values.length\
    ? values.map((position) => `<span class="pill">$\{escapeHtml(position)\}</span>`).join('')\
    : '<span class="muted">Belum ada jawatan dipilih.</span>';\
\}\
\
function ensureTeacher(name) \{\
  const clean = (name || '').trim();\
  if (!clean) return false;\
  if (!state.teachers.includes(clean)) \{\
    state.teachers.push(clean);\
  \}\
  return clean;\
\}\
\
function ensurePositions(list) \{\
  list.forEach((pos) => \{\
    const clean = String(pos || '').trim();\
    if (clean && !state.positions.includes(clean)) \{\
      state.positions.push(clean);\
    \}\
  \});\
\}\
\
function clearForm(keepTeacher = false) \{\
  const teacher = keepTeacher ? el('teacherSelect').value : '';\
  el('rujKami').value = GLOBAL_RUJ;\
  el('tarikhSurat').value = todayISO();\
  el('tahunBuku').value = '';\
  el('sesiAkademik').value = '';\
  el('tajukSurat').value = 'PERLANTIKAN SEBAGAI JAWATANKUASA UNIT PENGURUSAN KURIKULUM DAN PENTADBIRAN SEKOLAH JENIS KEBANGSAAN (TAMIL) KUALA LIPIS';\
  el('tarikhMula').value = todayISO();\
  el('tarikhHingga').value = '';\
  el('newPositionText').value = '';\
  renderTeacherDropdowns(teacher);\
  renderPositions([]);\
  renderSelectedTeacherPositions();\
\}\
\
function fillFormFromRecord(name) \{\
  renderTeacherDropdowns(name);\
  const rec = state.letters[name];\
  el('rujKami').value = GLOBAL_RUJ;\
\
  if (!rec) \{\
    renderPositions([]);\
    renderSelectedTeacherPositions();\
    return;\
  \}\
\
  el('tarikhSurat').value = rec.tarikhSurat || todayISO();\
  el('tahunBuku').value = rec.tahunBuku || '';\
  el('sesiAkademik').value = rec.sesiAkademik || '';\
  el('tajukSurat').value = rec.tajukSurat || 'PERLANTIKAN SEBAGAI JAWATANKUASA UNIT PENGURUSAN KURIKULUM DAN PENTADBIRAN SEKOLAH JENIS KEBANGSAAN (TAMIL) KUALA LIPIS';\
  el('tarikhMula').value = rec.tarikhMula || '';\
  el('tarikhHingga').value = rec.tarikhHingga || '';\
  renderPositions(rec.positions || []);\
  renderSelectedTeacherPositions();\
\}\
\
function saveCurrentRecord() \{\
  let teacher = el('teacherSelect').value;\
\
  if (!teacher && el('newTeacherName').value.trim()) \{\
    teacher = ensureTeacher(el('newTeacherName').value.trim());\
  \}\
\
  if (!teacher) \{\
    alert('Sila pilih atau tambah nama guru terlebih dahulu.');\
    return;\
  \}\
\
  GLOBAL_RUJ = el('rujKami').value.trim() || 'CBD3047.100.6/1/3( )';\
\
  state.letters[teacher] = \{\
    teacher,\
    tarikhSurat: el('tarikhSurat').value,\
    tahunBuku: el('tahunBuku').value.trim(),\
    sesiAkademik: el('sesiAkademik').value.trim(),\
    tajukSurat: el('tajukSurat').value.trim(),\
    tarikhMula: el('tarikhMula').value,\
    tarikhHingga: el('tarikhHingga').value,\
    positions: getSelectedPositions()\
  \};\
\
  ensureTeacher(teacher);\
  saveState();\
  renderAll();\
  renderTeacherDropdowns(teacher);\
  fillFormFromRecord(teacher);\
  el('newTeacherName').value = '';\
  alert('Rekod guru berjaya disimpan / dikemaskini.');\
\}\
\
function buildPositionsHTML(list) \{\
  if (!(list || []).length) \{\
    return '<div class="roman-row"><span class="roman-span">i.</span><span>-</span></div>';\
  \}\
\
  return list\
    .map((position, index) => `<div class="roman-row"><span class="roman-span">$\{roman(index + 1)\}.</span><span>$\{escapeHtml(position)\}</span></div>`)\
    .join('');\
\}\
\
function getLeftLogoHTML() \{\
  return headerSettings.leftLogo\
    ? `<img src="$\{headerSettings.leftLogo\}" alt="Logo kiri">`\
    : '<div style="width:78px;height:88px;border:1px solid #777;font-size:10px;display:flex;align-items:center;justify-content:center;text-align:center;">LOGO KIRI</div>';\
\}\
\
function getRightLogoHTML() \{\
  return headerSettings.rightLogo\
    ? `<img src="$\{headerSettings.rightLogo\}" alt="Logo kanan">`\
    : '<div style="width:78px;height:88px;border:1px solid #777;font-size:10px;display:flex;align-items:center;justify-content:center;text-align:center;">LOGO SEKOLAH</div>';\
\}\
\
function generateLetterHTML(rec) \{\
  const positions = buildPositionsHTML(rec.positions || []);\
  const teacherUpper = (rec.teacher || '').toUpperCase();\
  const principalName = headerSettings.principalName || 'JEYAKANTAN PATHMANABAN';\
\
  return `<div class="page">\
    <div class="box">\
      <div class="header">\
        <div class="logo-left">$\{getLeftLogoHTML()\}</div>\
        <div class="header-center">\
          <div class="kpm">KEMENTERIAN PENDIDIKAN MALAYSIA</div>\
          <div class="school">SEKOLAH JENIS KEBANGSAAN (TAMIL) KUALA LIPIS</div>\
          <div class="addr">27200 Kuala Lipis</div>\
          <div class="addr">Pahang Darul Makmur</div>\
          <div class="small-meta">Tel/Faks : 09-3125150</div>\
          <div class="small-meta">Email : $\{escapeHtml(headerSettings.schoolEmail || 'cbd3047@moe.edu.my')\}</div>\
        </div>\
        <div class="logo-right">$\{getRightLogoHTML()\}</div>\
      </div>\
      <div class="line"></div>\
      <div class="ref-wrap">\
        <div>Ruj. Kami: $\{escapeHtml(GLOBAL_RUJ)\}</div>\
        <div>Tarikh: $\{escapeHtml(formatMalayDate(rec.tarikhSurat))\}</div>\
      </div>\
      <div class="recipient">$\{escapeHtml(teacherUpper)\}<br>Sekolah Jenis Kebangsaan Tamil Kuala Lipis<br>27200 Kuala Lipis,<br>Pahang Darul Makmur</div>\
      <div class="tuan">Tuan/Puan,</div>\
      <div class="title">$\{escapeHtml(rec.tajukSurat)\}</div>\
      <div class="para">Dengan segala hormatnya perkara di atas dirujuk.</div>\
      <div class="para numrow">\
        <span class="num-span">2.</span>\
        <span class="numrow-text">Sukacita dimaklumkan bahawa tuan/puan telah dilantik menganggotai jawatankuasa yang terkandung seperti dalam Buku Pengurusan dan Takwim Sekolah :</span>\
      </div>\
      <div class="roman-group">$\{positions\}</div>\
      <div class="para numrow">\
        <span class="num-span">3.</span>\
        <span class="numrow-text">Tugas tuan/puan ini berkuat kuasa mulai sesi akademik $\{escapeHtml(rec.sesiAkademik || '')\}$\{rec.tarikhMula || rec.tarikhHingga ? `, mulai $\{escapeHtml(formatMalayDate(rec.tarikhMula))\}$\{rec.tarikhHingga ? ` hingga $\{escapeHtml(formatMalayDate(rec.tarikhHingga))\}` : ''\}` : ''\} dan tertakluk kepada sebarang perubahan daripada pihak pentadbir sekolah dari semasa ke semasa.</span>\
      </div>\
      <div class="para numrow">\
        <span class="num-span">4.</span>\
        <span class="numrow-text">Tuan/puan dikehendaki melaksanakan semua tugas yang telah ditetapkan dan mematuhi semua peraturan, prosedur yang menjadi KPI (Key Performance Indicator) KPM. Sukacita juga diingatkan bahawa tugas-tugas yang dipertanggungjawabkan adalah merupakan tugas-tugas rasmi dan diuruskan selari dengan visi dan misi sekolah.</span>\
      </div>\
      <div class="para numrow">\
        <span class="num-span">5.</span>\
        <span class="numrow-text">Saya berkeyakinan bahawa tuan/puan mampu melaksanakan tugas dan tanggungjawab yang diamanahkan berdasarkan kebolehan, keupayaan, minat dan komitmen yang ditunjukkan selama ini.</span>\
      </div>\
      <div class="sekian">Sekian, terima kasih.</div>\
      <div class="slogan-group">\
        <strong>"MALAYSIA MADANI"</strong><br>\
        <strong>"BERKHIDMAT UNTUK NEGARA"</strong><br>\
        <strong>"TRANSFORMASI PENDIDIKAN PAHANG"</strong>\
      </div>\
      <div class="saya">Saya yang menjalankan amanah,</div>\
      <div class="signature-gap"></div>\
      <div class="signature-line">.....................................................</div>\
      <div class="signature-block">\
        <strong>($\{escapeHtml(principalName)\})</strong><br>\
        <strong>GURU BESAR</strong><br>\
        SJKT KUALA LIPIS\
      </div>\
      <div class="sk-block">s.k. Fail Pengurusan Kurikulum</div>\
    </div>\
  </div>`;\
\}\
\
function buildPreviewHTML(records, autoPrint) \{\
  const pages = records\
    .map((rec, idx) => `<div class="sheet $\{idx < records.length - 1 ? 'page-break' : ''\}">$\{generateLetterHTML(rec)\}</div>`)\
    .join('');\
\
  return `<!doctype html>\
<html lang="ms">\
<head>\
<meta charset="UTF-8">\
<title>Preview Surat</title>\
<style>\
@page\{size:A4;margin:11mm 14mm 12mm 14mm\}\
body\{margin:0;background:#e5e7eb;font-family:Arial,sans-serif\}\
.toolbar\{position:sticky;top:0;background:#fff;padding:14px;border-bottom:1px solid #d1d5db;z-index:10\}\
.toolbar button\{padding:10px 12px;border:none;border-radius:8px;font-weight:bold;cursor:pointer;margin-right:8px\}\
.btn1\{background:#0f4c81;color:#fff\}\
.btn2\{background:#e5e7eb;color:#111\}\
.sheet\{display:block;width:100%;background:#fff;max-width:900px;margin:14px auto;box-shadow:0 10px 30px rgba(0,0,0,.08);padding:10px 14px\}\
.page-break\{page-break-after:always;break-after:page\}\
.page\{max-width:780px;margin:0 auto;font-family:"Times New Roman",Times,serif;font-size:10.6pt;color:#000\}\
.box\{border:1px solid #000;padding:24px 28px;box-sizing:border-box\}\
.header\{display:grid;grid-template-columns:90px 1fr 90px;align-items:center;column-gap:18px\}\
.logo-left,.logo-right\{display:flex;align-items:center;justify-content:center\}\
.logo-left img,.logo-right img\{width:76px;height:auto;object-fit:contain\}\
.header-center\{text-align:center;padding:0 10px\}\
.kpm\{font-weight:bold;font-size:12.8pt;line-height:1.0;margin:0 0 2px 0\}\
.school\{font-weight:bold;font-size:11pt;line-height:1.0;margin:0 0 2px 0\}\
.addr\{font-size:10.4pt;line-height:1.15;margin:0\}\
.small-meta\{font-size:8.3pt;line-height:1.0;margin:0\}\
.line\{border-bottom:1px solid #000;margin-top:6px;margin-bottom:2px\}\
.ref-wrap\{text-align:right;font-size:8.5pt;line-height:1.2;width:260px;margin-left:auto;margin-bottom:8px\}\
.ref-wrap div\{margin:0;padding:0;text-indent:0\}\
.recipient\{font-size:10.6pt;line-height:1.15;margin-top:12pt;margin-bottom:12pt\}\
.tuan\{font-size:10.6pt;line-height:1.15;margin-top:0;margin-bottom:12pt\}\
.title\{font-size:10.6pt;line-height:1.15;margin-top:12pt;margin-bottom:12pt;font-weight:bold;text-transform:uppercase;text-align:justify\}\
.para\{font-size:10.6pt;line-height:1.5;margin-top:12pt;margin-bottom:12pt;text-align:justify\}\
.numrow\{display:block\}\
.num-span\{display:inline-block;width:24px\}\
.numrow-text\{display:inline\}\
.roman-group\{margin-left:0.75in;margin-top:0;margin-bottom:12pt\}\
.roman-row\{text-indent:-0.25in;padding-left:0.25in;line-height:1.15;text-align:justify;margin:0\}\
.roman-span\{display:inline-block;width:0.25in\}\
.sekian\{font-size:10.6pt;line-height:1.5;margin-top:0;margin-bottom:18pt;margin-left:0;text-align:left\}\
.slogan-group\{font-size:10.6pt;line-height:1.5;margin-top:0;margin-bottom:0;text-align:left\}\
.saya\{font-size:10.6pt;line-height:1.5;margin-top:24pt;margin-bottom:0;text-align:left\}\
.signature-gap\{height:36px\}\
.signature-line\{margin-left:0;line-height:1.0;text-align:left\}\
.signature-block\{font-size:10.6pt;line-height:1.0;margin-top:0\}\
.sk-block\{font-size:8.6pt;line-height:1.0;font-style:italic;margin-top:24px;margin-left:36px\}\
@media print\{\
  body\{background:#fff\}\
  .toolbar\{display:none\}\
  .sheet\{margin:0;box-shadow:none;max-width:none;padding:0;background:#fff\}\
\}\
</style>\
</head>\
<body>\
<div class="toolbar">\
  <button class="btn1" id="btnCetak">Cetak</button>\
  <button class="btn2" onclick="window.close()">Tutup</button>\
</div>\
$\{pages\}\
<script>\
function autoFitPages()\{\
  document.querySelectorAll('.page').forEach(function(page)\{\
    let fs=10.6,gap=36,tries=0;\
    while(page.scrollHeight>1035&&fs>9.5&&tries<16)\{\
      fs-=0.1;\
      gap=Math.max(20,gap-2);\
      page.style.fontSize=fs+'pt';\
      let sg=page.querySelector('.signature-gap');\
      if(sg) sg.style.height=gap+'px';\
      tries++;\
    \}\
  \});\
\}\
document.getElementById('btnCetak').addEventListener('click',function()\{\
  window.focus();\
  setTimeout(function()\{window.print();\},300);\
\});\
window.addEventListener('load',function()\{\
  autoFitPages();\
  $\{autoPrint ? 'window.focus();setTimeout(function()\{window.print();\},800);' : ''\}\
\});\
<\\/script>\
</body>\
</html>`;\
\}\
\
function openPreview(records, autoPrint = false) \{\
  if (!records.length) \{\
    alert('Tiada rekod untuk dipreview.');\
    return;\
  \}\
\
  const previewWindow = window.open('', '_blank');\
  if (!previewWindow) \{\
    alert('Pop-up diblokir. Sila benarkan pop-up untuk sistem ini.');\
    return;\
  \}\
\
  previewWindow.document.open();\
  previewWindow.document.write(buildPreviewHTML(records, autoPrint));\
  previewWindow.document.close();\
\}\
\
function renderTable() \{\
  const tbody = el('recordTableBody');\
  const query = el('searchTeacher').value.trim().toLowerCase();\
\
  const names = [...state.teachers]\
    .sort()\
    .filter((name) => !query || name.toLowerCase().includes(query));\
\
  tbody.innerHTML = names.map((name, index) => \{\
    const rec = state.letters[name] || \{ positions: [] \};\
    const safe = name.replace(/'/g, "\\\\'");\
    return `<tr>\
      <td>$\{index + 1\}</td>\
      <td>$\{escapeHtml(name)\}</td>\
      <td>$\{(rec.positions || []).map((p) => `<span class="pill">$\{escapeHtml(p)\}</span>`).join('')\}</td>\
      <td>$\{escapeHtml(rec.tahunBuku || '')\}</td>\
      <td>$\{escapeHtml(formatMalayDate(rec.tarikhMula || ''))\}$\{rec.tarikhHingga ? ` - $\{escapeHtml(formatMalayDate(rec.tarikhHingga))\}` : ''\}</td>\
      <td>\
        <button class="ghost" type="button" onclick="editRecord('$\{safe\}')">Edit</button>\
        <button class="danger" type="button" onclick="deleteRecord('$\{safe\}')">Delete</button>\
      </td>\
    </tr>`;\
  \}).join('') || '<tr><td colspan="6" class="muted">Tiada rekod dijumpai.</td></tr>';\
\
  el('recordCount').textContent = `$\{names.length\} rekod`;\
\}\
\
function renderTeacherListView() \{\
  const names = [...state.teachers].sort();\
\
  el('teacherListView').innerHTML = names.length\
    ? names.map((name) => \{\
        const rec = state.letters[name] || \{ positions: [] \};\
        return `<div style="padding:12px 0;border-bottom:1px solid #e5e7eb;">\
          <div style="font-weight:700;">$\{escapeHtml(name)\}</div>\
          <div class="muted small">$\{escapeHtml(rec.tahunBuku || '-')\} \'95 $\{escapeHtml(rec.sesiAkademik || '-')\}</div>\
          <div style="margin-top:6px;">\
            $\{(rec.positions || []).map((p) => `<span class="pill">$\{escapeHtml(p)\}</span>`).join('') || '<span class="muted">Tiada jawatan disimpan</span>'\}\
          </div>\
        </div>`;\
      \}).join('')\
    : '<span class="muted">Belum ada nama guru yang disimpan.</span>';\
\}\
\
function renderAll() \{\
  renderTeacherDropdowns();\
  renderPositions([]);\
  renderSelectedTeacherPositions();\
  renderTable();\
  renderTeacherListView();\
  el('rujKami').value = GLOBAL_RUJ;\
\}\
\
function exportJSON() \{\
  const blob = new Blob(\
    [JSON.stringify(\{ ...state, globalRuj: GLOBAL_RUJ, headerSettings \}, null, 2)],\
    \{ type: 'application/json' \}\
  );\
\
  const link = document.createElement('a');\
  link.href = URL.createObjectURL(blob);\
  link.download = 'data-surat-lantikan-sjkt-kuala-lipis.json';\
  link.click();\
  URL.revokeObjectURL(link.href);\
\}\
\
function importJSON(file) \{\
  const reader = new FileReader();\
\
  reader.onload = (event) => \{\
    try \{\
      const data = JSON.parse(event.target.result);\
      state.teachers = Array.isArray(data.teachers) ? data.teachers : [...DEFAULT_TEACHERS];\
      state.positions = Array.isArray(data.positions) ? data.positions : [...DEFAULT_POSITIONS];\
      state.letters = data.letters && typeof data.letters === 'object' ? data.letters : \{\};\
      GLOBAL_RUJ = (data.globalRuj && String(data.globalRuj).trim()) ? String(data.globalRuj).trim() : 'CBD3047.100.6/1/3( )';\
\
      if (data.headerSettings && typeof data.headerSettings === 'object') \{\
        headerSettings = \{ ...headerSettings, ...data.headerSettings \};\
      \}\
\
      saveState();\
      renderAll();\
      clearForm();\
      updateLogoPreviews();\
      alert('Import berjaya.');\
    \} catch (error) \{\
      alert('Fail JSON tidak sah.');\
    \}\
  \};\
\
  reader.readAsText(file, 'utf-8');\
\}\
\
function editRecord(name) \{\
  showTab('tab1');\
  fillFormFromRecord(name);\
\}\
window.editRecord = editRecord;\
\
function deleteRecord(name) \{\
  if (!confirm(`Padam rekod $\{name\}?`)) return;\
\
  delete state.letters[name];\
  state.teachers = state.teachers.filter((teacher) => teacher !== name);\
  saveState();\
  renderAll();\
  clearForm();\
\}\
window.deleteRecord = deleteRecord;\
\
document.querySelectorAll('.tab-btn').forEach((btn) => \{\
  btn.addEventListener('click', () => showTab(btn.dataset.tab));\
\});\
\
el('logoLeftInput').addEventListener('change', (event) => handleLogoUpload(event.target.files[0], 'leftLogo'));\
el('logoRightInput').addEventListener('change', (event) => handleLogoUpload(event.target.files[0], 'rightLogo'));\
el('saveLogoSettingsBtn').addEventListener('click', () => saveHeaderSettings(true));\
el('clearLogoSettingsBtn').addEventListener('click', clearHeaderSettings);\
\
el('addTeacherBtn').addEventListener('click', () => \{\
  const name = el('newTeacherName').value.trim();\
\
  if (!name) \{\
    alert('Sila taip nama guru.');\
    return;\
  \}\
\
  ensureTeacher(name);\
  saveState();\
  renderAll();\
  renderTeacherDropdowns(name);\
  el('newTeacherName').value = '';\
  alert('Nama guru berjaya ditambah.');\
\});\
\
el('addPositionBtn').addEventListener('click', () => \{\
  const lines = el('newPositionText').value\
    .split(/\\n+/)\
    .map((value) => value.trim())\
    .filter(Boolean);\
\
  if (!lines.length) \{\
    alert('Sila masukkan sekurang-kurangnya satu jawatan.');\
    return;\
  \}\
\
  const previouslySelected = getSelectedPositions();\
  ensurePositions(lines);\
  saveState();\
  renderPositions([...new Set([...previouslySelected, ...lines])]);\
  renderSelectedTeacherPositions();\
  el('newPositionText').value = '';\
\});\
\
el('selectAllPositionsBtn').addEventListener('click', selectAllPositions);\
el('clearAllPositionsBtn').addEventListener('click', clearAllPositions);\
\
el('teacherSelect').addEventListener('change', (event) => fillFormFromRecord(event.target.value));\
el('saveAssignmentBtn').addEventListener('click', saveCurrentRecord);\
el('resetFormBtn').addEventListener('click', () => clearForm());\
\
el('searchTeacher').addEventListener('input', renderTable);\
el('exportJsonBtn').addEventListener('click', exportJSON);\
\
el('importJsonInput').addEventListener('change', (event) => \{\
  const file = event.target.files[0];\
  if (file) \{\
    importJSON(file);\
  \}\
\});\
\
el('rujKami').addEventListener('input', () => \{\
  GLOBAL_RUJ = el('rujKami').value.trim() || 'CBD3047.100.6/1/3( )';\
  saveState();\
\});\
\
el('previewOneBtn').addEventListener('click', () => \{\
  const name = el('printTeacherSelect').value;\
  if (!name || !state.letters[name]) \{\
    alert('Sila pilih guru yang mempunyai rekod.');\
    return;\
  \}\
  saveHeaderSettings(false);\
  openPreview([state.letters[name]], false);\
\});\
\
el('printOneBtn').addEventListener('click', () => \{\
  const name = el('printTeacherSelect').value;\
  if (!name || !state.letters[name]) \{\
    alert('Sila pilih guru yang mempunyai rekod.');\
    return;\
  \}\
  saveHeaderSettings(false);\
  openPreview([state.letters[name]], true);\
\});\
\
el('previewAllBtn').addEventListener('click', () => \{\
  const records = [...state.teachers]\
    .sort()\
    .map((name) => state.letters[name])\
    .filter(Boolean);\
\
  saveHeaderSettings(false);\
  openPreview(records, false);\
\});\
\
el('printAllBtn').addEventListener('click', () => \{\
  const records = [...state.teachers]\
    .sort()\
    .map((name) => state.letters[name])\
    .filter(Boolean);\
\
  saveHeaderSettings(false);\
  openPreview(records, true);\
\});\
\
loadState();\
renderAll();\
updateLogoPreviews();\
el('tarikhSurat').value = todayISO();\
el('tarikhMula').value = todayISO();\
el('rujKami').value = GLOBAL_RUJ;}
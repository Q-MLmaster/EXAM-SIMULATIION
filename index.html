<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>MAHE Online Examination Portal - Business Statistics</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* { margin:0; padding:0; box-sizing:border-box; font-family:'Segoe UI', Tahoma, sans-serif; }
body { background:#eef2f7; color:#222; min-height:100vh; }
.hidden { display:none !important; }

.login-wrap { display:flex; justify-content:center; align-items:center; min-height:100vh;
  background:linear-gradient(135deg,#1e3c72,#2a5298); }
.login-box { background:#fff; padding:40px; border-radius:12px; width:400px;
  box-shadow:0 20px 60px rgba(0,0,0,.3); }
.login-box h1 { color:#1e3c72; text-align:center; margin-bottom:8px; font-size:22px; }
.login-box .sub { text-align:center; color:#666; margin-bottom:25px; font-size:13px; }
.login-box input { width:100%; padding:12px; margin:8px 0; border:1px solid #ccc;
  border-radius:6px; font-size:14px; }
.login-box button { width:100%; padding:12px; background:#1e3c72; color:#fff;
  border:none; border-radius:6px; font-size:15px; cursor:pointer; margin-top:10px; }
.login-box button:hover { background:#2a5298; }
.demo-info { margin-top:15px; padding:10px; background:#f0f7ff; border-radius:6px;
  font-size:12px; color:#1e3c72; text-align:center; }

.exam-header { background:#1e3c72; color:#fff; padding:10px 20px;
  display:flex; justify-content:space-between; align-items:center;
  box-shadow:0 2px 8px rgba(0,0,0,.2); position:sticky; top:0; z-index:100; }
.exam-header .logo { font-weight:bold; font-size:16px; }
.exam-header .timer { background:#d32f2f; padding:8px 18px; border-radius:6px;
  font-weight:bold; font-size:16px; font-family:'Courier New',monospace; }
.exam-header .timer.warn { background:#ff9800; animation:pulse 1s infinite; }
@keyframes pulse { 50% { opacity:.6; } }
.exam-header .user-info { font-size:13px; }

.instr-wrap { max-width:900px; margin:30px auto; background:#fff; padding:30px;
  border-radius:10px; box-shadow:0 4px 20px rgba(0,0,0,.1); }
.instr-wrap h2 { color:#1e3c72; border-bottom:2px solid #1e3c72; padding-bottom:10px;
  margin-bottom:20px; }
.instr-wrap ol { padding-left:25px; line-height:1.9; }
.instr-wrap li { margin:6px 0; }
.instr-wrap .warn-box { background:#fff3cd; border-left:4px solid #ff9800;
  padding:12px; margin:15px 0; border-radius:4px; }
.instr-wrap .attempt-info { background:#e3f2fd; border-left:4px solid #1e3c72;
  padding:12px; margin:15px 0; border-radius:4px; font-size:14px; }
.instr-wrap .agree { margin:20px 0; }
.btn-primary { background:#1e3c72; color:#fff; border:none; padding:12px 30px;
  border-radius:6px; cursor:pointer; font-size:15px; }
.btn-primary:hover { background:#2a5298; }
.btn-primary:disabled { background:#aaa; cursor:not-allowed; }
.btn-danger { background:#d32f2f; color:#fff; border:none; padding:10px 20px;
  border-radius:6px; cursor:pointer; }
.btn-success { background:#4caf50; color:#fff; border:none; padding:10px 20px;
  border-radius:6px; cursor:pointer; }

.exam-body { display:grid; grid-template-columns:1fr 300px; gap:15px;
  padding:15px; max-width:1400px; margin:0 auto; }
.question-area { background:#fff; border-radius:10px; padding:25px;
  box-shadow:0 2px 10px rgba(0,0,0,.08); min-height:500px; }
.question-area .q-head { display:flex; justify-content:space-between;
  align-items:center; margin-bottom:15px; padding-bottom:10px;
  border-bottom:2px solid #eee; }
.question-area .q-num { font-weight:bold; color:#1e3c72; font-size:16px; }
.question-area .q-marks { background:#e8f5e9; color:#2e7d32; padding:4px 12px;
  border-radius:12px; font-size:13px; font-weight:bold; }
.question-area .q-text { font-size:15px; line-height:1.7; margin:15px 0 20px;
  white-space:pre-wrap; }
.option { display:block; padding:12px 15px; margin:8px 0; background:#f8f9fa;
  border:2px solid #e0e0e0; border-radius:6px; cursor:pointer; transition:.2s; }
.option:hover { background:#e3f2fd; border-color:#2196f3; }
.option.selected { background:#e3f2fd; border-color:#1e3c72; font-weight:600; }
.option input { margin-right:10px; }
.q-actions { display:flex; justify-content:space-between; margin-top:25px;
  padding-top:15px; border-top:1px solid #eee; }
.q-actions button { padding:8px 16px; border:none; border-radius:5px;
  cursor:pointer; font-size:13px; }
.btn-mark { background:#ff9800; color:#fff; }
.btn-clear { background:#9e9e9e; color:#fff; }
.btn-nav { background:#1e3c72; color:#fff; }

.palette { background:#fff; border-radius:10px; padding:15px;
  box-shadow:0 2px 10px rgba(0,0,0,.08); position:sticky; top:80px;
  max-height:calc(100vh - 100px); overflow-y:auto; }
.palette h3 { color:#1e3c72; font-size:14px; margin-bottom:10px;
  text-align:center; border-bottom:1px solid #eee; padding-bottom:8px; }
.palette-grid { display:grid; grid-template-columns:repeat(5,1fr); gap:6px;
  margin-bottom:15px; }
.p-btn { aspect-ratio:1; border:2px solid #ccc; background:#fff; border-radius:5px;
  cursor:pointer; font-size:12px; font-weight:bold; transition:.2s; }
.p-btn:hover { transform:scale(1.05); }
.p-btn.current { border-color:#1e3c72; background:#bbdefb; }
.p-btn.answered { background:#4caf50; color:#fff; border-color:#388e3c; }
.p-btn.marked { background:#ff9800; color:#fff; border-color:#f57c00; }
.legend { font-size:11px; margin-top:10px; }
.legend div { display:flex; align-items:center; margin:4px 0; }
.legend .dot { width:14px; height:14px; border-radius:3px; margin-right:8px;
  border:1px solid #999; }
.submit-section { margin-top:15px; text-align:center; }
.submit-section button { width:100%; padding:10px; background:#d32f2f; color:#fff;
  border:none; border-radius:6px; font-weight:bold; cursor:pointer; }

.desc-area textarea { width:100%; min-height:300px; padding:12px;
  border:1px solid #ccc; border-radius:6px; font-size:14px; resize:vertical;
  font-family:inherit; line-height:1.6; }
.word-count { text-align:right; color:#666; font-size:12px; margin-top:5px; }

.modal-bg { position:fixed; top:0; left:0; width:100%; height:100%;
  background:rgba(0,0,0,.6); display:flex; justify-content:center;
  align-items:center; z-index:1000; }
.modal { background:#fff; padding:30px; border-radius:10px; max-width:600px;
  width:90%; text-align:center; max-height:85vh; overflow-y:auto; }
.modal h2 { color:#1e3c72; margin-bottom:15px; }
.modal .stats { display:grid; grid-template-columns:1fr 1fr; gap:10px;
  margin:20px 0; text-align:left; }
.modal .stat { background:#f5f5f5; padding:10px; border-radius:6px; }
.modal .stat .v { font-size:20px; font-weight:bold; color:#1e3c72; }
.modal .stat .l { font-size:12px; color:#666; }
.modal-btns { display:flex; gap:10px; justify-content:center; margin-top:15px; }

.result-wrap { max-width:900px; margin:30px auto; background:#fff; padding:30px;
  border-radius:10px; box-shadow:0 4px 20px rgba(0,0,0,.1); }
.result-wrap h2 { color:#1e3c72; text-align:center; margin-bottom:20px; }
.score-card { background:linear-gradient(135deg,#1e3c72,#2a5298); color:#fff;
  padding:25px; border-radius:10px; text-align:center; margin-bottom:20px; }
.score-card .big { font-size:48px; font-weight:bold; }
.score-card .lbl { font-size:14px; opacity:.9; }
.breakdown { display:grid; grid-template-columns:repeat(3,1fr); gap:15px;
  margin:20px 0; }
.breakdown .card { background:#f5f5f5; padding:15px; border-radius:8px;
  text-align:center; }
.breakdown .card .n { font-size:24px; font-weight:bold; color:#1e3c72; }

.admin-wrap { max-width:1200px; margin:20px auto; padding:20px; }
.admin-tabs { display:flex; gap:5px; margin-bottom:20px; flex-wrap:wrap; }
.admin-tabs button { padding:10px 18px; background:#fff; border:1px solid #ccc;
  border-radius:6px 6px 0 0; cursor:pointer; font-size:13px; }
.admin-tabs button.active { background:#1e3c72; color:#fff; }
.admin-panel { background:#fff; padding:25px; border-radius:10px;
  box-shadow:0 2px 10px rgba(0,0,0,.1); }
.admin-panel h3 { color:#1e3c72; margin-bottom:15px; }
.admin-panel textarea, .admin-panel input, .admin-panel select {
  width:100%; padding:10px; margin:5px 0; border:1px solid #ccc;
  border-radius:5px; font-size:14px; font-family:inherit; }
.admin-panel textarea { min-height:100px; }
.q-list { margin-top:20px; }
.q-item { background:#f8f9fa; padding:12px; margin:8px 0; border-radius:6px;
  border-left:4px solid #1e3c72; }
.q-item .del { float:right; background:#d32f2f; color:#fff; border:none;
  padding:4px 10px; border-radius:4px; cursor:pointer; font-size:12px; }

/* Submissions table */
.sub-table { width:100%; border-collapse:collapse; margin-top:15px; }
.sub-table th, .sub-table td { padding:10px; text-align:left; border-bottom:1px solid #eee; font-size:13px; }
.sub-table th { background:#1e3c72; color:#fff; }
.sub-table tr:hover { background:#f5f5f5; cursor:pointer; }
.sub-table .score { font-weight:bold; color:#2e7d32; }
.sub-table .low { color:#d32f2f; }
.sub-detail { background:#fffde7; padding:15px; margin:10px 0; border-radius:6px;
  border-left:4px solid #ff9800; }
.sub-detail .qa { background:#fff; padding:10px; margin:8px 0; border-radius:4px;
  border-left:3px solid #1e3c72; }
.sub-detail .qa.correct { border-left-color:#4caf50; }
.sub-detail .qa.wrong { border-left-color:#d32f2f; }
.sub-detail .qa .tag { display:inline-block; padding:2px 8px; border-radius:10px;
  font-size:11px; margin-right:5px; font-weight:bold; }
.tag.green { background:#e8f5e9; color:#2e7d32; }
.tag.red { background:#ffebee; color:#c62828; }
.tag.gray { background:#f5f5f5; color:#666; }

.stats-grid { display:grid; grid-template-columns:repeat(4,1fr); gap:15px; margin-bottom:20px; }
.stats-card { background:linear-gradient(135deg,#1e3c72,#2a5298); color:#fff;
  padding:20px; border-radius:8px; text-align:center; }
.stats-card .n { font-size:28px; font-weight:bold; }
.stats-card .l { font-size:12px; opacity:.9; }

.toolbar { display:flex; gap:10px; margin-bottom:15px; flex-wrap:wrap; }
.toolbar button { padding:8px 15px; border:none; border-radius:5px; cursor:pointer; font-size:13px; }
</style>
</head>
<body oncontextmenu="return false;">

<!-- LOGIN -->
<div id="loginScreen" class="login-wrap">
  <div class="login-box">
    <div style="text-align:center;font-size:40px;">🎓</div>
    <h1>MAHE Online Examination</h1>
    <div class="sub">Directorate of Online Education<br>First Semester PGCP/MSc Business Analytics</div>
    <input type="text" id="collegeId" placeholder="College ID (e.g., STU001)">
    <input type="password" id="password" placeholder="Password">
    <button onclick="doLogin()">Login to Exam</button>
    <div class="demo-info">
      <b>Demo Credentials:</b><br>
      Student: <code>STU001</code> / <code>pass123</code><br>
      Admin: <code>ADMIN</code> / <code>admin123</code>
    </div>
  </div>
</div>

<!-- INSTRUCTIONS -->
<div id="instrScreen" class="hidden">
  <div class="exam-header">
    <div class="logo">🎓 Business Statistics - End Term Examination</div>
    <div class="user-info" id="userInfo1"></div>
  </div>
  <div class="instr-wrap">
    <h2>📋 General Instructions</h2>
    <div class="attempt-info" id="attemptInfo"></div>
    <ol>
      <li>Total duration: <b>2 hours 30 minutes</b>.</li>
      <li><b>Part A:</b> 20 MCQs (1 mark) + 10 MSQs (2 marks) = <b>40 marks</b>.</li>
      <li><b>Part B:</b> 3 Descriptive questions (10 marks each) = <b>30 marks</b>.</li>
      <li>Total: <b>70 marks</b>. Complete Part A first → Part B unlocks.</li>
      <li>MSQ: 2 or 4 correct options. <b>Any wrong option = 0 marks</b>.</li>
      <li>Questions distributed across <b>6 syllabus segments</b>.</li>
      <li>⚠️ <b>Each attempt generates a NEW shuffled paper</b> from the question bank.</li>
      <li>Timer starts on "I am ready to begin". Auto-submits at 00:00.</li>
      <li>Answers auto-saved. Do not refresh.</li>
    </ol>
    <div class="warn-box">⚠️ Copy/paste, right-click, and developer tools are disabled during the exam.</div>
    <div class="agree">
      <label><input type="checkbox" id="agreeCheck" onchange="toggleStartBtn()">
        I have read and understood all instructions.</label>
    </div>
    <button class="btn-primary" id="startBtn" disabled onclick="startExam()">
      I am ready to begin →
    </button>
  </div>
</div>

<!-- EXAM -->
<div id="examScreen" class="hidden">
  <div class="exam-header">
    <div class="logo">🎓 Business Statistics <span id="attemptBadge" style="font-size:12px;opacity:.8;"></span></div>
    <div class="timer" id="timer">02:30:00</div>
    <div class="user-info" id="userInfo2"></div>
  </div>
  <div class="exam-body">
    <div class="question-area" id="questionArea"></div>
    <div class="palette">
      <h3 id="paletteTitle">Part A - Question Palette</h3>
      <div class="palette-grid" id="paletteGrid"></div>
      <div class="legend">
        <div><span class="dot" style="background:#fff"></span>Not Visited</div>
        <div><span class="dot" style="background:#bbdefb"></span>Current</div>
        <div><span class="dot" style="background:#4caf50"></span>Answered</div>
        <div><span class="dot" style="background:#ff9800"></span>Marked</div>
      </div>
      <div class="submit-section">
        <button onclick="confirmSubmit()" id="submitBtn">Submit Part A</button>
      </div>
    </div>
  </div>
</div>

<!-- RESULT -->
<div id="resultScreen" class="hidden">
  <div class="exam-header">
    <div class="logo">🎓 Examination Completed</div>
    <div class="user-info" id="userInfo3"></div>
  </div>
  <div class="result-wrap" id="resultContent"></div>
</div>

<!-- ADMIN -->
<div id="adminScreen" class="hidden">
  <div class="exam-header">
    <div class="logo">🎓 Admin Panel</div>
    <button class="btn-danger" onclick="logout()">Logout</button>
  </div>
  <div class="admin-wrap">
    <div class="admin-tabs">
      <button class="active" onclick="showAdminTab('submissions',this)">📊 Student Submissions</button>
      <button onclick="showAdminTab('mcq',this)">MCQ Bank</button>
      <button onclick="showAdminTab('msq',this)">MSQ Bank</button>
      <button onclick="showAdminTab('desc',this)">Descriptive Bank</button>
      <button onclick="showAdminTab('bulk',this)">📥 Bulk Import</button>
      <button onclick="showAdminTab('syllabus',this)">Syllabus</button>
      <button onclick="showAdminTab('config',this)">Config</button>
    </div>
    <div class="admin-panel" id="adminPanel"></div>
  </div>
</div>

<div id="modal" class="modal-bg hidden">
  <div class="modal" id="modalContent"></div>
</div>

<script>
/* ============ STORAGE ============ */
const DEFAULT_USERS = { STU001:'pass123', STU002:'pass123', ADMIN:'admin123' };

const DEFAULT_SYLLABUS = [
  {id:1, name:"Segment 1: Descriptive Statistics", topics:"Measures of central tendency, variation, data types, scales"},
  {id:2, name:"Segment 2: Probability and Uncertainty", topics:"Addition/multiplication theorem, conditional probability, Bayes' theorem"},
  {id:3, name:"Segment 3: Probability Distributions", topics:"Random variables, PMF/PDF, Binomial, Normal, Poisson, Exponential"},
  {id:4, name:"Segment 4: Sampling and Estimation", topics:"Sampling techniques, CLT, Confidence intervals"},
  {id:5, name:"Segment 5: Hypothesis Testing", topics:"Null/alternative, Type I/II errors, z-test, t-test"},
  {id:6, name:"Segment 6: Correlation & Regression", topics:"Karl Pearson, SLR, R-square, Least squares"}
];

const DEFAULT_MCQ = [
  {id:'m1', seg:1, q:"Which is NOT a measure of variation?", opts:["Range","Variance","Mean","Standard deviation"], ans:2},
  {id:'m2', seg:1, q:"Which scale has a true zero?", opts:["Nominal","Ordinal","Interval","Ratio"], ans:3},
  {id:'m3', seg:1, q:"The most frequent value is:", opts:["Mean","Median","Mode","Range"], ans:2},
  {id:'m4', seg:1, q:"Least affected by extreme values?", opts:["Mean","Variance","Median","Standard deviation"], ans:2},
  {id:'m5', seg:1, q:"Example of qualitative data?", opts:["Age","Salary","Blood Group","Temperature"], ans:2},
  {id:'m6', seg:1, q:"Number of students in a class is:", opts:["Continuous","Qualitative","Discrete","Ratio only"], ans:2},
  {id:'m7', seg:2, q:"In binomial, p denotes:", opts:["Mean","Prob of failure","No. of obs","Prob of success"], ans:3},
  {id:'m8', seg:2, q:"P(A|B) is defined as:", opts:["P(A)+P(B)","P(A∩B)/P(B)","P(A)×P(B)","P(A)-P(B)"], ans:1},
  {id:'m9', seg:2, q:"If independent, then:", opts:["P(A|B)=0","P(A|B)=P(A)","P(A|B)=1","P(A|B)=P(B)"], ans:1},
  {id:'m10', seg:2, q:"Independent events mean:", opts:["One doesn't affect other","One guarantees other","No common outcomes","Same probability"], ans:0},
  {id:'m11', seg:2, q:"Probability of event lies between:", opts:["-1 and 1","0 and 100","0 and 1","-∞ and +∞"], ans:2},
  {id:'m12', seg:2, q:"Bayes' theorem is used to:", opts:["Find complements","Update probabilities with new info","Find sample spaces","Calculate averages"], ans:1},
  {id:'m13', seg:3, q:"Range of normal distribution values:", opts:["<0",">0","-∞ to +∞","-1 to 1"], ans:2},
  {id:'m14', seg:3, q:"Distribution for arrivals/hour:", opts:["Normal","Exponential","Poisson","Uniform"], ans:2},
  {id:'m15', seg:3, q:"Exponential models:", opts:["No. of defects","Waiting time","No. of successes","Heights"], ans:1},
  {id:'m16', seg:3, q:"Normal determined by:", opts:["λ","n and p","Mean & SD","Median & mode"], ans:2},
  {id:'m17', seg:3, q:"Discrete random variable example:", opts:["Rainfall","Time","Defective products","Weight"], ans:2},
  {id:'m18', seg:3, q:"For continuous RV, P(X=x)=", opts:["1","0","0.5","Undetermined"], ans:1},
  {id:'m19', seg:4, q:"Sampling frame is:", opts:["List of population","List of sample","Subset","Same as population"], ans:0},
  {id:'m20', seg:4, q:"CLT says sampling dist of mean:", opts:["Uniform","Approx normal for large n","Binomial","Exponential"], ans:1},
  {id:'m21', seg:4, q:"Standard error of mean:", opts:["σ×n","σ/√n","σ/n","√σ"], ans:1},
  {id:'m22', seg:4, q:"If n increases 100→400, SE:", opts:["4x larger","2x larger","Half","Unchanged"], ans:2},
  {id:'m23', seg:4, q:"Parameter describes:", opts:["Sample","Population","Statistic","Subset"], ans:1},
  {id:'m24', seg:5, q:"Prob of rejecting true H0:", opts:["Confidence level","Level of significance","Power","SE"], ans:1},
  {id:'m25', seg:5, q:"If α=0.05, confidence level:", opts:["90%","95%","99%","5%"], ans:1},
  {id:'m26', seg:5, q:"Large-sample z-test, σ unknown, use:", opts:["Median","Sample SD","Pop mean","Range"], ans:1},
  {id:'m27', seg:5, q:"Null hypothesis is:", opts:["Researcher's claim","Assumed true until evidence","Sample estimate","Always rejected"], ans:1},
  {id:'m28', seg:5, q:"H1: μ<24 is which test?", opts:["Right-tailed","Two-tailed","Left-tailed","F-test"], ans:2},
  {id:'m29', seg:6, q:"ŷ=120+8x, slope 8 means:", opts:["Sales decrease 8/unit","Sales increase 8/unit","Exp increases 8","Sales=8 when x=0"], ans:1},
  {id:'m30', seg:6, q:"R²=0.84 means:", opts:["IV explains 84% variation","84% accuracy","Slope=0.84","Unexplained=84%"], ans:0},
  {id:'m31', seg:6, q:"Difference observed-predicted:", opts:["Intercept","R²","Residual","SD of x"], ans:2},
  {id:'m32', seg:6, q:"Least squares minimizes:", opts:["Total residuals","Sum of squared residuals","Slope","Intercept"], ans:1},
  {id:'m33', seg:6, q:"ŷ=250+15x, x=20 → ŷ=?", opts:["270","300","550","5000"], ans:2},
  {id:'m34', seg:1, q:"Histogram is used for:", opts:["Categorical","Continuous numerical","Ranking","Nominal"], ans:1},
  {id:'m35', seg:2, q:"Sample space for die roll:", opts:["{1,2,3,4,5}","{0..5}","{1,2,3,4,5,6}","{2,4,6}"], ans:2},
  {id:'m36', seg:3, q:"If Var(X)=9, SD(X)=", opts:["81","3","4.5","18"], ans:1},
  {id:'m37', seg:4, q:"Stratified sampling divides population into:", opts:["Clusters","Homogeneous strata","Random groups","Pairs"], ans:1},
  {id:'m38', seg:5, q:"Type II error is:", opts:["True H0 rejected","False H0 accepted","False negative","Both B and C"], ans:3},
  {id:'m39', seg:6, q:"Multiple regression equation ŷ=40+3x1+5x2, 3 means:", opts:["y↑3 when x1↑1 (x2 const)","y↑3 when both ↑","x1↑3 when y↑","y=3 when x2=0"], ans:0},
  {id:'m40', seg:1, q:"Data arranged by years is:", opts:["Geographical","Qualitative","Quantitative","Chronological"], ans:3}
];

const DEFAULT_MSQ = [
  {id:'s1', seg:1, q:"Which are ratio scale data?", opts:["Weight","Distance","Temp(°C)","Age","No. of books"], ans:[0,1,3,4]},
  {id:'s2', seg:1, q:"Measures of dispersion:", opts:["Range","Variance","SD","Mean","CV"], ans:[0,1,2,4]},
  {id:'s3', seg:1, q:"Quantitative data examples:", opts:["Salary","Height","Blood Group","Temperature","Religion"], ans:[0,1,3]},
  {id:'s4', seg:1, q:"Median preferred over mean when:", opts:["Outliers","Skewed","Ordinal","All equal","Extreme values"], ans:[0,1,2,4]},
  {id:'s5', seg:2, q:"Conditional probability correct:", opts:["P(A|B)=P(A∩B)/P(B) if P(B)≠0","Uses additional info","Written P(A|B)","Computable if P(B)=0"], ans:[0,1,2]},
  {id:'s6', seg:2, q:"Bayes' theorem applications:", opts:["Medical diagnosis","Spam detection","Fraud detection","Updating probabilities"], ans:[0,1,2,3]},
  {id:'s7', seg:2, q:"Random experiments:", opts:["Tossing coin","Rolling die","Drawing card","25×4 calculation"], ans:[0,1,2]},
  {id:'s8', seg:2, q:"Independent events indicators:", opts:["P(B|A)=P(B)","P(A∩B)=P(A)P(B)","One affects other","Successive coin tosses"], ans:[0,1,3]},
  {id:'s9', seg:3, q:"Normal distribution characteristics:", opts:["Symmetric","Mean=Median=Mode","Bell-shaped","Positively skewed"], ans:[0,1,2]},
  {id:'s10', seg:3, q:"Discrete distributions:", opts:["Binomial","Poisson","Normal","Exponential"], ans:[0,1]},
  {id:'s11', seg:3, q:"Discrete random variables:", opts:["No. of customers","Product weight","Defective products","Emails received"], ans:[0,2,3]},
  {id:'s12', seg:3, q:"Binomial assumptions:", opts:["Fixed trials","Independent","Constant p","Infinite outcomes"], ans:[0,1,2]},
  {id:'s13', seg:4, q:"Sampling true statements:", opts:["Sample is representative","Population=all members","Frame lists all members","Sample must include all"], ans:[0,1,2]},
  {id:'s14', seg:4, q:"CLT correct statements:", opts:["Sampling dist → normal","Larger n improves approx","Applies to sample means","Pop must be normal"], ans:[0,1,2]},
  {id:'s15', seg:4, q:"SRS characteristics:", opts:["Equal probability","Based on chance","Judgement influences","Random tables used","Unknown probs","Probability sampling"], ans:[0,1,3,5]},
  {id:'s16', seg:5, q:"Type I & II errors correct:", opts:["Type I: true H0 rejected","Type II: false H0 accepted","Type I=false negative","Type II reduced by larger n"], ans:[0,1,3]},
  {id:'s17', seg:5, q:"Hypothesis testing steps:", opts:["Formulate hypotheses","Choose α","Compute test stat","Compare with critical value"], ans:[0,1,2,3]},
  {id:'s18', seg:5, q:"Statistical hypotheses examples:", opts:["Avg salary=₹60k","70% prefer Brand A","Best food in city","Defect rate<2%","Satisfaction excellent","Avg delivery=48h"], ans:[0,1,3,5]},
  {id:'s19', seg:6, q:"Least squares correct:", opts:["Minimizes SSE","Residuals eᵢ=yᵢ-ŷᵢ","Line of best fit","Minimizes squared residuals"], ans:[0,1,2,3]},
  {id:'s20', seg:6, q:"SLRM true statements:", opts:["One DV","One IV","Straight line","Quantifies relationship"], ans:[0,1,2,3]},
  {id:'s21', seg:6, q:"R² correct statements:", opts:["Value 0 to 1","Proportion of variation explained","Higher=better fit","R²=0.90 → 90% explained"], ans:[0,1,2,3]},
  {id:'s22', seg:6, q:"Multiple regression correct:", opts:["One DV, 2+ IVs","Each coeff holds others const","Uses least squares","Can use Excel"], ans:[0,1,2,3]}
];

const DEFAULT_DESC = [
  {id:'d1', seg:1, q:"Probability distribution for y:\ny: 1, 5, 9, 0\nf(y): 0.1, 0.2, 0.1, 0.6\n(a) Compute E(y). [5]\n(b) Compute Var(y) and σ. [5]",
   model:"E(y)=1(0.1)+5(0.2)+9(0.1)+0(0.6)=2.0\nE(y²)=13.2\nVar(y)=13.2-4=9.2\nσ=√9.2≈3.03"},
  {id:'d2', seg:5, q:"Tyre company claims mean life 50,000 km. Sample 250: x̄=48,500, s=3,500. Normal.\n(a) Formulate H0, H1. Define Type I/II errors with consequences. [5]\n(b) At 1% significance, conduct test, show test statistic, critical region, interpret. [5]",
   model:"H₀: μ=50000, H₁: μ≠50000\nType I: Concluding mean≠50000 when it is → reputation damage\nType II: Concluding mean=50000 when it isn't → selling substandard tyres\nz=(48500-50000)/(3500/√250)=-2.26\nCritical ±2.576. |z|<2.576 → Fail to reject H₀"},
  {id:'d3', seg:6, q:"Regression: ŷ=120+15x (x=advertising ₹ lakh, y=sales ₹ lakh)\n(a) Explain SLR, distinguish DV vs IV with business example. [6]\n(b) Estimate sales when advertising=₹18 lakh. Interpret slope. [4]",
   model:"SLR models linear relationship between one DV and one IV.\nDV=sales, IV=advertising.\nŷ=120+15(18)=390 lakh. Slope 15: each ₹1 lakh ↑ in advertising → ₹15 lakh ↑ in expected sales."},
  {id:'d4', seg:4, q:"(a) Define sampling. Explain 3 needs with business examples. [6]\n(b) σ=12 min, n=64, x̄=42 min. Construct 95% CI for mean. (Z=1.96) [4]",
   model:"Sampling: selecting subset from population.\nNeeds: cost-effective, time-saving, practical.\nSE=12/√64=1.5\nME=1.96×1.5=2.94\nCI: 42±2.94 = (39.06, 44.94)"},
  {id:'d5', seg:5, q:"Water company claims 1 litre/bottle. Sample 64: x̄=990ml, s=40ml.\n(a) Define hypothesis testing, statistical hypothesis. Importance in business with example. [6]\n(b) Test at 5% significance (two-tailed, ±1.96). [4]",
   model:"Hypothesis testing: evaluating claims about population using sample data.\nH₀: μ=1000, H₁: μ≠1000\nz=(990-1000)/(40/8)=-2.00\n|-2.00|>1.96 → Reject H₀. Avg volume significantly different from 1000ml."},
  {id:'d6', seg:2, q:"Urn: 4 red, 7 blue. Two balls drawn without replacement.\n(a) Define random experiment, sample space, event. [4]\n(b) Find P(both red). [6]",
   model:"Random experiment: outcomes known, exact outcome uncertain.\nSample space: set of all outcomes.\nEvent: subset of sample space.\nP(both red)=(4/11)×(3/10)=12/110=6/55"}
];

const DEFAULT_CONFIG = {
  duration:150, mcqPerSeg:[4,4,4,3,3,2], msqPerSeg:[2,2,2,1,2,1],
  descCount:3, mcqMarks:1, msqMarks:2, descMarks:10
};

function load(k,def){ try{const v=localStorage.getItem('exam_'+k); return v?JSON.parse(v):def;}catch(e){return def;} }
function save(k,v){ localStorage.setItem('exam_'+k, JSON.stringify(v)); }

let state = {
  mcq: load('mcq', DEFAULT_MCQ),
  msq: load('msq', DEFAULT_MSQ),
  desc: load('desc', DEFAULT_DESC),
  syllabus: load('syllabus', DEFAULT_SYLLABUS),
  config: load('config', DEFAULT_CONFIG),
  users: load('users', DEFAULT_USERS),
  submissions: load('submissions', []),
  attempts: load('attempts', {}) // {STU001: 2}
};

/* ============ AUTH ============ */
function doLogin(){
  const id=document.getElementById('collegeId').value.trim().toUpperCase();
  const pw=document.getElementById('password').value;
  if(!id||!pw){ alert('Enter College ID and Password'); return; }
  if(id==='ADMIN' && pw==='admin123'){ showAdmin(); return; }
  if(state.users[id]===pw){
    sessionStorage.setItem('user', id);
    document.getElementById('loginScreen').classList.add('hidden');
    document.getElementById('instrScreen').classList.remove('hidden');
    document.getElementById('userInfo1').textContent='Welcome, '+id;
    const attemptNo=(state.attempts[id]||0)+1;
    document.getElementById('attemptInfo').innerHTML=
      `📝 <b>Attempt #${attemptNo}</b> — A new shuffled question paper will be generated for you. Each attempt has different questions in different order.`;
  } else { alert('Invalid credentials'); }
}
function logout(){ sessionStorage.clear(); location.reload(); }
function toggleStartBtn(){
  document.getElementById('startBtn').disabled=!document.getElementById('agreeCheck').checked;
}

/* ============ SHUFFLE HELPERS ============ */
function shuffle(a){ for(let i=a.length-1;i>0;i--){ const j=Math.floor(Math.random()*(i+1)); [a[i],a[j]]=[a[j],a[i]]; } return a; }

function shuffleOptions(q){
  // Create index mapping
  const opts=q.opts.map((o,i)=>({o,i}));
  shuffle(opts);
  const newOpts=opts.map(x=>x.o);
  const newAns = Array.isArray(q.ans)
    ? q.ans.map(a=>opts.findIndex(x=>x.i===a))
    : opts.findIndex(x=>x.i===q.ans);
  return {...q, opts:newOpts, ans:newAns};
}

/* ============ EXAM ENGINE ============ */
let exam = {
  part:'A', current:0,
  partA:[], partB:[],
  answers:{}, marked:{},
  timeLeft:0, timerId:null,
  startTime:null, attemptNo:0
};

function buildPaper(){
  const mcq=[], msq=[];
  for(let s=1;s<=6;s++){
    const need=state.config.mcqPerSeg[s-1]||3;
    const pool=state.mcq.filter(q=>q.seg===s).map(shuffleOptions);
    shuffle(pool);
    mcq.push(...pool.slice(0,need).map(q=>({...q,type:'mcq'})));
    const needM=state.config.msqPerSeg[s-1]||1;
    const poolM=state.msq.filter(q=>q.seg===s).map(shuffleOptions);
    shuffle(poolM);
    msq.push(...poolM.slice(0,needM).map(q=>({...q,type:'msq'})));
  }
  // Pad if needed
  while(mcq.length<20){ const q=shuffleOptions(state.mcq[mcq.length%state.mcq.length]); mcq.push({...q,type:'mcq'}); }
  while(msq.length<10){ const q=shuffleOptions(state.msq[msq.length%state.msq.length]); msq.push({...q,type:'msq'}); }
  shuffle(mcq); shuffle(msq);
  exam.partA = mcq.slice(0,20).concat(msq.slice(0,10));
  const d=[...state.desc]; shuffle(d);
  exam.partB = d.slice(0,state.config.descCount).map(q=>({...q,type:'desc'}));
}

function startExam(){
  const uid=sessionStorage.getItem('user');
  exam.attemptNo=(state.attempts[uid]||0)+1;
  state.attempts[uid]=exam.attemptNo;
  save('attempts', state.attempts);

  exam.startTime=Date.now();
  exam.timeLeft=state.config.duration*60;
  buildPaper();
  document.getElementById('instrScreen').classList.add('hidden');
  document.getElementById('examScreen').classList.remove('hidden');
  document.getElementById('userInfo2').textContent='User: '+uid;
  document.getElementById('attemptBadge').textContent=`(Attempt #${exam.attemptNo})`;
  startTimer();
  renderQuestion();
  renderPalette();
}

function currentList(){ return exam.part==='A'?exam.partA:exam.partB; }

function renderQuestion(){
  const list=currentList();
  const q=list[exam.current];
  const area=document.getElementById('questionArea');
  const marks = q.type==='mcq'?state.config.mcqMarks : q.type==='msq'?state.config.msqMarks : state.config.descMarks;
  let html=`<div class="q-head">
    <span class="q-num">Q${exam.current+1} of ${list.length} | ${q.type.toUpperCase()} | ${state.syllabus[q.seg-1].name}</span>
    <span class="q-marks">${marks} Mark${marks>1?'s':''}</span>
  </div>
  <div class="q-text"><b>Q${exam.current+1}.</b> ${escapeHtml(q.q)}</div>`;

  if(q.type==='mcq'){
    const cur=exam.answers[exam.part+'_'+exam.current];
    q.opts.forEach((o,i)=>{
      html+=`<label class="option ${cur===i?'selected':''}" onclick="selectMCQ(${i})">
        <input type="radio" name="opt" ${cur===i?'checked':''}> ${String.fromCharCode(65+i)}. ${escapeHtml(o)}</label>`;
    });
  } else if(q.type==='msq'){
    const cur=exam.answers[exam.part+'_'+exam.current]||[];
    html+=`<div style="color:#d32f2f;font-size:13px;margin-bottom:10px;">⚠️ Multiple correct options. Any wrong option = 0 marks.</div>`;
    q.opts.forEach((o,i)=>{
      html+=`<label class="option ${cur.includes(i)?'selected':''}" onclick="toggleMSQ(${i})">
        <input type="checkbox" ${cur.includes(i)?'checked':''}> ${String.fromCharCode(65+i)}. ${escapeHtml(o)}</label>`;
    });
  } else {
    const cur=exam.answers[exam.part+'_'+exam.current]||'';
    html+=`<div class="desc-area">
      <textarea id="descAns" oninput="saveDesc()" placeholder="Type your answer...">${escapeHtml(cur)}</textarea>
      <div class="word-count" id="wc">Words: 0</div>
    </div>`;
  }

  html+=`<div class="q-actions">
    <div>
      <button class="btn-mark" onclick="markReview()">🚩 Mark for Review</button>
      <button class="btn-clear" onclick="clearAns()">Clear</button>
    </div>
    <div>
      ${exam.current>0?'<button class="btn-nav" onclick="nav(-1)">← Previous</button>':''}
      ${exam.current<list.length-1?'<button class="btn-nav" onclick="nav(1)">Next →</button>':''}
    </div>
  </div>`;
  area.innerHTML=html;
  if(q.type==='desc') updateWC();
}

function escapeHtml(s){ return (s||'').replace(/[&<>"]/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[c])); }

function selectMCQ(i){ exam.answers[exam.part+'_'+exam.current]=i; saveState(); renderQuestion(); renderPalette(); }
function toggleMSQ(i){
  const k=exam.part+'_'+exam.current;
  let cur=exam.answers[k]||[];
  if(cur.includes(i)) cur=cur.filter(x=>x!==i); else cur.push(i);
  exam.answers[k]=cur; saveState(); renderQuestion(); renderPalette();
}
function saveDesc(){ exam.answers[exam.part+'_'+exam.current]=document.getElementById('descAns').value; saveState(); updateWC(); renderPalette(); }
function updateWC(){ const t=document.getElementById('descAns')?.value||''; const w=t.trim()?t.trim().split(/\s+/).length:0; const el=document.getElementById('wc'); if(el) el.textContent='Words: '+w; }
function markReview(){ exam.marked[exam.part+'_'+exam.current]=true; saveState(); renderPalette(); }
function clearAns(){ delete exam.answers[exam.part+'_'+exam.current]; delete exam.marked[exam.part+'_'+exam.current]; saveState(); renderQuestion(); renderPalette(); }
function nav(d){ exam.current+=d; renderQuestion(); renderPalette(); }
function goTo(i){ exam.current=i; renderQuestion(); renderPalette(); }

function renderPalette(){
  const list=currentList();
  document.getElementById('paletteTitle').textContent=(exam.part==='A'?'Part A':'Part B')+' - Palette';
  const g=document.getElementById('paletteGrid'); g.innerHTML='';
  list.forEach((q,i)=>{
    const k=exam.part+'_'+i;
    let cls='p-btn';
    if(i===exam.current) cls+=' current';
    const answered = q.type==='desc' ? (exam.answers[k]&&exam.answers[k].trim().length>0)
                   : (exam.answers[k]!==undefined && (Array.isArray(exam.answers[k])?exam.answers[k].length>0:true));
    if(answered) cls+=' answered';
    if(exam.marked[k]) cls+=' marked';
    const b=document.createElement('button');
    b.className=cls; b.textContent=i+1; b.onclick=()=>goTo(i);
    g.appendChild(b);
  });
  document.getElementById('submitBtn').textContent = exam.part==='A'?'Submit Part A →':'Submit Exam';
}

function saveState(){
  localStorage.setItem('exam_state', JSON.stringify({
    answers:exam.answers, marked:exam.marked, part:exam.part,
    current:exam.current, timeLeft:exam.timeLeft, startTime:exam.startTime,
    attemptNo:exam.attemptNo
  }));
}

function startTimer(){
  updateTimerDisplay();
  exam.timerId=setInterval(()=>{
    exam.timeLeft--;
    updateTimerDisplay();
    if(exam.timeLeft%30===0) saveState();
    if(exam.timeLeft<=0){ clearInterval(exam.timerId); autoSubmit(); }
  },1000);
}
function updateTimerDisplay(){
  const h=Math.floor(exam.timeLeft/3600);
  const m=Math.floor((exam.timeLeft%3600)/60);
  const s=exam.timeLeft%60;
  const el=document.getElementById('timer');
  el.textContent=`${String(h).padStart(2,'0')}:${String(m).padStart(2,'0')}:${String(s).padStart(2,'0')}`;
  el.classList.toggle('warn', exam.timeLeft<300);
}

function confirmSubmit(){
  const list=currentList();
  let answered=0, marked=0;
  list.forEach((q,i)=>{
    const k=exam.part+'_'+i;
    const a=exam.answers[k];
    const ok = q.type==='desc' ? (a&&a.trim().length>0)
             : (a!==undefined && (Array.isArray(a)?a.length>0:true));
    if(ok) answered++;
    if(exam.marked[k]) marked++;
  });
  showModal(`
    <h2>${exam.part==='A'?'Submit Part A?':'Submit Exam?'}</h2>
    <div class="stats">
      <div class="stat"><div class="v">${answered}/${list.length}</div><div class="l">Answered</div></div>
      <div class="stat"><div class="v">${list.length-answered}</div><div class="l">Unanswered</div></div>
      <div class="stat"><div class="v">${marked}</div><div class="l">Marked for Review</div></div>
      <div class="stat"><div class="v">${formatTime(exam.timeLeft)}</div><div class="l">Time Left</div></div>
    </div>
    ${exam.part==='A'?'<p style="color:#d32f2f;font-size:13px;">⚠️ After submitting Part A, you cannot go back.</p>':''}
    <div class="modal-btns">
      <button class="btn-primary" onclick="closeModal()">Cancel</button>
      <button class="btn-danger" onclick="doSubmit()">${exam.part==='A'?'Submit Part A':'Submit Exam'}</button>
    </div>
  `);
}
function formatTime(s){ return `${Math.floor(s/3600)}h ${Math.floor((s%3600)/60)}m`; }

function doSubmit(){
  closeModal();
  if(exam.part==='A'){
    exam.part='B'; exam.current=0;
    renderQuestion(); renderPalette();
    alert('✅ Part A submitted. Part B is now open.');
  } else { finishExam(); }
  saveState();
}
function autoSubmit(){ alert('⏰ Time up! Auto-submitting.'); finishExam(); }

function finishExam(){
  clearInterval(exam.timerId);
  let mcqScore=0, msqScore=0, descScore=0;
  const partARecord=[], partBRecord=[];

  exam.partA.forEach((q,i)=>{
    const a=exam.answers['A_'+i];
    let studentAns, correctAns, isCorrect=false;
    if(q.type==='mcq'){
      studentAns = a!==undefined ? q.opts[a] : 'Not answered';
      correctAns = q.opts[q.ans];
      if(a===q.ans){ mcqScore+=state.config.mcqMarks; isCorrect=true; }
    } else {
      studentAns = Array.isArray(a)&&a.length ? a.map(x=>q.opts[x]).join(', ') : 'Not answered';
      correctAns = q.ans.map(x=>q.opts[x]).join(', ');
      if(Array.isArray(a) && a.length>0){
        const wrong=a.some(x=>!q.ans.includes(x));
        const allCorrect=q.ans.every(x=>a.includes(x)) && a.length===q.ans.length;
        if(!wrong && allCorrect){ msqScore+=state.config.msqMarks; isCorrect=true; }
      }
    }
    partARecord.push({qNo:i+1, type:q.type, seg:q.seg, q:q.q, studentAns, correctAns, isCorrect});
  });

  exam.partB.forEach((q,i)=>{
    const ans=(exam.answers['B_'+i]||'');
    const model=(q.model||'');
    const keywords=(model.toLowerCase().match(/\b[a-z0-9]{4,}\b/g)||[]);
    const matched=keywords.filter(k=>ans.toLowerCase().includes(k)).length;
    const ratio=keywords.length?matched/keywords.length:0;
    const score=Math.round(ratio*state.config.descMarks);
    descScore+=score;
    partBRecord.push({qNo:i+1, seg:q.seg, q:q.q, studentAns:ans, modelAns:model, score});
  });

  const total=mcqScore+msqScore+descScore;
  const timeTaken=state.config.duration*60-exam.timeLeft;
  const uid=sessionStorage.getItem('user');

  const submission = {
    id: 'sub_'+Date.now(),
    studentId: uid,
    attemptNo: exam.attemptNo,
    timestamp: new Date().toISOString(),
    partA: partARecord,
    partB: partBRecord,
    scores: {mcq:mcqScore, msq:msqScore, desc:descScore, total},
    timeTaken,
    paper: {partA:exam.partA, partB:exam.partB}
  };
  state.submissions.push(submission);
  save('submissions', state.submissions);

  showResult(mcqScore, msqScore, descScore, total, timeTaken, partARecord, partBRecord);
}

function showResult(mcq, msq, desc, total, timeTaken, partA, partB){
  document.getElementById('examScreen').classList.add('hidden');
  document.getElementById('resultScreen').classList.remove('hidden');
  document.getElementById('userInfo3').textContent='User: '+sessionStorage.getItem('user');
  document.getElementById('resultContent').innerHTML=`
    <h2>🎉 Examination Completed (Attempt #${exam.attemptNo})</h2>
    <div class="score-card">
      <div class="lbl">Total Score</div>
      <div class="big">${total} / 70</div>
      <div class="lbl">${((total/70)*100).toFixed(1)}% | Time: ${Math.floor(timeTaken/60)}m ${timeTaken%60}s</div>
    </div>
    <div class="breakdown">
      <div class="card"><div class="n">${mcq}/20</div><div>MCQ</div></div>
      <div class="card"><div class="n">${msq}/20</div><div>MSQ</div></div>
      <div class="card"><div class="n">${desc}/30</div><div>Descriptive</div></div>
    </div>
    <div style="text-align:center;margin-top:20px; display:flex; gap:10px; justify-content:center; flex-wrap:wrap;">
      <button class="btn-success" onclick="retakeExam()">🔁 Retake Exam (New Paper)</button>
      <button class="btn-primary" onclick="logout()">Back to Login</button>
    </div>
    <details style="margin-top:25px;">
      <summary style="cursor:pointer;font-weight:bold;color:#1e3c72;padding:10px;background:#f5f5f5;border-radius:6px;">📝 View Your Answers</summary>
      <div style="padding:15px;">
        <h3 style="margin:15px 0 10px;color:#1e3c72;">Part A</h3>
        ${partA.map(r=>`<div class="q-item" style="border-left-color:${r.isCorrect?'#4caf50':'#d32f2f'}">
          <b>Q${r.qNo} (${r.type.toUpperCase()}):</b> ${escapeHtml(r.q)}<br>
          <small>Your: ${escapeHtml(r.studentAns)}<br>Correct: ${escapeHtml(r.correctAns)}</small></div>`).join('')}
        <h3 style="margin:15px 0 10px;color:#1e3c72;">Part B</h3>
        ${partB.map(r=>`<div class="q-item">
          <b>Q${r.qNo} (${r.score}/10):</b> ${escapeHtml(r.q).slice(0,100)}...<br>
          <small>Your answer: ${escapeHtml(r.studentAns).slice(0,200)}</small></div>`).join('')}
      </div>
    </details>
  `;
}

function retakeExam(){
  if(!confirm('Start a new attempt with a freshly shuffled paper?')) return;
  exam={part:'A', current:0, partA:[], partB:[], answers:{}, marked:{}, timeLeft:0, timerId:null, startTime:null, attemptNo:0};
  document.getElementById('resultScreen').classList.add('hidden');
  document.getElementById('instrScreen').classList.remove('hidden');
  document.getElementById('agreeCheck').checked=false;
  document.getElementById('startBtn').disabled=true;
  const uid=sessionStorage.getItem('user');
  const attemptNo=(state.attempts[uid]||0)+1;
  document.getElementById('attemptInfo').innerHTML=
    `📝 <b>Attempt #${attemptNo}</b> — A new shuffled question paper will be generated.`;
}

function showModal(html){ document.getElementById('modalContent').innerHTML=html; document.getElementById('modal').classList.remove('hidden'); }
function closeModal(){ document.getElementById('modal').classList.add('hidden'); }

/* ============ ADMIN ============ */
function showAdmin(){
  document.getElementById('loginScreen').classList.add('hidden');
  document.getElementById('adminScreen').classList.remove('hidden');
  showAdminTab('submissions', document.querySelector('.admin-tabs button'));
}

function showAdminTab(tab, btn){
  document.querySelectorAll('.admin-tabs button').forEach(b=>b.classList.remove('active'));
  btn.classList.add('active');
  const p=document.getElementById('adminPanel');

  if(tab==='submissions'){
    renderSubmissionsDashboard(p);
  } else if(tab==='mcq'){
    p.innerHTML=`<h3>MCQ Bank (${state.mcq.length} questions)</h3>
      <select id="mcqSeg">${state.syllabus.map(s=>`<option value="${s.id}">${s.name}</option>`).join('')}</select>
      <textarea id="mcqQ" placeholder="Question text"></textarea>
      <textarea id="mcqOpts" placeholder="Options (one per line, 4 options)"></textarea>
      <input id="mcqAns" type="number" min="0" max="3" placeholder="Correct option index (0-3)">
      <button class="btn-primary" onclick="addMCQ()">Add MCQ</button>
      <div class="q-list">${state.mcq.map(q=>`<div class="q-item">
        <button class="del" onclick="delQ('mcq','${q.id}')">Delete</button>
        <b>[Seg ${q.seg}]</b> ${escapeHtml(q.q)}<br><small>Ans: ${q.opts[q.ans]}</small></div>`).join('')}</div>`;
  } else if(tab==='msq'){
    p.innerHTML=`<h3>MSQ Bank (${state.msq.length} questions)</h3>
      <select id="msqSeg">${state.syllabus.map(s=>`<option value="${s.id}">${s.name}</option>`).join('')}</select>
      <textarea id="msqQ" placeholder="Question text"></textarea>
      <textarea id="msqOpts" placeholder="Options (one per line)"></textarea>
      <input id="msqAns" placeholder="Correct indices comma-separated (e.g., 0,1,3)">
      <button class="btn-primary" onclick="addMSQ()">Add MSQ</button>
      <div class="q-list">${state.msq.map(q=>`<div class="q-item">
        <button class="del" onclick="delQ('msq','${q.id}')">Delete</button>
        <b>[Seg ${q.seg}]</b> ${escapeHtml(q.q)}<br><small>Ans: ${q.ans.map(i=>q.opts[i]).join(', ')}</small></div>`).join('')}</div>`;
  } else if(tab==='desc'){
    p.innerHTML=`<h3>Descriptive Bank (${state.desc.length} questions)</h3>
      <select id="descSeg">${state.syllabus.map(s=>`<option value="${s.id}">${s.name}</option>`).join('')}</select>
      <textarea id="descQ" placeholder="Question" style="min-height:150px;"></textarea>
      <textarea id="descModel" placeholder="Model answer" style="min-height:150px;"></textarea>
      <button class="btn-primary" onclick="addDesc()">Add Descriptive</button>
      <div class="q-list">${state.desc.map(q=>`<div class="q-item">
        <button class="del" onclick="delQ('desc','${q.id}')">Delete</button>
        <b>[Seg ${q.seg}]</b> ${escapeHtml(q.q).slice(0,100)}...</div>`).join('')}</div>`;
  } else if(tab==='bulk'){
    p.innerHTML=`<h3>📥 Bulk Import Questions</h3>
      <p style="color:#666;margin-bottom:15px;">Paste multiple questions at once. Format: one question per block, separated by blank lines.</p>
      <h4 style="margin:10px 0;">MCQ Format (one per block):</h4>
      <pre style="background:#f5f5f5;padding:10px;font-size:12px;border-radius:5px;">Q: question text
A: option1
B: option2
C: option3
D: option4
ANS: A
SEG: 1</pre>
      <textarea id="bulkMCQ" placeholder="Paste MCQs here..." style="min-height:200px;"></textarea>
      <button class="btn-primary" onclick="bulkImportMCQ()">Import MCQs</button>
      <hr style="margin:20px 0;">
      <h4 style="margin:10px 0;">MSQ Format:</h4>
      <pre style="background:#f5f5f5;padding:10px;font-size:12px;border-radius:5px;">Q: question text
A: option1
B: option2
C: option3
D: option4
ANS: A,C
SEG: 2</pre>
      <textarea id="bulkMSQ" placeholder="Paste MSQs here..." style="min-height:200px;"></textarea>
      <button class="btn-primary" onclick="bulkImportMSQ()">Import MSQs</button>
      <hr style="margin:20px 0;">
      <h4 style="margin:10px 0;">Import from JSON (full export):</h4>
      <textarea id="bulkJSON" placeholder='Paste JSON from Export button' style="min-height:100px;"></textarea>
      <div style="display:flex;gap:10px;">
        <button class="btn-primary" onclick="importJSON()">Import JSON</button>
        <button class="btn-success" onclick="exportJSON()">📤 Export All Data</button>
      </div>`;
  } else if(tab==='syllabus'){
    p.innerHTML=`<h3>Syllabus Segments</h3>
      ${state.syllabus.map((s,i)=>`<div class="q-item">
        <b>Segment ${s.id}:</b> <input value="${escapeHtml(s.name)}" onchange="updSyl(${i},'name',this.value)" style="width:70%;display:inline-block;">
        <br><textarea onchange="updSyl(${i},'topics',this.value)">${escapeHtml(s.topics)}</textarea></div>`).join('')}
      <button class="btn-primary" onclick="alert('Syllabus saved!')">Save</button>`;
  } else if(tab==='config'){
    const c=state.config;
    p.innerHTML=`<h3>Exam Configuration</h3>
      <label>Duration (minutes): <input type="number" id="cfgDur" value="${c.duration}"></label>
      <label>MCQ per segment (6 values): <input id="cfgMcq" value="${c.mcqPerSeg.join(',')}"></label>
      <label>MSQ per segment (6 values): <input id="cfgMsq" value="${c.msqPerSeg.join(',')}"></label>
      <label>Descriptive count: <input type="number" id="cfgDesc" value="${c.descCount}"></label>
      <label>MCQ marks: <input type="number" id="cfgMcqM" value="${c.mcqMarks}"></label>
      <label>MSQ marks: <input type="number" id="cfgMsqM" value="${c.msqMarks}"></label>
      <label>Descriptive marks: <input type="number" id="cfgDescM" value="${c.descMarks}"></label>
      <br><button class="btn-primary" onclick="saveConfig()">Save</button>
      <hr style="margin:20px 0;">
      <button class="btn-danger" onclick="if(confirm('Reset all data?')){localStorage.clear();location.reload();}">Reset All</button>`;
  }
}

function renderSubmissionsDashboard(p){
  const subs=state.submissions;
  if(subs.length===0){
    p.innerHTML=`<h3>📊 Student Submissions</h3>
      <div style="text-align:center;padding:40px;color:#666;">
        <div style="font-size:50px;">📭</div>
        <p>No submissions yet. Students' exam attempts will appear here.</p>
      </div>`;
    return;
  }

  // Stats
  const totalAttempts=subs.length;
  const uniqueStudents=new Set(subs.map(s=>s.studentId)).size;
  const avgScore=subs.reduce((a,s)=>a+s.scores.total,0)/totalAttempts;
  const bestScore=Math.max(...subs.map(s=>s.scores.total));

  // Per-question analytics
  const qStats={};
  subs.forEach(s=>{
    s.partA.forEach(r=>{
      const key=r.q.slice(0,50);
      if(!qStats[key]) qStats[key]={q:r.q, type:r.type, correct:0, total:0};
      qStats[key].total++;
      if(r.isCorrect) qStats[key].correct++;
    });
  });
  const hardQs=Object.values(qStats).filter(q=>q.total>=3).sort((a,b)=>(a.correct/a.total)-(b.correct/b.total)).slice(0,5);

  let html=`<h3>📊 Student Submissions Dashboard</h3>
    <div class="stats-grid">
      <div class="stats-card"><div class="n">${totalAttempts}</div><div class="l">Total Attempts</div></div>
      <div class="stats-card"><div class="n">${uniqueStudents}</div><div class="l">Unique Students</div></div>
      <div class="stats-card"><div class="n">${avgScore.toFixed(1)}</div><div class="l">Avg Score /70</div></div>
      <div class="stats-card"><div class="n">${bestScore}</div><div class="l">Best Score /70</div></div>
    </div>
    <div class="toolbar">
      <button class="btn-success" onclick="exportCSV()">📤 Export CSV</button>
      <button class="btn-danger" onclick="clearSubmissions()">🗑️ Clear All</button>
      <input type="text" id="searchSub" placeholder="🔍 Search student ID..." oninput="filterSubs()" style="padding:8px;border:1px solid #ccc;border-radius:5px;">
    </div>
    <table class="sub-table" id="subTable">
      <thead><tr>
        <th>Student ID</th><th>Attempt</th><th>Date/Time</th>
        <th>MCQ</th><th>MSQ</th><th>Desc</th><th>Total</th><th>Time</th><th>Action</th>
      </tr></thead>
      <tbody>`;

  subs.slice().reverse().forEach(s=>{
    const d=new Date(s.timestamp);
    const dateStr=d.toLocaleString();
    const timeStr=`${Math.floor(s.timeTaken/60)}m ${s.timeTaken%60}s`;
    const totalCls=s.scores.total<35?'low':'';
    html+=`<tr onclick="toggleSubDetail('${s.id}')" data-sid="${s.studentId.toLowerCase()}">
      <td><b>${s.studentId}</b></td>
      <td>#${s.attemptNo}</td>
      <td>${dateStr}</td>
      <td>${s.scores.mcq}/20</td>
      <td>${s.scores.msq}/20</td>
      <td>${s.scores.desc}/30</td>
      <td class="score ${totalCls}">${s.scores.total}/70</td>
      <td>${timeStr}</td>
      <td><button class="btn-primary" style="padding:4px 10px;font-size:12px;" onclick="event.stopPropagation();toggleSubDetail('${s.id}')">View</button></td>
    </tr>
    <tr id="detail-${s.id}" class="hidden"><td colspan="9">
      <div class="sub-detail">
        <h4 style="color:#1e3c72;margin-bottom:10px;">Part A - MCQ/MSQ Answers</h4>
        ${s.partA.map(r=>`<div class="qa ${r.isCorrect?'correct':'wrong'}">
          <span class="tag ${r.isCorrect?'green':'red'}">${r.isCorrect?'✓ CORRECT':'✗ WRONG'}</span>
          <span class="tag gray">${r.type.toUpperCase()} | Seg ${r.seg}</span>
          <b>Q${r.qNo}:</b> ${escapeHtml(r.q)}<br>
          <small><b>Your answer:</b> ${escapeHtml(r.studentAns)}<br>
          <b>Correct:</b> ${escapeHtml(r.correctAns)}</small>
        </div>`).join('')}
        <h4 style="color:#1e3c72;margin:15px 0 10px;">Part B - Descriptive Answers</h4>
        ${s.partB.map(r=>`<div class="qa">
          <span class="tag gray">Seg ${r.seg} | Score: ${r.score}/10</span>
          <b>Q${r.qNo}:</b> ${escapeHtml(r.q).slice(0,200)}...<br>
          <b>Student's Answer:</b><br>
          <div style="background:#f5f5f5;padding:10px;margin:5px 0;border-radius:4px;white-space:pre-wrap;">${escapeHtml(r.studentAns)||'<i>No answer</i>'}</div>
          <details><summary style="cursor:pointer;color:#1e3c72;">View Model Answer</summary>
            <div style="background:#e8f5e9;padding:10px;margin:5px 0;border-radius:4px;white-space:pre-wrap;">${escapeHtml(r.modelAns)}</div>
          </details>
        </div>`).join('')}
      </div>
    </td></tr>`;
  });

  html+=`</tbody></table>`;

  if(hardQs.length>0){
    html+=`<h3 style="margin-top:25px;color:#1e3c72;">📉 Most Difficult Questions (Lowest Accuracy)</h3>
      ${hardQs.map(q=>{
        const acc=((q.correct/q.total)*100).toFixed(0);
        return `<div class="q-item" style="border-left-color:#d32f2f;">
          <b>[${q.type.toUpperCase()}]</b> ${escapeHtml(q.q)}<br>
          <small>Accuracy: <b style="color:#d32f2f;">${acc}%</b> (${q.correct}/${q.total} correct)</small></div>`;
      }).join('')}`;
  }

  p.innerHTML=html;
}

function toggleSubDetail(id){
  const row=document.getElementById('detail-'+id);
  row.classList.toggle('hidden');
}

function filterSubs(){
  const q=document.getElementById('searchSub').value.toLowerCase();
  document.querySelectorAll('#subTable tbody tr[data-sid]').forEach(tr=>{
    const match=tr.dataset.sid.includes(q);
    tr.style.display=match?'':'none';
    const detail=document.getElementById('detail-'+tr.querySelector('button').getAttribute('onclick').match(/'([^']+)'/)[1]);
    if(!match && detail) detail.classList.add('hidden');
  });
}

function exportCSV(){
  const subs=state.submissions;
  let csv='Student ID,Attempt,Timestamp,MCQ,MSQ,Descriptive,Total,Time(sec)\n';
  subs.forEach(s=>{
    csv+=`${s.studentId},${s.attemptNo},"${new Date(s.timestamp).toLocaleString()}",${s.scores.mcq},${s.scores.msq},${s.scores.desc},${s.scores.total},${s.timeTaken}\n`;
  });
  const blob=new Blob([csv],{type:'text/csv'});
  const url=URL.createObjectURL(blob);
  const a=document.createElement('a');
  a.href=url; a.download='exam_submissions_'+Date.now()+'.csv'; a.click();
}

function clearSubmissions(){
  if(!confirm('Delete ALL student submissions? This cannot be undone.')) return;
  state.submissions=[];
  save('submissions',[]);
  showAdminTab('submissions', document.querySelector('.admin-tabs button.active'));
}

function bulkImportMCQ(){
  const text=document.getElementById('bulkMCQ').value.trim();
  if(!text){ alert('Paste MCQs first'); return; }
  const blocks=text.split(/\n\s*\n/);
  let count=0;
  blocks.forEach(block=>{
    const lines=block.split('\n').map(l=>l.trim()).filter(Boolean);
    const obj={};
    lines.forEach(l=>{
      const m=l.match(/^([A-Z]+):\s*(.+)$/);
      if(m) obj[m[1]]=m[2];
    });
    if(obj.Q && obj.A && obj.ANS && obj.SEG){
      const opts=[obj.A,obj.B,obj.C,obj.D].filter(Boolean);
      const ansLetter=obj.ANS.trim().toUpperCase();
      const ansIdx='ABCD'.indexOf(ansLetter);
      if(ansIdx>=0 && opts.length>=2){
        state.mcq.push({id:'m'+Date.now()+'_'+Math.random(), seg:+obj.SEG, q:obj.Q, opts, ans:ansIdx});
        count++;
      }
    }
  });
  save('mcq', state.mcq);
  alert(`✅ Imported ${count} MCQs successfully!`);
  document.getElementById('bulkMCQ').value='';
}

function bulkImportMSQ(){
  const text=document.getElementById('bulkMSQ').value.trim();
  if(!text){ alert('Paste MSQs first'); return; }
  const blocks=text.split(/\n\s*\n/);
  let count=0;
  blocks.forEach(block=>{
    const lines=block.split('\n').map(l=>l.trim()).filter(Boolean);
    const obj={};
    lines.forEach(l=>{
      const m=l.match(/^([A-Z]+):\s*(.+)$/);
      if(m) obj[m[1]]=m[2];
    });
    if(obj.Q && obj.A && obj.ANS && obj.SEG){
      const opts=[obj.A,obj.B,obj.C,obj.D].filter(Boolean);
      const ansLetters=obj.ANS.split(',').map(s=>s.trim().toUpperCase());
      const ansIdx=ansLetters.map(l=>'ABCD'.indexOf(l)).filter(i=>i>=0);
      if(ansIdx.length>0 && opts.length>=2){
        state.msq.push({id:'s'+Date.now()+'_'+Math.random(), seg:+obj.SEG, q:obj.Q, opts, ans:ansIdx});
        count++;
      }
    }
  });
  save('msq', state.msq);
  alert(`✅ Imported ${count} MSQs successfully!`);
  document.getElementById('bulkMSQ').value='';
}

function exportJSON(){
  const data={mcq:state.mcq, msq:state.msq, desc:state.desc, syllabus:state.syllabus, config:state.config};
  const blob=new Blob([JSON.stringify(data,null,2)],{type:'application/json'});
  const url=URL.createObjectURL(blob);
  const a=document.createElement('a');
  a.href=url; a.download='exam_data_'+Date.now()+'.json'; a.click();
}

function importJSON(){
  const text=document.getElementById('bulkJSON').value.trim();
  if(!text){ alert('Paste JSON first'); return; }
  try{
    const data=JSON.parse(text);
    if(data.mcq) state.mcq=data.mcq;
    if(data.msq) state.msq=data.msq;
    if(data.desc) state.desc=data.desc;
    if(data.syllabus) state.syllabus=data.syllabus;
    if(data.config) state.config=data.config;
    save('mcq',state.mcq); save('msq',state.msq); save('desc',state.desc);
    save('syllabus',state.syllabus); save('config',state.config);
    alert('✅ Data imported successfully!');
  } catch(e){ alert('Invalid JSON: '+e.message); }
}

function addMCQ(){
  const seg=+document.getElementById('mcqSeg').value;
  const q=document.getElementById('mcqQ').value.trim();
  const opts=document.getElementById('mcqOpts').value.split('\n').map(s=>s.trim()).filter(Boolean);
  const ans=+document.getElementById('mcqAns').value;
  if(!q||opts.length<2||isNaN(ans)){ alert('Fill all fields'); return; }
  state.mcq.push({id:'m'+Date.now(), seg, q, opts, ans});
  save('mcq', state.mcq); showAdminTab('mcq', document.querySelector('.admin-tabs button.active'));
}
function addMSQ(){
  const seg=+document.getElementById('msqSeg').value;
  const q=document.getElementById('msqQ').value.trim();
  const opts=document.getElementById('msqOpts').value.split('\n').map(s=>s.trim()).filter(Boolean);
  const ans=document.getElementById('msqAns').value.split(',').map(s=>+s.trim()).filter(x=>!isNaN(x));
  if(!q||opts.length<2||ans.length===0){ alert('Fill all fields'); return; }
  state.msq.push({id:'s'+Date.now(), seg, q, opts, ans});
  save('msq', state.msq); showAdminTab('msq', document.querySelector('.admin-tabs button.active'));
}
function addDesc(){
  const seg=+document.getElementById('descSeg').value;
  const q=document.getElementById('descQ').value.trim();
  const model=document.getElementById('descModel').value.trim();
  if(!q){ alert('Enter question'); return; }
  state.desc.push({id:'d'+Date.now(), seg, q, model});
  save('desc', state.desc); showAdminTab('desc', document.querySelector('.admin-tabs button.active'));
}
function delQ(type,id){
  if(!confirm('Delete?')) return;
  state[type]=state[type].filter(q=>q.id!==id);
  save(type, state[type]);
  showAdminTab(type, document.querySelector('.admin-tabs button.active'));
}
function updSyl(i,k,v){ state.syllabus[i][k]=v; save('syllabus', state.syllabus); }
function saveConfig(){
  state.config={
    duration:+document.getElementById('cfgDur').value,
    mcqPerSeg:document.getElementById('cfgMcq').value.split(',').map(Number),
    msqPerSeg:document.getElementById('cfgMsq').value.split(',').map(Number),
    descCount:+document.getElementById('cfgDesc').value,
    mcqMarks:+document.getElementById('cfgMcqM').value,
    msqMarks:+document.getElementById('cfgMsqM').value,
    descMarks:+document.getElementById('cfgDescM').value
  };
  save('config', state.config);
  alert('Saved!');
}

/* Anti-cheat */
document.addEventListener('keydown', e=>{
  if(['F12'].includes(e.key) || (e.ctrlKey&&e.shiftKey&&['I','J','C'].includes(e.key))
     || (e.ctrlKey&&['U','S','P','A','C','V'].includes(e.key.toUpperCase()))){
    if(document.getElementById('examScreen').classList.contains('hidden')) return;
    e.preventDefault(); alert('⚠️ Disabled during exam.');
  }
});
</script>
</body>
</html>

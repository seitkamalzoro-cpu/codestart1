# codestart1
<html lang="kk">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="description" content="Бағдарламалау негіздері бойынша интерактивті электронды оқу құралы">
<title>CodeStart — Бағдарламалау негіздері</title>
<style>
:root{--bg:#f5f7fb;--paper:#fff;--ink:#182235;--muted:#69758a;--line:#e6eaf1;--brand:#5b5ce2;--brand2:#8586ff;--mint:#dff8f0;--green:#17865c;--orange:#fff1dc;--red:#ffe8e8;--shadow:0 16px 42px rgba(31,46,86,.08)}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",Arial,sans-serif}.shell{max-width:1180px;margin:auto;padding:22px}.topbar{display:flex;align-items:center;justify-content:space-between;gap:18px;margin-bottom:22px}.brand{display:flex;align-items:center;gap:12px;font-weight:800;font-size:20px;letter-spacing:-.4px}.brand-mark{width:42px;height:42px;border-radius:14px;background:linear-gradient(135deg,var(--brand),#9a72f8);color:#fff;display:grid;place-items:center;font-weight:900;font-size:20px;box-shadow:0 8px 18px #7778e344}.topnote{color:var(--muted);font-size:13px}.layout{display:grid;grid-template-columns:260px minmax(0,1fr);gap:22px;align-items:start}.sidebar,.panel,.hero,.module-card{background:var(--paper);border:1px solid var(--line);border-radius:22px;box-shadow:var(--shadow)}.sidebar{padding:18px;position:sticky;top:16px}.side-label{font-size:11px;letter-spacing:1.3px;color:#929bad;font-weight:800;margin:4px 10px 12px}.nav{display:grid;gap:7px}.nav button{border:0;background:transparent;color:#647087;text-align:left;padding:11px 12px;border-radius:12px;font:inherit;font-weight:650;cursor:pointer;display:flex;align-items:center;gap:10px;transition:.2s}.nav button:hover{background:#f3f4ff;color:var(--brand)}.nav button.active{background:#eeefff;color:#4546c5}.nav .num{width:25px;height:25px;border-radius:8px;background:#f0f2f7;display:grid;place-items:center;font-size:12px}.nav button.active .num{background:#dedeff;color:#4546c5}.side-progress{padding:16px 12px 6px;margin-top:16px;border-top:1px solid var(--line)}.progress-row{display:flex;justify-content:space-between;color:var(--muted);font-size:12px;font-weight:700}.track{height:7px;background:#eef0f5;border-radius:20px;overflow:hidden;margin-top:9px}.fill{height:100%;width:0;background:linear-gradient(90deg,var(--brand),#9c7af7);border-radius:20px;transition:width .3s}.main{min-width:0}.hero{padding:32px;position:relative;overflow:hidden;background:linear-gradient(115deg,#fff 15%,#f2f1ff 100%);margin-bottom:20px}.hero:after{content:"{ }";position:absolute;right:34px;top:22px;font-size:90px;font-weight:900;color:#dcdcff;opacity:.7;letter-spacing:-10px;transform:rotate(-8deg)}.eyebrow{color:var(--brand);font-size:12px;font-weight:850;letter-spacing:1.4px;text-transform:uppercase}.hero h1{font-size:clamp(30px,4vw,46px);line-height:1.12;letter-spacing:-1.5px;max-width:650px;margin:12px 0}.hero p{max-width:660px;color:var(--muted);margin:0 0 22px}.hero-actions{display:flex;gap:10px;flex-wrap:wrap;position:relative;z-index:1}.btn{border:0;border-radius:12px;padding:11px 17px;font:inherit;font-weight:750;cursor:pointer;transition:.18s}.btn-primary{background:var(--brand);color:white;box-shadow:0 8px 18px #5b5ce233}.btn-primary:hover{background:#494acb;transform:translateY(-1px)}.btn-soft{background:#eeefff;color:#4b4cc5}.btn-soft:hover{background:#e2e3ff}.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-bottom:20px}.stat{padding:16px 18px;border:1px solid var(--line);background:#fff;border-radius:17px}.stat strong{display:block;font-size:23px;letter-spacing:-.5px}.stat span{color:var(--muted);font-size:12px;font-weight:650}.panel{padding:26px;margin-bottom:18px;display:none;animation:up .25s ease}.panel.active{display:block}@keyframes up{from{opacity:.3;transform:translateY(6px)}to{opacity:1;transform:translateY(0)}}.panel-head{display:flex;align-items:flex-start;justify-content:space-between;gap:14px;margin-bottom:20px}.panel h2{font-size:26px;letter-spacing:-.7px;line-height:1.2;margin:0 0 7px}.panel-intro{color:var(--muted);margin:0;max-width:750px}.pill{display:inline-flex;align-items:center;padding:6px 10px;border-radius:999px;background:#f0f1ff;color:#5051c8;font-size:11px;font-weight:800;white-space:nowrap}.section-title{font-size:18px;margin:24px 0 12px;letter-spacing:-.3px}.topic-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:13px}.topic{border:1px solid var(--line);border-radius:16px;padding:18px;background:#fff}.topic-icon{width:38px;height:38px;border-radius:12px;background:#f0f1ff;color:var(--brand);display:grid;place-items:center;font-weight:900;font-size:19px;margin-bottom:12px}.topic h3{font-size:16px;margin:0 0 7px}.topic p{font-size:13px;color:var(--muted);margin:0}.code{background:#151b2b;color:#e9eeff;border-radius:14px;padding:16px 18px;overflow:auto;font:13px/1.7 ui-monospace,SFMono-Regular,Consolas,monospace;margin:12px 0}.code .comment{color:#8a97b5}.callout{padding:14px 16px;border-radius:13px;background:#f2f4ff;border-left:4px solid var(--brand);color:#424b70;margin:14px 0}.callout.good{background:#eafaf3;border-color:#2ab27c;color:#286c53}.callout.warn{background:#fff7e8;border-color:#eba943;color:#76531d}.exercise{border:1px solid var(--line);border-radius:17px;padding:18px;margin:14px 0;background:#fff}.exercise-top{display:flex;justify-content:space-between;gap:12px;align-items:center}.exercise h3{margin:0;font-size:17px}.exercise p{color:var(--muted);margin:8px 0 12px}.exercise textarea,.chat-input,.name-input{width:100%;border:1px solid #dfe4ee;border-radius:12px;padding:12px 13px;font:14px/1.55 ui-monospace,Consolas,monospace;outline:none;resize:vertical;background:#fbfcff;color:var(--ink)}.exercise textarea:focus,.chat-input:focus,.name-input:focus{border-color:#8c8df0;box-shadow:0 0 0 3px #5b5ce21b}.feedback{font-size:13px;font-weight:700;margin-top:10px;min-height:20px}.answer{display:none;margin-top:10px}.answer.show{display:block}.answer pre{white-space:pre-wrap;background:#f3f5fa;padding:12px;border-radius:10px;margin:7px 0;font:13px/1.6 ui-monospace,Consolas,monospace}.quiz-list{display:grid;gap:13px}.question{border:1px solid var(--line);border-radius:15px;padding:16px}.question h3{margin:0 0 10px;font-size:15px}.option{display:flex;gap:10px;align-items:flex-start;padding:8px 10px;border-radius:10px;cursor:pointer;color:#4f5a6f;font-size:14px}.option:hover{background:#f7f8fc}.option input{margin-top:5px;accent-color:var(--brand)}.quiz-result{display:none;margin-top:18px;padding:18px;border-radius:16px;background:#f1f2ff}.quiz-result.show{display:block}.score{font-size:34px;font-weight:900;color:var(--brand);letter-spacing:-1px}.result-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-top:12px}.result-chip{background:#fff;padding:11px;border-radius:12px}.result-chip strong{display:block;font-size:18px}.result-chip span{color:var(--muted);font-size:11px}.chatbox{border:1px solid var(--line);border-radius:17px;overflow:hidden}.chat-head{display:flex;gap:12px;align-items:center;padding:15px 17px;background:#f7f7ff;border-bottom:1px solid var(--line)}.bot-avatar{width:38px;height:38px;border-radius:13px;background:linear-gradient(135deg,#5b5ce2,#9879f4);color:#fff;display:grid;place-items:center;font-weight:900}.chat-head strong{display:block}.chat-head small{color:var(--muted)}.chat-messages{padding:16px;min-height:210px;max-height:340px;overflow:auto;display:flex;flex-direction:column;gap:10px;background:#fff}.bubble{max-width:88%;padding:11px 13px;border-radius:14px;font-size:14px;white-space:pre-wrap}.bubble.bot{background:#f0f2fa;color:#3b465d;align-self:flex-start;border-bottom-left-radius:4px}.bubble.user{background:#595be0;color:#fff;align-self:flex-end;border-bottom-right-radius:4px}.chat-compose{padding:13px;display:grid;grid-template-columns:1fr auto;gap:9px;background:#fafbfe;border-top:1px solid var(--line)}.chat-compose .chat-input{font-family:inherit;resize:none}.tiny-note{font-size:11px;color:var(--muted);margin-top:9px}.assessment-grid{display:grid;grid-template-columns:1fr 1fr;gap:13px}.assessment-card{border:1px solid var(--line);border-radius:16px;padding:17px}.assessment-card h3{margin:0 0 8px;font-size:15px}.assessment-card p{margin:0;color:var(--muted);font-size:13px}.meter{height:11px;background:#edf0f6;border-radius:20px;overflow:hidden;margin:14px 0 8px}.meter span{display:block;height:100%;width:0;background:linear-gradient(90deg,#5b5ce2,#9e81f3);border-radius:20px}.footer{text-align:center;color:#909aab;font-size:12px;padding:14px 0 24px}.hidden{display:none!important}
@media(max-width:850px){.layout{grid-template-columns:1fr}.sidebar{position:static}.nav{grid-template-columns:repeat(2,1fr)}.side-progress{margin-top:10px}.topic-grid{grid-template-columns:1fr 1fr}}
@media(max-width:560px){.shell{padding:12px}.topbar{align-items:flex-start}.topnote{display:none}.hero{padding:24px}.hero:after{font-size:60px;right:12px}.stats{grid-template-columns:1fr 1fr}.stats .stat:last-child{grid-column:span 2}.panel{padding:19px}.panel-head{display:block}.pill{margin-top:10px}.topic-grid,.assessment-grid{grid-template-columns:1fr}.result-grid{grid-template-columns:1fr 1fr}.nav{grid-template-columns:1fr 1fr}.chat-compose{grid-template-columns:1fr}.chat-compose button{width:100%}}
@media print{.sidebar,.topbar,.hero-actions,.btn,.chat-compose{display:none!important}.layout{display:block}.panel{display:block!important;box-shadow:none;page-break-inside:avoid}.hero{box-shadow:none}}
</style>
</head>
<body>
<div class="shell">
  <header class="topbar">
    <div class="brand"><div class="brand-mark">{ }</div><span>CodeStart <span style="color:var(--brand)">Оқу құралы</span></span></div>
    <div class="topnote">ИНФОРМАТИКА · PYTHON · ИНТЕРАКТИВТІ КУРС</div>
  </header>
  <div class="layout">
    <aside class="sidebar">
      <div class="side-label">ОҚУ БӨЛІМДЕРІ</div>
      <nav class="nav" aria-label="Оқу құралы бөлімдері">
        <button class="active" data-target="home"><span class="num">⌂</span> Басты бет</button>
        <button data-target="theory"><span class="num">01</span> Теориялық материал</button>
        <button data-target="practice"><span class="num">02</span> Практикалық тапсырмалар</button>
        <button data-target="quiz"><span class="num">03</span> Интеллектуалды тест</button>
        <button data-target="assistant"><span class="num">04</span> ЖИ көмекшісі</button>
        <button data-target="analysis"><span class="num">05</span> Бағалау және талдау</button>
      </nav>
      <div class="side-progress">
        <div class="progress-row"><span>Оқу барысы</span><strong id="progressText">0%</strong></div>
        <div class="track"><div class="fill" id="progressFill"></div></div>
      </div>
    </aside>
    <main class="main">
      <section class="hero" id="home">
        <div class="eyebrow">Сандық білім кеңістігі</div>
        <h1>Бағдарламалауды<br>бірге үйренейік!</h1>
        <p>Python тілінің негізгі ұғымдарын меңгеріп, код жазып көріңіз, біліміңізді тест арқылы тексеріңіз. Әр бөлім өз қарқыныңызбен оқуға арналған.</p>
        <div class="hero-actions">
          <button class="btn btn-primary" onclick="showPanel('theory')">Оқуды бастау <span aria-hidden="true">→</span></button>
          <button class="btn btn-soft" onclick="showPanel('quiz')">Білімімді тексеру</button>
        </div>
      </section>
      <div class="stats">
        <div class="stat"><strong>10</strong><span>Теориялық тақырып</span></div>
        <div class="stat"><strong>15</strong><span>Практикалық тапсырма</span></div>
        <div class="stat"><strong>20</strong><span>Тест сұрағы</span></div>
      </div>

      <section class="panel" id="theory"><div class="panel-head"><div><h2>Теориялық материал</h2><p class="panel-intro">Python бағдарламалау тілінің 10 негізгі тақырыбы: анықтама, мысал және есте сақтайтын ереже.</p></div><span class="pill">10 тақырып</span></div><div class="topic-grid"><article class="topic"><div class="topic-icon">1</div><h3>1. Айнымалылар және мән меншіктеу</h3><p>Айнымалы — бағдарламада мән сақтайтын атау. Python типті мәніне қарай автоматты анықтайды. Атау әріптен немесе _ таңбасынан басталып, бос орынсыз жазылады.</p></article><article class="topic"><div class="topic-icon">2</div><h3>2. Деректер типтері және түрлендіру</h3><p>int — бүтін сан, float — бөлшек сан, str — мәтін, bool — True/False. type() типті анықтайды. int(), float(), str() мәндерді түрлендіреді.</p></article><article class="topic"><div class="topic-icon">3</div><h3>3. Енгізу, шығару және операторлар</h3><p>input() пайдаланушыдан дерек алады, print() экранға шығарады. Арифметикалық операторлар: +, -, *, /, //, %, **. Салыстыру: ==, !=, &gt;, &lt;, &gt;=, &lt;=. Логикалық: and, or, not.</p></article><article class="topic"><div class="topic-icon">4</div><h3>4. Шартты операторлар</h3><p>if шартты тексереді, elif қосымша шарттарды қарайды, else қалған жағдайды орындайды. Шарт соңына қос нүкте қойылып, ішкі код шегініспен жазылады.</p></article><article class="topic"><div class="topic-icon">5</div><h3>5. Циклдер: for, while және range</h3><p>for тізбек элементтерін ретімен қарастырады. while шарт ақиқат болғанша орындалады. range(start, stop, step) сандар тізбегін жасайды; stop тізбекке кірмейді.</p></article><article class="topic"><div class="topic-icon">6</div><h3>6. Функциялар және параметрлер</h3><p>Функция — қайта қолданылатын код бөлігі. def функцияны анықтайды, параметр мән қабылдайды, аргумент шақыру кезінде беріледі, return нәтиже қайтарады.</p></article><article class="topic"><div class="topic-icon">7</div><h3>7. Тізімдер және кортеждер</h3><p>list бірнеше мәнді ретімен сақтайды және өзгертіледі. Индекс 0-ден басталады. append() қосады, remove() өшіреді, pop() элементті алып тастайды. tuple — өзгермейтін реттелген тізбек.</p></article><article class="topic"><div class="topic-icon">8</div><h3>8. Сөздіктер және жиындар</h3><p>dict деректерді кілт-мән жұбы ретінде сақтайды. set қайталанбайтын элементтер жиынын сақтайды. Сөздікке кілт арқылы жүгінеміз.</p></article><article class="topic"><div class="topic-icon">9</div><h3>9. Жолдар және мәтінді өңдеу</h3><p>str — мәтіндік дерек. Жолдарды + арқылы біріктіруге болады. upper(), lower(), strip(), replace(), split() — жиі қолданылатын әдістер. f-string айнымалыны мәтінге кірістіреді.</p></article><article class="topic"><div class="topic-icon">10</div><h3>10. Файлдар, модульдер және қателерді өңдеу</h3><p>open() файлды ашады: r — оқу, w — жазу, a — соңына қосу. with файлды автоматты жабады. import модульді қосады. try/except қатені өңдейді.</p></article></div><h3 class="section-title">1-тақырып. Айнымалылар және мән меншіктеу</h3><p>Айнымалы — бағдарламада мән сақтайтын атау. Python типті мәніне қарай автоматты анықтайды. Атау әріптен немесе _ таңбасынан басталып, бос орынсыз жазылады.</p><pre class="code-pre">name = &quot;Aruzhan&quot;
age = 17
is_student = True
print(name, age)</pre><div class="callout"><strong>Есте сақта:</strong> = мән меншіктейді. Айнымалының мәнін бағдарлама барысында өзгертуге болады.</div><h3 class="section-title">2-тақырып. Деректер типтері және түрлендіру</h3><p>int — бүтін сан, float — бөлшек сан, str — мәтін, bool — True/False. type() типті анықтайды. int(), float(), str() мәндерді түрлендіреді.</p><pre class="code-pre">age_text = &quot;18&quot;
age = int(age_text)
price = float(&quot;1250.5&quot;)
print(type(age), price)</pre><div class="callout"><strong>Есте сақта:</strong> input() енгізген мәнді str түрінде береді. Санмен есептеу үшін int() не float() қолданыңыз.</div><h3 class="section-title">3-тақырып. Енгізу, шығару және операторлар</h3><p>input() пайдаланушыдан дерек алады, print() экранға шығарады. Арифметикалық операторлар: +, -, *, /, //, %, **. Салыстыру: ==, !=, &gt;, &lt;, &gt;=, &lt;=. Логикалық: and, or, not.</p><pre class="code-pre">a = int(input(&quot;Бірінші сан: &quot;))
b = int(input(&quot;Екінші сан: &quot;))
print(&quot;Қосынды:&quot;, a + b)
print(&quot;Қалдық:&quot;, a % b)</pre><div class="callout"><strong>Есте сақта:</strong> = меншіктеу, == салыстыру. / нақты бөледі, // бүтін бөлік, % қалдық береді.</div><h3 class="section-title">4-тақырып. Шартты операторлар</h3><p>if шартты тексереді, elif қосымша шарттарды қарайды, else қалған жағдайды орындайды. Шарт соңына қос нүкте қойылып, ішкі код шегініспен жазылады.</p><pre class="code-pre">score = 85
if score &gt;= 90:
    print(&quot;Өте жақсы&quot;)
elif score &gt;= 70:
    print(&quot;Жақсы&quot;)
else:
    print(&quot;Қайталау қажет&quot;)</pre><div class="callout"><strong>Есте сақта:</strong> Бірнеше шартты and, or, not арқылы біріктіруге болады.</div><h3 class="section-title">5-тақырып. Циклдер: for, while және range</h3><p>for тізбек элементтерін ретімен қарастырады. while шарт ақиқат болғанша орындалады. range(start, stop, step) сандар тізбегін жасайды; stop тізбекке кірмейді.</p><pre class="code-pre">for n in range(1, 6):
    print(n)

i = 3
while i &gt; 0:
    print(i)
    i -= 1</pre><div class="callout"><strong>Есте сақта:</strong> break циклді тоқтатады, continue ағымдағы қадамды өткізіп жібереді. while шартын өзгертуді ұмытпаңыз.</div><h3 class="section-title">6-тақырып. Функциялар және параметрлер</h3><p>Функция — қайта қолданылатын код бөлігі. def функцияны анықтайды, параметр мән қабылдайды, аргумент шақыру кезінде беріледі, return нәтиже қайтарады.</p><pre class="code-pre">def rectangle_area(width, height):
    return width * height

print(rectangle_area(5, 3))</pre><div class="callout"><strong>Есте сақта:</strong> Функциялар код қайталануын азайтып, бағдарламаны бөліктерге бөледі.</div><h3 class="section-title">7-тақырып. Тізімдер және кортеждер</h3><p>list бірнеше мәнді ретімен сақтайды және өзгертіледі. Индекс 0-ден басталады. append() қосады, remove() өшіреді, pop() элементті алып тастайды. tuple — өзгермейтін реттелген тізбек.</p><pre class="code-pre">scores = [85, 90, 78]
scores.append(95)
print(scores[0], len(scores))
point = (10, 20)</pre><div class="callout"><strong>Есте сақта:</strong> Тізім [] жақшасымен, кортеж () жақшасымен жазылады. Кесінді: scores[1:3].</div><h3 class="section-title">8-тақырып. Сөздіктер және жиындар</h3><p>dict деректерді кілт-мән жұбы ретінде сақтайды. set қайталанбайтын элементтер жиынын сақтайды. Сөздікке кілт арқылы жүгінеміз.</p><pre class="code-pre">student = {&quot;name&quot;: &quot;Aruzhan&quot;, &quot;grade&quot;: 10}
print(student[&quot;name&quot;])
student[&quot;city&quot;] = &quot;Almaty&quot;
unique = {1, 2, 2, 3}
print(unique)</pre><div class="callout"><strong>Есте сақта:</strong> dict үшін get(), keys(), values() пайдалы. set ішінде тұрақты индекс болмайды.</div><h3 class="section-title">9-тақырып. Жолдар және мәтінді өңдеу</h3><p>str — мәтіндік дерек. Жолдарды + арқылы біріктіруге болады. upper(), lower(), strip(), replace(), split() — жиі қолданылатын әдістер. f-string айнымалыны мәтінге кірістіреді.</p><pre class="code-pre">name = &quot;  Python тілі  &quot;
clean = name.strip()
print(clean.upper())
user = &quot;Aruzhan&quot;
print(f&quot;Сәлем, {user}!&quot;)</pre><div class="callout"><strong>Есте сақта:</strong> Жолдар өзгермейтін объектілер: әдістер бастапқы жолды өзгертпей, жаңа жол қайтарады.</div><h3 class="section-title">10-тақырып. Файлдар, модульдер және қателерді өңдеу</h3><p>open() файлды ашады: r — оқу, w — жазу, a — соңына қосу. with файлды автоматты жабады. import модульді қосады. try/except қатені өңдейді.</p><pre class="code-pre">try:
    n = int(input(&quot;Сан: &quot;))
    with open(&quot;result.txt&quot;, &quot;w&quot;, encoding=&quot;utf-8&quot;) as f:
        f.write(str(n))
except ValueError:
    print(&quot;Бүтін сан енгізіңіз&quot;)</pre><div class="callout"><strong>Есте сақта:</strong> SyntaxError — синтаксис, NameError — атау, TypeError — тип, ValueError — мән қатесі.</div><button class="btn btn-primary" onclick="showPanel('practice');markDone('theory')">Практикаға өту →</button></section>
<section class="panel" id="practice"><div class="panel-head"><div><h2>Практикалық тапсырмалар</h2><p class="panel-intro">15 тапсырманы орындаңыз. Кодты енгізіп, тексеріңіз немесе үлгі шешімімен салыстырыңыз.</p></div><span class="pill">15 тапсырма</span></div><div class="exercise" data-task="1"><div class="exercise-top"><h3>1-тапсырма. Екі санның қосындысы</h3><span class="pill">Айнымалылар</span></div><p>a және b айнымалыларына екі сан беріп, қосындысын result айнымалысына сақтап, экранға шығарыңыз.</p><textarea rows="5" id="code1" placeholder="Python кодын осында жазыңыз..."></textarea><div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px"><button class="btn btn-primary" onclick="checkTask(1)">Тексеру</button><button class="btn btn-soft" onclick="toggleAnswer(1)">Үлгі шешімді көру</button></div><div class="feedback" id="feedback1"></div><div class="answer" id="answer1"><strong>Үлгі шешімі:</strong><pre class="code-pre">a = 12
b = 8
result = a + b
print(result)</pre></div></div><div class="exercise" data-task="2"><div class="exercise-top"><h3>2-тапсырма. Санның таңбасын анықтау</h3><span class="pill">Шартты оператор</span></div><p>Енгізілген санның оң, теріс немесе нөл екенін if, elif және else арқылы анықтаңыз.</p><textarea rows="5" id="code2" placeholder="Python кодын осында жазыңыз..."></textarea><div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px"><button class="btn btn-primary" onclick="checkTask(2)">Тексеру</button><button class="btn btn-soft" onclick="toggleAnswer(2)">Үлгі шешімді көру</button></div><div class="feedback" id="feedback2"></div><div class="answer" id="answer2"><strong>Үлгі шешімі:</strong><pre class="code-pre">number = int(input(&quot;Сан: &quot;))
if number &gt; 0:
    print(&quot;Оң сан&quot;)
elif number &lt; 0:
    print(&quot;Теріс сан&quot;)
else:
    print(&quot;Нөл&quot;)</pre></div></div><div class="exercise" data-task="3"><div class="exercise-top"><h3>3-тапсырма. Жұп немесе тақ сан</h3><span class="pill">Шарт және қалдық</span></div><p>Бүтін санның жұп не тақ екенін % операторы арқылы анықтаңыз.</p><textarea rows="5" id="code3" placeholder="Python кодын осында жазыңыз..."></textarea><div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px"><button class="btn btn-primary" onclick="checkTask(3)">Тексеру</button><button class="btn btn-soft" onclick="toggleAnswer(3)">Үлгі шешімді көру</button></div><div class="feedback" id="feedback3"></div><div class="answer" id="answer3"><strong>Үлгі шешімі:</strong><pre class="code-pre">number = int(input(&quot;Сан: &quot;))
if number % 2 == 0:
    print(&quot;Жұп сан&quot;)
else:
    print(&quot;Тақ сан&quot;)</pre></div></div><div class="exercise" data-task="4"><div class="exercise-top"><h3>4-тапсырма. Үш санның ең үлкені</h3><span class="pill">Салыстыру</span></div><p>Үш санның ішіндегі ең үлкенін max() функциясымен табыңыз.</p><textarea rows="5" id="code4" placeholder="Python кодын осында жазыңыз..."></textarea><div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px"><button class="btn btn-primary" onclick="checkTask(4)">Тексеру</button><button class="btn btn-soft" onclick="toggleAnswer(4)">Үлгі шешімді көру</button></div><div class="feedback" id="feedback4"></div><div class="answer" id="answer4"><strong>Үлгі шешімі:</strong><pre class="code-pre">a, b, c = 12, 27, 19
print(max(a, b, c))</pre></div></div><div class="exercise" data-task="5"><div class="exercise-top"><h3>5-тапсырма. 1-ден 10-ға дейін шығару</h3><span class="pill">for циклі</span></div><p>for және range() арқылы 1-ден 10-ға дейінгі сандарды шығарыңыз.</p><textarea rows="5" id="code5" placeholder="Python кодын осында жазыңыз..."></textarea><div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px"><button class="btn btn-primary" onclick="checkTask(5)">Тексеру</button><button class="btn btn-soft" onclick="toggleAnswer(5)">Үлгі шешімді көру</button></div><div class="feedback" id="feedback5"></div><div class="answer" id="answer5"><strong>Үлгі шешімі:</strong><pre class="code-pre">for i in range(1, 11):
    print(i)</pre></div></div><div class="exercise" data-task="6"><div class="exercise-top"><h3>6-тапсырма. 1-ден n-ге дейінгі қосынды</h3><span class="pill">Цикл және жинақтау</span></div><p>Пайдаланушы енгізген n санына дейінгі натурал сандардың қосындысын есептеңіз.</p><textarea rows="5" id="code6" placeholder="Python кодын осында жазыңыз..."></textarea><div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px"><button class="btn btn-primary" onclick="checkTask(6)">Тексеру</button><button class="btn btn-soft" onclick="toggleAnswer(6)">Үлгі шешімді көру</button></div><div class="feedback" id="feedback6"></div><div class="answer" id="answer6"><strong>Үлгі шешімі:</strong><pre class="code-pre">n = int(input(&quot;n = &quot;))
total = 0
for i in range(1, n + 1):
    total += i
print(total)</pre></div></div><div class="exercise" data-task="7"><div class="exercise-top"><h3>7-тапсырма. Көбейту кестесі</h3><span class="pill">Цикл</span></div><p>Енгізілген санның 1-ден 10-ға дейінгі көбейту кестесін шығарыңыз.</p><textarea rows="5" id="code7" placeholder="Python кодын осында жазыңыз..."></textarea><div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px"><button class="btn btn-primary" onclick="checkTask(7)">Тексеру</button><button class="btn btn-soft" onclick="toggleAnswer(7)">Үлгі шешімді көру</button></div><div class="feedback" id="feedback7"></div><div class="answer" id="answer7"><strong>Үлгі шешімі:</strong><pre class="code-pre">n = int(input(&quot;Сан: &quot;))
for i in range(1, 11):
    print(n, &quot;x&quot;, i, &quot;=&quot;, n * i)</pre></div></div><div class="exercise" data-task="8"><div class="exercise-top"><h3>8-тапсырма. Кері санау</h3><span class="pill">while циклі</span></div><p>while арқылы 5-тен 1-ге дейін кері санаңыз.</p><textarea rows="5" id="code8" placeholder="Python кодын осында жазыңыз..."></textarea><div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px"><button class="btn btn-primary" onclick="checkTask(8)">Тексеру</button><button class="btn btn-soft" onclick="toggleAnswer(8)">Үлгі шешімді көру</button></div><div class="feedback" id="feedback8"></div><div class="answer" id="answer8"><strong>Үлгі шешімі:</strong><pre class="code-pre">count = 5
while count &gt;= 1:
    print(count)
    count -= 1</pre></div></div><div class="exercise" data-task="9"><div class="exercise-top"><h3>9-тапсырма. Функция арқылы квадрат табу</h3><span class="pill">Функциялар</span></div><p>square функциясын құрып, берілген санның квадратын return арқылы қайтарыңыз.</p><textarea rows="5" id="code9" placeholder="Python кодын осында жазыңыз..."></textarea><div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px"><button class="btn btn-primary" onclick="checkTask(9)">Тексеру</button><button class="btn btn-soft" onclick="toggleAnswer(9)">Үлгі шешімді көру</button></div><div class="feedback" id="feedback9"></div><div class="answer" id="answer9"><strong>Үлгі шешімі:</strong><pre class="code-pre">def square(number):
    return number ** 2

print(square(6))</pre></div></div><div class="exercise" data-task="10"><div class="exercise-top"><h3>10-тапсырма. Тізімнің орташа мәні</h3><span class="pill">Тізімдер</span></div><p>[4, 6, 8, 10] тізімінің орташа арифметикалық мәнін есептеңіз.</p><textarea rows="5" id="code10" placeholder="Python кодын осында жазыңыз..."></textarea><div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px"><button class="btn btn-primary" onclick="checkTask(10)">Тексеру</button><button class="btn btn-soft" onclick="toggleAnswer(10)">Үлгі шешімді көру</button></div><div class="feedback" id="feedback10"></div><div class="answer" id="answer10"><strong>Үлгі шешімі:</strong><pre class="code-pre">numbers = [4, 6, 8, 10]
average = sum(numbers) / len(numbers)
print(average)</pre></div></div><div class="exercise" data-task="11"><div class="exercise-top"><h3>11-тапсырма. Тізімдегі жұп сандар</h3><span class="pill">Тізім және шарт</span></div><p>Тізімнен тек жұп сандарды for және if көмегімен шығарыңыз.</p><textarea rows="5" id="code11" placeholder="Python кодын осында жазыңыз..."></textarea><div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px"><button class="btn btn-primary" onclick="checkTask(11)">Тексеру</button><button class="btn btn-soft" onclick="toggleAnswer(11)">Үлгі шешімді көру</button></div><div class="feedback" id="feedback11"></div><div class="answer" id="answer11"><strong>Үлгі шешімі:</strong><pre class="code-pre">numbers = [1, 2, 3, 4, 5, 6]
for number in numbers:
    if number % 2 == 0:
        print(number)</pre></div></div><div class="exercise" data-task="12"><div class="exercise-top"><h3>12-тапсырма. Оқушы сөздігін құру</h3><span class="pill">Сөздік</span></div><p>name, age және group кілттері бар сөздік құрып, оқушының атын шығарыңыз.</p><textarea rows="5" id="code12" placeholder="Python кодын осында жазыңыз..."></textarea><div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px"><button class="btn btn-primary" onclick="checkTask(12)">Тексеру</button><button class="btn btn-soft" onclick="toggleAnswer(12)">Үлгі шешімді көру</button></div><div class="feedback" id="feedback12"></div><div class="answer" id="answer12"><strong>Үлгі шешімі:</strong><pre class="code-pre">student = {&quot;name&quot;: &quot;Aruzhan&quot;, &quot;age&quot;: 17, &quot;group&quot;: &quot;IS-251&quot;}
print(student[&quot;name&quot;])</pre></div></div><div class="exercise" data-task="13"><div class="exercise-top"><h3>13-тапсырма. Мәтінді өңдеу</h3><span class="pill">Жолдар</span></div><p>Мәтінді енгізіп, бас әріпке айналдырыңыз және таңбалар санын шығарыңыз.</p><textarea rows="5" id="code13" placeholder="Python кодын осында жазыңыз..."></textarea><div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px"><button class="btn btn-primary" onclick="checkTask(13)">Тексеру</button><button class="btn btn-soft" onclick="toggleAnswer(13)">Үлгі шешімді көру</button></div><div class="feedback" id="feedback13"></div><div class="answer" id="answer13"><strong>Үлгі шешімі:</strong><pre class="code-pre">text = input(&quot;Мәтін: &quot;)
print(text.upper())
print(len(text))</pre></div></div><div class="exercise" data-task="14"><div class="exercise-top"><h3>14-тапсырма. Қатені өңдеу</h3><span class="pill">try/except</span></div><p>Сан енгізуді сұрап, жарамсыз мән енгізілсе ValueError қатесін өңдеңіз.</p><textarea rows="5" id="code14" placeholder="Python кодын осында жазыңыз..."></textarea><div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px"><button class="btn btn-primary" onclick="checkTask(14)">Тексеру</button><button class="btn btn-soft" onclick="toggleAnswer(14)">Үлгі шешімді көру</button></div><div class="feedback" id="feedback14"></div><div class="answer" id="answer14"><strong>Үлгі шешімі:</strong><pre class="code-pre">try:
    number = int(input(&quot;Сан: &quot;))
    print(number * 2)
except ValueError:
    print(&quot;Сан енгізу қажет&quot;)</pre></div></div><div class="exercise" data-task="15"><div class="exercise-top"><h3>15-тапсырма. Файлға мәтін жазу</h3><span class="pill">Файлдар</span></div><p>with open() арқылы result.txt файлына Python туралы қысқа мәтін жазыңыз.</p><textarea rows="5" id="code15" placeholder="Python кодын осында жазыңыз..."></textarea><div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px"><button class="btn btn-primary" onclick="checkTask(15)">Тексеру</button><button class="btn btn-soft" onclick="toggleAnswer(15)">Үлгі шешімді көру</button></div><div class="feedback" id="feedback15"></div><div class="answer" id="answer15"><strong>Үлгі шешімі:</strong><pre class="code-pre">with open(&quot;result.txt&quot;, &quot;w&quot;, encoding=&quot;utf-8&quot;) as file:
    file.write(&quot;Python бағдарламалау тілі&quot;)</pre></div></div><div class="callout warn">Ескерту: браузердегі тексеру кодтың негізгі құрылымы мен қажетті командаларын қарайды. Кодты толық орындап көру үшін Python ортасын пайдаланыңыз.</div></section>
<section class="panel" id="quiz">
        <div class="panel-head"><div><h2>Интеллектуалды тест</h2><p class="panel-intro">10 сұраққа жауап беріңіз. 20 сұраққа жауап беріңіз. Тест аяқталған соң нәтиже автоматты есептеледі.</p></div><span class="pill">4-модуль</span></div>
        <form id="quizForm" onsubmit="return false;">
          <div class="quiz-list" id="questions"></div>
          <div style="display:flex;gap:10px;flex-wrap:wrap;margin-top:17px"><button type="button" class="btn btn-primary" onclick="gradeQuiz()">Тестті аяқтау және бағалау</button><button type="button" class="btn btn-soft" onclick="resetQuiz()">Қайта бастау</button></div>
        </form>
        <div class="quiz-result" id="quizResult" aria-live="polite"></div>
      </section>

      <section class="panel" id="assistant">
        <div class="panel-head"><div><h2>ЖИ көмекшісі</h2><p class="panel-intro">Бағдарламалау негіздері бойынша сұрақ қойып, қысқаша түсіндірме алыңыз.</p></div><span class="pill">5-модуль</span></div>
        <div class="chatbox">
          <div class="chat-head"><div class="bot-avatar">AI</div><div><strong>CodeStart көмекшісі</strong><small>Оқу тақырыптары бойынша виртуалды кеңесші</small></div></div>
          <div class="chat-messages" id="chatMessages"><div class="bubble bot">Сәлем! Мен Python тақырыптарын түсіндіруге көмектесемін. Мысалы: «айнымалы деген не?», «for циклі қалай жұмыс істейді?» немесе «функция деген не?» деп сұраңыз.</div></div>
          <form class="chat-compose" id="chatForm" onsubmit="return false;"><textarea class="chat-input" id="chatInput" rows="2" placeholder="Сұрағыңызды жазыңыз..."></textarea><button class="btn btn-primary" type="button" onclick="sendChat()">Жіберу ↗</button></form>
        </div>
        <p class="tiny-note">Бұл нұсқада көмекші оқу тақырыптарына арналған алдын ала дайындалған жауаптармен жұмыс істейді. Нақты генеративті ЖИ моделіне қосылмаған; API арқылы интеграциялау үшін серверлік кілт пен backend қажет.</p>
        <div class="callout"><strong>Кеңес:</strong> сұрақты нақты жазыңыз. Мысалы, «while мен for циклдерінің айырмашылығы қандай?» деген сұраққа тақырыптық жауап беріледі.</div>
      </section>

      <section class="panel" id="analysis">
        <div class="panel-head"><div><h2>Білімді бағалау және талдау</h2><p class="panel-intro">Оқу құралы тест нәтижесі мен орындалған тапсырмаларды жинақтап, келесі қадамға ұсыныс береді.</p></div><span class="pill">6-модуль</span></div>
        <div class="assessment-grid">
          <div class="assessment-card"><h3>Тест нәтижесі</h3><div class="score" id="analysisScore">—</div><p id="analysisStatus">Алдымен интеллектуалды тестті орындаңыз.</p><div class="meter"><span id="analysisMeter"></span></div><small id="analysisCount" style="color:var(--muted)">Дұрыс жауап: — / 20</small></div>
          <div class="assessment-card"><h3>Практикалық жұмыстар</h3><div class="score" id="taskScore">0/3</div><p>Тексеруден өткен жаттығулар саны.</p><div class="meter"><span id="taskMeter"></span></div><small style="color:var(--muted)">Әр тапсырманы жеке тексеріңіз.</small></div>
        </div>
        <h3 class="section-title">Жеке оқу ұсынысы</h3>
        <div class="callout" id="recommendation">Тест нәтижесі шыққаннан кейін осы жерде сізге арналған оқу ұсынысы көрсетіледі.</div>
        <h3 class="section-title">Бағалау шкаласы</h3>
        <div class="topic-grid">
          <article class="topic"><div class="topic-icon">A</div><h3>90–100%</h3><p>Өте жақсы. Күрделірек есептерді орындап, біліміңізді бекітіңіз.</p></article>
          <article class="topic"><div class="topic-icon">B</div><h3>70–89%</h3><p>Жақсы. Қате кеткен сұрақтарды қайталап, қосымша жаттығу жасаңыз.</p></article>
          <article class="topic"><div class="topic-icon">C</div><h3>0–69%</h3><p>Материалды қайта қарап, теориядан кейін тестті қайталап өтіңіз.</p></article>
        </div>
        <button class="btn btn-soft" style="margin-top:18px" onclick="showPanel('quiz')">Тестке қайта оралу</button>
      </section>
      <div class="footer">CodeStart · «Бағдарламалау негіздері» электронды оқу құралы · Оқу мақсатында әзірленген</div>
    </main>
  </div>
</div>
<script>
const navButtons=[...document.querySelectorAll('.nav button')];
const panels=[...document.querySelectorAll('.panel')];
const completed=new Set();let taskCompleted=new Set();let lastQuiz=null;
function showPanel(id){document.getElementById('home').classList.toggle('hidden',id!=='home');panels.forEach(p=>p.classList.toggle('active',p.id===id));navButtons.forEach(b=>b.classList.toggle('active',b.dataset.target===id));if(id==='analysis')updateAnalysis();window.scrollTo({top:0,behavior:'smooth'});}
navButtons.forEach(b=>b.addEventListener('click',()=>{showPanel(b.dataset.target);if(b.dataset.target!=='home')markDone(b.dataset.target)}));
function markDone(id){if(['theory','practice','quiz','assistant','analysis'].includes(id)){completed.add(id);updateProgress()}}
function updateProgress(){const percent=Math.round((completed.size/5)*100);document.getElementById('progressText').textContent=percent+'%';document.getElementById('progressFill').style.width=percent+'%'}
function checkTask(n){
 const v=document.getElementById('code'+n).value.toLowerCase();
 const rules={
  1:/print\s*\(/.test(v)&&/\+/.test(v),
  2:/if\s+/.test(v)&&/elif\s+/.test(v)&&/else\s*:/.test(v),
  3:/%/.test(v)&&/if\s+/.test(v),
  4:/max\s*\(/.test(v)||(/if\s+/.test(v)&&/>/.test(v)),
  5:/for\s+/.test(v)&&/range\s*\(/.test(v),
  6:/for\s+/.test(v)&&/(total|sum)/.test(v)&&/range\s*\(/.test(v),
  7:/for\s+/.test(v)&&/range\s*\(/.test(v)&&/\*/.test(v),
  8:/while\s+/.test(v)&&/print\s*\(/.test(v),
  9:/def\s+/.test(v)&&/return/.test(v),
  10:/sum\s*\(/.test(v)&&/len\s*\(/.test(v),
  11:/for\s+/.test(v)&&/if\s+/.test(v)&&/%/.test(v),
  12:/\{/.test(v)&&/\}/.test(v)&&/print\s*\(/.test(v),
  13:/upper\s*\(/.test(v)&&/len\s*\(/.test(v),
  14:/try\s*:/.test(v)&&/except/.test(v),
  15:/with\s+open\s*\(/.test(v)&&/write\s*\(/.test(v)
 };
 const ok=!!v.trim()&&!!rules[n];
 const f=document.getElementById('feedback'+n);
 f.textContent=!v.trim()?'Алдымен код жазыңыз.':ok?'Жақсы! Тапсырманың негізгі командалары анықталды. Кодты Python ортасында да іске қосып тексеріңіз.':'Код толық емес сияқты. Шарттағы негізгі командаларды және үлгі шешімді салыстырыңыз.';
 f.style.color=ok?'#168257':'#b16a17';
 if(ok)taskCompleted.add(n);else taskCompleted.delete(n);
 document.getElementById('taskScore').textContent=taskCompleted.size+'/15';
 document.getElementById('taskMeter').style.width=(taskCompleted.size/15*100)+'%';
 markDone('practice');
}
function toggleAnswer(n){document.getElementById('answer'+n).classList.toggle('show')}
const qs=[
{q:"Экранға ақпарат шығаратын функция?",a:["input()", "print()", "type()", "len()"],c:1,topic:"Негізгі командалар"},
{q:"Бүтін санның типі?",a:["str", "float", "int", "bool"],c:2,topic:"Деректер типтері"},
{q:"Мән меншіктеу операторы?",a:["==", "=", "!=", ">="],c:1,topic:"Айнымалылар"},
{q:"input() әдетте қандай тип қайтарады?",a:["int", "float", "bool", "str"],c:3,topic:"Енгізу"},
{q:"Екі мәннің теңдігін салыстыру операторы?",a:["=", "==", "!=", "<"],c:1,topic:"Операторлар"},
{q:"Шартты тексеретін кілт сөз?",a:["for", "def", "if", "return"],c:2,topic:"Шарттар"},
{q:"Екі шарттың да ақиқат болуын талап ететін оператор?",a:["or", "not", "and", "in"],c:2,topic:"Логикалық операторлар"},
{q:"range(1, 5) қандай сандар береді?",a:["1,2,3,4,5", "0,1,2,3,4", "1,2,3,4", "2,3,4,5"],c:2,topic:"range"},
{q:"Қайталау үшін қолданылатын цикл?",a:["if", "for", "try", "def"],c:1,topic:"Циклдер"},
{q:"while циклі қашан орындалады?",a:["Әрқашан бір рет", "Шарт ақиқат болғанша", "Тек тізімде", "Функция шақырылғанда"],c:1,topic:"Циклдер"},
{q:"Циклді бірден тоқтататын команда?",a:["continue", "pass", "break", "return"],c:2,topic:"Циклді басқару"},
{q:"Функцияны анықтайтын кілт сөз?",a:["func", "function", "define", "def"],c:3,topic:"Функциялар"},
{q:"Функция нәтижесін қайтаратын оператор?",a:["break", "return", "continue", "pass"],c:1,topic:"Функциялар"},
{q:"Тізім қандай жақшамен жазылады?",a:["()", "{}", "[]", "<>"],c:2,topic:"Тізімдер"},
{q:"nums=[5,8,2] болса nums[0] мәні?",a:["8", "5", "2", "0"],c:1,topic:"Индекстер"},
{q:"Тізім соңына элемент қосатын әдіс?",a:["append()", "remove()", "sort()", "clear()"],c:0,topic:"Тізім әдістері"},
{q:"Кілт-мән жұбын сақтайтын құрылым?",a:["list", "tuple", "dict", "str"],c:2,topic:"Сөздіктер"},
{q:"Қайталанбайтын элементтер жиынының типі?",a:["set", "list", "str", "float"],c:0,topic:"Жиындар"},
{q:"Мәтінді бас әріпке айналдыратын әдіс?",a:["lower()", "upper()", "strip()", "split()"],c:1,topic:"Жолдар"},
{q:"Қате өңдеуге арналған құрылым?",a:["for/while", "if/else", "try/except", "def/return"],c:2,topic:"Қателер"}
];
function renderQuestions(){const root=document.getElementById('questions');root.innerHTML=qs.map((q,i)=>`<article class="question"><h3>${i+1}. ${q.q}</h3>${q.a.map((a,j)=>`<label class="option"><input type="radio" name="q${i}" value="${j}"><span>${a}</span></label>`).join('')}</article>`).join('')}
renderQuestions();
function gradeQuiz(){
  let correct=0, answered=0;
  const errors=[];
  qs.forEach((q,i)=>{
    const selected=document.querySelector('input[name="q'+i+'"]:checked');
    if(selected){
      answered++;
      if(Number(selected.value)===q.c) correct++;
      else errors.push(q.topic);
    }
  });
  const pct=Math.round(correct/qs.length*100);
  lastQuiz={correct,pct,answered,errors};
  const box=document.getElementById('quizResult');
  box.classList.add('show');
  box.innerHTML=
    '<div class="score">'+pct+'%</div>'+
    '<strong>'+correct+' / '+qs.length+' дұрыс жауап</strong>'+
    '<p>'+(answered<qs.length?'Сіз '+answered+' сұраққа жауап бердіңіз.':'Тест аяқталды.')+' '+
    (pct>=90?'Тамаша нәтиже!':pct>=70?'Жақсы нәтиже! Қателерді қайталаңыз.':'Материалды қайта қарап, тестті тағы орындаңыз.')+'</p>'+
    '<div class="result-grid">'+
      '<div class="result-chip"><strong>'+correct+'</strong><span>Дұрыс жауап</span></div>'+
      '<div class="result-chip"><strong>'+(qs.length-correct)+'</strong><span>Қате/жауапсыз</span></div>'+
      '<div class="result-chip"><strong>'+pct+'%</strong><span>Жалпы нәтиже</span></div>'+
    '</div>'+
    '<p style="margin-bottom:0"><strong>Қайталау керек тақырыптар:</strong> '+
    (errors.length?[...new Set(errors)].join(', '):'Қате жауап жоқ. Жарайсыз!')+'</p>';
  markDone('quiz');
  updateAnalysis();
  box.scrollIntoView({behavior:'smooth',block:'nearest'});
}
function resetQuiz(){document.getElementById('quizForm').reset();document.getElementById('quizResult').classList.remove('show');lastQuiz=null;updateAnalysis()}
function updateAnalysis(){const score=document.getElementById('analysisScore'),status=document.getElementById('analysisStatus'),meter=document.getElementById('analysisMeter'),count=document.getElementById('analysisCount'),rec=document.getElementById('recommendation');if(!lastQuiz){score.textContent='—';status.textContent='Алдымен интеллектуалды тестті орындаңыз.';meter.style.width='0';count.textContent='Дұрыс жауап: — / 20';rec.textContent='Тест нәтижесі шыққаннан кейін осы жерде сізге арналған оқу ұсынысы көрсетіледі.'}else{score.textContent=lastQuiz.pct+'%';status.textContent=lastQuiz.pct>=90?'Өте жақсы меңгердіңіз.':lastQuiz.pct>=70?'Негізгі білім қалыптасқан.':'Қайталау қажет.';meter.style.width=lastQuiz.pct+'%';count.textContent='Дұрыс жауап: '+lastQuiz.correct+' / 20';rec.textContent=lastQuiz.pct>=90?'Тақырыптарды жақсы меңгердіңіз. Енді функциялар мен циклдерді біріктіретін күрделірек есептер орындаңыз.':lastQuiz.pct>=70?'Қате кеткен сұрақтардың тақырыптарын қайталаңыз: '+([...new Set(lastQuiz.errors)].join(', ')||'теориялық материал')+'. Қосымша 2–3 жаттығу орындап, тестті қайта тапсырыңыз.':'Алдымен теориялық материалдың үш тақырыбын қайта оқыңыз. Айнымалылар, шарттар, циклдер және функциялар бойынша практикалық тапсырмаларды үлгімен салыстырып орындаңыз.'}document.getElementById('taskScore').textContent=taskCompleted.size+'/15';document.getElementById('taskMeter').style.width=(taskCompleted.size/15*100)+'%'}
const answerBank=[
{keys:['сәлем','салем','қайырлы күн','қайырлы таң','hello','hi'],text:'Сәлем! Мен CodeStart оқу көмекшісімін. Python бойынша айнымалылар, деректер типтері, операторлар, шарттар, циклдер, функциялар, тізімдер, сөздіктер және қателерді түзету тақырыптарын түсіндіре аламын. Қандай тақырыпты қарастырамыз?'},
{keys:['айнымалы','variable'],text:'Айнымалы — бағдарламада мән сақтайтын атауы бар орын. Мысалы:\n\nname = "Aruzhan"\nage = 16\n\nМұнда name және age — айнымалылар. = белгісі мән меншіктейді. Айнымалы атауы әріптен немесе төменгі сызықтан басталады, бос орын қолданылмайды. Python типті мәніне қарай өзі анықтайды.'},
{keys:['деректер типі','дерек типтері','типтер','data type','type()'],text:'Python-дағы негізгі деректер типтері:\n• int — бүтін сан: 12\n• float — бөлшек сан: 3.5\n• str — мәтін: "Сәлем"\n• bool — логикалық мән: True немесе False\n• list — тізім: [1, 2, 3]\n• tuple — өзгермейтін тізбек: (1, 2)\n• dict — кілт-мән жұбы: {"аты": "Айша"}\n• set — қайталанбайтын элементтер жиыны: {1, 2, 3}\nМәннің типін type(мән) арқылы тексеруге болады.'},
{keys:['бүтін сан','int'],text:'int — бүтін сандар типі. Мысалы: age = 17 немесе count = -3. Мәтінді бүтін санға айналдыру үшін int("25") деп жазуға болады. Егер мәтінде сан болмаса, түрлендіру қатесі пайда болады.'},
{keys:['нақты сан','бөлшек сан','float'],text:'float — бөлшек немесе нақты сандар типі. Мысалы: price = 12.5. Мәтінді float("3.14") арқылы санға айналдыруға болады. Python-да бөлшек бөлікті нүктемен жазады.'},
{keys:['мәтін','жолдық тип','string','str'],text:'str — мәтіндік деректер типі. Мәтін бір немесе қос тырнақшаға алынады: city = "Алматы". Мәтіндерді + арқылы біріктіруге болады: "Сәлем, " + "әлем!". Ұзындығын len(text) қайтарады.'},
{keys:['логикалық тип','boolean','bool','true','false'],text:'bool — екі мәннің бірін қабылдайтын логикалық тип: True немесе False. Ол шарттарды тексеруде қолданылады. Мысалы: is_student = True. Python-да True және False сөздері бас әріптен басталады.'},
{keys:['меншіктеу','теңдік операторы','оператор ='],text:'Меншіктеу операторы = айнымалыға мән береді: x = 10. Ал == екі мәннің тең екенін салыстырады: x == 10. Бұлар бірдей емес: біріншісі мәнді сақтайды, екіншісі True немесе False нәтижесін береді.'},
{keys:['арифметикалық оператор','арифметикалық амал','қосу','көбейту','бөлу'],text:'Python-дағы негізгі арифметикалық операторлар:\n• + қосу\n• - азайту\n• * көбейту\n• / бөлу (нәтиже float)\n• // бүтін бөлікке бөлу\n• % қалдықты табу\n• ** дәрежеге шығару\nМысал: 17 % 5 нәтижесі — 2, ал 2 ** 3 нәтижесі — 8.'},
{keys:['салыстыру операторы','салыстыру','үлкен кіші','==','!='],text:'Салыстыру операторлары екі мәнді салыстырып, True немесе False қайтарады: == тең; != тең емес; > үлкен; < кіші; >= үлкен немесе тең; <= кіші немесе тең. Мысалы: age >= 18.'},
{keys:['логикалық оператор','and','or','not'],text:'Логикалық операторлар шарттарды біріктіреді:\n• and — екі шарт та ақиқат болуы керек\n• or — кемінде бір шарт ақиқат болса жеткілікті\n• not — логикалық мәнді кері аударады\nМысалы: age >= 12 and age <= 18.'},
{keys:['input','print','енгізу','шығару'],text:'input() пайдаланушыдан мәлімет енгізеді және нәтижені str түрінде қайтарады. Санмен есептеу үшін int(input()) немесе float(input()) қолданыңыз. print() экранға ақпарат шығарады.\nМысал:\nname = input("Атыңыз: ")\nprint("Сәлем,", name)'},
{keys:['if','шартты оператор','шарт','elif','else'],text:'Шартты оператор бағдарламаға таңдау жасауға мүмкіндік береді. if шартты тексереді, elif қосымша шартты тексереді, else қалған жағдайды орындайды.\nМысал:\nscore = 85\nif score >= 90:\n    print("Өте жақсы")\nelif score >= 70:\n    print("Жақсы")\nelse:\n    print("Қайталау қажет")\nШарт соңына қос нүкте қойып, ішкі кодты шегініспен жазыңыз.'},
{keys:['циклдердің айырмашылығы','for мен while','for while айырмашылығы'],text:'for циклі тізім немесе range сияқты тізбектің элементтері бойынша қайталанады. while циклі шарт True болып тұрғанша орындалады. Қайталау саны белгілі болса for ыңғайлы; қайталану шартына тәуелді болса while қолайлы.'},
{keys:['for','цикл'],text:'Цикл — командаларды бірнеше рет орындау тәсілі. for циклі тізбек элементтерін бір-бірлеп алады.\nМысал:\nfor number in range(1, 6):\n    print(number)\nБұл код 1-ден 5-ке дейінгі сандарды шығарады. range(1, 6) соңғы 6 санын қоспайды.'},
{keys:['while'],text:'while циклі берілген шарт ақиқат болғанша орындалады.\nМысал:\nnumber = 1\nwhile number <= 3:\n    print(number)\n    number += 1\nНәтиже: 1, 2, 3. Цикл ішінде шартқа әсер ететін өзгеріс болуы керек, әйтпесе шексіз цикл туындауы мүмкін.'},
{keys:['range'],text:'range() сандар тізбегін құруға көмектеседі. range(5) — 0,1,2,3,4; range(1, 5) — 1,2,3,4; range(2, 10, 2) — 2,4,6,8. Соңғы шекара тізбекке кірмейді.'},
{keys:['break','continue','pass'],text:'Циклді басқару командалары:\n• break — циклді бірден тоқтатады\n• continue — ағымдағы қайталануды өткізіп, келесісіне өтеді\n• pass — еш әрекет орындамайтын бос команда; уақытша бос блок жазуға қолданылады.'},
{keys:['ішкі цикл','қабаттасқан цикл','nested loop'],text:'Ішкі немесе қабаттасқан цикл — бір циклдің ішінде екінші циклдің орналасуы. Ол кесте, координаталар және көбейту кестесі сияқты есептерге қолданылады.\nМысал:\nfor i in range(1, 3):\n    for j in range(1, 4):\n        print(i, j)\nСыртқы циклдің әр қадамында ішкі цикл толық орындалады.'},
{keys:['функция','def','return'],text:'Функция — белгілі бір әрекетті орындайтын, қайта қолдануға болатын код бөлігі. def арқылы анықталады. Параметрлер функцияға берілетін мәндерді қабылдайды, return нәтижені қайтарады.\nМысал:\ndef add(a, b):\n    return a + b\n\nprint(add(3, 4))\nНәтиже: 7.'},
{keys:['параметр','аргумент'],text:'Параметр — функция анықтамасында көрсетілетін айнымалы, ал аргумент — функция шақырылғанда берілетін нақты мән.\nМысал:\ndef greet(name):  # name — параметр\n    print("Сәлем,", name)\ngreet("Аружан")  # "Аружан" — аргумент.'},
{keys:['рекурсия','рекурсив'],text:'Рекурсия — функцияның өзінің өзін шақыруы. Рекурсияда міндетті түрде тоқтау шарты болуы керек, әйтпесе шақырулар шексіз жалғасуы мүмкін. Ол кейбір есептерді қысқа әрі құрылымды шешуге көмектеседі.'},
{keys:['тізім','list','индекс'],text:'Тізім (list) бірнеше мәнді бір айнымалыда сақтайды және өзгертіле алады.\nМысал:\nfruits = ["алма", "алмұрт", "өрік"]\nprint(fruits[0])  # алма\nИндекс 0-ден басталады. len(fruits) элементтер санын қайтарады. append() соңына элемент қосады, remove() элементті өшіреді, sort() сұрыптайды.'},
{keys:['тізімге қосу','append','элемент қосу'],text:'Тізімге элемент қосу үшін append() қолданылады:\nnums = [1, 2]\nnums.append(3)\nprint(nums)  # [1, 2, 3]\ninsert(орын, мән) нақты орынға қосады, extend() басқа тізімнің элементтерін қосады.'},
{keys:['тізімнен өшіру','remove','pop','del'],text:'Тізім элементтерін өшіру тәсілдері:\n• remove(мән) — көрсетілген мәнді өшіреді\n• pop(индекс) — элементті өшіріп, оның мәнін қайтарады\n• del — индекс бойынша элементті немесе бөлікті өшіреді\nМысал: nums = [4, 5, 6]; nums.pop(1) нәтижесінде 5 өшеді.'},
{keys:['кортеж','tuple'],text:'Кортеж (tuple) — реттелген, бірақ жасалғаннан кейін элементтері өзгертілмейтін деректер тізбегі. Дөңгелек жақшамен жазылады: point = (10, 20). Элементіне point[0] арқылы қол жеткіземіз.'},
{keys:['сөздік','dictionary','dict'],text:'Сөздік (dict) деректерді кілт пен мән жұбы түрінде сақтайды.\nМысал:\nstudent = {"name": "Aruzhan", "age": 16}\nprint(student["name"])\nКілт арқылы мәнге қол жеткіземіз. Жаңа жұп қосу: student["city"] = "Алматы". get() кілт табылмаса қауіпсіз мән қайтаруға көмектеседі.'},
{keys:['жиын','set'],text:'Жиын (set) — қайталанбайтын элементтер жиыны. Фигуралы жақшамен жазылады: nums = {1, 2, 3}. Қайталанған мәндер бір рет қана сақталады. add() элемент қосады, discard() элементті өшіреді. Жиын элементтерінің тұрақты индексі жоқ.'},
{keys:['индекс','индекстеу'],text:'Индекс — тізбектегі элементтің орны. Python-да индекс 0-ден басталады: letters = ["a", "b", "c"]; letters[0] — "a". Теріс индекс соңынан санайды: letters[-1] — соңғы элемент.'},
{keys:['кесінді','slicing','тілім','[ : ]'],text:'Кесінді (slicing) тізбектің белгілі бір бөлігін алуға мүмкіндік береді. Мысал: nums = [0,1,2,3,4]; nums[1:4] нәтижесі [1,2,3]. Бастапқы индекс кіреді, соңғы индекс кірмейді. nums[:3] басынан, nums[2:] екінші индекстен соңына дейін алады.'},
{keys:['жол әдістері','мәтін әдістері','upper','lower','split','replace'],text:'Жолдармен жұмыс істеу әдістері:\n• upper() — әріптерді бас әріпке айналдырады\n• lower() — кіші әріпке айналдырады\n• strip() — шеткі бос орындарды алып тастайды\n• split() — мәтінді бөліктерге бөледі\n• replace(a, b) — мәтіндегі бөлікті ауыстырады\nМысал: "Salem".upper() → "SALEM".'},
{keys:['f-string','форматтау','format()'],text:'f-string мәтін ішіне айнымалы мәндерін енгізуге мүмкіндік береді. f әрпін тырнақшаның алдына жазыңыз:\nname = "Aruzhan"\nage = 16\nprint(f"{name} жасы {age}-да")\nБұл тәсіл мәтін мен айнымалыны біріктіруді жеңілдетеді.'},
{keys:['ұзындық','len()'],text:'len() функциясы тізім, мәтін, кортеж сияқты объектілердегі элементтер санын немесе таңбалар санын қайтарады.\nМысал:\nword = "Python"\nprint(len(word))  # 6\nnums = [2, 4, 6]\nprint(len(nums))  # 3'},
{keys:['комментарий','түсініктеме','#'],text:'Комментарий — кодты түсіндіруге арналған, Python орындамайтын мәтін. Бір жолдық комментарий # таңбасымен жазылады:\n# Бұл — түсіндірме\nx = 5\nКомментарий кодтың мақсатын түсіндіруге және оны оқуды жеңілдетуге көмектеседі.'},
{keys:['шегініс','indentation','отступ'],text:'Python-да шегініс код блогын анықтайды. if, for, while және def ішіндегі командалар әдетте 4 бос орынмен шегіндіріледі. Шегініс дұрыс болмаса IndentationError қатесі шығуы мүмкін.'},
{keys:['синтаксистік қате','syntaxerror','қате түрлері','қате'],text:'Бағдарламада жиі кездесетін қателер:\n• SyntaxError — код жазылу ережесі бұзылған\n• NameError — анықталмаған атау қолданылған\n• TypeError — сәйкес емес типтерге амал қолданылған\n• ValueError — мәннің форматы жарамсыз\n• IndexError — тізім индексі шектен шыққан\nҚате хабарламасын оқып, көрсетілген жолды тексеріңіз.'},
{keys:['try','except','finally','ерекшелікті өңдеу'],text:'try/except қате туындауы мүмкін кодты қауіпсіз өңдеуге көмектеседі.\nМысал:\ntry:\n    age = int(input("Жас: "))\n    print(age)\nexcept ValueError:\n    print("Бүтін сан енгізіңіз")\nfinally блогы болса, қате болған-болмағанына қарамастан орындалады.'},
{keys:['файлмен жұмыс','файл оқу','open()','with open'],text:'Python файлды ашу үшін open() қолданады. Режимдер: "r" — оқу, "w" — жазу (ескі мазмұнды ауыстырады), "a" — соңына қосу. Файлды with арқылы ашу оны автоматты түрде жабуға көмектеседі:\nwith open("data.txt", "r", encoding="utf-8") as file:\n    content = file.read()'},
{keys:['модуль','import','кітапхана'],text:'Модуль — Python кодтары мен функциялары бар файл немесе кітапхана бөлігі. import арқылы қосылады.\nМысал:\nimport math\nprint(math.sqrt(25))  # 5.0\nfrom math import pi деп нақты бір атауды да импорттауға болады.'},
{keys:['random','кездейсоқ сан'],text:'random модулі кездейсоқ мәндер алуға көмектеседі.\nМысал:\nimport random\nnumber = random.randint(1, 10)\nprint(number)\nrandint(a, b) екі шекараны да қоса есептейді.'},
{keys:['математикалық модуль','math','sqrt','pi'],text:'math — математикалық функциялар мен тұрақтылар модулі. import math арқылы қосылады. math.sqrt(25) квадрат түбірді табады, math.ceil(2.2) жоғары бүтінге дөңгелектейді, math.floor(2.8) төмен бүтінге дөңгелектейді, math.pi π тұрақтысын береді.'},
{keys:['алгоритм','алгоритм деген'],text:'Алгоритм — белгілі бір есепті шешуге арналған нақты әрі реттелген әрекеттер тізбегі. Негізгі қасиеттері: анықтылық, қадамдылық, нәтижелілік және жалпылық. Бағдарлама жазбас бұрын есептің кіріс деректерін, орындалатын қадамдарын және нәтижесін анықтаған дұрыс.'},
{keys:['python деген не','python тілі','бағдарламалау тілі'],text:'Python — оқуға және жазуға ыңғайлы жоғары деңгейлі бағдарламалау тілі. Ол веб-әзірлеуде, деректерді талдауда, автоматтандыруда, ғылыми есептеулерде және білім беруде қолданылады. Python коды интерпретатор арқылы орындалады.'},
{keys:['ide','бағдарлама жазу ортасы','редактор'],text:'IDE — код жазуға, іске қосуға және қателерді іздеуге арналған интеграцияланған әзірлеу ортасы. Python үшін IDLE, PyCharm және Visual Studio Code сияқты құралдар қолданылады. Бастапқы үйрену кезінде қарапайым редактор мен Python интерпретаторы жеткілікті.'},
{keys:['debug','debugging','қателерді түзету','түзету'],text:'Debugging — бағдарламадағы қателерді табу және түзету үдерісі. Алдымен қате хабарламасын оқыңыз, көрсетілген жолды тексеріңіз, айнымалылар мәнін print() арқылы бақылаңыз және кодты шағын бөліктермен іске қосыңыз.'},
{keys:['мысал','мысал келтір','код жаз','бағдарлама жаз'],text:'Мысал ретінде екі санның қосындысын есептейік:\na = int(input("Бірінші сан: "))\nb = int(input("Екінші сан: "))\nresult = a + b\nprint("Қосынды:", result)\nБұл бағдарлама екі мәнді енгізіп, оларды бүтін санға айналдырады және қосындысын шығарады.'},
{keys:['көмек','не істей аласың','тақырыптар'],text:'Мен мына тақырыптар бойынша көмектесемін:\n1. Айнымалылар және деректер типтері\n2. Енгізу/шығару және операторлар\n3. Шартты операторлар\n4. for, while циклдері\n5. Функциялар және параметрлер\n6. Тізім, кортеж, сөздік, жиын\n7. Мәтіндер мен файлдар\n8. Модульдер, қателер және алгоритмдер\nСұрағыңызды жазыңыз немесе кодты жіберіп, түсіндіруді сұраңыз.'}
];
function sendChat(){
  const input=document.getElementById('chatInput');
  const q=input.value.trim();
  if(!q){
    addBubble('Алдымен сұрағыңызды жазыңыз. Мысалы: Python-да цикл қалай жұмыс істейді?','bot');
    input.focus();
    return;
  }
  addBubble(q,'user');
  input.value='';
  const lower=q.toLowerCase().replace(/ё/g,'е');
  const found=answerBank.find(item=>item.keys.some(key=>{
    const k=key.toLowerCase();
    // Ағылшын тіліндегі Python кілт сөздерін жеке сөз ретінде тексеру:
    if(/^[a-z_][a-z0-9_]*$/i.test(k)){
      return new RegExp('(^|[^a-z0-9_])'+k.replace(/[.*+?^${}()|[\]\\]/g,'\\$&')+'([^a-z0-9_]|$)','i').test(lower);
    }
    return lower.includes(k);
  }));
  let response=found ? found.text :
    'Бұл сұрақ бойынша дайын жауап қорынан дәл сәйкестік табылмады. Сұрағыңызды басқаша тұжырымдап көріңіз немесе тақырып атауын жазыңыз. Мен Python айнымалылары, деректер типтері, операторлар, шарттар, циклдер, функциялар, тізімдер, сөздіктер, файлдар және қателерді түзету бойынша түсіндіре аламын.';
  if(lower.includes('айырмашылық') && lower.includes('for') && lower.includes('while')){
    response='for циклі тізім немесе range сияқты тізбек элементтерін қайталау үшін қолданылады. while циклі шарт ақиқат болып тұрғанша орындалады. Қайталау саны белгілі болса for, ал қайталану шартқа тәуелді болса while ыңғайлы.';
  }
  addBubble(response,'bot');
  markDone('assistant');
}
document.getElementById('chatInput').addEventListener('keydown',function(e){
  if(e.key==='Enter' && (e.ctrlKey || e.metaKey)){
    e.preventDefault();
    sendChat();
  }
});
function addBubble(text,kind){const el=document.createElement('div');el.className='bubble '+kind;el.textContent=text;const area=document.getElementById('chatMessages');area.appendChild(el);area.scrollTop=area.scrollHeight}
showPanel('home');
</script>
</body>
</html>

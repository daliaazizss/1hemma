# 1hemma
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>هِمّة - الوصول الشامل</title>
  <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700&display=swap" rel="stylesheet"/>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>
  <style>
    body {
      margin: 0;
      font-family: 'Tajawal', sans-serif;
      background: #f7f7f7;
      color: #333;
      scroll-behavior: smooth;
    }

    .marquee {
      background: #dfe6e9;
      padding: 10px;
      color: #2d3436;
      font-weight: bold;
      font-size: 18px;
      white-space: nowrap;
      overflow: hidden;
    }

    .marquee span {
      display: inline-block;
      padding-left: 100%;
      animation: scrollText 15s linear infinite;
    }

    @keyframes scrollText {
      0% { transform: translateX(0); }
      100% { transform: translateX(-100%); }
    }

    header {
      background: #e0e0e0;
      padding: 20px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
      color: #2c3e50;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #2c3e50;
      font-weight: bold;
    }

    section {
      padding: 60px 20px;
      background: #fff;
      margin: 20px auto;
      max-width: 1000px;
      border-radius: 10px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      animation: fadeInUp 1s ease-in-out;
    }

    section h2 {
      text-align: center;
      color: #34495e;
      margin-bottom: 20px;
    }

    section p {
      font-size: 1.2em;
      line-height: 1.8;
      text-align: justify;
    }

    .features, .quotes, .facts {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      margin-top: 40px;
    }

    .feature, .quote, .fact {
      background: #ecf0f1;
      padding: 20px;
      margin: 10px;
      border-radius: 8px;
      flex: 1 1 250px;
      text-align: center;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .feature:hover, .quote:hover, .fact:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.15);
    }

    .feature i {
      font-size: 2em;
      color: #2980b9;
      margin-bottom: 10px;
    }

    iframe {
      width: 100%;
      height: 300px;
      border: none;
      border-radius: 10px;
    }

    #scrollTopBtn {
      position: fixed;
      bottom: 30px;
      left: 30px;
      background: #2980b9;
      color: #fff;
      border: none;
      padding: 10px 15px;
      border-radius: 50%;
      font-size: 1.5em;
      cursor: pointer;
      display: none;
      z-index: 1000;
      transition: background 0.3s;
    }

    #scrollTopBtn:hover {
      background: #1abc9c;
    }

    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @media (max-width: 600px) {
      .features, .quotes, .facts {
        flex-direction: column;
        align-items: center;
      }
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #dcdde1;
      color: #2f3640;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <div class="marquee">
    <span>أهلاً بكم في منصة هِمّة - نسعى لمجتمع أكثر شمولية ووعي 💙</span>
  </div>

  <header>
    <h1>هِمّة</h1>
    <nav>
      <a href="#about">من نحن</a>
      <a href="#features">الخدمات</a>
      <a href="#quotes">التحفيز</a>
      <a href="#facts">حقائق</a>
      <a href="#video">الرؤية</a>
      <a href="#support">الرسالة</a>
    </nav>
  </header>

  <section id="about">
    <h2>من نحن</h2>
    <p>نحن في <strong>هِمّة</strong> فريق يؤمن بحق ذوي الهمم في الوصول السهل والآمن إلى كل مكان. صممنا هذه المنصّة لتكون دليلكم الأول للأماكن والخدمات المهيأة، لتسهيل حياتكم،
وتعزيز استقلاليتكم، ودعم مجتمع أكثر شمولية ووعي.</p>
  </section>

  <section id="features">
    <h2>الخدمات</h2>
    <div class="features">
      <div class="feature">
        <i class="fas fa-bus"></i>
        <h3>تنقل</h3>
        <p>مواصلات مجهزة ومواقف خاصة.</p>
      </div>
      <div class="feature">
        <i class="fas fa-gamepad"></i>
        <h3>ترفيه</h3>
        <p>أنشطة ممتعة لجميع القدرات.</p>
      </div>
      <div class="feature">
        <i class="fas fa-hospital"></i>
        <h3>مراكز</h3>
        <p>مرافق طبية وخدمية مهيأة بالكامل.</p>
      </div>
      <div class="feature">
        <i class="fas fa-dumbbell"></i>
        <h3>نوادي</h3>
        <p>أماكن رياضية تناسب كل الاحتياجات.</p>
      </div>
    </div>
  </section>

  <section id="quotes">
    <h2>عبارات تحفيزية</h2>
    <div class="quotes">
      <div class="quote">"قد تكون مختلفًا، لكنك لست أقل!"</div>
      <div class="quote">"الهمّة طريقك للقمّة 💪"</div>
      <div class="quote">"الإصرار يتجاوز أي عائق"</div>
      <div class="quote">"أنت القوة.. أنت الأمل ✨"</div>
      <div class="quote">"قدراتك أكبر مما تتخيل"</div>
    </div>
  </section>

  <section id="facts">
    <h2>حقائق ملهمة</h2>
    <div class="facts">
      <div class="fact">أكثر من مليار شخص حول العالم يعيشون بإعاقات.</div>
      <div class="fact">سهولة الوصول ليست ميزة، بل حق.</div>
      <div class="fact">كل بيئة مهيأة تفتح أبوابًا جديدة للنجاح.</div>
    </div>
  </section>

  <section id="video">
    <h2>رسالة هِمّة 💙</h2>
    <iframe src="https://www.youtube.com/watch?v=KuZX9WS_tfQ" allowfullscreen></iframe>
  </section>

  <!-- القسم الجديد: ختام يخدم المشروع -->
  <section id="support">
    <h2>ختامها... هِمّة لا تنكسر 💙</h2>
    <div class="facts">
      <div class="fact">
        لأننا نؤمن أن الوصول حق للجميع، جاءت منصة <strong>هِمّة</strong> لتكون صوت ذوي الهمم في كل مكان.
        رؤيتنا أن نخلق بيئة شاملة، مهيأة، ومليئة بالفرص لجميع أفراد المجتمع، دون استثناء.
        <br><br>
        🌟 انضموا لنا في رحلتنا نحو مستقبل أكثر شمولية ووعي.
        كونوا الداعمين، كونوا الصانعين للتغيير.
        أنتم الهمّة... وأنتم الأمل. ✨
      </div>
    </div>
  </section>

  <button id="scrollTopBtn" onclick="scrollToTop()">↑</button>

  <footer>
    حقوق طالبات ثالث ثانوي - مشروع هِمّة 💙
  </footer>

  <script>
    const scrollBtn = document.getElementById("scrollTopBtn");
    window.onscroll = () => {
      scrollBtn.style.display = window.scrollY > 300 ? "block" : "none";
    };
    function scrollToTop() {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    }
  </script>

</body>
</html>

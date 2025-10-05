<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>عرض المشاريع</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Cairo&family=Tajawal&display=swap" rel="stylesheet" />

  <style>
    /* --- الألوان والهوية البصرية --- */
    :root {
      --color-primary-dark: #003366; /* أزرق داكن */
      --color-primary-light: #1976D2; /* أزرق فاتح */
      --color-secondary: #D32F2F; /* أحمر */
      --color-white: #FFFFFF;
      --color-black: #000000;
    }

    /* الخطوط */
    body {
      margin: 0;
      font-family: 'Tajawal', 'Cairo', sans-serif;
      background-color: var(--color-white);
      color: var(--color-primary-dark);
      line-height: 1.6;
    }

    a {
      color: var(--color-primary-light);
      text-decoration: none;
      transition: color 0.3s ease;
    }
    a:hover {
      color: var(--color-secondary);
    }

    /* الهيدر مع الفيديو التعريفي */
    header {
      background-color: var(--color-primary-dark);
      color: var(--color-white);
      padding: 1rem;
      text-align: center;
      position: relative;
    }

    header h1 {
      margin: 0 0 0.5rem;
      font-weight: 700;
      font-size: 2rem;
    }

    .video-container {
      max-width: 700px;
      margin: 0 auto;
      position: relative;
      padding-bottom: 56.25%; /* 16:9 */
      height: 0;
      overflow: hidden;
      border-radius: 8px;
      box-shadow: 0 0 15px rgba(0,0,0,0.3);
    }

    .video-container iframe {
      position: absolute;
      top:0;
      left:0;
      width: 100%;
      height: 100%;
      border: none;
    }

    /* التنقل */
    nav {
      background-color: var(--color-primary-dark);
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }

    nav ul {
      margin: 0;
      padding: 0 1rem;
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 2rem;
    }

    nav ul li {
      display: inline-block;
    }

    nav ul li a {
      color: var(--color-white);
      font-weight: 600;
      padding: 1rem 0;
      display: block;
    }

    nav ul li a:hover {
      color: var(--color-secondary);
    }

    /* القسم الرئيسي */
    main {
      max-width: 1200px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    /* أقسام المشاريع */
    section.projects-section {
      margin-bottom: 3rem;
    }

    section.projects-section h2 {
      font-size: 1.8rem;
      margin-bottom: 1rem;
      border-bottom: 3px solid var(--color-primary-light);
      padding-bottom: 0.3rem;
    }

    /* أزرار المشاريع قيد التنفيذ */
    .projects-buttons {
      display: flex;
      flex-wrap: wrap;
      gap: 1.5rem;
      justify-content: center;
    }

    .project-btn {
      background: linear-gradient(145deg, var(--color-primary-light), var(--color-primary-dark));
      color: var(--color-white);
      border: none;
      border-radius: 12px;
      padding: 1.2rem 2rem;
      font-size: 1.2rem;
      font-weight: 700;
      cursor: pointer;
      box-shadow:
        4px 4px 6px rgba(0, 0, 0, 0.3),
        -4px -4px 6px rgba(255, 255, 255, 0.1);
      transition: all 0.3s ease;
      display: flex;
      align-items: center;
      gap: 0.8rem;
      min-width: 220px;
    }

    .project-btn:hover {
      box-shadow:
        6px 6px 10px rgba(0, 0, 0, 0.4),
        -6px -6px 10px rgba(255, 255, 255, 0.15);
      transform: translateY(-4px);
      background: linear-gradient(145deg, var(--color-secondary), #a52727);
    }

    .project-btn svg {
      width: 24px;
      height: 24px;
      fill: var(--color-white);
    }

    /* بطاقات المشاريع المقترحة */
    .projects-cards {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(280px,1fr));
      gap: 1.8rem;
    }

    .project-card {
      background: var(--color-white);
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      overflow: hidden;
      display: flex;
      flex-direction: column;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      cursor: pointer;
    }

    .project-card:hover {
      transform: translateY(-8px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.15);
    }

    .project-card img {
      width: 100%;
      height: 160px;
      object-fit: cover;
    }

    .project-card-content {
      padding: 1rem 1.2rem;
      flex-grow: 1;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .project-card-content h3 {
      margin: 0 0 0.5rem;
      color: var(--color-primary-dark);
    }

    .project-card-content p {
      flex-grow: 1;
      color: #555;
      font-size: 0.95rem;
      line-height: 1.3;
    }

    .btn-details {
      margin-top: 1rem;
      align-self: flex-start;
      background-color: var(--color-secondary);
      color: var(--color-white);
      border: none;
      padding: 0.6rem 1.2rem;
      border-radius: 8px;
      font-weight: 600;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .btn-details:hover {
      background-color: #a52727;
    }

    /* تأثيرات ظهور تدريجي */
    .fade-in {
      opacity: 0;
      transform: translateY(20px);
      animation: fadeInUp 0.8s forwards;
    }

    @keyframes fadeInUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* Responsive */
    @media (max-width: 600px) {
      nav ul {
        flex-direction: column;
        gap: 1rem;
      }

      .projects-buttons {
        flex-direction: column;
        align-items: center;
      }
    }

    /* --- تصميم النافذة المنبثقة (Modal) --- */
    .modal-overlay {
      position: fixed;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0,0,0,0.6);
      display: flex;
      justify-content: center;
      align-items: center;
      visibility: hidden;
      opacity: 0;
      transition: opacity 0.3s ease;
      z-index: 2000;
    }

    .modal-overlay.active {
      visibility: visible;
      opacity: 1;
    }

    .modal {
      background: var(--color-white);
      border-radius: 12px;
      max-width: 400px;
      width: 90%;
      padding: 1.5rem 2rem;
      box-shadow: 0 8px 20px rgba(0,0,0,0.25);
      position: relative;
      text-align: center;
      font-size: 1.1rem;
      color: var(--color-primary-dark);
    }

    .modal h3 {
      margin-top: 0;
      font-weight: 700;
      margin-bottom: 1rem;
    }

    .modal p {
      margin-bottom: 1.5rem;
      line-height: 1.4;
    }

    .modal-close {
      position: absolute;
      top: 10px;
      left: 15px;
      font-size: 1.8rem;
      font-weight: 700;
      color: var(--color-secondary);
      background: none;
      border: none;
      cursor: pointer;
      transition: color 0.3s ease;
    }

    .modal-close:hover {
      color: #a52727;
    }
  </style>
</head>
<body>

  <!-- التنقل -->
  <nav>
    <ul>
      <li><a href="#">الرئيسية</a></li>
      <li><a href="#">من نحن</a></li>
      <li><a href="#">المشاريع</a></li>
      <li><a href="#">الأنشطة</a></li>
      <li><a href="#">حجز الأسهم</a></li>
      <li><a href="#">اتصل بنا</a></li>
    </ul>
  </nav>

  <!-- الهيدر مع فيديو تعريفي -->
  <header>
    <h1>رؤية الشركة ومشاريعنا</h1>
    <div class="video-container fade-in">
      <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="فيديو تعريفي" allowfullscreen></iframe>
    </div>
  </header>

  <!-- المحتوى الرئيسي -->
  <main>

    <!-- المشاريع قيد التنفيذ -->
    <section class="projects-section">
      <h2>المشاريع قيد التنفيذ</h2>
      <div class="projects-buttons fade-in" style="animation-delay: 0.2s;">
        <button class="project-btn" onclick="alert('تفاصيل مشروع الدواجن اللاحم')">
          <!-- أيقونة دجاجة -->
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M13 2c-1 0-2 .5-2 1.5S12 5 13 5s2-.5 2-1.5S14 2 13 2zM6 15v4h2v-4H6zm10-3v7h2v-7h-2zM3 12v7h2v-7H3z"/></svg>
          مشروع الدواجن اللاحم
        </button>
        <button class="project-btn" onclick="alert('تفاصيل مشروع الطاقة الشمسية')">
          <!-- أيقونة شمس -->
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 4.5a1 1 0 0 1 1 1v1a1 1 0 0 1-2 0v-1a1 1 0 0 1 1-1zm0 11a4.5 4.5 0 1 0 0-9 4.5 4.5 0 0 0 0 9zm6.364-5.364 1.415-1.415 1.414 1.414-1.414 1.415-1.415-1.414zm-12.728 0-1.414-1.415 1.414-1.414 1.415 1.414-1.415 1.415zm12.728 5.728 1.415 1.414-1.414 1.415-1.415-1.414 1.414-1.415zm-12.728 0-1.414 1.415-1.415-1.414 1.415-1.415 1.414 1.414zM12 19.5a1 1 0 0 1 1 1v1a1 1 0 0 1-2 0v-1a1 1 0 0 1 1-1z"/></svg>
          مشروع الطاقة الشمسية
        </button>
      </div>
    </section>

    <!-- المشاريع المقترحة -->
    <section class="projects-section">
      <h2>المشاريع المقترحة</h2>
      <div class="projects-cards fade-in" style="animation-delay: 0.4s;">
        <div class="project-card" onclick="alert('تفاصيل مشروع الزراعة الذكية')">
          <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=600&q=80" alt="مشروع الزراعة الذكية" />
          <div class="project-card-content">
            <h3>مشروع الزراعة الذكية</h3>
            <p>استخدام التكنولوجيا لتحسين الإنتاج الزراعي وتقليل الهدر.</p>
            <button class="btn-details">المزيد من التفاصيل</button>
          </div>
        </div>
        <div class="project-card" onclick="alert('تفاصيل مشروع إعادة التدوير')">
          <img src="https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=600&q=80" alt="مشروع إعادة التدوير" />
          <div class="project-card-content">
            <h3>مشروع إعادة التدوير</h3>
            <p>تحويل النفايات إلى موارد قابلة للاستخدام للحفاظ على البيئة.</p>
            <button class="btn-details">المزيد من التفاصيل</button>
          </div>
        </div>
      </div>
    </section>

  </main>

  <!-- نافذة منبثقة (Modal) -->
  <div id="welcomeModal" class="modal-overlay">
    <div class="modal" role="dialog" aria-modal="true" aria-labelledby="modalTitle" aria-describedby="modalDesc">
      <button class="modal-close" aria-label="إغلاق النافذة">&times;</button>
      <h3 id="modalTitle">مرحبًا بكم في منصة Sudanese Dream</h3>
      <p id="modalDesc">
        نسعى لتحقيق أحلام السودان من خلال مشاريعنا المبتكرة والمستدامة. تصفح مشاريعنا وقم بالتواصل معنا للمزيد من المعلومات.
      </p>
      <button onclick="document.getElementById('welcomeModal').classList.remove('active')" class="btn-details">أغلق</button>
    </div>
  </div>

  <script>
    // إظهار النافذة المنبثقة عند تحميل الصفحة
    window.addEventListener('load', () => {
      const modal = document.getElementById('welcomeModal');
      modal.classList.add('active');
    });

    // إغلاق النافذة عند الضغط على زر الإغلاق
    document.querySelector('.modal-close').addEventListener('click', () => {
      document.getElementById('welcomeModal').classList.remove('active');
    });

    // إغلاق النافذة عند الضغط خارجها
    document.getElementById('welcomeModal').addEventListener('click', (e) => {
      if(e.target === e.currentTarget) {
        e.currentTarget.classList.remove('active');
      }
    });
  </script>
</body>
</html>

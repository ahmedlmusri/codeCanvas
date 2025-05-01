<template>
  <div class="code-canvas" dir="rtl">
    <!-- Header Section -->
    <header class="header">
      <div class="container">
        <nav class="navbar">
          <div class="logo">
            <img src="/assets/images/logo.png" alt="كود كانفاس" class="logo-img">
            <span class="logo-text">كود كنفاس</span>
          </div>
          <div class="nav-links">
            <a href="#home">الرئيسية</a>
            <a href="#courses">الدورات</a>
            <a href="#company">عن الشركة</a>
            <a href="#footer">اتصل بنا</a>
          </div>
        </nav>
      </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
      <div class="container">
        <div class="hero-content">
          <h1>مرحباً بك في كود كانفاس</h1>
          <p>شكل مستقبلك مع دوراتنا البرمجية بقيادة خبراء المجال</p>
          <button class="cta-button" @click="scrollToCourses">استكشف الدورات</button>
        </div>
      </div>
    </section>

    <!-- What We Do Section -->
    <section class="what-we-do" id="company">
      <div class="container">
        <p class="section-subtitle">ماذا نقدم</p>
        <h2 class="section-title">إمكانيات لا حدود لها</h2>
        <div class="underline"></div>
        <div class="features-grid">
          <div class="feature-card">
            <div class="feature-icon">
              <!-- Book Icon -->
              <svg width="48" height="48" fill="none" stroke="#27ae60" stroke-width="2" viewBox="0 0 24 24"><rect x="3" y="6" width="18" height="13" rx="2"/><path d="M16 3v4M8 3v4"/><circle cx="17" cy="8" r="1"/><rect x="7" y="10" width="6" height="2" rx="1"/></svg>
            </div>
            <h3>دورات عبر الإنترنت</h3>
            <p>اختر من مئات الدورات التدريبية المجانية، أو ادفع للحصول على شهادة لإكمال دورة أو تخصص.</p>
          </div>
          <div class="feature-card">
            <div class="feature-icon">
              <!-- Lightbulb Icon -->
              <svg width="48" height="48" fill="none" stroke="#27ae60" stroke-width="2" viewBox="0 0 24 24"><path d="M9 18h6M10 22h4M12 2a7 7 0 0 1 7 7c0 2.5-1.5 4.5-3.5 5.5V17a1 1 0 0 1-2 0v-2.5C6.5 13.5 5 11.5 5 9a7 7 0 0 1 7-7z"/></svg>
            </div>
            <h3>مهمتنا</h3>
            <p>تطوير رؤية ورسالة قوية تساعد المتعلمين في مدرستنا على الوصول إلى فهم مشترك.</p>
          </div>
          <div class="feature-card">
            <div class="feature-icon">
              <!-- Certificate Icon -->
              <svg width="48" height="48" fill="none" stroke="#27ae60" stroke-width="2" viewBox="0 0 24 24"><circle cx="12" cy="12" r="10"/><path d="M12 16v-4M12 8h.01"/></svg>
            </div>
            <h3>شهادة احترافية</h3>
            <p>انضم إلى ملايين الطلاب حول العالم الذين يتعلمون بالفعل! اعثر على مدرب خبير ومناسب لك.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Popular Courses Section -->
    <section id="courses" class="popular-courses">
      <div class="container">
        <p class="section-subtitle">الخيار الأفضل</p>
        <h2 class="section-title">الدورات الشائعة</h2>
        <div class="underline"></div>
        <div class="popular-courses-grid">
          <div class="popular-course-card">
            <div class="course-image">
              <img src="/assets/images/frontend.avif" alt="Frontend Development">
            </div>
            <span class="course-tag development">Frontend</span>
            <div class="course-content">
              <h3>تطوير واجهات المستخدم</h3>
              <p>تعلم HTML, CSS, JavaScript وأطر العمل الحديثة</p>
              <div class="course-meta">
                <p class="course-price">2,000 جنيه</p>
                <button class="enroll-button" disabled>قريباً</button>
              </div>
            </div>
          </div>

          <div class="popular-course-card">
            <div class="course-image">
              <img src="/assets/images/backend.jpg" alt="Backend Development">
            </div>
            <span class="course-tag development">Backend</span>
            <div class="course-content">
              <h3>تطوير خلفيات المواقع</h3>
              <p>تعلم Node.js, Python, Databases وأكثر</p>
              <div class="course-meta">
                <p class="course-price">2,000 جنيه</p>
                <button class="enroll-button" disabled>قريباً</button>
              </div>
            </div>
          </div>

          <div class="popular-course-card">
            <div class="course-image">
              <img src="/assets/images/mobile.jpeg" alt="Mobile Development">
            </div>
            <span class="course-tag development">Mobile Application</span>
            <div class="course-content">
              <h3>تطوير تطبيقات الموبايل</h3>
              <p>تعلم React Native, Flutter وتطوير iOS/Android</p>
              <div class="course-meta">
                <p class="course-price">2,500 جنيه</p>
                <button class="enroll-button" disabled>قريباً</button>
              </div>
            </div>
          </div>

          <div class="popular-course-card">
            <div class="course-image">
              <img src="/assets/images/design.jpeg" alt="Graphic Design">
            </div>
            <span class="course-tag design">Graphic Designer</span>
            <div class="course-content">
              <h3>التصميم الجرافيكي</h3>
              <p>تعلم Photoshop, Illustrator والتصميم الإبداعي</p>
              <div class="course-meta">
                <p class="course-price">1,200 جنيه</p>
                <button class="enroll-button" disabled>قريباً</button>
              </div>
            </div>
          </div>

          <div class="popular-course-card">
            <div class="course-image">
              <img src="/assets/images/english.webp" alt="English Course">
            </div>
            <span class="course-tag language">English Course</span>
            <div class="course-content">
              <h3>دورة اللغة الإنجليزية</h3>
              <p>تعلم المحادثة، الكتابة والتواصل باحترافية</p>
              <div class="course-meta">
                <p class="course-price">1,400 جنيه</p>
                <button class="enroll-button" disabled>قريباً</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Stats Section -->
    <section class="stats-section">
      <div class="stats-bg">
        <div class="stats-overlay"></div>
      </div>
      <div class="container stats-content">
        <p class="section-subtitle">الخيار الأفضل</p>
        <h2 class="section-title">دورات مفيدة وشائعة</h2>
        <div class="underline"></div>
        <div class="stats-grid">
          <div class="stat-card">
            <div class="stat-icon">
              <svg width="48" height="48" fill="none" stroke="#27ae60" stroke-width="2" viewBox="0 0 24 24"><circle cx="12" cy="8" r="4"/><path d="M4 20c0-4 8-4 8-4s8 0 8 4"/></svg>
            </div>
            <div class="stat-value">1,000</div>
            <div class="stat-label">متعلم تم تدريبهم</div>
          </div>
          <div class="stat-card">
            <div class="stat-icon">
              <svg width="48" height="48" fill="none" stroke="#27ae60" stroke-width="2" viewBox="0 0 24 24"><path d="M12 3L2 9l10 6 10-6-10-6z"/><path d="M2 9v6c0 2.21 3.58 4 8 4s8-1.79 8-4V9"/></svg>
            </div>
            <div class="stat-value">1,000</div>
            <div class="stat-label">خريج</div>
          </div>
          <div class="stat-card">
            <div class="stat-icon">
              <svg width="48" height="48" fill="none" stroke="#27ae60" stroke-width="2" viewBox="0 0 24 24"><rect x="3" y="6" width="18" height="13" rx="2"/><path d="M16 3v4M8 3v4"/></svg>
            </div>
            <div class="stat-value">20</div>
            <div class="stat-label">دورة منشورة</div>
          </div>
          <div class="stat-card">
            <div class="stat-icon">
              <svg width="48" height="48" fill="none" stroke="#27ae60" stroke-width="2" viewBox="0 0 24 24"><circle cx="12" cy="12" r="10"/><path d="M2 12h20M12 2a15.3 15.3 0 0 1 0 20M12 2a15.3 15.3 0 0 0 0 20"/></svg>
            </div>
            <div class="stat-value">5,584</div>
            <div class="stat-label">متعلم حول العالم</div>
          </div>
        </div>
      </div>
    </section>

   

    <!-- Footer -->
    <footer class="footer" id="footer">
      <div class="container">
        <div class="footer-grid">
          <!-- Logo and Info Column -->
          <div class="footer-col">
            <div class="footer-logo">
              كود كانفاس
            </div>
            <p class="footer-description">
              شكل مستقبلك مع دوراتنا البرمجية بقيادة خبراء المجال. انضم إلى مجتمعنا من المتعلمين وحقق أهدافك.
            </p>
            <div class="contact-info">
              <p><i class="location-icon">📍</i> 192 ميدان الحصري ٦ اكتوبر</p>
              <p><i class="email-icon">✉️</i> codeCanvas@info.com</p>
              <p><i class="phone-icon">📞</i>  (+20) 123-4567</p>
            </div>
          </div>

          <!-- Recent Posts Column -->
          <div class="footer-col">
            <h3 class="footer-title">آخر المقالات</h3>
            <div class="recent-posts">
              <div class="post-item">
                <img src="/assets/images/news1.png" alt="طالب يحلل" class="post-thumb">
                <div class="post-info">
                  <h4>أهم 7 مهارات مطلوبة في سوق العمل 2025</h4>
                  <p class="post-meta">01.02.2024 بواسطة عبدالله </p>
                </div>
              </div>
              <div class="post-item">
                <img src="/assets/images/student.jpg" alt="طالب يحلل" class="post-thumb">
                <div class="post-info">
                  <h4>5 نصائح لإتمام أي كورس أونلاين بدون ملل</h4>
                  <p class="post-meta">28.01.2024 بواسطة عبدالله </p>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- Footer Bottom -->
        <div class="footer-bottom">
          <p class="copyright">كود كانفاس © 2024 جميع الحقوق محفوظة. شروط الاستخدام وسياسة الخصوصية</p>
          <div class="social-links">
            <a href="#" class="social-link">𝕏</a>
            <a href="https://www.facebook.com/profile.php?id=61575783206612" class="social-link" target="_blank" rel="noopener noreferrer">f</a>
            <a href="#" class="social-link">t</a>
            <a href="#" class="social-link">📷</a>
          </div>
        </div>
      </div>
    </footer>

  </div>
</template>

<script>
export default {
  data() {
    return {
      menuActive: false
    };
  },
  methods: {
    scrollToCourses() {
      const coursesSection = document.getElementById('courses');
      if (coursesSection) {
        coursesSection.scrollIntoView({ 
          behavior: 'smooth',
          block: 'start'
        });
      }
    },
    toggleMenu() {
      this.menuActive = !this.menuActive;
    }
  }
}
</script>

<style>
/* Reset and Base Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

:root {
  --primary-color: #E86C2C;  /* Orange from logo */
  --primary-dark: #d15a1f;   /* Darker orange */
  --secondary-color: #002B4D; /* Navy blue from logo */
  --text-color: #002B4D;     /* Navy blue for text */
  --light-gray: #f5f6fa;
  --white: #ffffff;
  --shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  --transition: all 0.3s ease;
}

body {
  font-family: 'Cairo', sans-serif;
  line-height: 1.6;
  direction: rtl;
  color: var(--text-color);
  background-color: var(--light-gray);
  margin: 0; /* Remove default margin */
}

.container {
  max-width: 1200px; /* Set a max width for larger screens */
  margin: 0 auto; /* Center the container */
  padding: 0 20px; /* Add padding */
}

/* Header Styles */
.header {
  background-color: #062847;
  box-shadow: var(--shadow);
  position: fixed;
  width: 100%;
  z-index: 1000;
  padding: 15px 0;
}

.logo {
  display: flex;
  align-items: center;
  gap: 15px;
}

.logo-img {
  height: 74px;
}

.logo-text {
  color: #fff;
  font-size: 24px;
  font-weight: 700;
  letter-spacing: -0.5px;
  margin-right: -21px;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0;
}

.nav-links {
  display: flex;
  gap: 30px;
}

.nav-links a {
  color: var(--white);
  text-decoration: none;
  font-weight: 600;
  font-size: 16px;
  padding: 8px 0;
  position: relative;
  transition: var(--transition);
}

.nav-links a::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  width: 0;
  height: 2px;
  background-color: var(--primary-color);
  transition: var(--transition);
}

.nav-links a:hover {
  color: var(--primary-color);
}

.nav-links a:hover::after {
  width: 100%;
}

/* Hero Section */
.hero {
  background: linear-gradient(rgba(6, 40, 71, 0.8), rgba(6, 40, 71, 0.9)), url('/assets/images/cover.jpg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center; /* Center content */
  text-align: center;
  color: var(--white);
  padding-top: 80px;
  position: relative;
}

.hero::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: radial-gradient(circle at center, rgba(232, 108, 44, 0.2), transparent);
}

.hero-content {
  position: relative;
  z-index: 2;
  max-width: 800px;
  margin: 0 auto;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  height: 100%;
}

.hero-content h1 {
  font-size: 56px;
  margin-bottom: 30px;
  font-weight: 800;
  line-height: 1.2;
  text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
}

.hero-content p {
  font-size: 24px;
  margin-bottom: 40px;
  font-weight: 400;
  opacity: 0.9;
}

.cta-button {
  background-color: var(--primary-color);
  color: var(--white);
  padding: 18px 40px;
  border: none;
  border-radius: 30px;
  font-size: 18px;
  font-weight: 600;
  cursor: pointer;
  transition: var(--transition);
  text-transform: uppercase;
  letter-spacing: 1px;
  box-shadow: var(--shadow);
}

.cta-button:hover {
  background-color: var(--primary-dark);
  transform: translateY(-2px);
  box-shadow: 0 6px 12px rgba(0,0,0,0.15);
}

/* Feature Cards */
.what-we-do {
  padding: 100px 0;
  background-color: var(--white);
  text-align: center;
}

.section-subtitle {
  color: var(--primary-color);
  font-size: 18px;
  font-weight: 600;
  margin-bottom: 15px;
  text-transform: uppercase;
  letter-spacing: 2px;
  text-align: center;
}

.section-title {
  font-size: 42px;
  color: var(--secondary-color);
  margin-bottom: 20px;
  font-weight: 700;
  text-align: center;
}

.underline {
  width: 80px;
  height: 4px;
  background-color: var(--primary-color);
  margin: 0 auto 50px;
}

.features-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
  margin-top: 50px;
}

.feature-card {
  background: var(--white);
  padding: 40px 30px;
  border-radius: 15px;
  text-align: center;
  transition: var(--transition);
  box-shadow: var(--shadow);
}

.feature-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 8px 16px rgba(0,0,0,0.1);
}

.feature-icon {
  margin-bottom: 25px;
  color: var(--primary-color);
}

.feature-card h3 {
  font-size: 24px;
  margin-bottom: 15px;
  color: var(--secondary-color);
}

.feature-card p {
  color: #666;
  font-size: 16px;
  line-height: 1.6;
}

/* Popular Courses Section */
.popular-courses {
  padding: 100px 0;
  background-color: var(--light-gray);
  overflow: hidden;
}

.popular-courses-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 30px;
  margin-top: 50px;
  padding: 10px;
  scroll-behavior: smooth;
}

.popular-course-card {
  background: var(--white);
  border-radius: 15px;
  overflow: hidden;
  box-shadow: var(--shadow);
  transition: var(--transition);
  display: flex;
  flex-direction: column;
  height: 450px;
}

.popular-course-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 16px rgba(0,0,0,0.1);
}

.course-image {
  height: 200px;
  width: 100%;
  overflow: hidden;
  position: relative;
}

.course-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: var(--transition);
}

.course-image img:hover {
  transform: scale(1.1);
}

.course-content {
  padding: 25px;
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.course-content h3 {
  font-size: 20px;
  margin-bottom: 12px;
  color: var(--secondary-color);
  font-weight: 700;
  line-height: 1.4;
  height: 56px;
  overflow: hidden;
  display: -webkit-box;
  -webkit-line-clamp: 2;
  -webkit-box-orient: vertical;
}

.course-content p {
  color: #666;
  font-size: 15px;
  margin-bottom: 20px;
  height: 48px;
  overflow: hidden;
  display: -webkit-box;
  -webkit-line-clamp: 2;
  -webkit-box-orient: vertical;
}

.course-tag {
  position: absolute;
  top: 20px;
  right: 20px;
  padding: 8px 16px;
  border-radius: 20px;
  font-size: 14px;
  font-weight: 600;
  text-transform: uppercase;
  background-color: var(--white);
}

.course-tag.development {
  color: var(--primary-color);
}

.course-tag.design {
  color: var(--primary-color);
}

.course-tag.language {
  color: var(--primary-color);
}

.course-meta {
  margin-top: auto;
  padding-top: 20px;
  border-top: 1px solid #eee;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.course-price {
  font-size: 20px;
  font-weight: 700;
  color: var(--primary-color);
  opacity: 0.7;
  text-decoration: line-through;
}

.enroll-button {
  background-color: #ccc;
  color: #666;
  border: none;
  padding: 10px 20px;
  border-radius: 25px;
  font-weight: 600;
  cursor: not-allowed;
  transition: var(--transition);
  opacity: 0.7;
}

.enroll-button:hover {
  background-color: #ccc;
  transform: none;
}

/* Stats Section */
.stats-section {
  position: relative;
  padding: 100px 0;
  background: linear-gradient(rgba(6, 40, 71, 0.85), rgba(6, 40, 71, 0.95)), url('/assets/images/teach.jpg');
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
  background-repeat: no-repeat;
  color: var(--white);
}

.stats-grid {
  position: relative;
  z-index: 2;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 40px;
  margin-top: 50px;
}

.stats-section .section-subtitle,
.stats-section .section-title {
  position: relative;
  z-index: 2;
  color: var(--white);
}

.stats-section .underline {
  position: relative;
  z-index: 2;
}

.stat-card {
  text-align: center;
  padding: 30px;
  background: rgba(255, 255, 255, 0.1);
  border-radius: 15px;
  backdrop-filter: blur(10px);
  transition: var(--transition);
}

.stat-card:hover {
  transform: translateY(-5px);
  background: rgba(255, 255, 255, 0.15);
}

.stat-icon {
  font-size: 40px;
  margin-bottom: 20px;
  color: var(--primary-color);
}

.stat-value {
  font-size: 48px;
  font-weight: 700;
  margin-bottom: 10px;
  background: linear-gradient(45deg, #2ecc71, #27ae60);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.stat-label {
  font-size: 18px;
  font-weight: 500;
  opacity: 0.9;
}

/* Footer Styles */
.footer {
  background-color: #1a1a1a;
  color: #fff;
  padding: 80px 0 20px;
}

.footer-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 40px;
  margin-bottom: 60px;
}

.footer-logo {
  font-size: 32px;
  margin-bottom: 20px;
  color: var(--primary-color);
}

.footer-description {
  margin-bottom: 30px;
  opacity: 0.8;
  line-height: 1.8;
}

.contact-info p {
  margin-bottom: 15px;
  display: flex;
  align-items: center;
  gap: 10px;
}

.footer-title {
  font-size: 24px;
  margin-bottom: 30px;
  position: relative;
}

.footer-title::after {
  content: '';
  position: absolute;
  bottom: -10px;
  right: 0;
  width: 50px;
  height: 3px;
  background-color: var(--primary-color);
}

.post-item {
  display: flex;
  gap: 15px;
  margin-bottom: 20px;
}

.post-thumb {
  width: 80px;
  height: 80px;
  border-radius: 10px;
  object-fit: cover;
}

.post-info h4 {
  font-size: 16px;
  margin-bottom: 8px;
  transition: var(--transition);
}

.post-info h4:hover {
  color: var(--primary-color);
}

.post-meta {
  font-size: 14px;
  opacity: 0.7;
}

.footer-bottom {
  padding-top: 30px;
  border-top: 1px solid rgba(255, 255, 255, 0.1);
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.copyright {
  opacity: 0.7;
}

.social-links {
  display: flex;
  gap: 20px;
}

.social-link {
  color: var(--white);
  font-size: 20px;
  transition: var(--transition);
}

.social-link:hover {
  color: var(--primary-color);
}

/* Floating Buttons */
.floating-buttons {
  position: fixed;
  left: 20px;
  bottom: 20px;
  display: flex;
  flex-direction: column;
  gap: 10px;
  z-index: 999;
}

.float-button {
  width: 50px;
  height: 50px;
  border-radius: 50%;
  background-color: var(--white);
  border: none;
  box-shadow: var(--shadow);
  cursor: pointer;
  transition: var(--transition);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 20px;
}

.float-button:hover {
  transform: scale(1.1);
  background-color: var(--primary-color);
  color: var(--white);
}

/* Animations */
@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}

.feature-card,
.popular-course-card,
.stat-card {
  animation: fadeIn 0.6s ease-out forwards;
}

/* Add smooth scroll behavior to html */
html {
  scroll-behavior: smooth;
}

/* Adjust the scroll offset to account for fixed header */
#courses {
  scroll-margin-top: 100px;
}

/* Responsive Styles */
@media (max-width: 1200px) {
  .hero-content h1 {
    font-size: 48px; /* Adjust font size for smaller screens */
  }
}

@media (max-width: 768px) {
  .hero-content h1 {
    font-size: 36px; /* Further adjust for mobile */
  }

  .hero-content p {
    font-size: 18px; /* Adjust paragraph size */
  }

  .footer-grid {
    grid-template-columns: 1fr; /* Stack footer items */
  }

  .popular-courses-grid {
    grid-template-columns: repeat(2, 1fr);
  }

  .header {
    padding: 10px 0;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .logo {
    flex-direction: row;
    justify-content: center;
    align-items: center;
  }
  .nav-links {
    display: none;
    flex-direction: column;
    gap: 15px;
    background-color: #062847;
    width: 100%;
    text-align: center;
  }
  .nav-links.active {
    display: flex;
  }
  .menu-toggle {
    display: block;
    cursor: pointer;
    font-size: 24px;
    color: var(--white);
    margin-top: 10px;
  }
}

@media (max-width: 480px) {
  .popular-courses-grid {
    grid-template-columns: 1fr;
  }
}

/* Responsive Images */
img {
  max-width: 100%; /* Ensure images are responsive */
  height: auto; /* Maintain aspect ratio */
}

/* Features Section */
.features-section {
  padding: 100px 0;
  background-color: var(--white);
  text-align: center;
}

.features-section .section-subtitle {
  color: #E86C2C;
  font-size: 18px;
  font-weight: 600;
  margin-bottom: 15px;
  text-transform: uppercase;
  letter-spacing: 2px;
}

.features-section .section-title {
  font-size: 42px;
  color: var(--secondary-color);
  margin-bottom: 20px;
  font-weight: 700;
}

.features-section .underline {
  width: 80px;
  height: 4px;
  background-color: #E86C2C;
  margin: 0 auto 50px;
}

.features-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 30px;
}

.feature-card {
  background: var(--white);
  padding: 20px;
  border-radius: 10px;
  text-align: center;
  transition: var(--transition);
  box-shadow: var(--shadow);
}

.feature-icon {
  margin-bottom: 15px;
  color: #E86C2C;
}

.feature-card h3 {
  font-size: 18px;
  color: var(--secondary-color);
}
</style>


<template>
  <div class="app">
    <nav class="navbar">
      <div class="container nav-container">
        <div class="logo">ProductivityPro</div>
        <ul class="nav-links">
          <li><a href="#Home">Home</a></li>
          <li><a href="#About">About</a></li>
          <li><a href="#contact">Contact</a></li>
          <li><a href="blog">Blog</a></li>
        </ul>
        <button class="btn-signup">Sign Up</button>
      </div>
    </nav>
    <section class="hero">
      <div class="container hero-container">
        <div class="hero-left">
          <h1 class="hero-title">
            Maximize Your<br />
            Efficiency with<br />
            <span class="gradient-text">ProductivityPro</span>
          </h1>
          <p class="hero-subtitle">
            Stay organized,focused,and achieve more with<br />
            our powerful productivity web app.Take control<br />
            of your tasks,conquer your goal
          </p>
        </div>
        <div class="hero-right">
          <div class="cards-grid">
            <!-- 科隆卡片 -->
            <div class="info-card">
              <h3 class="card-city">Cologne</h3>
              <p class="card-description">
                When you enter into any new area of science, you almost always find.
              </p>
              <a href="#" class="card-link">Details →</a>
            </div>
            <div class="info-card">
              <h3 class="card-city">Bengaluru</h3>
              <p class="card-description">
                Your business is in a continual battle for your customers' recognition whether you
              </p>
              <a href="#" class="card-link">Details →</a>
            </div>
            <div class="info-card">
              <h3 class="card-city">Kathmandu</h3>
              <p class="card-description">When you enter into any new area</p>
              <a href="#" class="card-link">Details →</a>
            </div>
            <div class="info-card">
              <h3 class="card-city">Melbourne</h3>
              <p class="card-description">
                When you enter into any new area of science, you almost always find.
              </p>
              <a href="#" class="card-link">Details →</a>
            </div>
            <div class="info-card">
              <h3 class="card-city">Casablanca</h3>
              <p class="card-description">
                When you enter into any new area of science, you almost always find.
              </p>
              <div class="card-tags">
                <span class="tag">Lost</span>
                <span class="tag">Columbus</span>
                <span class="tag">Bogota</span>
              </div>
              <a href="#" class="card-link">Details →</a>
            </div>
            <div class="info-card">
              <h3 class="card-city">Kuala Lumpur</h3>
              <p class="card-description">
                Your business is in a continual battle for your customers' recognition whether you
              </p>
              <a href="#" class="card-link">Details →</a>
            </div>
            <div class="info-card">
              <h3 class="card-city">Bristol</h3>
              <p class="card-description">
                When you enter into any new area of science, you almost always find.
              </p>
              <a href="#" class="card-link">Details →</a>
            </div>

            <div class="info-card">
              <h3 class="card-city">Brisbane</h3>
              <p class="card-description">
                When you enter into any new area of science, you almost always find.
              </p>
              <a href="#" class="card-link">Details →</a>
            </div>
            <div class="info-card">
              <h3 class="card-city">Louisville</h3>
              <p class="card-description">
                When you enter into any new area of science, you almost always find.
              </p>
              <div class="card-tags">
                <span class="tag">Lost</span>
                <span class="tag">Designer</span>
              </div>
              <div class="card-cities">
                <span class="city-tag">Milan</span>
                <span class="city-tag">Edinburgh</span>
              </div>
              <a href="#" class="card-link">Details →</a>
            </div>
            <div class="info-card">
              <h3 class="card-city">Helsinki</h3>
              <p class="card-description">
                When you enter into any new area of science, you almost always find.
              </p>
              <a href="#" class="card-link">Details →</a>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="feature-cards">
      <div class="container">
        <div class="features-grid">
          <div class="feature-card">
            <div class="feature-icon">📋</div>
            <h3 class="feature-title">Task Management</h3>
            <p class="feature-description">Effortlessly organize and prioritize your tasks.</p>
          </div>
          <div class="feature-card">
            <div class="feature-icon">⏱️</div>
            <h3 class="feature-title">Time Tracking</h3>
            <p class="feature-description">Stay accountable with time tracking and insights.</p>
          </div>
          <div class="feature-card">
            <div class="feature-icon">👥</div>
            <h3 class="feature-title">Collaboration Tools</h3>
            <p class="feature-description">
              Seamlessly collaborate and communicate with your team.
            </p>
          </div>
        </div>
      </div>
    </section>
    <section class="goals1" id="Home">
      <div class="container goals1-container">
        <div class="section1-left">
          <h2>Set and track your goals <br />for success</h2>
          <p>
            Embrace life's vastness,venture forth,and discover the wonders<br />
            waiting beyond.The world beckons;seize its grand offerings now!
            <br />
            <br />
            Embrace life's vastness,venture forth,and discover the<br />
            wonders waiting beyond.The world beckons;seize its<br />
            grand offerings now!
          </p>
        </div>
      </div>
    </section>
    <section class="goals2">
      <div class="container goals2-container">
        <div class="section2-left"></div>
        <div class="section2-right">
          <h2>Set and track your goals <br />for success</h2>
          <p>
            Embrace life's vastness,venture forth,and discover the wonders<br />
            waiting beyond.The world beckons;seize its grand offerings now!
            <br />
            <br />
            Embrace life's vastness,venture forth,and discover the<br />
            wonders waiting beyond.The world beckons;seize its<br />
            grand offerings now!
          </p>
        </div>
      </div>
    </section>
    <!-- 用户评价 -->
    <section class="testimonials" id="testimonials">
      <div class="container">
        <div class="section-header">
          <h2>Testimonials from our members</h2>
          <p>
            Embrace life's vastness,venture forth,and <br />discover the wonders waiting beyond.The
            world <br />beckons;seize its grand offerings now!
          </p>
        </div>
        <div class="testimonials-grid">
          <div class="testimonial-card" v-for="testimonial in testimonials" :key="testimonial.name">
            <div class="stars">
              <span v-for="n in 5" :key="n">★</span>
            </div>
            <p>"{{ testimonial.quote }}"</p>
            <div class="testimonial-author">
              <strong>{{ testimonial.name }}</strong>
              <span>{{ testimonial.role }}</span>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="cta">
      <div class="container cta-container">
        <h2>Ready to get started?</h2>
        <p>The world beckons;seize its grand offerings now!</p>
      </div>
    </section>
    <footer class="footer" id="contact">
      <div class="container">
        <div class="footer-grid">
          <div class="footer-col">
            <h3>Get In touch</h3>
            <p>the quick jumps over the lazy dog</p>
            <div class="social-links">
              <a href="#">𝕏</a>
              <a href="#">in</a>
              <a href="#">🐙</a>
            </div>
          </div>
          <div class="footer-col">
            <h4>Company</h4>
            <ul>
              <li><a href="#">About Us</a></li>
              <li><a href="#">Careers</a></li>
              <li><a href="#">We are hiring</a></li>
              <li><a href="#">Blog</a></li>
            </ul>
          </div>
          <div class="footer-col">
            <h4>Features</h4>
            <ul>
              <li><a href="#">Business Marketing</a></li>
              <li><a href="#">User Analytic</a></li>
              <li><a href="#">Live Chat</a></li>
              <li><a href="#">Unlimited Support</a></li>
            </ul>
          </div>
        </div>
        <div class="footer-bottom">
          <p>Made With Love By Figmaland All Right Reserved</p>
        </div>
      </div>
    </footer>
  </div>
</template>
<script>
export default {
  name: 'App',
  data() {
    return {
      goals: [
        {
          title: 'Smart Goal Setting',
          description: 'Create SMART goals with AI-powered suggestions to keep you on track.',
        },
        {
          title: 'Progress Analytics',
          description: 'Visualize your progress with detailed charts and insights.',
        },
        {
          title: 'Daily Reminders',
          description: 'Get personalized reminders to stay focused on your priorities.',
        },
      ],
      testimonials: [
        {
          quote: "ProductivityPro has revolutionized my work process,It's a game-changer!",
          name: 'Jennifer W',
          role: 'Director,Producer',
        },
        {
          quote: 'I love the simplicity and effecttiveness of ProductivityPro.Highly recommended!',
          name: 'Alex M',
          role: 'Directer,Producer',
        },
      ],
    }
  },
}
</script>

<style scoped>
.navbar {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background: rgba(248, 248, 248, 0.95);
  backdrop-filter: blur(10px);
  padding: 20px 0;
  z-index: 1000;
  border-bottom: 1px solid rgba(255, 255, 255, 0.1);
}

.nav-container {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
  padding: 0 40px;
  gap: 80px;
}

.logo {
  font-size: 40px;
  font-weight: bold;
  background: linear-gradient(135deg, #4167b1, #5b8ad6);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  position: absolute;
  left: 40px;
  top: 50%;
  transform: translateY(-50%);
}

.nav-links {
  display: flex;
  font-size: 20px;
  gap: 100px;
  margin: 0 auto;
  padding: 0;
  list-style: none;
}

.nav-links a {
  color: #8e8e8e;
  transition: color 0.3s;
}

.nav-links a:hover {
  color: #a855f7;
}

.btn-signup {
  background: linear-gradient(135deg, #4167b1, #a855f7);
  color: white;
  padding: 12px 30px;
  border-radius: 30px;
  font-size: 25px;
  position: absolute;
  right: 40px;
  top: 50%;
  transform: translateY(-50%);
  font-weight: 500;
  transition:
    transform 0.3s,
    opacity 0.3s;
}
.btn-signup:hover {
  transform: translateY(-1px);
  opacity: 0.9;
}

.hero {
  background: linear-gradient(to bottom, #7096d1, #ffffff);
  padding: 120px 0 80px;
  min-height: 100vh;
  position: relative;
  overflow: hidden;
  display: flex;
  align-items: center;
}

.hero-title {
  position: absolute;
  font-size: 80px;
  font-weight: 800;
  top: 50%;
  left: 15%;
  transform: translateY(-50%);
  max-width: 600px;
  line-height: 1.5;
  margin-bottom: 24px;
  color: #2a3646;
  margin: 0;
}

.gradient-text {
  background: linear-gradient(135deg, #4167b1, #5483cf);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
}

.hero-subtitle {
  position: absolute;
  top: calc(50% + 250px);
  left: 20%;
  transform: translateY(-50%);
  font-size: 18px;
  color: #a3a3a3;
  max-width: 600px;
  margin: 0 auto 32px;
  line-height: 1.6;
}

.hero-right {
  flex: 1;
  max-height: 80vh;
  overflow-y: auto;
  padding: 0 10px 0;
  margin-left: 600px;
}

.hero-right::-webkit-scrollbar {
  width: 6px;
}

.hero-right::-webkit-scrollbar-track {
  background: #f1f1f1;
  border-radius: 10px;
}

.hero-right::-webkit-scrollbar-thumb {
  background: #cbd5e1;
  border-radius: 10px;
}

.hero-right::-webkit-scrollbar-thumb:hover {
  background: #94a3b8;
}

.cards-grid {
  display: flex;
  flex-direction: column;
  gap: 16px;
}

.info-card {
  background: white;
  border-radius: 20px;
  padding: 20px 24px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
  transition: all 0.3s ease;
  border: 1px solid #eef2ff;
}

.info-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 12px 28px rgba(0, 0, 0, 0.08);
  border-color: #c7d2fe;
}

.card-city {
  font-size: 18px;
  font-weight: 600;
  color: #1e293b;
  margin-bottom: 8px;
  letter-spacing: -0.2px;
}

.card-description {
  font-size: 14px;
  color: #64748b;
  line-height: 1.5;
  margin-bottom: 12px;
}

.card-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-bottom: 12px;
}

.tag {
  font-size: 12px;
  padding: 4px 10px;
  background: #f1f5f9;
  border-radius: 20px;
  color: #475569;
}

.card-cities {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-bottom: 12px;
}

.city-tag {
  font-size: 12px;
  padding: 4px 10px;
  background: #eef2ff;
  border-radius: 20px;
  color: #4f46e5;
  font-weight: 500;
}

.card-link {
  font-size: 13px;
  color: #4f46e5;
  text-decoration: none;
  font-weight: 500;
  display: inline-flex;
  align-items: center;
  gap: 4px;
  transition: gap 0.2s;
}

.card-link:hover {
  gap: 8px;
  color: #6366f1;
}

.feature-cards {
  padding: 40px 0 0;
  background: #ffffff;
}

.features-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 32px;
  max-width: 1100px;
  margin: 0 auto;
}

.feature-card {
  background: white;
  border-radius: 28px;
  padding: 40px 32px;
  text-align: center;
  transition: all 0.3s ease;
  border: 1px solid #eef2ff;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.04);
}

.feature-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 20px 35px -12px rgba(0, 0, 0, 0.1);
  border-color: #c7d2fe;
}

.feature-icon {
  font-size: 48px;
  margin-bottom: 24px;
  display: inline-block;
}

.feature-title {
  font-size: 22px;
  font-weight: 700;
  color: #1e293b;
  margin-bottom: 16px;
}

.feature-description {
  font-size: 15px;
  color: #64748b;
  line-height: 1.6;
}

section {
  padding: 0 0;
}
.goals1-container {
  width: 100%;
  background-color: #ffffff;
}
.section1-left {
  width: 50%;
  position: relative;
  text-align: center;
}

.section1-left h2 {
  padding: 20% 0 20px;
  margin-top: 0;
  font-size: 50px;
  margin-bottom: 45px;
  color: #050505;
}

.section1-left p {
  color: #a3a3a3;
  font-size: large;
  max-width: 600px;
  margin: 0 auto;
  padding-bottom: 150px;
}
.goals2 {
  height: 80vh;
  background: #afc8da;
  position: relative;
  clip-path: polygon(0 0, 100% 0, 100% 60%, 0 85%);
}

.section2-right {
  width: 50%;
  margin-left: auto;
  position: relative;
  text-align: center;
}

.section2-right h2 {
  padding: 20% 0 20px;
  margin-top: 0;
  font-size: 50px;
  margin-bottom: 45px;
  color: #050505;
}

.section2-right p {
  color: #a3a3a3;
  font-size: large;
  max-width: 600px;
  margin: 0 auto;
  padding-bottom: 150px;
}

.section-header p {
  color: #a3a3a3;
  text-align: center;
  padding-top: 20px;
  padding-bottom: 20px;
}
.section-header h2 {
  font-size: 50px;
  text-align: center;
}
.testimonials-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 32px;
}

.testimonial-card {
  background: rgba(255, 255, 255, 0.05);
  padding: 32px;
  border-radius: 24px;
  border: 1px solid rgba(255, 255, 255, 0.1);
}

.stars {
  color: #fbbf24;
  font-size: 18px;
  margin-bottom: 16px;
}

.testimonial-card p {
  font-size: 16px;
  line-height: 1.6;
  margin-bottom: 20px;
  color: #3a3434;
}

.testimonial-author {
  display: flex;
  flex-direction: column;
}

.testimonial-author strong {
  color: rgb(4, 3, 3);
}

.testimonial-author span {
  font-size: 14px;
  color: #a3a3a3;
}

.cta {
  background: linear-gradient(135deg, rgba(99, 102, 241, 0.1), rgba(168, 85, 247, 0.1));
  border-radius: 32px;
  margin: 40px 20px;
  padding: 60px 0;
}

.cta-container {
  text-align: center;
}

.cta h2 {
  font-size: 50px;
  margin-bottom: 16px;
}

.cta p {
  color: #a3a3a3;
  margin-bottom: 32px;
}

.footer {
  background: #ffffff;
  padding: 60px 0 30px;
  border-top: 1px solid rgba(255, 255, 255, 0.1);
}

.footer-grid {
  display: grid;
  grid-template-columns: 2fr 1fr 1fr 1.5fr;
  gap: 40px;
  margin-bottom: 40px;
}

.footer-col h3 {
  font-size: 20px;
  margin-bottom: 16px;
}

.footer-col h4 {
  font-size: 16px;
  margin-bottom: 16px;
  color: #000000;
}

.footer-col p {
  color: #615a5a;
  line-height: 1.6;
  margin-bottom: 16px;
}

.footer-col ul {
  list-style: none;
}

.footer-col li {
  margin-bottom: 10px;
}

.footer-col a {
  color: #a3a3a3;
  transition: color 0.3s;
}

.footer-col a:hover {
  color: #a855f7;
}

.social-links {
  display: flex;
  gap: 16px;
}

.social-links a {
  width: 36px;
  height: 36px;
  background: rgba(255, 255, 255, 0.1);
  border-radius: 50%;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  transition: all 0.3s;
}

.social-links a:hover {
  background: #a855f7;
  transform: translateY(-2px);
}

.footer-bottom {
  font-weight: 500;
  text-align: center;
  padding-top: 30px;
  border-top: 1px solid rgba(255, 255, 255, 0.1);
  color: #666;
  font-size: 14px;
}

@media (max-width: 768px) {
  .hero-title {
    font-size: 36px;
  }

  .nav-links {
    display: none;
  }

  .footer-grid {
    grid-template-columns: 1fr;
    gap: 30px;
  }

  .hero-stats {
    gap: 24px;
  }

  .stat-number {
    font-size: 20px;
  }

  .goals-grid,
  .testimonials-grid {
    grid-template-columns: 1fr;
  }

  .cta h2 {
    font-size: 28px;
  }
}
</style>

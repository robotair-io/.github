<style>
  body {
    font-family: -apple-system, BlinkMacSystemFont, 'San Francisco', sans-serif;
    color: #333;
    background: #fff;
    line-height: 1.6;
    margin: 0;
  }
  a { text-decoration: none; color: inherit; }
  .container { max-width: 1200px; margin: 0 auto; padding: 0 20px; }
  .hero {
    text-align: center;
    padding: 100px 20px;
    background: linear-gradient(to bottom, rgba(255,255,255,1), rgba(245,245,245,1));
  }
  .hero h1 {
    font-size: 3.5rem;
    font-weight: 700;
    margin: 0;
  }
  .hero p {
    font-size: 1.25rem;
    color: #666;
    max-width: 600px;
    margin: 20px auto;
  }
  .cta-button {
    display: inline-block;
    padding: 15px 30px;
    background: linear-gradient(135deg, #1e3a8a, #3b82f6);
    color: #fff;
    font-size: 1.1rem;
    font-weight: 600;
    border-radius: 10px;
    transition: transform 0.2s ease;
  }
  .cta-button:hover { transform: scale(1.05); }
  .benefits {
    display: flex;
    justify-content: space-around;
    padding: 60px 20px;
    flex-wrap: wrap;
  }
  .benefit-card {
    flex: 1;
    min-width: 250px;
    text-align: center;
    padding: 20px;
    transition: transform 0.2s ease;
  }
  .benefit-card:hover { transform: translateY(-5px); }
  .benefit-card h3 { font-size: 1.5rem; margin: 10px 0; }
  .demo {
    text-align: center;
    padding: 60px 20px;
    background: #f5f5f5;
  }
  .demo video {
    max-width: 100%;
    border-radius: 15px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  }
  .testimonial {
    text-align: center;
    padding: 60px 20px;
    max-width: 800px;
    margin: 0 auto;
  }
  .testimonial q {
    font-size: 1.75rem;
    font-style: italic;
    color: #444;
  }
  .testimonial p { color: #888; margin-top: 10px; }
  .why-robotair {
    padding: 60px 20px;
    text-align: center;
  }
  .comparison {
    display: flex;
    justify-content: center;
    gap: 40px;
    flex-wrap: wrap;
  }
  .comparison div { max-width: 300px; }
  .comparison h4 { font-size: 1.25rem; margin-bottom: 10px; }
  .final-cta {
    text-align: center;
    padding: 80px 20px;
    background: linear-gradient(to bottom, rgba(245,245,245,1), rgba(255,255,255,1));
  }
  footer {
    background: #1a1a1a;
    color: #ccc;
    text-align: center;
    padding: 20px;
    font-size: 0.9rem;
  }
  footer a { color: #999; margin: 0 10px; }
  footer a:hover { color: #fff; }
  @media (max-width: 768px) {
    .hero h1 { font-size: 2.5rem; }
    .hero p { font-size: 1rem; }
    .benefits { flex-direction: column; }
    .comparison { flex-direction: column; gap: 20px; }
  }
</style>

<!-- Hero Section -->
<section class="hero">
  <div class="container">
    <h1>Deploy Faster. Innovate More.</h1>
    <p>Robotair automates your robotics CI/CD pipeline, so you can focus on building the future.</p>
    <a href="https://forms.gle/UFkR3ZqZeTVmBJFr7" class="cta-button">Start Free Trial</a>
  </div>
</section>

<!-- Benefits Section -->
<section class="benefits">
  <div class="container">
    <div class="benefit-card">
      <h3>Speed</h3>
      <p>Deploy in minutes, not hours.</p>
    </div>
    <div class="benefit-card">
      <h3>Reliability</h3>
      <p>Automated testing for flawless updates.</p>
    </div>
    <div class="benefit-card">
      <h3>Simplicity</h3>
      <p>Integrates seamlessly with your ROS setup.</p>
    </div>
  </div>
</section>

<!-- Demo Section -->
<section class="demo">
  <div class="container">
    <h2>See the Difference</h2>
    <div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;max-width:100%;border-radius:15px;box-shadow:0 4px 12px rgba(0,0,0,0.1);">
      <iframe 
        src="https://www.youtube.com/embed/kTrm6QVvKZ0?rel=0&autoplay=0&mute=1" 
        title="Robotair Demo" 
        allow="autoplay;" 
        allowfullscreen 
        style="position:absolute;top:0;left:0;width:100%;height:100%;border:0;">
      </iframe>
    </div>
  </div>
</section>


<!-- Why Robotair -->
<section class="why-robotair">
  <div class="container">
    <h2>Why Choose Robotair?</h2>
    <div class="comparison">
      <div>
        <h4>Traditional Deployment</h4>
        <p>Manual, error-prone, time-consuming.</p>
      </div>
      <div>
        <h4>Robotair</h4>
        <p>Automated, reliable, effortless.</p>
      </div>
    </div>
  </div>
</section>

<!-- Final CTA -->
<section class="final-cta">
  <div class="container">
    <h2>Ready to Transform Your Workflow?</h2>
    <p>Start your free trial. No credit card required.</p>
    <a href="https://forms.gle/UFkR3ZqZeTVmBJFr7" class="cta-button">Get Started</a>
  </div>
</section>

<!-- Footer -->
<footer>
  <p>&copy; 2023 Robotair. All rights reserved.</p>
  <p><a href="https://robotair.io/legal/privacy">Privacy Policy</a> | <a href="https://robotair.io/legal/robotair-terms-service">Terms of Service</a></p>
</footer>

---
theme: ./theme
colorscheme: dark
favicon: '/XMA-White.svg'
transition: my-transition
title: Lead Generation Solutions
layout: cover
background: /rainbow.jpg
fonts:
  mono: "JetBrains Mono"
  local: Mona Sans
---

<div class="flex my-auto flex-col items-center justify-center h-full">
  <h1 class="font-bold">Social Media Advertising Strategy</h1>
  <h2 class="!text-2xl">Positioning NBF in the UAE Banking Landscape</h2>
</div>

---
src: ./pages/AboutUs.md
---

---
src: ./pages/USP.md
---

---
src: ./pages/SocialProof.md
---

---
layout: center
---

<div v-motion :initial="{ opacity: 0, y: 50 }" :enter="{ opacity: 1, y: 0 }">
  <h1 class="opportunity-title">Your Digital Banking Opportunity</h1>
  <div class="opportunity-card">
    <p class="opportunity-intro">We've developed a strategic Facebook advertising roadmap to:</p>
    <div class="opportunity-grid">
      <div v-click class="opportunity-item">
        <div class="icon-circle">
          <lucide-eye class="icon" />
        </div>
        <p class="!m-0">Enhance your <span class="highlight-text">digital visibility</span> in the UAE banking sector</p>
      </div>
      <div v-click class="opportunity-item">
        <div class="icon-circle">
          <lucide-users class="icon" />
        </div>
        <p class="!my-0">Generate <span class="highlight-text">qualified leads</span> for business and personal banking</p>
      </div>
      <div v-click class="opportunity-item">
        <div class="icon-circle">
          <lucide-award class="icon" />
        </div>
        <p class="!m-0">Strengthen <span class="highlight-text">competitive positioning</span> against larger banks</p>
      </div>
      <div v-click class="opportunity-item">
        <div class="icon-circle">
          <lucide-trending-up class="icon" />
        </div>
        <p class="!my-0">Drive <span class="highlight-text">measurable ROI</span> from social media advertising</p>
      </div>
    </div>
  </div>
</div>

<style>
.opportunity-title {
  font-size: 2.25rem;
  font-weight: bold;
  margin-bottom: 1.5rem;
  background: linear-gradient(to right, #00AFEF, #87CEFA);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  text-align: center;
}
.opportunity-card {
  max-width: 850px;
  margin: 0 auto;
  padding: 1.5rem;
  background: linear-gradient(to bottom right, rgba(24, 24, 27, 0.8), rgba(39, 39, 42, 0.5));
  border-radius: 0.5rem;
  border: 1px solid rgba(0, 175, 239, 0.3);
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}
.opportunity-intro {
  font-size: 1.25rem;
  margin-bottom: 2rem;
  text-align: center;
}
.opportunity-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
}
.opportunity-item {
  display: flex;
  align-items: flex-start;
  gap: 0.75rem;
}
.icon-circle {
  padding: 0.5rem;
  background-color: rgba(0, 175, 239, 0.2);
  border-radius: 9999px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.icon {
  width: 1.5rem;
  height: 1.5rem;
  color: #00AFEF;
}
.highlight-text {
  color: #00AFEF;
  font-weight: 500;
}
</style>

---
layout: center
class: text-center
zoom: 0.8
---

<div v-motion :initial="{ opacity: 0 }" :enter="{ opacity: 1 }">
  <h1 class="section-title">Current State Analysis</h1>
</div>
<div class="analysis-grid">
  <div v-motion :initial="{ opacity: 0, x: -50 }" :enter="{ opacity: 1, x: 0, transition: { delay: 200 } }" class="analysis-card">
    <div class="card-header">
      <div class="icon-circle">
        <lucide-pie-chart class="icon" />
      </div>
      <h3 class="card-title">NBF Current Situation</h3>
    </div>
    <ul class="card-list">
      <li class="list-item">
        <lucide-minus-circle class="negative-icon" />
        <span>Limited social media engagement compared to competitors</span>
      </li>
      <li class="list-item">
        <lucide-minus-circle class="negative-icon" />
        <span>No active Facebook advertising campaigns detected</span>
      </li>
      <li class="list-item">
        <lucide-minus-circle class="negative-icon" />
        <span>Minimal retargeting or audience building</span>
      </li>
      <li class="list-item">
        <lucide-minus-circle class="negative-icon" />
        <span>Digital products (NBF Edge, NBF Direct) lack social visibility on social media</span>
      </li>
    </ul>
  </div>
  <div v-motion :initial="{ opacity: 0, x: 50 }" :enter="{ opacity: 1, x: 0, transition: { delay: 400 } }" class="analysis-card">
    <div class="card-header">
      <div class="icon-circle">
        <lucide-scan-face class="icon" />
      </div>
      <h3 class="card-title">Competitive Landscape</h3>
    </div>
    <ul class="card-list">
      <li class="list-item">
        <lucide-check-circle class="positive-icon" />
        <span>Major UAE banks running sophisticated Facebook campaigns</span>
      </li>
      <li class="list-item">
        <lucide-check-circle class="positive-icon" />
        <span>Competitors using video ads, static ads and carousels for lead generation</span>
      </li>
      <li class="list-item">
        <lucide-check-circle class="positive-icon" />
        <span>Banks leveraging Facebook for awareness and direct response</span>
      </li>
      <li class="list-item">
        <lucide-check-circle class="positive-icon" />
        <span>Similar products promoted with much higher visibility</span>
      </li>
    </ul>
  </div>
</div>

<style>
.section-title {
  font-size: 2.5rem;
  font-weight: bold;
  margin-bottom: 2.5rem;
  background: linear-gradient(to right, #00AFEF, #87CEFA);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
}
.analysis-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
}
.analysis-card {
  background: linear-gradient(to bottom right, rgba(24, 24, 27, 0.8), rgba(39, 39, 42, 0.5));
  border-radius: 0.5rem;
  border: 1px solid #27272A;
  padding: 1.5rem;
  transition: all 0.3s ease;
}
.analysis-card:hover {
  transform: scale(1.02);
  border-color: rgba(0, 175, 239, 0.5);
  box-shadow: 0 0 10px rgba(0, 175, 239, 0.1);
}
.card-header {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  margin-bottom: 1rem;
}
.card-title {
  font-size: 1.25rem;
  font-weight: bold;
  color: #00AFEF;
}
.card-list {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}
.list-item {
  display: flex;
  align-items: flex-start;
  gap: 0.5rem;
  text-align: left;
}
.negative-icon {
  width: 1.25rem;
  height: 1.25rem;
  color: #f87171;
  flex-shrink: 0;
  margin-top: 0.5rem;
}
.positive-icon {
  width: 1.25rem;
  height: 1.25rem;
  color: #4ade80;
  flex-shrink: 0;
  margin-top: 0.5rem;
}
</style>

---
layout: center
zoom: 0.8
---

<div v-motion :initial="{ opacity: 0 }" :enter="{ opacity: 1 }">
  <h1 class="section-title text-center">The Facebook Advertising Opportunity</h1>
</div>
<div class="opportunity-grid">
  <div v-motion :initial="{ opacity: 0, scale: 0.9 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 200 } }" class="opportunity-card">
    <div class="card-header">
      <div class="icon-circle">
        <lucide-rocket class="icon" />
      </div>
      <h3 class="card-title">Platform Advantages</h3>
    </div>
    <ul class="advantage-list">
      <li class="advantage-item">
        <div class="check-circle">
          <lucide-check class="check-icon" />
        </div>
        <span>UAE has one of the highest Facebook penetration rates globally</span>
      </li>
      <li class="advantage-item">
        <div class="check-circle">
          <lucide-check class="check-icon" />
        </div>
        <span>Banking customers research financial products on social platforms</span>
      </li>
      <li class="advantage-item">
        <div class="check-circle">
          <lucide-check class="check-icon" />
        </div>
        <span>Precise targeting capabilities for your ideal customer segments</span>
      </li>
      <li class="advantage-item">
        <div class="check-circle">
          <lucide-check class="check-icon" />
        </div>
        <span>Cost-effective lead generation compared to traditional channels</span>
      </li>
    </ul>
  </div>
  <div v-motion :initial="{ opacity: 0, scale: 0.9 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 400 } }" class="opportunity-card">
    <div class="card-header">
      <div class="icon-circle">
        <lucide-users class="icon" />
      </div>
      <h3 class="card-title">Target Audiences Available</h3>
    </div>
    <ul class="audience-list">
      <li class="audience-item">
        <div class="audience-icon-circle">
          <lucide-briefcase class="audience-icon" />
        </div>
        <span>Business owners and decision makers (business banking)</span>
      </li>
      <li class="audience-item">
        <div class="audience-icon-circle">
          <lucide-gem class="audience-icon" />
        </div>
        <span>High-net-worth individuals (premium services)</span>
      </li>
      <li class="audience-item">
        <div class="audience-icon-circle">
          <lucide-users class="audience-icon" />
        </div>
        <span>Specific expatriate communities (remittance services)</span>
      </li>
      <li class="audience-item">
        <div class="audience-icon-circle">
          <lucide-flag class="audience-icon" />
        </div>
        <span>UAE nationals (Ajyal and specialized offerings)</span>
      </li>
    </ul>
  </div>
</div>

<style>
.opportunity-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
}
.opportunity-card {
  background: linear-gradient(to bottom right, rgba(24, 24, 27, 0.8), rgba(39, 39, 42, 0.5));
  border-radius: 0.5rem;
  border: 1px solid #27272A;
  padding: 1.5rem;
  transition: all 0.3s ease;
}
.opportunity-card:hover {
  transform: translateY(-5px);
  border-color: rgba(0, 175, 239, 0.5);
  box-shadow: 0 5px 15px rgba(0, 175, 239, 0.1);
}
.advantage-list, .audience-list {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}
.advantage-item, .audience-item {
  display: flex;
  align-items: flex-start;
  gap: 0.75rem;
}
.check-circle, .audience-icon-circle {
  padding: 0.5rem;
  background-color: rgba(0, 175, 239, 0.1);
  border-radius: 9999px;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 0.125rem;
}
.check-icon, .audience-icon {
  width: 1rem;
  height: 1rem;
  color: #00AFEF;
}
.text-center {
  text-align: center;
}
.card-header {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  margin-bottom: 1rem;
}
.card-title {
  font-size: 1.25rem;
  font-weight: bold;
  color: #00AFEF;
}
.card-list {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}
.list-item {
  display: flex;
  align-items: flex-start;
  gap: 0.5rem;
  text-align: left;
}
</style>

---
layout: center
class: text-center
---

<div v-motion :initial="{ opacity: 0 }" :enter="{ opacity: 1 }">
  <h1 class="section-title">Our Proven Facebook Advertising Methodology</h1>
</div>

<div class="methodology-grid">
  <div v-motion :initial="{ opacity: 0, y: 50 }" :enter="{ opacity: 1, y: 0, transition: { delay: 200 } }" class="methodology-card">
    <div class="icon-large-circle">
      <lucide-target class="icon-large" />
    </div>
    <h3 class="methodology-title">Precision Targeting</h3>
    <p class="!my-0">Advanced audience building for your exact customer segments</p>
  </div>

  <div v-motion :initial="{ opacity: 0, y: 50 }" :enter="{ opacity: 1, y: 0, transition: { delay: 400 } }" class="methodology-card">
    <div class="icon-large-circle">
      <lucide-palette class="icon-large" />
    </div>
    <h3 class="methodology-title">Compelling Creative</h3>
    <p class="!my-0">Eye-catching ads that convert viewers to customers</p>
  </div>

  <div v-motion :initial="{ opacity: 0, y: 50 }" :enter="{ opacity: 1, y: 0, transition: { delay: 600 } }" class="methodology-card">
    <div class="icon-large-circle">
      <lucide-activity class="icon-large" />
    </div>
    <h3 class="methodology-title">Data-Driven Optimization</h3>
    <p class="!my-0">Continuous improvement based on performance metrics</p>
  </div>
</div>

<style>
.methodology-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 2rem;
  margin-bottom: 2rem;
}
.methodology-card {
  background: linear-gradient(to bottom right, rgba(24, 24, 27, 0.8), rgba(39, 39, 42, 0.5));
  border-radius: 0.75rem;
  border: 1px solid #27272A;
  padding: 1.5rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  transition: all 0.3s ease;
}
.methodology-card:hover {
  transform: translateY(-5px);
  border-color: rgba(0, 175, 239, 0.5);
  box-shadow: 0 5px 15px rgba(0, 175, 239, 0.1);
}
.icon-large-circle {
  padding: 1rem;
  background-color: rgba(0, 175, 239, 0.2);
  border-radius: 9999px;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 1rem;
}
.icon-large {
  width: 2.5rem;
  height: 2.5rem;
  color: #00AFEF;
}
.methodology-title {
  font-size: 1.25rem;
  font-weight: bold;
  color: #00AFEF;
  margin-bottom: 0.5rem;
}
.experience-banner {
  margin-top: 2rem;
  padding: 1.25rem;
  background: linear-gradient(to right, rgba(0, 175, 239, 0.1), rgba(135, 206, 250, 0.05));
  border-radius: 0.5rem;
  border: 1px solid rgba(0, 175, 239, 0.2);
}
.highlight-number {
  font-weight: bold;
  color: #fff;
}
.bold-text {
  font-weight: bold;
  color: #fff;
}
</style>

---
layout: center
class: text-center
zoom: 0.7
---

<div v-motion :initial="{ opacity: 0 }" :enter="{ opacity: 1 }">
  <h1 class="section-title !mb-8">Facebook Ad Strategy & Tactics for NBF</h1>
</div>

<div class="strategy-grid">
  <div v-motion :initial="{ opacity: 0, x: -50 }" :enter="{ opacity: 1, x: 0, transition: { delay: 200 } }" class="strategy-card">
    <div class="strategy-header">
      <div class="strategy-icon-circle">
        <lucide-paintbrush class="strategy-icon" />
      </div>
      <h3 class="strategy-title">Creative Optimization</h3>
    </div>
    <ul class="strategy-list">
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon" />
        <span>Systematic A/B testing of ads</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon" />
        <span>Performance-based budget allocation</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon" />
        <span>Continuous creative refreshment</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon" />
        <span>Format variation based on objective</span>
      </li>
    </ul>
  </div>

  <div v-motion :initial="{ opacity: 0, x: 50 }" :enter="{ opacity: 1, x: 0, transition: { delay: 300 } }" class="strategy-card">
    <div class="strategy-header">
      <div class="strategy-icon-circle">
        <lucide-layers class="strategy-icon" />
      </div>
      <h3 class="strategy-title">Campaign Structure</h3>
    </div>
    <ul class="strategy-list">
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon" />
        <span>Awareness campaigns for brand building</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon" />
        <span>Consideration campaigns showcasing benefits</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon" />
        <span>Conversion campaigns driving applications</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon" />
        <span>Retention campaigns for cross-selling</span>
      </li>
    </ul>
  </div>

  <div v-motion :initial="{ opacity: 0, x: -50 }" :enter="{ opacity: 1, x: 0, transition: { delay: 400 } }" class="strategy-card">
    <div class="strategy-header">
      <div class="strategy-icon-circle">
        <lucide-users class="strategy-icon" />
      </div>
      <h3 class="strategy-title">Custom Audience Building</h3>
    </div>
    <ul class="strategy-list">
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon" />
        <span>Website visitor retargeting</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon" />
        <span>Customer list matching</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon" />
        <span>Lookalike audience creation</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon" />
        <span>Saved audiences by demographics & interests</span>
      </li>
    </ul>
  </div>

  <div v-motion :initial="{ opacity: 0, x: 50 }" :enter="{ opacity: 1, x: 0, transition: { delay: 500 } }" class="strategy-card">
    <div class="strategy-header">
      <div class="strategy-icon-circle">
        <lucide-target class="strategy-icon" />
      </div>
      <h3 class="strategy-title">Advanced Targeting Tactics</h3>
    </div>
    <ul class="strategy-list">
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon" />
        <span>Business decision-maker targeting</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon" />
        <span>Income-level targeting for premium services</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon" />
        <span>Expatriate targeting strategies</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon" />
        <span>Location-based targeting around branches</span>
      </li>
    </ul>
  </div>
</div>

<style>
.strategy-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1.5rem;
}
.strategy-card {
  background: linear-gradient(to bottom right, rgba(24, 24, 27, 0.8), rgba(39, 39, 42, 0.5));
  border-radius: 0.5rem;
  border: 1px solid #27272A;
  padding: 1.5rem;
  transition: all 0.3s ease;
  text-align: left;
}
.strategy-card:hover {
  transform: scale(1.02);
  border-color: rgba(0, 175, 239, 0.5);
  box-shadow: 0 0 10px rgba(0, 175, 239, 0.1);
}
.strategy-header {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  margin-bottom: 1rem;
}
.strategy-icon-circle {
  padding: 0.75rem;
  background-color: rgba(0, 175, 239, 0.2);
  border-radius: 9999px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.strategy-icon {
  width: 1.5rem;
  height: 1.5rem;
  color: #00AFEF;
}
.strategy-title {
  font-size: 1.25rem;
  font-weight: bold;
  color: #00AFEF;
}
.strategy-list {
  display: flex;
  flex-direction: column;
  gap: 0.75rem;
}
.strategy-item {
  display: flex;
  align-items: flex-start;
  gap: 0.75rem;
}
.sparkle-icon {
  width: 1.25rem;
  height: 1.25rem;
  color: rgba(0, 175, 239, 0.7);
  margin-top: 0.125rem;
}
</style>

---
src: ./pages/VideoType.md
---

---
layout: center
class: text-center
zoom: 0.8
---

<div v-motion :initial="{ opacity: 0 }" :enter="{ opacity: 1 }">
  <h1 class="section-title">Why Partner With Us</h1>
</div>
<div class="partners-grid">
  <div v-motion :initial="{ opacity: 0, y: 30 }" :enter="{ opacity: 1, y: 0, transition: { delay: 200 } }" class="partner-card">
    <div class="partner-icon-circle">
      <lucide-badge-check class="partner-icon" />
    </div>
    <h3 class="partner-title">Custom Strategy</h3>
    <p class="partner-text">Built specifically for NBF's unique position in banking</p>
  </div>

  <div v-motion :initial="{ opacity: 0, y: 30 }" :enter="{ opacity: 1, y: 0, transition: { delay: 500 } }" class="partner-card">
    <div class="partner-icon-circle">
      <lucide-trending-up class="partner-icon" />
    </div>
    <h3 class="partner-title">Performance Focus</h3>
    <p class="partner-text">Clear ROI metrics and results-driven approach</p>
  </div>

  <div v-motion :initial="{ opacity: 0, y: 30 }" :enter="{ opacity: 1, y: 0, transition: { delay: 600 } }" class="partner-card">
    <div class="partner-icon-circle">
      <lucide-users class="partner-icon" />
    </div>
    <h3 class="partner-title">Dedicated Team</h3>
    <p class="partner-text">Facebook advertising specialists with financial experience</p>
  </div>

  <div v-motion :initial="{ opacity: 0, y: 30 }" :enter="{ opacity: 1, y: 0, transition: { delay: 700 } }" class="partner-card">
    <div class="partner-icon-circle">
      <lucide-bar-chart-2 class="partner-icon" />
    </div>
    <h3 class="partner-title">Transparent Reporting</h3>
    <p class="partner-text">Continuous optimization with clear performance metrics</p>
  </div>
</div>

<style>
.partners-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1.5rem;
}
.partner-card {
  background: linear-gradient(to bottom right, rgba(24, 24, 27, 0.8), rgba(39, 39, 42, 0.5));
  border-radius: 0.5rem;
  border: 1px solid #27272A;
  padding: 1.5rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  transition: all 0.3s ease;
}
.partner-card:hover {
  transform: translateY(-5px);
  border-color: rgba(0, 175, 239, 0.5);
  box-shadow: 0 5px 15px rgba(0, 175, 239, 0.1);
}
.partner-icon-circle {
  padding: 0.75rem;
  background-color: rgba(0, 175, 239, 0.2);
  border-radius: 9999px;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 1rem;
}
.partner-icon {
  width: 2rem;
  height: 2rem;
  color: #00AFEF;
}
.partner-title {
  font-size: 1.125rem;
  font-weight: bold;
  color: #00AFEF;
  margin-bottom: 0.25rem !important;
}
.partner-text {
  font-size: 0.875rem;
  margin-top: 0.2rem !important;
}
</style>

---
layout: center
zoom: 0.8
class: text-center
---

<div v-motion :initial="{ opacity: 0 }" :enter="{ opacity: 1 }">
  <h1 class="section-title !mb-8">Next Steps: Launching NBF's Facebook Advertising Strategy</h1>
</div>

<div class="next-steps-grid">
  <div v-motion :initial="{ opacity: 0, scale: 0.9 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 200 } }" class="next-step-card">
    <div class="next-step-header">
      <div class="step-number">1</div>
      <h3 class="next-step-title">Audience Targeting Workshop</h3>
    </div>
    <p class="next-step-desc">Define specific audience segments and targeting parameters for campaigns</p>
  </div>

  <div v-motion :initial="{ opacity: 0, scale: 0.9 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 300 } }" class="next-step-card">
    <div class="next-step-header">
      <div class="step-number">2</div>
      <h3 class="next-step-title">Creative Brief Development</h3>
    </div>
    <p class="next-step-desc">Outline messaging, visual direction and offers for initial campaigns</p>
  </div>

  <div v-motion :initial="{ opacity: 0, scale: 0.9 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 400 } }" class="next-step-card">
    <div class="next-step-header">
      <div class="step-number">3</div>
      <h3 class="next-step-title">Content Production</h3>
    </div>
    <p class="next-step-desc">Create high quality content for NBF advertising</p>
  </div>

  <div v-motion :initial="{ opacity: 0, scale: 0.9 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 500 } }" class="next-step-card">
    <div class="next-step-header">
      <div class="step-number">4</div>
      <h3 class="next-step-title">Launch Test Campaigns</h3>
    </div>
    <p class="next-step-desc">Begin initial test campaigns to establish baseline performance</p>
  </div>
</div>

<style>
.next-steps-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
  max-width: 1000px;
  width: 100%;
  margin: 0 auto;
}
.next-step-card {
  background: linear-gradient(to bottom right, rgba(24, 24, 27, 0.8), rgba(0, 40, 85, 0.1));
  border-radius: 0.5rem;
  border: 1px solid #27272A;
  padding: 1.5rem;
  text-align: left;
  transition: all 0.3s ease;
}
.next-step-card:hover {
  transform: scale(1.03);
  border-color: rgba(0, 175, 239, 0.5);
  box-shadow: 0 0 10px rgba(0, 175, 239, 0.1);
}
.next-step-header {
  display: flex;
  align-items: center;
  gap: 1rem;
  margin-bottom: 0.5rem;
}
.step-number {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 3rem;
  height: 3rem;
  border-radius: 9999px;
  background-color: rgba(0, 175, 239, 0.2);
  color: #00AFEF;
  font-weight: bold;
  font-size: 1.5rem;
}
.next-step-title {
  font-size: 1.25rem;
  font-weight: bold;
  color: #00AFEF;
}
.next-step-desc {
  margin-left: 4rem;
  margin-top: 0 !important;
}
.cta-container {
  margin-top: 3rem;
  padding: 1.5rem;
  background: linear-gradient(to bottom right, rgba(24, 24, 27, 0.8), rgba(0, 40, 85, 0.2));
  border-radius: 0.5rem;
  border: 1px solid rgba(0, 175, 239, 0.3);
  display: inline-block;
  max-width: 600px;
  box-shadow: 0 5px 15px rgba(0, 175, 239, 0.1);
}
.cta-title {
  font-weight: bold;
  margin-bottom: 0.75rem;
  font-size: 1.5rem;
  color: white;
}
.cta-text {
  font-size: 1.125rem;
  color: #d4d4d8;
}
</style>

---
layout: cover
background: /rainbow.jpg
---

<div class="h-full flex flex-col items-center justify-center">
  <div v-motion :initial="{ opacity: 0, y: -50 }" :enter="{ opacity: 1, y: 0 }">
    <h1 class="thank-you-title !leading-[2]">Thank You</h1>
  </div>
  <div v-motion :initial="{ opacity: 0 }" :enter="{ opacity: 1, transition: { delay: 300 } }" class="thank-you-subtitle">
    Let's work together to make NBF unmissable in the UAE banking landscape
  </div>
  <div v-motion :initial="{ opacity: 0 }" :enter="{ opacity: 1, transition: { delay: 500 } }" class="contact-container">
    <div class="contact-item">
      <lucide-phone class="contact-icon" />
      <span><a href="tel:+971503636856" class="contact-link">+971 50 363 6856</a></span>
    </div>
    <div class="contact-item">
      <lucide-mail class="contact-icon" />
      <span><a href="mailto:admin@xmaagency.com" class="contact-link">admin@xmaagency.com</a></span>
    </div>
  </div>
</div>

<style>
.thank-you-title {
  font-size: 4rem;
  font-weight: bold;
  margin-bottom: 2rem;
}
.thank-you-subtitle {
  font-size: 1.5rem;
  margin-bottom: 3rem;
  color: #d4d4d8;
}
.contact-container {
  display: flex;
  align-items: center;
  gap: 3rem;
  margin-top: 1rem;
}
.contact-item {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  background-color: rgba(0, 175, 239, 0.1);
  padding: 0.75rem 1rem;
  border-radius: 0.5rem;
  backdrop-filter: blur(3px);
}
.contact-icon {
  width: 1.5rem;
  height: 1.5rem;
  color: #00AFEF;
}
.contact-link {
  transition: color 0.3s ease;
}
.contact-link:hover {
  color: #00AFEF;
}
</style>

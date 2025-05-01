---
theme: ./theme
colorscheme: dark
favicon: '/XMA-White.svg'
transition: my-transition
title: Social Media Advertising Strategy
layout: cover
background: /gradient-dark.jpg
fonts:
  mono: "JetBrains Mono"
  local: Mona Sans
---

<div class="flex my-auto flex-col items-center justify-center h-full">
  <h1 class="font-bold bg-gradient-to-r from-blue-400 via-purple-400 to-orange-400 bg-clip-text text-transparent">Social Media Advertising Strategy</h1>
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
        <div class="icon-circle blue-gradient">
          <lucide-eye class="icon" />
        </div>
        <p class="!m-0">Enhance your <span class="highlight-text blue-text">digital visibility</span> in the UAE banking sector</p>
      </div>
      <div v-click class="opportunity-item">
        <div class="icon-circle purple-gradient">
          <lucide-users class="icon" />
        </div>
        <p class="!my-0">Generate <span class="highlight-text purple-text">qualified leads</span> for business and personal banking</p>
      </div>
      <div v-click class="opportunity-item">
        <div class="icon-circle teal-gradient">
          <lucide-award class="icon" />
        </div>
        <p class="!m-0">Strengthen <span class="highlight-text teal-text">competitive positioning</span> against larger banks</p>
      </div>
      <div v-click class="opportunity-item">
        <div class="icon-circle orange-gradient">
          <lucide-trending-up class="icon" />
        </div>
        <p class="!my-0">Drive <span class="highlight-text orange-text">measurable ROI</span> from social media advertising</p>
      </div>
    </div>
  </div>
</div>

<style>
.opportunity-title {
  font-size: 2.25rem;
  font-weight: bold;
  margin-bottom: 1.5rem;
  text-align: center;
}
.opportunity-card {
  max-width: 850px;
  margin: 0 auto;
  padding: 1.5rem;
  border-radius: 0.5rem;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  @apply bg-zinc-900 border border-zinc-700;
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
  border-radius: 9999px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.blue-gradient {
  background: linear-gradient(135deg, rgba(0, 175, 239, 0.2), rgba(59, 130, 246, 0.2));
}
.purple-gradient {
  background: linear-gradient(135deg, rgba(147, 51, 234, 0.2), rgba(192, 132, 252, 0.2));
}
.teal-gradient {
  background: linear-gradient(135deg, rgba(20, 184, 166, 0.2), rgba(45, 212, 191, 0.2));
}
.orange-gradient {
  background: linear-gradient(135deg, rgba(249, 115, 22, 0.2), rgba(251, 146, 60, 0.2));
}
.icon {
  width: 1.5rem;
  height: 1.5rem;
}
.blue-text {
  color: #3B82F6;
  font-weight: 500;
}
.purple-text {
  color: #A855F7;
  font-weight: 500;
}
.teal-text {
  color: #14B8A6;
  font-weight: 500;
}
.orange-text {
  color: #F97316;
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
  <div v-motion :initial="{ opacity: 0, x: -50 }" :enter="{ opacity: 1, x: 0, transition: { delay: 200 } }" class="analysis-card red-border">
    <div class="card-header">
      <div class="icon-circle red-text">
        <lucide-pie-chart class="icon" />
      </div>
      <h3 class="card-title red-text">NBF Current Situation</h3>
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
  <div v-motion :initial="{ opacity: 0, x: 50 }" :enter="{ opacity: 1, x: 0, transition: { delay: 400 } }" class="analysis-card green-border">
    <div class="card-header">
      <div class="icon-circle green-text">
        <lucide-scan-face class="icon" />
      </div>
      <h3 class="card-title green-text">Competitive Landscape</h3>
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
  filter: drop-shadow(0 0 8px rgba(0, 175, 239, 0.2));
}
.analysis-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
}
.analysis-card {
  border-radius: 0.5rem;
  padding: 1.5rem;
  transition: all 0.3s ease;
}
.red-border {
  border: 1px solid rgba(239, 68, 68, 0.3);
  background: linear-gradient(to bottom right, #1a0a0a, #1c1917);
}
.green-border {
  border: 1px solid rgba(34, 197, 94, 0.3);
  background: linear-gradient(to bottom right, #0a1a0e, #0f1b18);
}
.analysis-card:hover {
  transform: scale(1.02);
  box-shadow: 0 0 10px rgba(0, 175, 239, 0.1);
}
.red-border:hover {
  border-color: rgba(239, 68, 68, 0.5);
}
.green-border:hover {
  border-color: rgba(34, 197, 94, 0.5);
}
.card-header {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  margin-bottom: 1rem;
}
.red-gradient {
  background: linear-gradient(135deg, rgba(239, 68, 68, 0.2), rgba(248, 113, 113, 0.2));
}
.green-gradient {
  background: linear-gradient(135deg, rgba(34, 197, 94, 0.2), rgba(74, 222, 128, 0.2));
}
.red-text {
  color: #EF4444;
}
.green-text {
  color: #22C55E;
}
.card-title {
  font-size: 1.25rem;
  font-weight: bold;
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
  <div v-motion :initial="{ opacity: 0, scale: 0.9 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 200 } }" class="opportunity-card blue-border">
    <div class="card-header">
      <div class="icon-circle">
        <lucide-rocket class="icon blue-icon" />
      </div>
      <h3 class="card-title blue-text">Platform Advantages</h3>
    </div>
    <ul class="advantage-list">
      <li class="advantage-item">
        <div class="check-circle blue-check">
          <lucide-check class="check-icon" />
        </div>
        <span>UAE has one of the highest Facebook penetration rates globally</span>
      </li>
      <li class="advantage-item">
        <div class="check-circle blue-check">
          <lucide-check class="check-icon" />
        </div>
        <span>Banking customers research financial products on social platforms</span>
      </li>
      <li class="advantage-item">
        <div class="check-circle blue-check">
          <lucide-check class="check-icon" />
        </div>
        <span>Precise targeting capabilities for your ideal customer segments</span>
      </li>
      <li class="advantage-item">
        <div class="check-circle blue-check">
          <lucide-check class="check-icon" />
        </div>
        <span>Cost-effective lead generation compared to traditional channels</span>
      </li>
    </ul>
  </div>
  <div v-motion :initial="{ opacity: 0, scale: 0.9 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 400 } }" class="opportunity-card purple-border">
    <div class="card-header">
      <div class="icon-circle">
        <lucide-users class="icon purple-icon" />
      </div>
      <h3 class="card-title purple-text">Target Audiences Available</h3>
    </div>
    <ul class="audience-list">
      <li class="audience-item">
        <div class="audience-icon-circle orange-gradient">
          <lucide-briefcase class="audience-icon orange-icon" />
        </div>
        <span>Business owners and decision makers (business banking)</span>
      </li>
      <li class="audience-item">
        <div class="audience-icon-circle teal-gradient">
          <lucide-gem class="audience-icon teal-icon" />
        </div>
        <span>High-net-worth individuals (premium services)</span>
      </li>
      <li class="audience-item">
        <div class="audience-icon-circle pink-gradient">
          <lucide-users class="audience-icon pink-icon" />
        </div>
        <span>Specific expatriate communities (remittance services)</span>
      </li>
      <li class="audience-item">
        <div class="audience-icon-circle amber-gradient">
          <lucide-flag class="audience-icon amber-icon" />
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
  border-radius: 0.5rem;
  padding: 1.5rem;
  transition: all 0.3s ease;
}
.blue-border {
  border: 1px solid rgba(59, 130, 246, 0.3);
  background: linear-gradient(to bottom right, #0a1a2f, #0f172a);
}
.purple-border {
  border: 1px solid rgba(168, 85, 247, 0.3);
  background: linear-gradient(to bottom right, #1a0a2c, #1e1b33);
}
.opportunity-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
}
.blue-border:hover {
  border-color: rgba(59, 130, 246, 0.5);
  box-shadow: 0 5px 15px rgba(59, 130, 246, 0.1);
}
.purple-border:hover {
  border-color: rgba(168, 85, 247, 0.5);
  box-shadow: 0 5px 15px rgba(168, 85, 247, 0.1);
}
.blue-gradient {
  background: linear-gradient(135deg, rgba(59, 130, 246, 0.2), rgba(96, 165, 250, 0.2));
}
.purple-gradient {
  background: linear-gradient(135deg, rgba(168, 85, 247, 0.2), rgba(192, 132, 252, 0.2));
}
.orange-gradient {
  background: linear-gradient(135deg, rgba(249, 115, 22, 0.2), rgba(251, 146, 60, 0.2));
}
.teal-gradient {
  background: linear-gradient(135deg, rgba(20, 184, 166, 0.2), rgba(45, 212, 191, 0.2));
}
.pink-gradient {
  background: linear-gradient(135deg, rgba(236, 72, 153, 0.2), rgba(244, 114, 182, 0.2));
}
.amber-gradient {
  background: linear-gradient(135deg, rgba(245, 158, 11, 0.2), rgba(251, 191, 36, 0.2));
}
.blue-icon {
  color: #3B82F6;
}
.purple-icon {
  color: #A855F7;
}
.orange-icon {
  color: #F97316;
}
.teal-icon {
  color: #14B8A6;
}
.pink-icon {
  color: #EC4899;
}
.amber-icon {
  color: #F59E0B;
}
.blue-text {
  color: #3B82F6;
}
.purple-text {
  color: #A855F7;
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
  border-radius: 9999px;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 0.125rem;
}
.blue-check {
  background-color: rgba(59, 130, 246, 0.1);
}
.check-icon, .audience-icon {
  width: 1rem;
  height: 1rem;
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
  <div v-motion :initial="{ opacity: 0, y: 50 }" :enter="{ opacity: 1, y: 0, transition: { delay: 200 } }" class="methodology-card blue-glow">
    <div class="icon-large-circle blue-gradient">
      <lucide-target class="icon-large blue-icon" />
    </div>
    <h3 class="methodology-title blue-text">Precision Targeting</h3>
    <p class="!my-0">Advanced audience building for your exact customer segments</p>
  </div>

  <div v-motion :initial="{ opacity: 0, y: 50 }" :enter="{ opacity: 1, y: 0, transition: { delay: 400 } }" class="methodology-card purple-glow">
    <div class="icon-large-circle purple-gradient">
      <lucide-palette class="icon-large" />
    </div>
    <h3 class="methodology-title purple-text">Compelling Creative</h3>
    <p class="!my-0">Eye-catching ads that convert viewers to customers</p>
  </div>

  <div v-motion :initial="{ opacity: 0, y: 50 }" :enter="{ opacity: 1, y: 0, transition: { delay: 600 } }" class="methodology-card orange-glow">
    <div class="icon-large-circle orange-gradient">
      <lucide-activity class="icon-large orange-icon" />
    </div>
    <h3 class="methodology-title orange-text">Data-Driven Optimization</h3>
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
  border-radius: 0.75rem;
  padding: 1.5rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  transition: all 0.3s ease;
}
.blue-glow {
  border: 1px solid rgba(59, 130, 246, 0.3);
  background: linear-gradient(to bottom, #0c1c2f, #0f172a);
}
.purple-glow {
  border: 1px solid rgba(168, 85, 247, 0.3);
  background: linear-gradient(to bottom, #1a0d2a, #1e1b33);
}
.orange-glow {
  border: 1px solid rgba(249, 115, 22, 0.3);
  background: linear-gradient(to bottom, #2a170c, #27201a);
}
.methodology-card:hover {
  transform: translateY(-5px);
}
.blue-glow:hover {
  border-color: rgba(59, 130, 246, 0.5);
  box-shadow: 0 5px 15px rgba(59, 130, 246, 0.1);
}
.purple-glow:hover {
  border-color: rgba(168, 85, 247, 0.5);
  box-shadow: 0 5px 15px rgba(168, 85, 247, 0.1);
}
.orange-glow:hover {
  border-color: rgba(249, 115, 22, 0.5);
  box-shadow: 0 5px 15px rgba(249, 115, 22, 0.1);
}
.icon-large-circle {
  padding: 1rem;
  border-radius: 9999px;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 1rem;
}
.icon-large {
  width: 2.5rem;
  height: 2.5rem;
}
.methodology-title {
  font-size: 1.25rem;
  font-weight: bold;
  margin-bottom: 0.5rem;
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
  <div v-motion :initial="{ opacity: 0, x: -50 }" :enter="{ opacity: 1, x: 0, transition: { delay: 200 } }" class="strategy-card pink-glow">
    <div class="strategy-header">
      <div class="strategy-icon-circle">
        <lucide-paintbrush class="strategy-icon pink-icon" />
      </div>
      <h3 class="strategy-title pink-text">Creative Optimization</h3>
    </div>
    <ul class="strategy-list">
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon pink-sparkle" />
        <span>Systematic A/B testing of ads</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon pink-sparkle" />
        <span>Performance-based budget allocation</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon pink-sparkle" />
        <span>Continuous creative refreshment</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon pink-sparkle" />
        <span>Format variation based on objective</span>
      </li>
    </ul>
  </div>

  <div v-motion :initial="{ opacity: 0, x: 50 }" :enter="{ opacity: 1, x: 0, transition: { delay: 300 } }" class="strategy-card indigo-glow">
    <div class="strategy-header">
      <div class="strategy-icon-circle">
        <lucide-layers class="strategy-icon indigo-icon" />
      </div>
      <h3 class="strategy-title indigo-text">Campaign Structure</h3>
    </div>
    <ul class="strategy-list">
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon indigo-sparkle" />
        <span>Awareness campaigns for brand building</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon indigo-sparkle" />
        <span>Consideration campaigns showcasing benefits</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon indigo-sparkle" />
        <span>Conversion campaigns driving applications</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon indigo-sparkle" />
        <span>Retention campaigns for cross-selling</span>
      </li>
    </ul>
  </div>

  <div v-motion :initial="{ opacity: 0, x: -50 }" :enter="{ opacity: 1, x: 0, transition: { delay: 400 } }" class="strategy-card amber-glow">
    <div class="strategy-header">
      <div class="strategy-icon-circle">
        <lucide-users class="strategy-icon amber-icon" />
      </div>
      <h3 class="strategy-title amber-text">Custom Audience Building</h3>
    </div>
    <ul class="strategy-list">
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon amber-sparkle" />
        <span>Website visitor retargeting</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon amber-sparkle" />
        <span>Customer list matching</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon amber-sparkle" />
        <span>Lookalike audience creation</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon amber-sparkle" />
        <span>Saved audiences by demographics & interests</span>
      </li>
    </ul>
  </div>

  <div v-motion :initial="{ opacity: 0, x: 50 }" :enter="{ opacity: 1, x: 0, transition: { delay: 500 } }" class="strategy-card teal-glow">
    <div class="strategy-header">
      <div class="strategy-icon-circle teal-text">
        <lucide-target class="strategy-icon" />
      </div>
      <h3 class="strategy-title teal-text">Advanced Targeting Tactics</h3>
    </div>
    <ul class="strategy-list">
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon teal-sparkle" />
        <span>Business decision-maker targeting</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon teal-sparkle" />
        <span>Income-level targeting for premium services</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon teal-sparkle" />
        <span>Expatriate targeting strategies</span>
      </li>
      <li class="strategy-item">
        <lucide-sparkles class="sparkle-icon teal-sparkle" />
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
  border-radius: 0.5rem;
  padding: 1.5rem;
  transition: all 0.3s ease;
  text-align: left;
}
.pink-glow {
  border: 1px solid rgba(236, 72, 153, 0.3);
  background: linear-gradient(to bottom right, #2d0a20, #271625);
}
.indigo-glow {
  border: 1px solid rgba(99, 102, 241, 0.3);
  background: linear-gradient(to bottom right, #0e1188, #151933);
}
.amber-glow {
  border: 1px solid rgba(245, 158, 11, 0.3);
  background: linear-gradient(to bottom right, #2e1c08, #271f15);
}
.teal-glow {
  border: 1px solid rgba(20, 184, 166, 0.3);
  background: linear-gradient(to bottom right, #042f26, #0f2a29);
}
.strategy-card:hover {
  transform: scale(1.02);
}
.pink-glow:hover {
  border-color: rgba(236, 72, 153, 0.5);
  box-shadow: 0 0 10px rgba(236, 72, 153, 0.1);
}
.indigo-glow:hover {
  border-color: rgba(99, 102, 241, 0.5);
  box-shadow: 0 0 10px rgba(99, 102, 241, 0.1);
}
.amber-glow:hover {
  border-color: rgba(245, 158, 11, 0.5);
  box-shadow: 0 0 10px rgba(245, 158, 11, 0.1);
}
.teal-glow:hover {
  border-color: rgba(20, 184, 166, 0.5);
  box-shadow: 0 0 10px rgba(20, 184, 166, 0.1);
}
.strategy-header {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  margin-bottom: 1rem;
}
.strategy-icon-circle {
  padding: 0.75rem;
  border-radius: 9999px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.pink-gradient {
  background: linear-gradient(135deg, rgba(236, 72, 153, 0.2), rgba(244, 114, 182, 0.2));
}
.indigo-gradient {
  background: linear-gradient(135deg, rgba(99, 102, 241, 0.2), rgba(129, 140, 248, 0.2));
}
.amber-gradient {
  background: linear-gradient(135deg, rgba(245, 158, 11, 0.2), rgba(251, 191, 36, 0.2));
}
.pink-icon {
  color: #EC4899;
}
.indigo-icon {
  color: #6366F1;
}
.amber-icon {
  color: #F59E0B;
}
.teal-icon {
  color: #14B8A6;
}
.pink-text {
  color: #EC4899;
}
.indigo-text {
  @apply text-indigo-300;
}
.amber-text {
  color: #F59E0B;
}
.teal-text {
  color: #14B8A6;
}
.strategy-title {
  font-size: 1.25rem;
  font-weight: bold;
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
.pink-sparkle {
  color: rgba(236, 72, 153, 0.7);
}
.indigo-sparkle {
  color: rgba(99, 102, 241, 0.7);
}
.amber-sparkle {
  color: rgba(245, 158, 11, 0.7);
}
.teal-sparkle {
  color: rgba(20, 184, 166, 0.7);
}
.sparkle-icon {
  width: 1.25rem;
  height: 1.25rem;
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
  <div v-motion :initial="{ opacity: 0, y: 30 }" :enter="{ opacity: 1, y: 0, transition: { delay: 200 } }" class="partner-card purple-glow">
    <div class="partner-icon-circle purple-gradient">
      <lucide-badge-check class="partner-icon purple-icon" />
    </div>
    <h3 class="partner-title purple-text">Custom Strategy</h3>
    <p class="partner-text">Built specifically for NBF's unique position in banking</p>
  </div>

  <div v-motion :initial="{ opacity: 0, y: 30 }" :enter="{ opacity: 1, y: 0, transition: { delay: 500 } }" class="partner-card green-glow">
    <div class="partner-icon-circle green-gradient">
      <lucide-trending-up class="partner-icon green-icon" />
    </div>
    <h3 class="partner-title green-text">Performance Focus</h3>
    <p class="partner-text">Clear ROI metrics and results-driven approach</p>
  </div>

  <div v-motion :initial="{ opacity: 0, y: 30 }" :enter="{ opacity: 1, y: 0, transition: { delay: 600 } }" class="partner-card blue-glow">
    <div class="partner-icon-circle blue-gradient">
      <lucide-users class="partner-icon blue-icon" />
    </div>
    <h3 class="partner-title blue-text">Dedicated Team</h3>
    <p class="partner-text">Facebook advertising specialists with financial experience</p>
  </div>

  <div v-motion :initial="{ opacity: 0, y: 30 }" :enter="{ opacity: 1, y: 0, transition: { delay: 700 } }" class="partner-card orange-glow">
    <div class="partner-icon-circle orange-gradient">
      <lucide-bar-chart-2 class="partner-icon orange-icon" />
    </div>
    <h3 class="partner-title orange-text">Transparent Reporting</h3>
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
  border-radius: 0.5rem;
  padding: 1.5rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  transition: all 0.3s ease;
}
.purple-glow {
  border: 1px solid rgba(168, 85, 247, 0.3);
  background: linear-gradient(to bottom, #190a2a, #1e1b33);
}
.green-glow {
  border: 1px solid rgba(34, 197, 94, 0.3);
  background: linear-gradient(to bottom, #0a2816, #14201a);
}
.blue-glow {
  border: 1px solid rgba(59, 130, 246, 0.3);
  background: linear-gradient(to bottom, #0a1a2e, #0f172a);
}
.orange-glow {
  border: 1px solid rgba(249, 115, 22, 0.3);
  background: linear-gradient(to bottom, #2a1408, #27201a);
}
.partner-card:hover {
  transform: translateY(-5px);
}
.purple-glow:hover {
  border-color: rgba(168, 85, 247, 0.5);
  box-shadow: 0 5px 15px rgba(168, 85, 247, 0.1);
}
.green-glow:hover {
  border-color: rgba(34, 197, 94, 0.5);
  box-shadow: 0 5px 15px rgba(34, 197, 94, 0.1);
}
.blue-glow:hover {
  border-color: rgba(59, 130, 246, 0.5);
  box-shadow: 0 5px 15px rgba(59, 130, 246, 0.1);
}
.orange-glow:hover {
  border-color: rgba(249, 115, 22, 0.5);
  box-shadow: 0 5px 15px rgba(249, 115, 22, 0.1);
}
.partner-icon-circle {
  padding: 0.75rem;
  border-radius: 9999px;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 1rem;
}
.green-icon {
  color: #22C55E;
}
.partner-icon {
  width: 2rem;
  height: 2rem;
}
.green-text {
  color: #22C55E;
}
.partner-title {
  font-size: 1.125rem;
  font-weight: bold;
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
  <div v-motion :initial="{ opacity: 0, scale: 0.9 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 200 } }" class="next-step-card blue-border">
    <div class="next-step-header">
      <div class="step-number blue-step">1</div>
      <h3 class="next-step-title blue-text">Audience Targeting Workshop</h3>
    </div>
    <p class="next-step-desc">Define specific audience segments and targeting parameters for campaigns</p>
  </div>

  <div v-motion :initial="{ opacity: 0, scale: 0.9 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 300 } }" class="next-step-card purple-border">
    <div class="next-step-header">
      <div class="step-number purple-step">2</div>
      <h3 class="next-step-title purple-text">Creative Brief Development</h3>
    </div>
    <p class="next-step-desc">Outline messaging, visual direction and offers for initial campaigns</p>
  </div>

  <div v-motion :initial="{ opacity: 0, scale: 0.9 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 400 } }" class="next-step-card teal-border">
    <div class="next-step-header">
      <div class="step-number teal-step">3</div>
      <h3 class="next-step-title teal-text">Content Production</h3>
    </div>
    <p class="next-step-desc">Create high quality content for NBF advertising</p>
  </div>

  <div v-motion :initial="{ opacity: 0, scale: 0.9 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 500 } }" class="next-step-card orange-border">
    <div class="next-step-header">
      <div class="step-number orange-step">4</div>
      <h3 class="next-step-title orange-text">Launch Test Campaigns</h3>
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
  border-radius: 0.5rem;
  padding: 1.5rem;
  text-align: left;
  transition: all 0.3s ease;
}
.blue-border {
  border: 1px solid rgba(59, 130, 246, 0.3);
  background: linear-gradient(to bottom, #0a1a2e, #0f172a);
}
.purple-border {
  border: 1px solid rgba(168, 85, 247, 0.3);
  background: linear-gradient(to bottom, #190a2a, #1e1b33); 
}
.teal-border {
  border: 1px solid rgba(20, 184, 166, 0.3);
  background: linear-gradient(to bottom, #042f2a, #0f2a29);
}
.orange-border {
  border: 1px solid rgba(249, 115, 22, 0.3);
  background: linear-gradient(to bottom, #2a1408, #27201a);
}
.next-step-card:hover {
  transform: scale(1.03);
}
.blue-border:hover {
  border-color: rgba(59, 130, 246, 0.5);
  box-shadow: 0 0 10px rgba(59, 130, 246, 0.1);
}
.purple-border:hover {
  border-color: rgba(168, 85, 247, 0.5);
  box-shadow: 0 0 10px rgba(168, 85, 247, 0.1);
}
.teal-border:hover {
  border-color: rgba(20, 184, 166, 0.5);
  box-shadow: 0 0 10px rgba(20, 184, 166, 0.1);
}
.orange-border:hover {
  border-color: rgba(249, 115, 22, 0.5);
  box-shadow: 0 0 10px rgba(249, 115, 22, 0.1);
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
  font-weight: bold;
  font-size: 1.5rem;
}
.blue-step {
  background-color: rgba(59, 130, 246, 0.2);
  color: #3B82F6;
}
.purple-step {
  background-color: rgba(168, 85, 247, 0.2);
  color: #A855F7;
}
.teal-step {
  background-color: rgba(20, 184, 166, 0.2);
  color: #14B8A6;
}
.orange-step {
  background-color: rgba(249, 115, 22, 0.2);
  color: #F97316;
}
.next-step-desc {
  margin-left: 4rem;
  margin-top: 0 !important;
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
    <div class="contact-item blue-contact">
      <lucide-phone class="contact-icon blue-icon" />
      <span><a href="tel:+971503636856" class="contact-link">+971 50 363 6856</a></span>
    </div>
    <div class="contact-item purple-contact">
      <lucide-mail class="contact-icon purple-icon" />
      <span><a href="mailto:admin@xmaagency.com" class="contact-link">admin@xmaagency.com</a></span>
    </div>
  </div>
</div>

<style>
.thank-you-title {
  font-size: 4rem;
  font-weight: bold;
  margin-bottom: 2rem;
  filter: drop-shadow(0 0 12px rgba(59, 130, 246, 0.3));
}
.thank-you-subtitle {
  font-size: 1.5rem;
  margin-bottom: 3rem;
  color: #d4d4d8;
  text-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
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
  padding: 0.75rem 1rem;
  border-radius: 0.5rem;
  backdrop-filter: blur(3px);
}
.blue-contact {
  background-color: rgba(59, 130, 246, 0.1);
  border: 1px solid rgba(59, 130, 246, 0.2);
}
.purple-contact {
  background-color: rgba(168, 85, 247, 0.1);
  border: 1px solid rgba(168, 85, 247, 0.2);
}
.contact-icon {
  width: 1.5rem;
  height: 1.5rem;
}
.contact-link {
  transition: color 0.3s ease;
}
.blue-contact .contact-link:hover {
  color: #3B82F6;
}
.purple-contact .contact-link:hover {
  color: #A855F7;
}
</style>

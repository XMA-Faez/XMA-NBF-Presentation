---
layout: center
zoom: 0.7
---

<div v-motion :initial="{ opacity: 0 }" :enter="{ opacity: 1 }">
  <h1 class="section-title text-center">Implementation Roadmap</h1>
</div>

<div class="roadmap-grid">
  <div v-motion :initial="{ opacity: 0, scale: 0.8 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 200 } }" class="roadmap-card">
    <div class="phase-header">
      <div class="phase-number">1</div>
      <div>
        <h3 class="phase-title">Foundation Phase</h3>
        <div class="phase-time">Weeks 1-4</div>
      </div>
    </div>
    <ul class="phase-list">
      <li class="phase-item">
        <lucide-check-circle class="phase-check" />
        <span>Audience research and targeting setup</span>
      </li>
      <li class="phase-item">
        <lucide-check-circle class="phase-check" />
        <span>Pixel implementation and tracking</span>
      </li>
      <li class="phase-item">
        <lucide-check-circle class="phase-check" />
        <span>First wave creative development</span>
      </li>
      <li class="phase-item">
        <lucide-check-circle class="phase-check" />
        <span>Launch initial test campaigns</span>
      </li>
    </ul>
  </div>

  <div v-motion :initial="{ opacity: 0, scale: 0.8 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 400 } }" class="roadmap-card">
    <div class="phase-header">
      <div class="phase-number">2</div>
      <div>
        <h3 class="phase-title">Expansion Phase</h3>
        <div class="phase-time">Weeks 5-8</div>
      </div>
    </div>
    <ul class="phase-list">
      <li class="phase-item">
        <lucide-check-circle class="phase-check" />
        <span>Scale successful ads and audiences</span>
      </li>
      <li class="phase-item">
        <lucide-check-circle class="phase-check" />
        <span>Implement advanced targeting</span>
      </li>
      <li class="phase-item">
        <lucide-check-circle class="phase-check" />
        <span>Expand ad formats based on data</span>
      </li>
      <li class="phase-item">
        <lucide-check-circle class="phase-check" />
        <span>Increase budget to top performers</span>
      </li>
    </ul>
  </div>

  <div v-motion :initial="{ opacity: 0, scale: 0.8 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 600 } }" class="roadmap-card">
    <div class="phase-header">
      <div class="phase-number">3</div>
      <div>
        <h3 class="phase-title">Optimization Phase</h3>
        <div class="phase-time">Weeks 9-12</div>
      </div>
    </div>
    <ul class="phase-list">
      <li class="phase-item">
        <lucide-check-circle class="phase-check" />
        <span>Refined audience targeting</span>
      </li>
      <li class="phase-item">
        <lucide-check-circle class="phase-check" />
        <span>Creative optimization</span>
      </li>
      <li class="phase-item">
        <lucide-check-circle class="phase-check" />
        <span>Conversion rate improvements</span>
      </li>
      <li class="phase-item">
        <lucide-check-circle class="phase-check" />
        <span>Strategy refinement</span>
      </li>
    </ul>
  </div>
</div>

<div v-motion :initial="{ opacity: 0, y: 50 }" :enter="{ opacity: 1, y: 0, transition: { delay: 800 } }" class="results-container">
  <h3 class="results-title">Expected Results</h3>
  <div class="results-grid">
    <div class="result-card">
      <div class="result-icon-circle">
        <lucide-users class="result-icon" />
      </div>
      <div class="result-number">150-200</div>
      <div class="result-label">Qualified leads monthly</div>
    </div>
    <div class="result-card">
      <div class="result-icon-circle">
        <lucide-eye class="result-icon" />
      </div>
      <div class="result-number">500,000+</div>
      <div class="result-label">Targeted impressions</div>
    </div>
    <div class="result-card">
      <div class="result-icon-circle">
        <lucide-thumbs-up class="result-icon" />
      </div>
      <div class="result-number">300%+</div>
      <div class="result-label">Engagement growth</div>
    </div>
    <div class="result-card">
      <div class="result-icon-circle">
        <lucide-badge-percent class="result-icon" />
      </div>
      <div class="result-number">30-40%</div>
      <div class="result-label">Below industry CPA</div>
    </div>
  </div>
</div>

<style>
.roadmap-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.5rem;
  margin-bottom: 2rem;
}
.roadmap-card {
  background: linear-gradient(to bottom right, rgba(24, 24, 27, 0.8), rgba(0, 40, 85, 0.1));
  border-radius: 0.5rem;
  border: 1px solid #27272A;
  padding: 1.5rem;
  transition: all 0.3s ease;
}
.roadmap-card:hover {
  transform: scale(1.02);
  border-color: rgba(0, 175, 239, 0.5);
  box-shadow: 0 0 10px rgba(0, 175, 239, 0.1);
}
.phase-header {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  margin-bottom: 1rem;
}
.phase-number {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 2.5rem;
  height: 2.5rem;
  border-radius: 9999px;
  background-color: rgba(0, 175, 239, 0.2);
  color: #00AFEF;
  font-weight: bold;
  font-size: 1.25rem;
}
.phase-title {
  font-size: 1.25rem;
  font-weight: bold;
  color: #00AFEF;
}
.phase-time {
  font-size: 0.875rem;
  color: rgba(0, 175, 239, 0.7);
}
.phase-list {
  display: flex;
  flex-direction: column;
  gap: 0.75rem;
}
.phase-item {
  display: flex;
  align-items: flex-start;
  gap: 0.5rem;
}
.phase-check {
  width: 1.25rem;
  height: 1.25rem;
  color: #00AFEF;
  margin-top: 0.125rem;
  flex-shrink: 0;
}
.results-container {
  margin-top: 2rem;
  padding: 1.25rem;
  background: linear-gradient(to right, rgba(0, 175, 239, 0.1), rgba(0, 40, 85, 0.05));
  border-radius: 0.5rem;
  border: 1px solid rgba(0, 175, 239, 0.3);
}
.results-title {
  font-weight: bold;
  margin-bottom: 1rem;
  text-align: center;
  font-size: 1.25rem;
  color: #00AFEF;
}
.results-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 1.5rem;
  text-align: center;
}
.result-card {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.result-icon-circle {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 4rem;
  height: 4rem;
  border-radius: 9999px;
  background-color: rgba(0, 175, 239, 0.2);
  margin-bottom: 0.75rem;
}
.result-icon {
  width: 2rem;
  height: 2rem;
  color: #00AFEF;
}
.result-number {
  font-size: 1.5rem;
  font-weight: bold;
  color: white;
}
.result-label {
  font-size: 0.875rem;
  color: #a1a1aa;
}
.text-center {
  text-align: center;
}
</style>


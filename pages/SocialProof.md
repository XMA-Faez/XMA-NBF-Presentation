---
class: text-center
---

<h1 class="proof-heading !leading-[2]">Trusted By Leading Businesses</h1>

<div class="stats-container" v-motion :initial="{ opacity: 0, y: 100 }" :enter="{ opacity: 1, y: 0 }" :exit="{ opacity: 1, y: 0 }">
    <dl class="stats-grid">
        <div class="stat-card" v-motion :initial="{ filter: 'blur(12px)', opacity: 0, scale: 0.8 }" :enter="{ filter: 'blur(0px)', opacity: 1, scale: 1, transition: { delay: 200 } }">
            <dd class="stat-number">
                <Ticker :value="50" :decimalPlaces="0" />+
            </dd>
            <dt class="stat-label">Total Clients</dt>
        </div>
        <div class="stat-card" v-motion :initial="{ filter: 'blur(12px)', opacity: 0, scale: 0.8 }" :enter="{ filter: 'blur(0px)', opacity: 1, scale: 1, transition: { delay: 400 } }">
            <dd class="stat-number">
                <Ticker :value="30" decimalPlaces="0" />K+
            </dd>
            <dt class="stat-label">Leads Generated</dt>
        </div>
        <div class="stat-card" v-motion :initial="{ filter: 'blur(12px)', opacity: 0, scale: 0.8 }" :enter="{ filter: 'blur(0px)', opacity: 1, scale: 1, transition: { delay: 600 } }">
            <dd class="stat-number">
                AED <Ticker :value="3" decimalPlaces="0" />M+
            </dd>
            <dt class="stat-label">Ad Budget Managed</dt>
        </div>
    </dl>
</div>

<div class="marquee-container" v-motion :initial="{ opacity: 0 }" :enter="{ opacity: 1, transition: { delay: 800 } }">
    <Marquee class="[--duration:20s]">
        <img src="/packman_Logo.png" class="logo-image" />
        <img src="/Casapons.png" class="logo-image" />
        <img src="/DXtreme.svg" class="logo-image-padded" />
        <img src="/4Matic.jpg" class="logo-image-transparent" />
        <img src="/wyz-logo.png" class="logo-image-padded" />
        <img src="/Tick.webp" class="logo-image-padded" />
        <img src="/ASUS.png" class="logo-image" />
        <img src="/TFG.png" class="logo-image" />
    </Marquee>
    <div class="fade-left"></div>
    <div class="fade-right"></div>
</div>

<style>
.proof-heading {
  font-size: 2.5rem;
  font-weight: bold;
  margin-bottom: 1.5rem;
  background: linear-gradient(to right, #00AFEF, #87CEFA);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
}

.stats-container {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem 1rem;
}

.stats-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 2rem;
  margin-top: 2rem;
}

@media (min-width: 640px) {
  .stats-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (min-width: 1024px) {
  .stats-grid {
    grid-template-columns: repeat(3, 1fr);
  }
}

.stat-card {
  display: flex;
  flex-direction: column;
  padding: 2rem 1rem;
  text-align: center;
  background-color: rgba(24, 24, 27, 0.5);
  border-radius: 0.75rem;
  border: 1px solid #27272A;
  transition: all 0.3s ease;
}

.stat-card:hover {
  border-color: rgba(0, 175, 239, 0.5);
  box-shadow: 0 10px 15px -3px rgba(0, 175, 239, 0.1);
}

.stat-number {
  font-size: 2.25rem;
  font-weight: 800;
  color: #00AFEF;
  margin-bottom: 1rem;
}

@media (min-width: 768px) {
  .stat-number {
    font-size: 2.5rem;
  }
}

.stat-label {
  font-size: 1rem;
  font-weight: 500;
  color: #a1a1aa;
}

.marquee-container {
  position: relative;
  margin-top: 2rem;
}

.logo-image {
  height: 3rem;
  background-color: white;
  border-radius: 0.75rem;
  transition: transform 0.3s ease;
}

.logo-image-padded {
  height: 3rem;
  background-color: white;
  border-radius: 0.75rem;
  padding: 0.5rem;
  transition: transform 0.3s ease;
}

.logo-image-transparent {
  height: 3rem;
  border-radius: 0.75rem;
  transition: transform 0.3s ease;
}

.fade-left {
  pointer-events: none;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  width: 33.333%;
  background: linear-gradient(to right, #0f0f0f, transparent);
}

.fade-right {
  pointer-events: none;
  position: absolute;
  top: 0;
  bottom: 0;
  right: 0;
  width: 33.333%;
  background: linear-gradient(to left, #0f0f0f, transparent);
}
</style>

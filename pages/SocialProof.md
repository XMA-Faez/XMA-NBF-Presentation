---
class: text-center
---

<h1 class="proof-heading !leading-[2]">Trusted By Leading Businesses</h1>

<div class="stats-container" v-motion :initial="{ opacity: 0, y: 100 }" :enter="{ opacity: 1, y: 0 }" :exit="{ opacity: 1, y: 0 }">
    <dl class="stats-grid">
        <div class="stat-card blue-stat" v-motion :initial="{ filter: 'blur(12px)', opacity: 0, scale: 0.8 }" :enter="{ filter: 'blur(0px)', opacity: 1, scale: 1, transition: { delay: 200 } }">
            <dd class="stat-number" style="color: #3B82F6;">
                <Ticker :value="50" :decimalPlaces="0" color="#3B82F6" />+
            </dd>
            <dt class="stat-label">Total Clients</dt>
        </div>
        <div class="stat-card purple-stat" v-motion :initial="{ filter: 'blur(12px)', opacity: 0, scale: 0.8 }" :enter="{ filter: 'blur(0px)', opacity: 1, scale: 1, transition: { delay: 400 } }">
            <dd class="stat-number" style="color: #A855F7;">
                <Ticker :value="30" :decimalPlaces="0" color="#A855F7" />K+
            </dd>
            <dt class="stat-label">Leads Generated</dt>
        </div>
        <div class="stat-card orange-stat" v-motion :initial="{ filter: 'blur(12px)', opacity: 0, scale: 0.8 }" :enter="{ filter: 'blur(0px)', opacity: 1, scale: 1, transition: { delay: 600 } }">
            <dd class="stat-number" style="color: #F97316;">
                AED <Ticker :value="3" :decimalPlaces="0" color="#F97316" />M+
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
  background: linear-gradient(to right, #00AFEF, #9333EA, #F97316);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  filter: drop-shadow(0 0 8px rgba(0, 175, 239, 0.2));
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
  border-radius: 0.75rem;
  transition: all 0.3s ease;
}

.blue-stat {
  background: linear-gradient(135deg, #0a1a2e, #0f172a);
  border: 1px solid rgba(59, 130, 246, 0.3);
}

.purple-stat {
  background: linear-gradient(135deg, #190a2a, #1e1b33);
  border: 1px solid rgba(168, 85, 247, 0.3);
}

.orange-stat {
  background: linear-gradient(135deg, #2a1408, #27201a);
  border: 1px solid rgba(249, 115, 22, 0.3);
}

.stat-card:hover {
  transform: translateY(-5px);
}

.blue-stat:hover {
  border-color: rgba(59, 130, 246, 0.5);
  box-shadow: 0 10px 20px -3px rgba(59, 130, 246, 0.2);
}

.purple-stat:hover {
  border-color: rgba(168, 85, 247, 0.5);
  box-shadow: 0 10px 20px -3px rgba(168, 85, 247, 0.2);
}

.orange-stat:hover {
  border-color: rgba(249, 115, 22, 0.5);
  box-shadow: 0 10px 20px -3px rgba(249, 115, 22, 0.2);
}

.stat-number {
  font-size: 2.25rem;
  font-weight: 800;
  margin-bottom: 1rem;
  text-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
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
  margin: 0 1rem;
  box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
}

.logo-image-padded {
  height: 3rem;
  background-color: white;
  border-radius: 0.75rem;
  padding: 0.5rem;
  transition: transform 0.3s ease;
  margin: 0 1rem;
  box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
}

.logo-image-transparent {
  height: 3rem;
  border-radius: 0.75rem;
  transition: transform 0.3s ease;
  margin: 0 1rem;
}

.logo-image:hover, .logo-image-padded:hover, .logo-image-transparent:hover {
  transform: scale(1.05);
}

.fade-left {
  pointer-events: none;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  width: 33.333%;
  @apply bg-gradient-r from-zinc-600 to-transparent;
}

.fade-right {
  pointer-events: none;
  position: absolute;
  top: 0;
  bottom: 0;
  right: 0;
  width: 33.333%;
  @apply bg-gradient-r from-zinc-600 to-transparent;
}
</style>

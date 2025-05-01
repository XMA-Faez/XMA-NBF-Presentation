---
layout: center
class: text-center
---
<h1 class="gradient-heading">
  Full-Scale Marketing Solutions
</h1>

<div class="services-grid">
  <div
    v-click="1"
    v-motion
    :initial="{ filter: 'blur(12px)', opacity: 0, y: 20 }"
    :enter="{ filter: 'blur(0px)', opacity: 1, y: 0 }"
    class="service-card"
  >
    <div class="service-content">
      <lucide-video class="service-icon"/>
      <h3 class="service-title">Content Creation</h3>
    </div>
  </div>
  
  <div
    v-click="2"
    v-motion
    :initial="{ filter: 'blur(12px)', opacity: 0, y: 20 }"
    :enter="{ filter: 'blur(0px)', opacity: 1, y: 0 }"
    class="service-card"
  >
    <div class="service-content">
      <lucide-megaphone class="service-icon"/>
      <h3 class="service-title">Advertising</h3>
    </div>
  </div>
  
  <div
    v-click="3"
    v-motion
    :initial="{ filter: 'blur(12px)', opacity: 0, y: 20 }"
    :enter="{ filter: 'blur(0px)', opacity: 1, y: 0 }"
    class="service-card"
  >
    <div class="service-content">
      <lucide-layout-dashboard class="service-icon"/>
      <h3 class="service-title">Management</h3>
    </div>
  </div>
  
  <div
    v-click="4"
    v-motion
    :initial="{ filter: 'blur(12px)', opacity: 0, y: 20 }"
    :enter="{ filter: 'blur(0px)', opacity: 1, y: 0 }"
    class="service-card"
  >
    <div class="service-content">
      <lucide-plus-circle class="service-icon"/>
      <h3 class="service-title">And More...</h3>
    </div>
  </div>
</div>

<style>
.gradient-heading {
  margin-bottom: 2.5rem;
  text-align: center;
  font-size: 2.5rem;
  font-weight: bold;
  background: linear-gradient(to right, #00AFEF, #87CEFA);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
}

.services-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 1.5rem;
  max-width: 800px;
  margin: 0 auto;
}

.service-card {
  padding: 1.25rem 1rem;
  background-color: rgba(24, 24, 27, 0.5);
  border-radius: 0.75rem;
  backdrop-filter: blur(8px);
  border: 1px solid rgb(39, 39, 42);
  box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease;
  height: 120px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.service-card:hover {
  transform: translateY(-5px);
  border-color: rgba(0, 175, 239, 0.5);
  box-shadow: 0 10px 15px -3px rgba(0, 175, 239, 0.1);
}

.service-content {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0.75rem;
}

.service-icon {
  width: 2.5rem;
  height: 2.5rem;
  color: #00AFEF;
}

.service-title {
  font-size: 1.125rem;
  font-weight: 600;
  text-align: center;
  margin: 0;
}
</style>

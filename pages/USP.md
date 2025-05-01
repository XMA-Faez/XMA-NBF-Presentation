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
    class="service-card blue-service"
  >
    <div class="service-content">
      <lucide-video class="service-icon blue-icon"/>
      <h3 class="service-title blue-title">Content Creation</h3>
    </div>
  </div>
  
  <div
    v-click="2"
    v-motion
    :initial="{ filter: 'blur(12px)', opacity: 0, y: 20 }"
    :enter="{ filter: 'blur(0px)', opacity: 1, y: 0 }"
    class="service-card orange-service"
  >
    <div class="service-content">
      <lucide-megaphone class="service-icon orange-icon"/>
      <h3 class="service-title orange-title">Advertising</h3>
    </div>
  </div>
  
  <div
    v-click="3"
    v-motion
    :initial="{ filter: 'blur(12px)', opacity: 0, y: 20 }"
    :enter="{ filter: 'blur(0px)', opacity: 1, y: 0 }"
    class="service-card purple-service"
  >
    <div class="service-content">
      <lucide-layout-dashboard class="service-icon purple-icon"/>
      <h3 class="service-title purple-title">Management</h3>
    </div>
  </div>
  
  <div
    v-click="4"
    v-motion
    :initial="{ filter: 'blur(12px)', opacity: 0, y: 20 }"
    :enter="{ filter: 'blur(0px)', opacity: 1, y: 0 }"
    class="service-card teal-service"
  >
    <div class="service-content">
      <lucide-plus-circle class="service-icon teal-icon"/>
      <h3 class="service-title teal-title">And More...</h3>
    </div>
  </div>
</div>

<style>
.gradient-heading {
  margin-bottom: 2.5rem;
  text-align: center;
  font-size: 2.5rem;
  font-weight: bold;
  filter: drop-shadow(0 0 8px rgba(0, 175, 239, 0.2));
}

.services-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 1.5rem;
  max-width: 800px;
  margin: 0 auto;
}

.service-card {
  padding: 1.5rem 1rem;
  border-radius: 0.75rem;
  backdrop-filter: blur(8px);
  box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease;
  height: 140px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.blue-service {
  background: linear-gradient(135deg, #0a1a2e, #0f172a);
  border: 1px solid rgba(59, 130, 246, 0.3);
}

.orange-service {
  background: linear-gradient(135deg, #2a1408, #27201a);
  border: 1px solid rgba(249, 115, 22, 0.3);
}

.purple-service {
  background: linear-gradient(135deg, #190a2a, #1e1b33);
  border: 1px solid rgba(168, 85, 247, 0.3);
}

.teal-service {
  background: linear-gradient(135deg, #042f2a, #0f2a29);
  border: 1px solid rgba(20, 184, 166, 0.3);
}

.service-card:hover {
  transform: translateY(-5px);
}

.blue-service:hover {
  border-color: rgba(59, 130, 246, 0.5);
  box-shadow: 0 10px 20px -3px rgba(59, 130, 246, 0.2);
}

.orange-service:hover {
  border-color: rgba(249, 115, 22, 0.5);
  box-shadow: 0 10px 20px -3px rgba(249, 115, 22, 0.2);
}

.purple-service:hover {
  border-color: rgba(168, 85, 247, 0.5);
  box-shadow: 0 10px 20px -3px rgba(168, 85, 247, 0.2);
}

.teal-service:hover {
  border-color: rgba(20, 184, 166, 0.5);
  box-shadow: 0 10px 20px -3px rgba(20, 184, 166, 0.2);
}

.service-content {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 1rem;
}

.service-icon {
  width: 2.5rem;
  height: 2.5rem;
}

.blue-icon {
  color: #3B82F6;
}

.orange-icon {
  color: #F97316;
}

.purple-icon {
  color: #A855F7;
}

.teal-icon {
  color: #14B8A6;
}

.service-title {
  font-size: 1.125rem;
  font-weight: 600;
  text-align: center;
  margin: 0;
}

.blue-title {
  color: #60A5FA;
}

.orange-title {
  color: #FB923C;
}

.purple-title {
  color: #C084FC;
}

.teal-title {
  color: #2DD4BF;
}
</style>

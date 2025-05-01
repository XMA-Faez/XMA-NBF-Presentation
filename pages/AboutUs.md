---
class: text-center
---

# Who We Are

<div class="relative h-full -mt-10">
  <!-- Section 1: Advertising Agency -->
  <div class="absolute top-1/2 -translate-y-1/2 left-1/2 transform -translate-x-1/2" v-click.hide="1">
    <div
      v-motion
      :initial="{ filter: 'blur(12px)', opacity: 0, scale: 0.8 }"
      :enter="{ filter: 'blur(0px)', opacity: 1, scale: 1 }"
      class="agency-title"
    >
      Advertising Agency
    </div>
  </div>

  <!-- Section 2: In-House Team (Two-Column Layout) -->
  <div class="absolute top-1/2 -translate-y-1/2 left-1/2 transform -translate-x-1/2 w-full max-w-4xl">
    <div class="flex flex-col md:flex-row gap-12 justify-center items-center">
      <!-- Left Column: Team Label -->
      <div class="flex-1">
        <div
          v-click="1"
          v-motion
          :initial="{ filter: 'blur(12px)', opacity: 0, scale: 0.8 }"
          :enter="{ filter: 'blur(0px)', opacity: 1, scale: 1 }"
          class="team-label"
        >
          <span class="highlight-text">20</span> In-House<br/>Professionals
        </div>
      </div>
      <!-- Right Column: Team Members -->
      <div class="flex-1 text-left grid grid-cols-2 gap-4">
        <div
          v-click="2"
          v-motion
          :initial="{ filter: 'blur(12px)', opacity: 0, x: 50 }"
          :enter="{ filter: 'blur(0px)', opacity: 1, x: 0 }"
          class="team-member blue-member"
        >
          <lucide-video class="member-icon blue-icon"/>
          <span class="text-sm">Videographers</span>
        </div>
        <div
          v-click="3"
          v-motion
          :initial="{ filter: 'blur(12px)', opacity: 0, x: 50 }"
          :enter="{ filter: 'blur(0px)', opacity: 1, x: 0 }"
          class="team-member purple-member"
        >
          <lucide-clapperboard class="member-icon purple-icon"/>
          <span class="text-sm">Video Editors</span>
        </div>
        <div
          v-click="4"
          v-motion
          :initial="{ filter: 'blur(12px)', opacity: 0, x: 50 }"
          :enter="{ filter: 'blur(0px)', opacity: 1, x: 0 }"
          class="team-member teal-member"
        >
          <lucide-code-2 class="member-icon teal-icon"/>
          <span class="text-sm">Developers</span>
        </div>
        <div
          v-click="5"
          v-motion
          :initial="{ filter: 'blur(12px)', opacity: 0, x: 50 }"
          :enter="{ filter: 'blur(0px)', opacity: 1, x: 0 }"
          class="team-member pink-member"
        >
          <lucide-palette class="member-icon pink-icon"/>
          <span class="text-sm">Graphic Designers</span>
        </div>
        <div
          v-click="6"
          v-motion
          :initial="{ filter: 'blur(12px)', opacity: 0, x: 50 }"
          :enter="{ filter: 'blur(0px)', opacity: 1, x: 0 }"
          class="team-member amber-member"
        >
          <lucide-presentation class="member-icon amber-icon"/>
          <span class="text-sm">Marketing Managers</span>
        </div>
        <div
          v-click="7"
          v-motion
          :initial="{ filter: 'blur(12px)', opacity: 0, x: 50 }"
          :enter="{ filter: 'blur(0px)', opacity: 1, x: 0 }"
          class="team-member orange-member"
        >
          <lucide-megaphone class="member-icon orange-icon"/>
          <span class="text-sm">Advertising Experts</span>
        </div>
      </div>
    </div>
  </div>
</div>

<style>
.agency-title {
  text-align: center;
  font-size: 2.25rem;
  font-weight: bold;
  background: linear-gradient(to right, #00AFEF, #9333EA, #F97316);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  line-height: 50px;
  filter: drop-shadow(0 0 8px rgba(0, 175, 239, 0.2));
}

.team-label {
  font-size: 1.875rem;
  font-weight: bold;
  text-align: center;
  background: linear-gradient(to right, #3B82F6, #A855F7);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  filter: drop-shadow(0 0 5px rgba(59, 130, 246, 0.2));
}

.highlight-text {
  color: #F97316;
  text-shadow: 0 0 10px rgba(249, 115, 22, 0.2);
}

.team-member {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  padding: 0.75rem;
  border-radius: 0.5rem;
  backdrop-filter: blur(4px);
  transform: none;
  transition: all 0.3s ease;
}

.blue-member {
  background: linear-gradient(to bottom, #0a1a2e, #0f172a);
  border: 1px solid rgba(59, 130, 246, 0.3);
}

.purple-member {
  background: linear-gradient(to bottom, #190a2a, #1e1b33);
  border: 1px solid rgba(168, 85, 247, 0.3);
}

.teal-member {
  background: linear-gradient(to bottom, #042f2a, #0f2a29);
  border: 1px solid rgba(20, 184, 166, 0.3);
}

.pink-member {
  background: linear-gradient(to bottom, #2d0a20, #271625);
  border: 1px solid rgba(236, 72, 153, 0.3);
}

.amber-member {
  background: linear-gradient(to bottom, #2e1c08, #271f15);
  border: 1px solid rgba(245, 158, 11, 0.3);
}

.orange-member {
  background: linear-gradient(to bottom, #2a1408, #27201a);
  border: 1px solid rgba(249, 115, 22, 0.3);
}

.team-member:hover {
  transform: scale(1.05);
  box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
}

.blue-member:hover {
  border-color: rgba(59, 130, 246, 0.5);
  box-shadow: 0 5px 15px rgba(59, 130, 246, 0.1);
}

.purple-member:hover {
  border-color: rgba(168, 85, 247, 0.5);
  box-shadow: 0 5px 15px rgba(168, 85, 247, 0.1);
}

.teal-member:hover {
  border-color: rgba(20, 184, 166, 0.5);
  box-shadow: 0 5px 15px rgba(20, 184, 166, 0.1);
}

.pink-member:hover {
  border-color: rgba(236, 72, 153, 0.5);
  box-shadow: 0 5px 15px rgba(236, 72, 153, 0.1);
}

.amber-member:hover {
  border-color: rgba(245, 158, 11, 0.5);
  box-shadow: 0 5px 15px rgba(245, 158, 11, 0.1);
}

.orange-member:hover {
  border-color: rgba(249, 115, 22, 0.5);
  box-shadow: 0 5px 15px rgba(249, 115, 22, 0.1);
}

.blue-icon {
  color: #3B82F6;
}

.purple-icon {
  color: #A855F7;
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

.orange-icon {
  color: #F97316;
}

.member-icon {
  width: 1.5rem;
  height: 1.5rem;
}
</style>

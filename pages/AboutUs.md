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
          class="team-member"
        >
          <lucide-video class="member-icon"/>
          <span class="text-sm">Videographers</span>
        </div>
        <div
          v-click="3"
          v-motion
          :initial="{ filter: 'blur(12px)', opacity: 0, x: 50 }"
          :enter="{ filter: 'blur(0px)', opacity: 1, x: 0 }"
          class="team-member"
        >
          <lucide-clapperboard class="member-icon"/>
          <span class="text-sm">Video Editors</span>
        </div>
        <div
          v-click="4"
          v-motion
          :initial="{ filter: 'blur(12px)', opacity: 0, x: 50 }"
          :enter="{ filter: 'blur(0px)', opacity: 1, x: 0 }"
          class="team-member"
        >
          <lucide-code-2 class="member-icon"/>
          <span class="text-sm">Developers</span>
        </div>
        <div
          v-click="5"
          v-motion
          :initial="{ filter: 'blur(12px)', opacity: 0, x: 50 }"
          :enter="{ filter: 'blur(0px)', opacity: 1, x: 0 }"
          class="team-member"
        >
          <lucide-palette class="member-icon"/>
          <span class="text-sm">Graphic Designers</span>
        </div>
        <div
          v-click="6"
          v-motion
          :initial="{ filter: 'blur(12px)', opacity: 0, x: 50 }"
          :enter="{ filter: 'blur(0px)', opacity: 1, x: 0 }"
          class="team-member"
        >
          <lucide-presentation class="member-icon"/>
          <span class="text-sm">Marketing Managers</span>
        </div>
        <div
          v-click="7"
          v-motion
          :initial="{ filter: 'blur(12px)', opacity: 0, x: 50 }"
          :enter="{ filter: 'blur(0px)', opacity: 1, x: 0 }"
          class="team-member"
        >
          <lucide-megaphone class="member-icon"/>
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
  background: linear-gradient(to right, #00AFEF, #87CEFA);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  line-height: 50px;
}

.team-label {
  font-size: 1.875rem;
  font-weight: bold;
  text-align: center;
}

.highlight-text {
  color: #00AFEF;
}

.team-member {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  padding: 0.75rem;
  border-radius: 0.5rem;
  backdrop-filter: blur(4px);
  transform: none;
  border: 1px solid #27272A;
  transition: all 0.3s ease;
  @apply bg-slate-900 border border-blue-950;
}

.team-member:hover {
  transform: scale(1.05);
  border-color: rgba(0, 175, 239, 0.5);
}

.member-icon {
  width: 1.5rem;
  height: 1.5rem;
  color: #00AFEF;
}
</style>

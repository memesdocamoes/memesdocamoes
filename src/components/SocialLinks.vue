<template>
  <div class="social-wrapper">
    <a
      href="https://instagram.com/memesdocamoes"
      target="_blank"
      class="social-card instagram"
    >
      <i class="bi bi-instagram"></i>
      <span>Instagram</span>
    </a>

    <a
      href="https://www.tiktok.com/@memes_docamoes"
      target="_blank"
      class="social-card tiktok"
    >
      <i class="bi bi-tiktok"></i>
      <span>TikTok</span>
    </a>
  </div>
</template>

<style scoped>
.social-wrapper {
  display: flex;
  justify-content: center;
  gap: 16px;
  align-items: center;
  margin-top: 24px;
}

/* CARD BASE */
.social-card {
  width: 220px;
  padding: 14px 18px;
  display: flex;
  align-items: center;
  gap: 12px;
  border-radius: 12px;
  font-size: 18px;
  font-weight: 600;
  text-decoration: none;
  color: white;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

/* HOVER */
.social-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 30px rgba(0,0,0,0.35);
}

/* ICON */
.social-card i {
  font-size: 24px;
}

/* BRAND COLORS */
.instagram {
  background: linear-gradient(135deg, #833ab4, #fd1d1d, #fcb045);
}

.tiktok {
  background: linear-gradient(135deg, #000000, #1f1f1f);
}
</style>

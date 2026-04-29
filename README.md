
<html lang="fr" style="color-scheme: dark;">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#2E1F47">
<title>Inès Kouki — Appel de clarté gratuit · Rôle · Posture · Trajectoire</title>
<meta name="description" content="Consultante senior en transformation. 17 ans chez BNP Paribas, Société Générale, IDEMIA, Philip Morris. Réservez un appel de clarté de 30 minutes gratuit pour clarifier votre rôle, votre posture et votre trajectoire.">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;1,400;1,500&family=DM+Sans:opsz,wght@9..40,300;9..40,400;9..40,500;9..40,600&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">

<style>
:root {
  /* Palette V2 — Violet Nuit / Rose Poudré / Blanc Nacré */
  --midnight: #2E1F47;          /* Violet Nuit — fond principal, autorité */
  --deep-navy: #3A2856;         /* variation un cran plus claire */
  --slate: #5A4878;             /* texte mid-tone */
  --cream: #FAF7F2;             /* Blanc Nacré — texte/respiration */
  --ivory: #F5F0E8;             /* fond cartes clairs */
  --pearl: #E8DFD2;             /* séparateurs */
  --warm-gray: #A99CB8;         /* texte secondaire (warm violet-gray) */
  --terracotta: #C4789A;        /* Rose Poudré — accent principal, CTA */
  --terracotta-deep: #A55F7E;   /* hover du CTA */
  --teal: #4B7F8C;              /* Pilier P — Posture */
  --sage: #6B8068;              /* Pilier T — Trajectoire */

  --display: "Cormorant Garamond", Georgia, serif;
  --body: "DM Sans", -apple-system, BlinkMacSystemFont, "Helvetica Neue", sans-serif;
  --mono: "JetBrains Mono", "Courier New", monospace;
}

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

html { scroll-behavior: smooth; }

body {
  background: var(--midnight);
  color: var(--cream);
  font-family: var(--body);
  font-size: 16px;
  line-height: 1.6;
  font-weight: 400;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  overflow-x: hidden;
}

/* Skip link for keyboard users */
.skip-link {
  position: absolute;
  left: -9999px;
  top: 8px;
  background: var(--terracotta);
  color: var(--cream);
  padding: 12px 20px;
  font-family: var(--mono);
  font-size: 12px;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  z-index: 100;
}
.skip-link:focus-visible {
  left: 8px;
}

/* Focus styles — visible rings for all interactive elements */
a:focus-visible,
button:focus-visible,
input:focus-visible {
  outline: 2px solid var(--terracotta);
  outline-offset: 3px;
}

/* Touch targets */
button, a, input, label {
  touch-action: manipulation;
  -webkit-tap-highlight-color: transparent;
}

/* Grain overlay — adds editorial texture */
body::before {
  content: "";
  position: fixed; inset: 0;
  pointer-events: none;
  z-index: 1;
  opacity: 0.035;
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='200' height='200'><filter id='n'><feTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='2'/></filter><rect width='200' height='200' filter='url(%23n)'/></svg>");
}

.container { width: 100%; max-width: 1280px; margin: 0 auto; padding: 0 40px; }

a { color: inherit; text-decoration: none; }

/* ——— NAV ——— */
.nav {
  position: relative;
  z-index: 10;
  padding: 28px 0;
  border-bottom: 1px solid rgba(250, 247, 242, 0.08);
}
.nav-inner {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 24px;
}
.nav-brand {
  font-family: var(--display);
  font-size: 22px;
  font-weight: 500;
  letter-spacing: 0.01em;
  color: var(--cream);
}
.nav-brand-sub {
  display: block;
  font-family: var(--mono);
  font-size: 10px;
  font-weight: 400;
  letter-spacing: 0.18em;
  color: var(--warm-gray);
  text-transform: uppercase;
  margin-top: 2px;
}
.nav-cta {
  font-family: var(--mono);
  font-size: 11px;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  color: var(--cream);
  padding: 12px 20px;
  border: 1px solid rgba(250, 247, 242, 0.2);
  transition: background-color 0.3s ease, border-color 0.3s ease, color 0.3s ease;
}
.nav-cta:hover {
  background: var(--terracotta);
  border-color: var(--terracotta);
}

/* ——— HERO ——— */
.hero {
  position: relative;
  padding: 100px 0 120px;
  overflow: hidden;
}
.hero::before {
  content: "";
  position: absolute;
  top: 10%; right: -10%;
  width: 500px; height: 500px;
  background: radial-gradient(circle, rgba(196, 120, 154, 0.12) 0%, transparent 70%);
  pointer-events: none;
}
.hero-grid {
  display: grid;
  grid-template-columns: 1.4fr 1fr;
  gap: 80px;
  align-items: center;
  position: relative;
  z-index: 2;
}
.hero-single {
  position: relative;
  z-index: 2;
  max-width: 820px;
}
.kicker {
  display: inline-block;
  font-family: var(--mono);
  font-size: 11px;
  font-weight: 500;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--terracotta);
  margin-bottom: 40px;
  padding-left: 48px;
  position: relative;
}
.kicker::before {
  content: "";
  position: absolute;
  left: 0; top: 50%;
  width: 36px; height: 1px;
  background: var(--terracotta);
}
.hero h1 {
  font-family: var(--display);
  font-weight: 400;
  font-size: clamp(46px, 6.2vw, 84px);
  line-height: 1.04;
  letter-spacing: -0.015em;
  color: var(--cream);
  margin-bottom: 36px;
  text-wrap: balance;
}
.hero h1 .underline-accent {
  position: relative;
  white-space: nowrap;
}
.hero h1 .underline-accent::after {
  content: "";
  position: absolute;
  left: 0; right: 0;
  bottom: -0.04em;
  height: 0.11em;
  background: var(--terracotta);
  transform: skew(-6deg);
}
.hero h1 em {
  font-style: italic;
  color: var(--cream);
}
.hero-lede {
  font-size: 19px;
  line-height: 1.55;
  color: var(--pearl);
  max-width: 540px;
  margin-bottom: 44px;
  font-weight: 300;
}
.hero-meta {
  display: flex;
  gap: 40px;
  padding-top: 28px;
  border-top: 1px solid rgba(250, 247, 242, 0.1);
  max-width: 540px;
}
.hero-meta-item {
  flex: 1;
}
.hero-meta-label {
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--warm-gray);
  margin-bottom: 6px;
}
.hero-meta-value {
  font-family: var(--display);
  font-size: 22px;
  color: var(--cream);
  font-weight: 500;
}

/* Hero secondary CTA — discreet direct-booking link */
.hero-secondary-cta {
  display: inline-flex;
  align-items: center;
  gap: 12px;
  margin-top: 28px;
  font-family: var(--mono);
  font-size: 11px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--warm-gray);
  padding-bottom: 4px;
  border-bottom: 1px solid rgba(169, 156, 184, 0.3);
  transition: color 0.3s ease, border-color 0.3s ease, gap 0.3s ease;
}
.hero-secondary-cta:hover,
.hero-secondary-cta:focus-visible {
  color: var(--terracotta);
  border-bottom-color: var(--terracotta);
  gap: 18px;
}
.hero-secondary-cta .dot {
  width: 5px; height: 5px;
  border-radius: 50%;
  background: var(--terracotta);
  flex-shrink: 0;
}

/* ——— INTERSTITIAL CTA ——— */
.interstitial {
  background: var(--midnight);
  padding: 100px 0;
  border-top: 1px solid rgba(250, 247, 242, 0.06);
  border-bottom: 1px solid rgba(250, 247, 242, 0.06);
  position: relative;
  overflow: hidden;
}
.interstitial::before {
  content: "";
  position: absolute;
  top: -20%; left: -10%;
  width: 60%; height: 140%;
  background: radial-gradient(ellipse at left, rgba(196, 120, 154, 0.12) 0%, transparent 55%);
  pointer-events: none;
}
.interstitial-inner {
  position: relative;
  z-index: 2;
  display: grid;
  grid-template-columns: 1.3fr 1fr;
  gap: 80px;
  align-items: center;
}
.interstitial-label {
  font-family: var(--mono);
  font-size: 11px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--terracotta);
  margin-bottom: 20px;
  display: flex;
  align-items: center;
  gap: 14px;
}
.interstitial-label::before {
  content: "";
  width: 24px; height: 1px;
  background: var(--terracotta);
}
.interstitial-title {
  font-family: var(--display);
  font-size: clamp(34px, 3.8vw, 52px);
  font-weight: 400;
  line-height: 1.12;
  letter-spacing: -0.01em;
  color: var(--cream);
  margin-bottom: 18px;
  text-wrap: balance;
}
.interstitial-title em {
  font-style: italic;
  color: var(--terracotta);
}
.interstitial-sub {
  font-family: var(--display);
  font-style: italic;
  font-size: 19px;
  line-height: 1.5;
  color: var(--pearl);
  font-weight: 400;
  max-width: 520px;
}
.interstitial-action {
  display: flex;
  justify-content: flex-end;
}
.interstitial-cta {
  display: inline-flex;
  align-items: center;
  gap: 16px;
  background: var(--terracotta);
  color: var(--cream);
  padding: 24px 38px;
  font-family: var(--mono);
  font-size: 12px;
  font-weight: 500;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  transition: background-color 0.3s ease, gap 0.3s ease;
  position: relative;
  border: 1px solid var(--terracotta);
}
.interstitial-cta::before {
  content: "";
  position: absolute;
  inset: 4px;
  border: 1px solid rgba(250, 247, 242, 0.15);
  pointer-events: none;
}
.interstitial-cta:hover,
.interstitial-cta:focus-visible {
  background: var(--terracotta-deep);
  gap: 22px;
}
.interstitial-cta .arrow {
  font-size: 14px;
  position: relative;
}
.interstitial-micro {
  margin-top: 16px;
  text-align: right;
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: var(--warm-gray);
}

/* ——— INÈS PHOTO (cutout, floats on dark) ——— */
.ines-photo {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: flex-end;
  min-height: 500px;
}
.ines-photo::before {
  /* Soft terracotta glow behind the subject */
  content: "";
  position: absolute;
  inset: 8% 8% 0 8%;
  background: radial-gradient(ellipse at 50% 60%, rgba(196, 120, 154, 0.22) 0%, transparent 65%);
  z-index: 0;
  pointer-events: none;
}
.ines-photo::after {
  /* A thin terracotta rule on the left as editorial accent */
  content: "";
  position: absolute;
  left: 0;
  top: 15%;
  bottom: 15%;
  width: 1px;
  background: linear-gradient(to bottom, transparent, var(--terracotta), transparent);
  opacity: 0.5;
  z-index: 1;
}
.ines-photo img {
  position: relative;
  z-index: 2;
  max-width: 100%;
  max-height: 640px;
  width: auto;
  height: auto;
  filter: drop-shadow(-18px 24px 32px rgba(0, 0, 0, 0.45));
}
.ines-photo-sigil {
  position: absolute;
  left: 16px;
  bottom: 24px;
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.32em;
  text-transform: uppercase;
  color: var(--terracotta);
  z-index: 3;
  writing-mode: vertical-rl;
  transform: rotate(180deg);
  white-space: nowrap;
}

/* Hero primary CTA — the main button in the hero */
.hero-primary-cta {
  display: inline-flex;
  align-items: center;
  gap: 14px;
  background: var(--terracotta);
  color: var(--cream);
  padding: 20px 34px;
  margin-top: 36px;
  font-family: var(--mono);
  font-size: 12px;
  font-weight: 500;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  transition: background-color 0.3s ease, gap 0.3s ease;
  position: relative;
  border: 1px solid var(--terracotta);
}
.hero-primary-cta::before {
  content: "";
  position: absolute;
  inset: 4px;
  border: 1px solid rgba(250, 247, 242, 0.15);
  pointer-events: none;
}
.hero-primary-cta:hover,
.hero-primary-cta:focus-visible {
  background: var(--terracotta-deep);
  gap: 20px;
}

/* ——— SECTION SHARED ——— */
section { position: relative; z-index: 2; }
.section-label {
  font-family: var(--mono);
  font-size: 11px;
  font-weight: 500;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--terracotta);
  margin-bottom: 32px;
  display: flex;
  align-items: center;
  gap: 14px;
}
.section-label::before {
  content: "";
  width: 24px; height: 1px;
  background: var(--terracotta);
}

/* ——— MANIFESTO ——— */
.manifesto {
  background: var(--cream);
  color: var(--midnight);
  padding: 120px 0;
  position: relative;
}
.manifesto::before,
.manifesto::after {
  content: "";
  position: absolute;
  left: 0; right: 0;
  height: 80px;
  pointer-events: none;
}
.manifesto-inner {
  max-width: 860px;
  margin: 0 auto;
  text-align: left;
}
.manifesto-quote {
  font-family: var(--display);
  font-size: clamp(32px, 4vw, 52px);
  line-height: 1.22;
  font-weight: 400;
  color: var(--midnight);
  letter-spacing: -0.01em;
  margin-bottom: 40px;
  text-wrap: balance;
}
.manifesto-quote em {
  font-style: italic;
  color: var(--terracotta);
}
.manifesto-sig {
  display: flex;
  align-items: center;
  gap: 20px;
  padding-top: 24px;
  border-top: 1px solid var(--pearl);
  max-width: 380px;
}
.manifesto-sig-name {
  font-family: var(--display);
  font-size: 20px;
  font-weight: 500;
  color: var(--midnight);
}
.manifesto-sig-role {
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--slate);
  margin-top: 4px;
}

/* ——— R.P.T. SECTION ——— */
.rpt {
  padding: 140px 0;
  background: var(--midnight);
}
.rpt-intro {
  max-width: 720px;
  margin-bottom: 80px;
}
.rpt-title {
  font-family: var(--display);
  font-size: clamp(38px, 4.5vw, 60px);
  font-weight: 400;
  line-height: 1.1;
  letter-spacing: -0.01em;
  margin-bottom: 24px;
  color: var(--cream);
}
.rpt-lede {
  font-size: 17px;
  line-height: 1.65;
  color: var(--pearl);
  font-weight: 300;
  max-width: 620px;
}
.rpt-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 2px;
  background: rgba(250, 247, 242, 0.08);
  border: 1px solid rgba(250, 247, 242, 0.08);
}
.pillar {
  background: var(--deep-navy);
  padding: 56px 44px 52px;
  position: relative;
  transition: background 0.4s ease;
  cursor: default;
  min-height: 380px;
  display: flex;
  flex-direction: column;
}
.pillar:hover { background: #4A3568; }
.pillar-letter {
  font-family: var(--display);
  font-size: 120px;
  line-height: 1;
  font-weight: 300;
  letter-spacing: -0.02em;
  margin-bottom: 8px;
  transition: color 0.4s ease;
}
.pillar--r .pillar-letter { color: var(--terracotta); }
.pillar--p .pillar-letter { color: var(--teal); }
.pillar--t .pillar-letter { color: var(--sage); }
.pillar-tag {
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--warm-gray);
  margin-bottom: 20px;
}
.pillar-name {
  font-family: var(--display);
  font-size: 30px;
  font-weight: 500;
  color: var(--cream);
  margin-bottom: 18px;
  letter-spacing: -0.005em;
}
.pillar-desc {
  font-size: 15px;
  line-height: 1.6;
  color: var(--pearl);
  font-weight: 300;
  flex: 1;
}
.pillar-result {
  margin-top: 28px;
  padding-top: 20px;
  border-top: 1px solid rgba(250, 247, 242, 0.1);
  font-family: var(--display);
  font-style: italic;
  font-size: 17px;
  line-height: 1.4;
}
.pillar--r .pillar-result { color: var(--terracotta); }
.pillar--p .pillar-result { color: var(--teal); }
.pillar--t .pillar-result { color: var(--sage); }

/* ——— POUR QUI ——— */
.pour-qui {
  background: var(--ivory);
  color: var(--midnight);
  padding: 140px 0;
}
.pour-qui-grid {
  display: grid;
  grid-template-columns: 0.9fr 1.1fr;
  gap: 100px;
  align-items: start;
}
.pour-qui-title {
  font-family: var(--display);
  font-size: clamp(38px, 4.5vw, 56px);
  font-weight: 400;
  line-height: 1.1;
  letter-spacing: -0.01em;
  color: var(--midnight);
}
.pour-qui-title em {
  font-style: italic;
  color: var(--terracotta);
}
.pour-qui-list {
  list-style: none;
}
.pour-qui-item {
  display: flex;
  gap: 24px;
  padding: 26px 0;
  border-bottom: 1px solid var(--pearl);
}
.pour-qui-item:last-child { border-bottom: none; }
.pour-qui-num {
  font-family: var(--mono);
  font-size: 11px;
  font-weight: 500;
  letter-spacing: 0.15em;
  color: var(--terracotta);
  flex-shrink: 0;
  padding-top: 4px;
}
.pour-qui-text {
  font-family: var(--display);
  font-size: 20px;
  line-height: 1.4;
  color: var(--slate);
  font-weight: 400;
}
.pour-qui-text strong {
  color: var(--midnight);
  font-weight: 500;
}

/* ——— INÈS ——— */
.ines {
  padding: 140px 0;
  background: var(--midnight);
  border-top: 1px solid rgba(250, 247, 242, 0.06);
}
.ines-grid {
  display: grid;
  grid-template-columns: 1.2fr 1fr;
  gap: 80px;
  align-items: center;
}
.ines-name {
  font-family: var(--display);
  font-size: clamp(40px, 4.5vw, 56px);
  font-weight: 400;
  line-height: 1.05;
  letter-spacing: -0.01em;
  margin-bottom: 14px;
  color: var(--cream);
}
.ines-role {
  font-family: var(--mono);
  font-size: 11px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--terracotta);
  margin-bottom: 36px;
}
.ines-bio {
  font-size: 17px;
  line-height: 1.7;
  color: var(--pearl);
  font-weight: 300;
  margin-bottom: 24px;
}
.ines-bio em {
  font-family: var(--display);
  font-style: italic;
  color: var(--cream);
  font-size: 19px;
}
.ines-stats {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 32px;
  margin-top: 40px;
  padding-top: 40px;
  border-top: 1px solid rgba(250, 247, 242, 0.1);
}
.stat-num {
  font-family: var(--display);
  font-size: 42px;
  font-weight: 400;
  line-height: 1;
  color: var(--terracotta);
  margin-bottom: 8px;
}
.stat-label {
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--warm-gray);
}

/* ——— CAPTURE ——— */
.capture {
  position: relative;
  padding: 140px 0;
  background: var(--midnight);
  overflow: hidden;
}
.capture::before {
  content: "";
  position: absolute;
  inset: 0;
  background: radial-gradient(circle at 75% 40%, rgba(196, 120, 154, 0.14) 0%, transparent 55%);
  pointer-events: none;
}
.capture-inner {
  position: relative;
  max-width: 980px;
  margin: 0 auto;
  background: var(--deep-navy);
  border: 1px solid rgba(196, 120, 154, 0.25);
  padding: 80px;
  z-index: 2;
}
.capture-inner::before {
  content: "";
  position: absolute;
  top: 18px; left: 18px; right: 18px; bottom: 18px;
  border: 1px solid rgba(250, 247, 242, 0.05);
  pointer-events: none;
}
.capture-title {
  font-family: var(--display);
  font-size: clamp(34px, 4vw, 52px);
  font-weight: 400;
  line-height: 1.1;
  letter-spacing: -0.01em;
  color: var(--cream);
  margin-bottom: 20px;
  max-width: 720px;
}
.capture-title em {
  font-style: italic;
  color: var(--terracotta);
}
.capture-sub {
  font-size: 17px;
  line-height: 1.55;
  color: var(--pearl);
  margin-bottom: 44px;
  max-width: 640px;
  font-weight: 300;
}
.form {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 18px;
  max-width: 700px;
}
.form-row {
  grid-column: span 2;
}
.field {
  display: flex;
  flex-direction: column;
  gap: 8px;
}
.field label {
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--warm-gray);
}
.field input {
  background: transparent;
  border: none;
  border-bottom: 1px solid rgba(250, 247, 242, 0.2);
  padding: 12px 2px;
  color: var(--cream);
  font-family: var(--body);
  font-size: 16px;
  outline: none;
  transition: border-color 0.3s ease;
}
.field input:focus {
  border-bottom-color: var(--terracotta);
}
.field input::placeholder {
  color: rgba(250, 247, 242, 0.3);
}
.submit {
  margin-top: 18px;
  grid-column: span 2;
  display: flex;
  align-items: center;
  gap: 20px;
  flex-wrap: wrap;
}
.btn-primary {
  display: inline-flex;
  align-items: center;
  gap: 14px;
  background: var(--terracotta);
  color: var(--cream);
  border: none;
  padding: 20px 36px;
  font-family: var(--mono);
  font-size: 12px;
  font-weight: 500;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  cursor: pointer;
  transition: background-color 0.3s ease, transform 0.3s ease;
  position: relative;
  overflow: hidden;
}
.btn-primary::before {
  content: "";
  position: absolute;
  inset: 0;
  background: var(--terracotta-deep);
  transform: translateX(-100%);
  transition: transform 0.4s ease;
}
.btn-primary span { position: relative; }
.btn-primary:hover::before { transform: translateX(0); }
.btn-primary .arrow {
  transition: transform 0.3s ease;
  position: relative;
}
.btn-primary:hover .arrow { transform: translateX(6px); }
.submit-note {
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: var(--warm-gray);
  line-height: 1.6;
  flex: 1;
  min-width: 200px;
}
.submit-note strong { color: var(--terracotta); font-weight: 500; }

.form-status {
  margin-top: 24px;
  font-family: var(--mono);
  font-size: 11px;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: var(--sage);
  min-height: 1.4em;
}
.form-status.is-error { color: var(--terracotta); }

/* ——— DIRECT CALENDLY CTA (no form) ——— */
.capture-cta {
  display: inline-flex;
  align-items: center;
  gap: 16px;
  background: var(--terracotta);
  color: var(--cream);
  padding: 24px 40px;
  margin: 8px 0 20px;
  font-family: var(--mono);
  font-size: 12px;
  font-weight: 500;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  transition: background-color 0.3s ease, gap 0.3s ease;
  position: relative;
  border: 1px solid var(--terracotta);
}
.capture-cta::before {
  content: "";
  position: absolute;
  inset: 4px;
  border: 1px solid rgba(250, 247, 242, 0.15);
  pointer-events: none;
}
.capture-cta:hover,
.capture-cta:focus-visible {
  background: var(--terracotta-deep);
  gap: 22px;
}
.capture-note {
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: var(--warm-gray);
  line-height: 1.8;
  max-width: 520px;
}
.capture-note strong { color: var(--terracotta); font-weight: 500; }

/* ——— WHAT YOU GET ——— */
.perks {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 0;
  margin-top: 56px;
  padding-top: 40px;
  border-top: 1px solid rgba(250, 247, 242, 0.08);
}
.perk {
  display: flex;
  gap: 18px;
  padding: 20px 0;
}
.perk-num {
  font-family: var(--display);
  font-style: italic;
  font-size: 28px;
  color: var(--terracotta);
  font-weight: 400;
  line-height: 1;
  flex-shrink: 0;
}
.perk-text {
  font-size: 14px;
  line-height: 1.55;
  color: var(--pearl);
}
.perk-text strong {
  color: var(--cream);
  font-weight: 500;
  display: block;
  margin-bottom: 4px;
  font-size: 15px;
}

/* ——— FOOTER ——— */
.footer {
  background: var(--midnight);
  padding: 80px 0 40px;
  border-top: 1px solid rgba(250, 247, 242, 0.08);
  position: relative;
}
.footer::before {
  /* subtle decorative glow */
  content: "";
  position: absolute;
  top: 0; left: 50%;
  width: 60%; height: 200px;
  transform: translateX(-50%);
  background: radial-gradient(ellipse at center, rgba(196, 120, 154, 0.08) 0%, transparent 70%);
  pointer-events: none;
}
.footer-grid {
  position: relative;
  display: grid;
  grid-template-columns: 1.2fr 1.4fr 1fr;
  gap: 60px;
  align-items: start;
  padding-bottom: 56px;
  border-bottom: 1px solid rgba(250, 247, 242, 0.08);
}
.footer-col-label {
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--terracotta);
  margin-bottom: 18px;
  display: flex;
  align-items: center;
  gap: 12px;
}
.footer-col-label::before {
  content: "";
  width: 18px; height: 1px;
  background: var(--terracotta);
}
.footer-brand-block .footer-name {
  font-family: var(--display);
  font-size: 30px;
  font-weight: 500;
  color: var(--cream);
  line-height: 1.1;
  margin-bottom: 8px;
  letter-spacing: -0.005em;
}
.footer-tagline {
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--warm-gray);
  margin-bottom: 20px;
}
.footer-tagline span { color: var(--terracotta); }
.footer-pitch {
  font-family: var(--display);
  font-style: italic;
  font-size: 16px;
  line-height: 1.5;
  color: var(--pearl);
  max-width: 280px;
}

/* Contacts */
.footer-contacts {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: column;
  gap: 16px;
}
.footer-contact-item {
  display: flex;
  align-items: center;
  gap: 14px;
  color: var(--cream);
  font-family: var(--body);
  font-size: 15px;
  transition: color 0.3s ease, gap 0.3s ease;
  line-height: 1.4;
}
.footer-contact-item:hover,
.footer-contact-item:focus-visible {
  color: var(--terracotta);
  gap: 18px;
}
.contact-icon {
  flex-shrink: 0;
  width: 36px; height: 36px;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  border: 1px solid rgba(196, 120, 154, 0.3);
  color: var(--terracotta);
  transition: background-color 0.3s ease, border-color 0.3s ease;
}
.footer-contact-item:hover .contact-icon,
.footer-contact-item:focus-visible .contact-icon {
  background: var(--terracotta);
  border-color: var(--terracotta);
  color: var(--cream);
}
.contact-icon svg {
  width: 16px; height: 16px;
  display: block;
}
.contact-label {
  font-family: var(--mono);
  font-size: 9px;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  color: var(--warm-gray);
  display: block;
  margin-bottom: 2px;
}
.contact-value {
  font-size: 15px;
  color: inherit;
}

/* Footer CTA mini */
.footer-cta-block {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.footer-cta {
  display: inline-flex;
  align-items: center;
  gap: 12px;
  background: transparent;
  color: var(--cream);
  padding: 14px 22px;
  font-family: var(--mono);
  font-size: 11px;
  font-weight: 500;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  border: 1px solid var(--terracotta);
  transition: background-color 0.3s ease, gap 0.3s ease;
}
.footer-cta:hover,
.footer-cta:focus-visible {
  background: var(--terracotta);
  gap: 16px;
}

/* Footer bottom bar */
.footer-bottom {
  position: relative;
  margin-top: 32px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: 16px;
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--warm-gray);
}
.footer-credit { color: var(--warm-gray); }
.footer-credit em {
  font-family: var(--display);
  font-style: italic;
  font-size: 13px;
  letter-spacing: 0.02em;
  text-transform: none;
  color: var(--pearl);
}

/* ——— WHATSAPP FLOATING BUTTON ——— */
.whatsapp-fab {
  position: fixed;
  bottom: 24px;
  right: 24px;
  z-index: 50;
  display: inline-flex;
  align-items: center;
  gap: 10px;
  background: #25D366; /* WhatsApp brand green */
  color: #fff;
  padding: 14px 18px 14px 14px;
  font-family: var(--body);
  font-size: 14px;
  font-weight: 500;
  letter-spacing: 0.01em;
  border-radius: 999px;
  box-shadow:
    0 12px 28px rgba(37, 211, 102, 0.35),
    0 4px 8px rgba(0, 0, 0, 0.2);
  transition: transform 0.3s ease, box-shadow 0.3s ease, background-color 0.3s ease;
  text-decoration: none;
}
.whatsapp-fab:hover,
.whatsapp-fab:focus-visible {
  background: #20BA5A;
  transform: translateY(-2px);
  box-shadow:
    0 16px 32px rgba(37, 211, 102, 0.45),
    0 6px 12px rgba(0, 0, 0, 0.25);
}
.whatsapp-fab svg {
  width: 24px; height: 24px;
  display: block;
}
.whatsapp-fab .wa-label {
  display: inline-block;
}

@media (max-width: 520px) {
  .whatsapp-fab {
    padding: 14px;
    bottom: 18px;
    right: auto;
    left: 50%;
    transform: translateX(-50%);
  }
  .whatsapp-fab:hover,
  .whatsapp-fab:focus-visible {
    transform: translateX(-50%) translateY(-2px);
  }
  .whatsapp-fab .wa-label {
    display: none;
  }
}

/* ——— REVEAL ——— */
.reveal {
  opacity: 0;
  transform: translateY(24px);
  transition: opacity 0.8s ease, transform 0.8s ease;
}
.reveal.is-visible {
  opacity: 1;
  transform: translateY(0);
}

/* ——— PREFERS REDUCED MOTION ——— */
@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after {
    animation-duration: 0.01ms !important;
    animation-iteration-count: 1 !important;
    transition-duration: 0.01ms !important;
    scroll-behavior: auto !important;
  }
  .reveal { opacity: 1; transform: none; transition: none; }
}

/* ——— RESPONSIVE ——— */
@media (max-width: 960px) {
  .container { padding: 0 24px; }
  .hero { padding: 60px 0 80px; }
  .hero-grid { grid-template-columns: 1fr; gap: 60px; }
  .hero-photo { order: -1; }
  .ines-grid { grid-template-columns: 1fr; gap: 56px; }
  .ines-photo { order: -1; min-height: auto; }
  .ines-photo img { max-height: 480px; }
  .ines-photo-sigil { display: none; }
  .ines-photo::after { display: none; }
  .hero-meta { gap: 24px; }
  .rpt-grid { grid-template-columns: 1fr; }
  .pour-qui-grid { grid-template-columns: 1fr; gap: 48px; }
  .interstitial { padding: 72px 0; }
  .interstitial-inner { grid-template-columns: 1fr; gap: 40px; }
  .interstitial-action { justify-content: flex-start; }
  .interstitial-micro { text-align: left; }
  .interstitial-cta { padding: 20px 28px; width: 100%; justify-content: center; }
  .capture-inner { padding: 48px 28px; }
  .perks { grid-template-columns: 1fr; }
  .manifesto, .rpt, .pour-qui, .ines, .capture { padding: 80px 0; }
  .footer-grid { grid-template-columns: 1fr; gap: 48px; padding-bottom: 40px; }
  .footer { padding: 60px 0 32px; }
}

@media (max-width: 520px) {
  .nav-cta { display: none; }
  .hero h1 { font-size: 44px; }
  .hero-meta { flex-direction: column; gap: 16px; }
  .ines-stats { gap: 20px; }
  .stat-num { font-size: 32px; }
}
</style>
</head>

<body>

<a href="#main" class="skip-link">Aller au contenu</a>

<!-- NAV -->
<nav class="nav">
  <div class="container nav-inner">
    <div>
      <div class="nav-brand">Inès Kouki</div>
      <div class="nav-brand-sub">Rôle · Posture · Trajectoire</div>
    </div>
    <a href="#capture" class="nav-cta">Réserver un appel</a>
  </div>
</nav>

<!-- HERO -->
<main id="main">
<section class="hero">
  <div class="container">
    <div class="hero-single">
      <div class="kicker reveal">Appel de clarté · 30&nbsp;minutes · Gratuit</div>
      <h1 class="reveal">La transformation échoue quand les <span class="underline-accent">rôles sont flous</span>.</h1>
      <p class="hero-lede reveal">
        17&nbsp;ans à piloter des programmes de transformation dans la banque, le retail et la tech. Aujourd'hui, j'accompagne les femmes en transformation Agile à clarifier leur rôle, renforcer leur posture et piloter leur trajectoire.
      </p>
      <div class="hero-meta reveal">
        <div class="hero-meta-item">
          <div class="hero-meta-label">Terrain</div>
          <div class="hero-meta-value">17&nbsp;ans</div>
        </div>
        <div class="hero-meta-item">
          <div class="hero-meta-label">Pays</div>
          <div class="hero-meta-value">4</div>
        </div>
        <div class="hero-meta-item">
          <div class="hero-meta-label">Secteurs</div>
          <div class="hero-meta-value">3</div>
        </div>
      </div>

      <a href="https://calendly.com/ines-kouki-yb9r/30min" class="hero-primary-cta reveal">
        <span>Réserver mon appel gratuit</span>
        <span aria-hidden="true">→</span>
      </a>
    </div>
  </div>
</section>

<!-- MANIFESTO -->
<section class="manifesto">
  <div class="container">
    <div class="manifesto-inner reveal">
      <div class="section-label" style="color: var(--terracotta);">Manifeste</div>
      <p class="manifesto-quote">
        La transformation n'échoue pas par manque de méthode. <em>Elle échoue quand les rôles sont flous, les postures fragiles et les trajectoires subies.</em>
      </p>
      <div class="manifesto-sig">
        <div>
          <div class="manifesto-sig-name">Inès Kouki</div>
          <div class="manifesto-sig-role">Consultante en transformation · 17&nbsp;ans · 4&nbsp;pays</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- R.P.T. -->
<section class="rpt">
  <div class="container">
    <div class="rpt-intro reveal">
      <div class="section-label">Ce que vous allez comprendre</div>
      <h2 class="rpt-title">Trois piliers. <em style="font-style: italic;">Une lecture claire de votre situation.</em></h2>
      <p class="rpt-lede">
        La méthode R.P.T. ne remplace ni SAFe, ni ICP-ACC, ni votre expérience. Elle vous donne un cadre pour y voir clair sur votre place dans le système &mdash; avant que le système ne décide à votre place.
      </p>
    </div>

    <div class="rpt-grid">
      <div class="pillar pillar--r reveal">
        <div class="pillar-letter">R</div>
        <div class="pillar-tag">Pilier 01 · Rôle</div>
        <h3 class="pillar-name">Rôle</h3>
        <p class="pillar-desc">
          Scrum Master, PMO, Product Owner, Transformation Lead : les titres sont trompeurs. Vous apprenez à définir la valeur réelle que vous apportez, votre périmètre d'influence, et les attentes implicites que personne n'énonce.
        </p>
        <div class="pillar-result">Fin du flou professionnel.</div>
      </div>

      <div class="pillar pillar--p reveal">
        <div class="pillar-letter">P</div>
        <div class="pillar-tag">Pilier 02 · Posture</div>
        <h3 class="pillar-name">Posture</h3>
        <p class="pillar-desc">
          Deux personnes avec le même rôle peuvent avoir des impacts opposés. La différence tient à la posture : présence en réunion, niveau d'affirmation, gestion des jeux politiques, crédibilité perçue.
        </p>
        <div class="pillar-result">Influence sans surjouer.</div>
      </div>

      <div class="pillar pillar--t reveal">
        <div class="pillar-letter">T</div>
        <div class="pillar-tag">Pilier 03 · Trajectoire</div>
        <h3 class="pillar-name">Trajectoire</h3>
        <p class="pillar-desc">
          Vous enchaînez les missions sans direction claire. Vous apprenez à lire les signaux de carrière, choisir la prochaine étape intentionnellement, et construire une cohérence de long terme.
        </p>
        <div class="pillar-result">Carrière pilotée, non subie.</div>
      </div>
    </div>
  </div>
</section>

<!-- POUR QUI -->
<section class="pour-qui">
  <div class="container">
    <div class="pour-qui-grid">
      <div class="reveal">
        <div class="section-label">Pour qui</div>
        <h2 class="pour-qui-title">Si vous vous reconnaissez dans <em>ne serait-ce qu'une seule</em> de ces situations, 30&nbsp;minutes avec moi peuvent tout changer.</h2>
      </div>

      <ul class="pour-qui-list">
        <li class="pour-qui-item reveal">
          <span class="pour-qui-num">01</span>
          <span class="pour-qui-text">Votre mission vient de changer et vous ne savez <strong>plus comment présenter ce que vous valez vraiment.</strong></span>
        </li>
        <li class="pour-qui-item reveal">
          <span class="pour-qui-num">02</span>
          <span class="pour-qui-text">Une réorganisation a flouté votre périmètre et <strong>vous ne savez plus où vous situer.</strong></span>
        </li>
        <li class="pour-qui-item reveal">
          <span class="pour-qui-num">03</span>
          <span class="pour-qui-text">Un collègue moins expérimenté a été promu à votre place &mdash; <strong>et ce n'est pas une question de compétence.</strong></span>
        </li>
        <li class="pour-qui-item reveal">
          <span class="pour-qui-num">04</span>
          <span class="pour-qui-text">Vous cumulez les missions sans jamais <strong>construire de trajectoire lisible.</strong></span>
        </li>
        <li class="pour-qui-item reveal">
          <span class="pour-qui-num">05</span>
          <span class="pour-qui-text">Vous travaillez bien, vous êtes fiable, mais <strong>on vous voit peu là où ça compte.</strong></span>
        </li>
      </ul>
    </div>
  </div>
</section>

<!-- INTERSTITIAL CTA — pic émotionnel, après reconnaissance des pain points -->
<section class="interstitial">
  <div class="container">
    <div class="interstitial-inner">
      <div class="reveal">
        <div class="interstitial-label">L'étape suivante</div>
        <h2 class="interstitial-title">Vous vous êtes reconnue dans l'une de ces situations<em>&nbsp;?</em></h2>
        <p class="interstitial-sub">
          30&nbsp;minutes avec Inès suffisent pour poser une première lecture claire de votre rôle, de votre posture et de votre trajectoire.
        </p>
      </div>
      <div class="reveal">
        <div class="interstitial-action">
          <a href="https://calendly.com/ines-kouki-yb9r/30min" class="interstitial-cta">
            <span>Réserver mon appel</span>
            <span class="arrow" aria-hidden="true">→</span>
          </a>
        </div>
        <div class="interstitial-micro">
          Gratuit · 30&nbsp;minutes · Sans engagement
        </div>
      </div>
    </div>
  </div>
</section>

<!-- INÈS -->
<section class="ines">
  <div class="container">
    <div class="ines-grid">
      <div class="reveal">
        <div class="section-label">Qui est Inès</div>
        <h2 class="ines-name">Inès Kouki</h2>
        <div class="ines-role">Consultante senior · Transformation · Méthode R.P.T.</div>
        <p class="ines-bio">
          <em>Vous pouvez être hautement compétente… et vous sentir invisible. Ce n'est pas un problème de compétence. C'est un problème de positionnement.</em>
        </p>
        <p class="ines-bio">
          17&nbsp;ans à piloter des programmes de transformation à travers l'Afrique, l'Europe et le Moyen-Orient. Banque, retail, tech. J'ai vu des profils remarquables stagner non par manque de capacité, mais par manque de clarté sur leur rôle réel.
        </p>
        <p class="ines-bio">
          Ma conviction&nbsp;: la certification valide vos connaissances, pas votre positionnement. Ce qui change vraiment tout, c'est la clarté sur le rôle que vous occupez, la posture que vous tenez, et la trajectoire que vous pilotez — plutôt que de la subir.
        </p>

        <div class="ines-stats">
          <div>
            <div class="stat-num">17</div>
            <div class="stat-label">Années de terrain</div>
          </div>
          <div>
            <div class="stat-num">4</div>
            <div class="stat-label">Pays</div>
          </div>
          <div>
            <div class="stat-num">3</div>
            <div class="stat-label">Secteurs</div>
          </div>
        </div>
      </div>

      <div class="ines-photo reveal">
        <div class="ines-photo-sigil" aria-hidden="true">Rôle · Posture · Trajectoire</div>
        <img src="data:image/webp;base64,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" alt="Portrait d'Inès Kouki, consultante senior en transformation" width="495" height="760">
      </div>
    </div>
  </div>
</section>

<!-- CAPTURE (direct Calendly CTA) -->
<section class="capture" id="capture">
  <div class="container">
    <div class="capture-inner reveal">
      <div class="section-label">Réserver votre appel</div>
      <h2 class="capture-title">30&nbsp;minutes pour poser les premières pierres de votre <em>clarté professionnelle.</em></h2>
      <p class="capture-sub">
        Un échange privé avec Inès. Votre situation, vos blocages réels, votre prochaine étape. Gratuit, sans engagement, sans relance commerciale.
      </p>

      <a href="https://calendly.com/ines-kouki-yb9r/30min" class="capture-cta">
        <span>Choisir mon créneau</span>
        <span aria-hidden="true">→</span>
      </a>
      <div class="capture-note">
        Vous serez redirigée vers le calendrier de réservation. <strong>Confidentialité absolue.</strong>
      </div>

      <div class="perks">
        <div class="perk">
          <div class="perk-num">i.</div>
          <div class="perk-text">
            <strong>Une lecture claire de votre situation</strong>
            On regarde ensemble votre rôle réel, votre posture actuelle, votre trajectoire — sans jargon ni généralités.
          </div>
        </div>
        <div class="perk">
          <div class="perk-num">ii.</div>
          <div class="perk-text">
            <strong>L'angle R.P.T. appliqué à vous</strong>
            Rôle · Posture · Trajectoire&nbsp;: où c'est aligné, où ça bloque, et pourquoi.
          </div>
        </div>
        <div class="perk">
          <div class="perk-num">iii.</div>
          <div class="perk-text">
            <strong>Des prochaines étapes concrètes</strong>
            Vous repartez avec 2 ou 3&nbsp;leviers immédiatement actionnables dans votre contexte.
          </div>
        </div>
        <div class="perk">
          <div class="perk-num">iv.</div>
          <div class="perk-text">
            <strong>Aucun engagement</strong>
            Pas de relance commerciale. Vous repartez avec une lecture, c'est tout.
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
</main>
<footer class="footer">
  <div class="container">
    <div class="footer-grid">
      <div class="footer-brand-block">
        <div class="footer-col-label">Marque</div>
        <div class="footer-name">Inès Kouki</div>
        <div class="footer-tagline">Rôle <span>·</span> Posture <span>·</span> Trajectoire</div>
        <p class="footer-pitch">Je transforme la confusion professionnelle en clarté stratégique.</p>
      </div>

      <div>
        <div class="footer-col-label">Me contacter</div>
        <ul class="footer-contacts">
          <li>
            <a class="footer-contact-item" href="mailto:ines.kouki@outlook.com">
              <span class="contact-icon" aria-hidden="true">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round">
                  <rect x="3" y="5" width="18" height="14" rx="1"></rect>
                  <path d="M3 7l9 6 9-6"></path>
                </svg>
              </span>
              <span>
                <span class="contact-label">Email</span>
                <span class="contact-value">ines.kouki@outlook.com</span>
              </span>
            </a>
          </li>
          <li>
            <a class="footer-contact-item" href="https://wa.me/33631805966" target="_blank" rel="noopener">
              <span class="contact-icon" aria-hidden="true">
                <svg viewBox="0 0 24 24" fill="currentColor">
                  <path d="M17.5 14.4c-.3-.1-1.7-.8-2-.9-.3-.1-.5-.1-.7.1-.2.3-.8.9-.9 1.1-.2.2-.3.2-.6.1-.3-.1-1.2-.5-2.3-1.5-.9-.8-1.5-1.7-1.6-2-.2-.3 0-.4.1-.6.1-.1.3-.3.4-.5.1-.1.2-.3.3-.4.1-.2 0-.3 0-.5-.1-.1-.7-1.6-.9-2.2-.2-.6-.5-.5-.7-.5h-.6c-.2 0-.5.1-.8.4-.3.3-1 1-1 2.4 0 1.4 1 2.8 1.2 3 .1.2 2 3 4.8 4.2.7.3 1.2.5 1.6.6.7.2 1.3.2 1.8.1.5-.1 1.7-.7 1.9-1.4.2-.7.2-1.2.2-1.4-.1-.1-.3-.2-.5-.3z"></path>
                  <path d="M20.5 3.5C18.3 1.2 15.3 0 12.1 0 5.5 0 .2 5.3.2 11.9c0 2.1.6 4.2 1.6 6L0 24l6.3-1.7c1.8 1 3.7 1.5 5.7 1.5h.1c6.5 0 11.9-5.3 11.9-11.9 0-3.2-1.2-6.2-3.5-8.4zM12.1 21.7c-1.8 0-3.6-.5-5.1-1.4l-.4-.2-3.7 1 1-3.6-.2-.4c-1-1.6-1.5-3.5-1.5-5.4 0-5.5 4.5-10 10-10 2.7 0 5.2 1 7.1 2.9 1.9 1.9 2.9 4.4 2.9 7.1-.1 5.5-4.5 10-10.1 10z"></path>
                </svg>
              </span>
              <span>
                <span class="contact-label">WhatsApp</span>
                <span class="contact-value">+33&nbsp;6&nbsp;31&nbsp;80&nbsp;59&nbsp;66</span>
              </span>
            </a>
          </li>
          <li>
            <a class="footer-contact-item" href="https://www.linkedin.com/in/ines-kouki-ik/" target="_blank" rel="noopener" aria-label="Profil LinkedIn d'Inès Kouki">
              <span class="contact-icon" aria-hidden="true">
                <svg viewBox="0 0 24 24" fill="currentColor">
                  <path d="M20.45 20.45h-3.55v-5.57c0-1.33-.02-3.04-1.85-3.04-1.85 0-2.14 1.45-2.14 2.94v5.67H9.36V9h3.41v1.56h.05c.47-.9 1.64-1.85 3.37-1.85 3.6 0 4.27 2.37 4.27 5.46v6.28zM5.34 7.43a2.06 2.06 0 1 1 0-4.12 2.06 2.06 0 0 1 0 4.12zM7.12 20.45H3.56V9h3.56v11.45zM22.22 0H1.77C.79 0 0 .77 0 1.72v20.56C0 23.23.79 24 1.77 24h20.45C23.2 24 24 23.23 24 22.28V1.72C24 .77 23.2 0 22.22 0z"></path>
                </svg>
              </span>
              <span>
                <span class="contact-value">LinkedIn</span>
              </span>
            </a>
          </li>
        </ul>
      </div>

      <div class="footer-cta-block">
        <div class="footer-col-label">Prochaine étape</div>
        <p class="footer-pitch" style="margin-bottom: 22px;">Un appel de clarté, 30&nbsp;minutes, gratuit.</p>
        <a href="https://calendly.com/ines-kouki-yb9r/30min" class="footer-cta">
          <span>Réserver</span>
          <span aria-hidden="true">→</span>
        </a>
      </div>
    </div>

    <div class="footer-bottom">
      <div class="footer-credit">© 2026 Inès Kouki · Tous droits réservés</div>
    </div>
  </div>
</footer>

<!-- WhatsApp floating CTA -->
<a class="whatsapp-fab" href="https://wa.me/33631805966?text=Bonjour%20In%C3%A8s%2C%20j%27aimerais%20%C3%A9changer%20avec%20vous." target="_blank" rel="noopener" aria-label="Discuter avec Inès sur WhatsApp">
  <svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true">
    <path d="M17.5 14.4c-.3-.1-1.7-.8-2-.9-.3-.1-.5-.1-.7.1-.2.3-.8.9-.9 1.1-.2.2-.3.2-.6.1-.3-.1-1.2-.5-2.3-1.5-.9-.8-1.5-1.7-1.6-2-.2-.3 0-.4.1-.6.1-.1.3-.3.4-.5.1-.1.2-.3.3-.4.1-.2 0-.3 0-.5-.1-.1-.7-1.6-.9-2.2-.2-.6-.5-.5-.7-.5h-.6c-.2 0-.5.1-.8.4-.3.3-1 1-1 2.4 0 1.4 1 2.8 1.2 3 .1.2 2 3 4.8 4.2.7.3 1.2.5 1.6.6.7.2 1.3.2 1.8.1.5-.1 1.7-.7 1.9-1.4.2-.7.2-1.2.2-1.4-.1-.1-.3-.2-.5-.3z"></path>
    <path d="M20.5 3.5C18.3 1.2 15.3 0 12.1 0 5.5 0 .2 5.3.2 11.9c0 2.1.6 4.2 1.6 6L0 24l6.3-1.7c1.8 1 3.7 1.5 5.7 1.5h.1c6.5 0 11.9-5.3 11.9-11.9 0-3.2-1.2-6.2-3.5-8.4zM12.1 21.7c-1.8 0-3.6-.5-5.1-1.4l-.4-.2-3.7 1 1-3.6-.2-.4c-1-1.6-1.5-3.5-1.5-5.4 0-5.5 4.5-10 10-10 2.7 0 5.2 1 7.1 2.9 1.9 1.9 2.9 4.4 2.9 7.1-.1 5.5-4.5 10-10.1 10z"></path>
  </svg>
  <span class="wa-label">Discutons sur WhatsApp</span>
</a>

<script>
// Intersection Observer for reveal animations
const observer = new IntersectionObserver((entries) => {
  entries.forEach((entry, i) => {
    if (entry.isIntersecting) {
      setTimeout(() => entry.target.classList.add('is-visible'), i * 80);
      observer.unobserve(entry.target);
    }
  });
}, { threshold: 0.12, rootMargin: '0px 0px -40px 0px' });

document.querySelectorAll('.reveal').forEach(el => observer.observe(el));

// Hero reveals immediately with stagger
document.addEventListener('DOMContentLoaded', () => {
  const heroReveals = document.querySelectorAll('.hero .reveal');
  heroReveals.forEach((el, i) => {
    setTimeout(() => el.classList.add('is-visible'), 120 + i * 140);
  });
});
</script>

</body>
</html>

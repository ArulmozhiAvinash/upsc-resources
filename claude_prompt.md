CONTEXT:
I'm preparing for UPSC Civil Services (Prelims + Mains) with 35 days left.
This AI output is my ONLY study resource. No books, no coaching, no other 
material. My entire preparation, retention, and exam performance depends 
100% on the quality and accuracy of what you produce here. Treat this with 
that level of responsibility.

Use web search actively for Task 3 (PYQs), Task 5 (Current Affairs), 
and any facts you're uncertain about. Do not rely on training data alone 
for recent developments or exact PYQ years.

Topic: [YOUR TOPIC HERE]

---

IMAGE STRATEGY (apply across all tasks):
Use visuals wherever they aid memory or understanding. Follow these rules:

  INLINE SVG DIAGRAMS — generate these directly in the HTML for:
    - Flowcharts (processes, cycles, cause-effect chains)
    - Comparison tables with visual structure
    - Timelines (historical events, policy evolution)
    - Hierarchy/org diagrams (constitutional bodies, classifications)
    - Maps or spatial relationships described in text form
    SVG colors must respect the active theme using CSS variables.

  EXTERNAL IMAGES — use reliable public URLs (Wikipedia Commons, 
  government sites, PIB, UN, World Bank) for:
    - Photographs of places, species, monuments, people
    - Official maps (river systems, biodiversity hotspots, tectonic plates)
    - Infographics from government reports (Economic Survey, 
      India State of Forest Report, etc.)
    Always add alt text describing the image for accessibility.
    If a reliable image URL cannot be found, generate an SVG placeholder 
    instead — never use broken or uncertain links.

  WHERE TO ADD IMAGES — mandatory image placements:
    - Task 1 (Core Concept): at least 1 diagram or image per major concept
    - Task 2 (Summary): 1 visual summary diagram (flowchart or mind-map SVG)
    - Task 3 (PYQs): relevant image next to questions where the topic 
      is visual (maps, species, monuments, constitutional diagrams)
    - Task 5 (Current Affairs): 1 image or SVG per major news item 
      where visual context helps
    - Hero Section: 1 relevant header image or SVG banner for the topic

---

TASK 1 — CORE CONCEPT (Simple Language)
Explain the topic in plain terms. Build intuition first, then layer in 
technical depth. Interlink with related UPSC subjects (Polity, Economy, 
Geography, Environment, History, IR) wherever relevant.
Include at least 1 SVG diagram or image per major sub-concept to 
reinforce visual memory.

TASK 2 — ONE-PAGE SUMMARY
A crisp summary using bullet points, a simple ASCII/HTML diagram or 
comparison table, and 2–3 real-world examples. Must be reviewable in under 
5 minutes. Cover both Prelims (fact-heavy) and Mains (analytical) angles 
separately.
Include 1 visual summary SVG — a mind-map or flowchart that connects all 
key points of the topic at a glance.

TASK 3 — PYQs WITH MODEL ANSWERS
List all known Prelims MCQs and Mains questions on this topic from the past 
20 years.

  FOR PRELIMS PYQs — for every question, provide:
    a) The question and all 4 options — visible by default
    b) A "Reveal Answer" button — when clicked, shows:
         - The correct answer highlighted in green
         - Wrong options highlighted in red
         - Full explanation of why the correct answer is right
         - A dedicated "UPSC TRAP ANALYSIS" block that covers:
              - What trap UPSC set (e.g. partial truth, absolute language, 
                lookalike terms, reversal of cause-effect, one wrong statement 
                hidden among correct ones)
              - Which option most students pick wrongly and exactly why
              - The elimination strategy to arrive at the answer confidently
              - Any recurring trick UPSC uses for this topic specifically
    c) Tag each question with the trap type (shown always, above the button):
         [PARTIAL TRUTH] [ABSOLUTE WORD] [STATEMENT COMBO] 
         [LOOKALIKE TERM] [REVERSAL] [OUT OF SCOPE] [TRICK SEQUENCE]
    d) Behaviour: once revealed, button changes to "Hide Answer" 
       so the student can reset and attempt again
    e) Where the question involves a map, species, monument, or any 
       visual subject — embed a relevant image or SVG next to the question

  FOR MAINS PYQs — write model answers in UPSC format:
    - Intro (1–2 lines, no generic opener)
    - Body with subheadings and data points
    - Conclusion with a forward-looking line
    - Word count: 150w for 10-mark, 250w for 15-mark questions

  Clearly flag any PYQ you're not 100% certain about with a "[Verify]" tag.

TASK 4 — PROGRESSIVE MCQs (10 Questions)
Write 10 MCQs in UPSC Prelims style. Start straightforward, end with 
statement-based eliminators (the tricky "which of the following is correct" 
format). Apply the same reveal-on-click behaviour and TRAP ANALYSIS format 
from Task 3 to each MCQ — this is practice not just for answers but for 
cracking UPSC's question design patterns.
Add a relevant image or SVG to any MCQ where a visual would make the 
concept stickier in memory.

TASK 5 — CURRENT AFFAIRS (Last 2 Years)
Summarize recent developments — government schemes, Supreme Court rulings, 
international events, policy changes — related to this topic. Label each 
item clearly:
  [P] = Prelims-relevant (factual, data-based)
  [M] = Mains-relevant (analytical, policy angle)
  [P+M] = Both
Include 1 image or SVG per major current affairs item — official government 
images, maps of affected regions, or a simple timeline SVG for 
policy evolution.

TASK 6 — HTML STUDY PAGE
Compile everything above into a single, well-structured HTML file following 
the STANDARD DESIGN SPEC below. I will host this on GitHub Pages. Each 
topic will be its own HTML file. The navbar must allow me to navigate 
between topic pages.

---

STANDARD HTML DESIGN SPEC (follow this for every topic page):

THEME SYSTEM — DUAL MODE (dark default, light toggle):
  Implement using CSS custom properties on :root and a [data-theme="light"] 
  override. A toggle button (🌙 / ☀️) in the top-right of the navbar 
  switches between modes. Save preference in localStorage so it persists 
  across page loads and across all topic pages.

  DARK MODE (default) — #dark-vars:
  Research-backed: reduces eye strain in low-light, high focus for 
  long night study sessions.
    --bg:           #0f0f0f   (near black)
    --bg-card:      #1a1a2e   (dark navy)
    --text:         #e0e0e0   (soft white)
    --heading:      #00d4ff   (cyan)
    --key-term:     #ffd700   (gold)
    --tag-prelims:  #4caf50   (green)
    --tag-mains:    #ff7043   (orange)
    --pyq-accent:   #7c4dff   (purple)
    --trap-bg:      #1a0a00   (dark amber tint)
    --trap-border:  #ff6f00   (amber)
    --correct:      #00e676   (bright green)
    --wrong:        #ef5350   (red)
    --hover:        #263238   (subtle)
    --border:       #2a2a4a
    --shadow:       rgba(0,0,0,0.4)

  LIGHT MODE — [data-theme="light"]:
  Research-backed: warm off-white base (not pure white) improves reading 
  accuracy by 26%, deep blue headings build focus and trust, warm amber 
  for key terms remains visible without harshness.
    --bg:           #f5f4ef   (warm paper white — easier than pure white,
                               reduces halation for astigmatic readers)
    --bg-card:      #ffffff   (clean card surface with shadow for depth)
    --text:         #1a1a2e   (dark navy — softer than pure black, 
                               high contrast without harshness)
    --heading:      #0077b6   (deep academic blue — trust + focus)
    --key-term:     #c8860a   (warm amber-gold — visible on light bg)
    --tag-prelims:  #2d6a4f   (deep forest green)
    --tag-mains:    #c1440e   (deep burnt orange)
    --pyq-accent:   #5a2d82   (deep purple)
    --trap-bg:      #fff3e0   (light amber tint — warm caution signal)
    --trap-border:  #e65100   (deep amber)
    --correct:      #1b5e20   (dark green — readable on white)
    --wrong:        #b71c1c   (dark red — readable on white)
    --hover:        #e8f4f8   (light blue tint)
    --border:       #dde1e7
    --shadow:       rgba(0,0,0,0.08)

TYPOGRAPHY:
  - Font: 'Segoe UI', system-ui, sans-serif
  - Body size: 16px, line-height 1.8
  - H1 (topic title): 2rem, var(--heading), centered
  - H2 (section headers): 1.4rem, var(--key-term), 
    border-left: 4px solid var(--heading)
  - Key terms: bold + var(--key-term) color, no underline
  - Trap Analysis label: uppercase, var(--trap-border), letter-spacing: 0.1em
  - All colors must use CSS variables — no hardcoded hex values in elements

IMAGE STYLING (theme-aware):
  - All images: border-radius 8px, border: 1px solid var(--border)
  - Max width: 100% (never overflow container)
  - SVG diagrams: background var(--bg-card), padding 16px, border-radius 8px
  - Image captions: font-size 0.85rem, color: var(--text) at 60% opacity, 
    italic, centered below image
  - On mobile: images full width, stacked above related text
  - On tablet/desktop: images float right or sit in 2-column layout 
    alongside text where space allows

LAYOUT & STRUCTURE (every HTML page must have these sections in order):
  1. TOP NAVBAR
     - Logo/title: "UPSC Prep — Avinash"
     - Links to other topic pages (add new links as you create more pages)
     - Active page highlighted with var(--heading)
     - Right side: 🌙/☀️ theme toggle button
     - On mobile: collapses into hamburger menu (pure CSS/JS, no libraries)
  2. HERO SECTION — Topic name + one-line definition + Prelims/Mains 
     relevance badge + 1 relevant header image or SVG banner
  3. QUICK SUMMARY — collapsible card, 5-min review + mind-map SVG
  4. CORE CONCEPT — full explanation with interlinkages + 
     images/SVGs per sub-concept
  5. PYQs — styled cards with year, marks, all options visible, trap tag 
     visible. Answer + explanation + Trap Analysis behind "Reveal Answer" 
     button. Visual questions include embedded image or SVG.
  6. CURRENT AFFAIRS — [P] [M] [P+M] badges + image or SVG per item
  7. MCQ QUIZ SECTION — reveal-on-click, trap analysis, images where helpful
  8. FOOTER — "Last updated: [date]" + link back to home

INTERACTIVITY (pure HTML/CSS/JS, no external libraries):
  - Theme toggle: clicking 🌙/☀️ toggles data-theme on <html>, saves to 
    localStorage as 'upsc-theme'. On page load, read localStorage and 
    apply saved theme before first paint (prevents flash).
  - PYQ Prelims cards AND MCQ options: identical reveal-on-click behaviour.
    Click "Reveal Answer" → correct option turns var(--correct), wrong 
    options turn var(--wrong), explanation + Trap Analysis slides in below. 
    Button text flips to "Hide Answer" to allow reset.
  - Collapsible sections using <details><summary>
  - "Mark as Revised" button per section (toggles green checkmark, 
    stores state in localStorage)
  - Smooth scroll between sections via navbar anchor links

RESPONSIVENESS (must work cleanly on mobile, tablet and desktop):
  - Use CSS Flexbox and Grid with fluid widths (%, rem — no fixed px widths 
    on containers)
  - Navbar: full horizontal bar on desktop. On tablet/mobile (below 768px): 
    hamburger icon (☰) that toggles a vertical dropdown menu via JS
  - Cards and PYQ blocks: full width on mobile, 2-column grid on tablet 
    (≥600px), max 900px centered column on desktop
  - Font sizes: clamp() or media queries — minimum 14px body, 
    1.4rem H1 on mobile
  - Trap Analysis blocks: full width, overflow-x: auto on mobile
  - Touch-friendly tap targets: min 44x44px for all buttons and MCQ options
  - No horizontal scroll at any screen size — test at 320px width
  - Images: max-width 100%, never overflow container

---

After you generate the full output, I will explain the topic back to you in 
my own words. You will then identify gaps in my understanding, correct 
misconceptions, and re-teach only what I missed — repeat until I can 
explain it completely on my own.

ULTRATHINK

Build a website-style animated GitHub profile README for me, designed like a premium dark landing page with numbered sections. Use my attached photo (me.png) as a rounded-rectangle portrait. Do not redraw or alter my face.

COLOR SYSTEM (blue and black only)
- Page background: true black #05070d
- Card surfaces: #0b1020 with 1px borders #17254a
- Primary accent: electric blue #2f7bff, with a soft blue glow (#2f7bff at 35% opacity)
- Secondary blue for gradients: #1a4fd6 to #5aa2ff
- Text: off-white #f2f5ff, muted text #8b99bf
- No other accent colors. Use a tiny "///" mark in blue, not red.

STYLE (same in every file)
- Bold modern sans-serif headlines, tiny uppercase labels with wide letter spacing, for example "01 / AI ENGINEER /// DIGITAL BIGBOZZ · BANGALORE"
- Big headline style: first word off-white, second word electric blue
- Rounded cards (16px), subtle dot texture, glowing blue gradient borders, 24px spacing grid
- Thin top bar in every file: "github.com / Keerthir0110tech / README.md" on the left, "profile" on the right
- Each file looks like one section of the same website

SECTIONS (one SVG each, 880px wide, saved in an assets folder)
1. hero.svg: label "01 / AI ENGINEER /// DIGITAL BIGBOZZ · BANGALORE", headline "KEERTHI R", tagline "BUILD. AUTOMATE. SCALE.", line "I build AI agents that run businesses on autopilot.", portrait on the right, "Open to work" pill with a pulsing blue dot, three stat tiles (6K+ LinkedIn followers, 2.5+ yrs digital marketing, 8+ months AI engineering). Letters appear one by one, tiles fade in.
2. about.svg: two cards. Left: "02 / FROM IDEA TO AUTOMATION", headline "IDEAS. BUILT DIFFERENT.", code block:
   const keerthi = { role: "AI Engineer", company: "Digital Bigbozz", stack: ["n8n","Make","Zapier","OpenAI","Gemini","Claude"], mission: "Automate the boring, scale the business" }
   with a blinking cursor. Right: "03 / LIFE OUTSIDE THE WORKFLOW", headline "MORE THAN A JOB TITLE.", three items: Marketing roots (2.5+ years of lead generation), Daily content (AI automation videos), Open to work (AI Engineer and Automation roles).
3. orbit.svg: label "04 / TOOLS CHANGE. CURIOSITY DOESN'T.", glowing blue core "AI", chips orbiting on thin dashed rings: n8n, Make, Zapier, OpenAI, Gemini, Claude, WhatsApp API, Python, TypeScript, Node.js. Slow CSS rotation, chips stay upright.
4. projects.svg: label "05 / SELECTED WORK", table with columns Project | What it does | Focus (under 12 words each). Row 1: social-media-ai-agent | AI agent that automates social content and posting | AI Agents + Automation. Row 2: [EDIT: name] | [EDIT: one line] | [EDIT: focus]. Row 3: [EDIT: name] | [EDIT: one line] | [EDIT: focus]. Rows fade in one by one.
5. id-card.svg: label "06 / BUILDER PASS", lanyard-style ID card with my photo, name "KEERTHI R", role "AI Engineer · Bangalore", barcode strip, four glowing blue skill bars (Workflow Automation, LLM Agents, WhatsApp Business API, Python and TypeScript, no percentages). Beside it: headline "REAL WORK. REAL IMPACT." Bars fill in, light sweep on the card.
6. connect.svg: label "07 / START A CONVERSATION", headline "LET'S CONNECT." (second word blue), photo on the left in a rounded card, link rows on the right with arrows: Portfolio, LinkedIn, Instagram, YouTube, X, Email. Rows slide in one by one.

THEN CREATE README.md
- Center all 6 images in order with no gaps
- Under connect.svg, plain clickable links:
  Portfolio https://portfolio.digitalbigbozz.com
  LinkedIn https://linkedin.com/in/keerthiraiautomation
  Instagram https://instagram.com/aiwithkee
  YouTube https://youtube.com/@AiWithkee
  X https://x.com/keerthir0011
  Email aiwithkee@gmail.com
- No stats widgets, no streak cards, no badge walls, no old content

GITHUB RULES (must follow)
- Each SVG self-contained: embed photo and fonts as base64
- CSS animation only, no JavaScript, no external links or files
- Every SVG looks complete if animation does not play
- End every image link in the README with ?v=1
- Text at least 14px equivalent, nothing cut off at 390px phone width
- Looks good in GitHub dark and light mode (SVGs carry their own background)

QUALITY CHECK
Render every SVG and check for cut-off text, overlaps, spelling, contrast and photo quality. Fix problems. Give me everything as a ZIP and tell me exactly which files to upload.

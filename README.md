Build a website-style animated GitHub profile README for me, designed like a premium dark landing page with numbered sections. Use my attached photo (me.png) as a rounded-rectangle portrait. Do not redraw or alter my face.

DESIGN SYSTEM (same for every file)
- Background deep navy #070b16, card surfaces #0e1630, thin 1px borders #1b2a52
- Electric blue #247bff for headline highlights, crimson/pink #ff354f for small accents and "///" marks
- Off-white text #f2f5ff, muted text #8fa0c8
- Font: bold modern sans-serif, tiny uppercase section labels with wide letter spacing (example: "01 / AI ENGINEER /// DIGITAL BIGBOZZ · BANGALORE")
- Big headline style: first word off-white, second word blue, a small crimson "///" after it
- Rounded cards (16px), subtle dot texture, soft glowing borders, 24px spacing grid
- Every file looks like a section of one website, with a thin top bar reading "github.com / Keerthir0110tech / README.md" and "profile" on the right

SECTIONS (one SVG each, 880px wide)
1. hero.svg
   - Label: "01 / AI ENGINEER /// DIGITAL BIGBOZZ · BANGALORE"
   - Headline: "KEERTHI" (white) + "R" (blue) with crimson "///"
   - Tagline: "BUILD. AUTOMATE. SCALE."
   - Sub line: "I build AI agents that run businesses on autopilot."
   - My portrait on the right in a rounded card
   - Small "Open to work" pill with a pulsing dot
   - Three stat tiles: "6K+ LinkedIn followers", "2.5+ yrs digital marketing", "8+ months AI engineering"
   - Animation: headline letters appear one by one, tiles fade in
2. about.svg (two cards side by side)
   - Left card: label "02 / FROM IDEA TO AUTOMATION", headline "IDEAS. BUILT DIFFERENT.", and a code-style block:
     const keerthi = {
       role: "AI Engineer",
       company: "Digital Bigbozz",
       stack: ["n8n", "Make", "Zapier", "OpenAI", "Gemini", "Claude"],
       mission: "Automate the boring, scale the business"
     }
   - Right card: label "03 / LIFE OUTSIDE THE WORKFLOW", headline "MORE THAN A JOB TITLE.", three short items: Marketing roots (2.5+ years of lead generation), Daily content (AI automation videos on Instagram and LinkedIn), Open to work (AI Engineer and Automation roles)
   - Animation: blinking cursor in the code block
3. orbit.svg
   - Label: "04 / TOOLS CHANGE. CURIOSITY DOESN'T."
   - Glowing blue core with text "AI", chips orbiting slowly on thin dashed rings: n8n, Make, Zapier, OpenAI, Gemini, Claude, WhatsApp API, Python, TypeScript, Node.js
   - Animation: slow CSS rotation, chips stay upright
4. projects.svg
   - Label: "05 / SELECTED WORK"
   - Clean table with 3 columns: Project | What it does | Focus (keep descriptions under 12 words)
   - Row 1: social-media-ai-agent | AI agent that automates social content and posting | AI Agents + Automation
   - Row 2: [EDIT: name] | [EDIT: one line] | [EDIT: focus]
   - Row 3: [EDIT: name] | [EDIT: one line] | [EDIT: focus]
   - Animation: rows fade in one by one
5. id-card.svg
   - Label: "06 / BUILDER PASS"
   - Lanyard-style ID card: my photo on top, name "KEERTHI R", role "AI Engineer · Bangalore", a barcode strip, and four glowing skill bars: Workflow Automation, LLM Agents, WhatsApp Business API, Python and TypeScript (bars are visual only, no percentages)
   - Next to it, the headline "REAL WORK. REAL IMPACT." with the 3 stat tiles again
   - Animation: bars fill in, soft glow sweep on the card
6. connect.svg
   - Label: "07 / START A CONVERSATION"
   - Headline "LET'S" (white) + "CONNECT." (crimson)
   - Second photo (me2.png) on the left in a rounded card (if not provided, reuse me.png)
   - Link rows on the right with a small arrow: Portfolio, LinkedIn, Instagram, YouTube, X, Email
   - Animation: rows slide in one by one

THEN CREATE README.md
- Center all 6 images in order, no gaps between them
- Under connect.svg add my links as plain clickable text:
  Portfolio https://portfolio.digitalbigbozz.com
  LinkedIn https://linkedin.com/in/keerthiraiautomation
  Instagram https://instagram.com/aiwithkee
  YouTube https://youtube.com/@AiWithkee
  X https://x.com/keerthir0011
  Email aiwithkee@gmail.com
- No stats widgets, no streak cards, no badge walls, no old content

GITHUB RULES (must follow)
- Each SVG self-contained: embed my photo and fonts as base64 inside it
- CSS animation only. No JavaScript, no external links or files
- Every SVG must look complete if animation does not play
- End every image link in the README with ?v=1
- Text at least 14px equivalent, nothing cut off when scaled to a 390px phone width
- Looks good in GitHub dark and light mode (SVGs carry their own background)

QUALITY CHECK BEFORE FINISHING
Render every SVG and check for cut-off text, overlaps, spelling, contrast and photo quality. Fix problems. Give me everything as a ZIP and tell me exactly which files to upload.

THEORY TESTER — OFFLINE COPY
============================

A fully offline copy of the Irish Driver Theory Test practice tool.
No internet connection is required to use it.

HOW TO USE
----------
Just double-click "index.html" — it opens in your web browser and works
completely offline. Nothing to install.

WHAT'S INSIDE
-------------
  index.html     The whole app (interface + logic).
  questions.js   All 783 questions, answers and explanations.
  img/           239 question images (road signs, junctions, etc).
  README.txt     This file.

Keep these together in the same folder. If you move it, move the whole folder.

MODES
-----
  • Mock Test        — 40 random questions, 40-minute timer, pass mark 35/40,
                       exactly like the real exam. Marked at the end with a
                       full review of correct/incorrect answers.
  • Practice         — Answer questions with instant feedback + explanation.
  • Revise Questions — Browse and search every question with the answer shown.
  • By Category      — Practice one topic at a time (Signs, Rules of the Road,
                       Safe & Responsible Driving, Technical Matters).
  • Hardest 50       — The questions people get wrong most often, ranked by how
                       often they're answered correctly. Browse or practise them.

Your best mock score and light/dark theme choice are remembered in the browser.

UPDATING THE QUESTIONS (optional, needs internet + Node.js)
-----------------------------------------------------------
The question bank was captured from theory-tester.com. To refresh it later,
from the project root run:
    node scrape.mjs      # re-downloads the full question pool
    node build.mjs       # rebuilds offline/questions.js and downloads images

Built for personal study. Not affiliated with theory-tester.com.

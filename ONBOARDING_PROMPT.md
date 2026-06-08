# Onboarding prompt

Get set up for the SUEWS Community Hackathon in one paste.

**Before you start:** be signed in to GitHub, and make sure we have added you to the **UMEP-dev hackathon team** (we do that from the GitHub handle you share in your team-formation post).

Open your AI agent (Codex or Claude Code), point it at an empty folder, and paste the prompt below.

---

You're helping me get set up for the SUEWS Community Hackathon. Do each step, check it worked before moving on, and tell me plainly if you need my input:

1. Create a GitHub repo for me from the template `UMEP-dev/suews-hackathon-template` (`gh repo create ... --template ...`) and clone it here.
2. Install the suews-agent from https://github.com/UMEP-dev/suews-agent, following its README.
3. Run one small end-to-end suews-agent query on the preconfigured sample data to confirm the pipeline works.
4. Publish the `docs/` folder as a public GitHub Pages site and give me the URL.
5. Save a transcript of this session into `transcripts/` and commit it.

Finish by printing: my repo URL, my Pages URL, and a one-line status per step.

---

This is a pipeline check, not a test of expertise. If the agent gets stuck, post in the hackathon channel and a table lead will help.

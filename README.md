# Hi, I'm Felipe 👋

AI engineer from [ITA](https://www.ita.br/). Founding engineer at [Hexagon](https://joinhexagon.com), where I build [**Milo**](https://joinhexagon.com/milo), an AI teammate you hand work to.

[felipefrf.com](https://felipefrf.com) · [LinkedIn](https://www.linkedin.com/in/felipe-farias-ribeiro) · São Paulo, Brazil

---

### Now: [Milo](https://joinhexagon.com/milo)

Every person on the team gets their own agent, running in its own Linux microVM with their apps and logins. You give it the job and it carries it through, instead of just answering. My parts of it:

- **Voice.** Live calls with Milo, on the phone and in the app. It keeps working while you talk, and you can cut in and steer it.
- **Where people already work.** Microsoft Teams and Google Chat on par with Slack and WhatsApp: act-as-user OAuth, streaming, files and voice notes.
- **Credentials.** An encrypted vault for the hosted browser agent. Passwords and one-time codes go in by alias and never reach the model.
- **Evals before shipping.** Bilingual ship gates that replay real cases, nightly LLM-judged reviews, and an "autopsy" tool that rebuilds any conversation end to end.

<sub>The company code is private. Happy to walk through the architecture on a call.</sub>

---

### Things I've built

<table>
  <tr>
    <td width="34%" valign="top">
      <a href="https://felipefrf.com/#chief"><img src="https://raw.githubusercontent.com/felipefrf/felipefrf.com/main/public/media/cos-app-poster.jpg" alt="The chief of staff's approval queue on a phone" width="260"></a>
    </td>
    <td valign="top">
      <h4><a href="https://felipefrf.com/#chief">Chief of staff: one person, run like a team</a></h4>
      I built my own chief of staff. It reads WhatsApp, Slack, e-mail, meetings and GitHub, works out what needs me, and has the answer, the e-mail or a whole working session ready. I only approve, from my phone.
      <ul>
        <li><b>Reads everything:</b> WhatsApp straight from the Mac's database (read-only, allow-listed contacts), Slack, three Gmail accounts, Granola after each meeting, calendar, Drive and GitHub.</li>
        <li><b>Decides what needs me:</b> a Claude session on my server loops every 15 minutes and wakes the moment I message it. It remembers people, projects and how I write, and learns from every draft I reject.</li>
        <li><b>Prepares the work:</b> replies with the reason behind them, e-mails, the daily's agenda. Anything bigger becomes a lane, a background Claude session with a brief that opens the PR or produces the PDF.</li>
        <li><b>I approve, it ships:</b> one queue on my phone with push notifications. Nothing goes out without me.</li>
      </ul>
      7,600+ Claude Code sessions and 22,000+ subagents in the last 30 days, across 7 accounts in parallel.
      <br><br><code>Claude Code</code> <code>MCP</code> <code>Node</code> <code>SQLite</code> <code>Web Push</code> <code>Cloudflare Tunnel</code>
      <br><br><a href="https://felipefrf.com/#systems">See the architecture →</a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/felipefrf/penpad"><img src="https://raw.githubusercontent.com/felipefrf/penpad/main/docs/img/variation.png" alt="penpad: the same sentence handwritten six times"></a>
      <h4><a href="https://github.com/felipefrf/penpad">penpad</a></h4>
      Markdown + LaTeX notes turned into realistic handwritten pages for iPad, Goodnotes and reMarkable. Fractions, integrals and vectors in handwriting. Offline, <code>pip install</code>, no API key.
      <br><br><code>Python</code> <code>resvg</code> <code>LaTeX</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://felipefrf.com/curo/"><img src="https://raw.githubusercontent.com/felipefrf/felipefrf.com/main/public/media/curo-en-poster.jpg" alt="Curo home page"></a>
      <h4><a href="https://felipefrf.com/curo/">Curo</a></h4>
      A WhatsApp patient-care layer for specialist doctors: one chat for the patient, while the agent deals with the hospital, the insurer and the referring doctor. Built with my brother; got us a Y Combinator interview.
      <br><br><code>Google ADK</code> <code>Gemini</code> <code>Postgres</code> <code>WhatsApp</code>
    </td>
  </tr>
</table>

**Smaller tools**

- [**editable-pets**](https://github.com/felipefrf/editable-pets): a macOS companion that keeps every Claude Code and Codex session in sight.
- [**yt-to-md**](https://github.com/felipefrf/yt-to-md): any YouTube video as clean Markdown for AI agents. No API key.
- [**dual-subtitles-extension**](https://github.com/felipefrf/dual-subtitles-extension): two synced subtitle languages on YouTube, for learning a language.
- [**x-reset**](https://github.com/felipefrf/x-reset): bulk-delete old tweets from your X archive. Resumable.

---

### Stack

<img src="https://skillicons.dev/icons?i=ts,python,react,nodejs,fastapi,postgres,gcp,aws,terraform,docker&perline=10" alt="TypeScript, Python, React, Node.js, FastAPI, Postgres, GCP, AWS, Terraform, Docker">

LLM agents and orchestration, voice, evals and guardrails, RAG, browser automation.

---

### Before this

**NG.CASH**: production LLM agents for a Brazilian fintech, including a WhatsApp debt-negotiation agent that never lets the model pick the number. **Credix**: credit models that became the automated decision engine. **LinkedIn**: an LLM chatbot for the US & Canada sales forecast.

Before code, physics: 1st overall at the Iberoamerican Physics Olympiad 2020, 50+ olympiad medals.

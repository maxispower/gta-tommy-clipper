# GTA Tommy

**Install in one message:** open your AI agent (Claude Code, Gemini, Antigravity or Codex) in an empty folder and type:

```
install this repo from https://github.com/maxispower/gta-tommy-clipper and run it
```

Free, local Shorts machine. It finds GTA videos and streams on YouTube, Twitch and Kick, transcribes them on your own PC, and lets Claude pick the best moments. Then it renders finished 9:16 Shorts with face-tracked framing, word-by-word captions, a hook title, a cover image and the post text.

**Look:** the *Vice Nights* theme (sunset pink `#FF2E88`, teal `#00E5D4`, purple night `#1A0B2E`, Righteous display font). It applies to the captions, the hook and the web app.

- Install: see `INSTALL.md`
- Claude's run book: `SKILL.md` (the default run) and `SKILL-REFERENCE.md` (options)
- Web app: `.venv\Scripts\python.exe app.py <workspace>` opens http://localhost:8765 (the whole frontend is `tommy.html`: top bar, dashboard, Make wizard)
- Settings and env vars: `TOMMY_*`, such as `TOMMY_THEME`, `TOMMY_WORKERS`, `TOMMY_BROWSER`. The Blotato key lives in `~/.gta-tommy/blotato.env`.
- Updates: off by default. Set `UPDATE_URL` to your own `manifest.json` to turn them on (see `update.py`).
- Nothing is ever posted unless you add your own Blotato key and press "Confirm send".

## Credits and licence

GTA Tommy is built on NoCodeHack's open-source **gta6-clipper** (v1.0.7), rebranded with its own Vice Nights look. MIT licence: see `LICENSE`. Bundled models and fonts keep their own licences (`models/NOTICES.txt`, `fonts/OFL*.txt`).

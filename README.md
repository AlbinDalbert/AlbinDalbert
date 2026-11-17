Developer in Gothenburg. Building self-hosted AI tools and running a homelab on Kubernetes

---
I run a private cloud at home: Kubernetes across 3 machines, GPUs for local LLMs and TTS, a git-backed knowledge base that syncs to every device. Most of what I build runs on it.

   ```
   arrakeen (Pi, control plane) ── caladan (3× GPU) ── sietch-tabr
      ├─ meridian + xebec        → agent harness + chat UI
      ├─ llama-server, qwen3-tts → local LLM + TTS on GPU
      ├─ seabed                  → git-backed Obsidian vault, synced from every device
      ├─ albindalbert.dev        → the site
      └─ game servers            → Minecraft, Valheim for friends
   ```
https://albindalbert.dev/
   
<!---
AlbinDalbert/AlbinDalbert is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

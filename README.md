# llama-android-build

Cloud builds of **llama.cpp server** for Android arm64 (Termux on OnePlus 11R).

- Built with Android NDK r27, `arm64-v8a`, static STL, no-native (all CPU variants).
- Target: `llama-server` + `llama-cli` (v0.6.0+, Qwen3.5-capable runner for the 9b model).
- Trigger: Actions tab → **Run workflow** (or push to main).
- Fetch: Artifacts → `llama-android-arm64` (~15–30 MB, phone-friendly).

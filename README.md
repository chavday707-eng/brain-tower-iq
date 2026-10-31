# Brain Tower IQ

A Hindi brain-training puzzle game for kids and adults: 104 levels on 6 floors, from counting and letters to tricky logic, colour sorting, sliding tiles and more.

- **Play in the browser:** after enabling GitHub Pages (Settings -> Pages -> Source: GitHub Actions) the game is live at `https://<your-username>.github.io/<repo-name>/`.
- **Android app:** `app/` is a tiny WebView wrapper around `app/src/main/assets/index.html`. The *Build Android* workflow builds a debug APK (any phone) and a release AAB (Play Store). Download both from the workflow run's *Artifacts*.
- **Edit the game:** it is a single HTML file. Edit `docs/index.html`, then copy it to `app/src/main/assets/index.html` so the app matches.

Package name: `com.rocktiles.braintoweriq`

## Roman Gujarati ma saral steps
1. GitHub par aa repo banavo, code upload karo.
2. Settings -> Pages -> Source = "GitHub Actions". Thodi vaar ma game no link maLshe: `https://<username>.github.io/<repo>/` (aa link koi pan sathe share kari shako).
3. Actions tab -> "Build Android" -> Run workflow. Pachhi "Artifacts" ma `BrainTowerIQ-apk` (phone ma install) ane `BrainTowerIQ-aab` (Play Store mate) download karo.

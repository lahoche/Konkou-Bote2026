# Konkou Bote 2026 — APK

Pwojè sa a mete vèsyon Supabase sit la andedan yon aplikasyon Android WebView.

## Enpòtan
Anvan build la, ranpli `app/src/main/assets/web/supabase-config.js` ak:
- SUPABASE_URL
- SUPABASE_ANON_KEY (public/anon key sèlman)

Pa mete `service_role` key oswa modpas Admin nan GitHub.

## Fè APK san Android Studio
1. Kreye yon nouvo repository GitHub.
2. Upload tout dosye pwojè sa a.
3. Ale nan **Actions**.
4. Chwazi workflow **Build Konkou Bote APK**.
5. Peze **Run workflow**.
6. Lè li fini, antre nan run lan epi pran **Artifacts → konkou-bote-2026-apk**.
7. APK la ladan l kòm `app-debug.apk`.

VS Code sèlman ka sèvi pou modifye fichye yo; build la fèt sou GitHub Actions.

# EduGuide APK Recovery Report

## Original APK
- File: Eduguide.apk
- APK size: 32 MB
- Packaging: Android WebView/web-app wrapper
- Wrapper platform: AppsGeyser

## Recovered application URL
`https://careercompasseduguide.lovable.app`

## App configuration
- Widget name: `Eduguide_19247519`
- AppsGeyser ID: `19247519`
- Tab name: `Eduguide`
- Tab type: `web`
- Tab ID: `22926020`

## What this means
The APK does not contain the original HTML/CSS/JavaScript application source. It contains the Android wrapper and configuration that loads the web application URL.

The original website source may still be recoverable if the corresponding Lovable project/account or a deployed copy is available.

## Recovered files
- `config/configuration.xml` — exact AppsGeyser configuration, including the original web URL
- `assets/user_custom_script.js` — custom JavaScript bundled in the wrapper
- `resources/index.html` — offline/server-unavailable fallback page
- `resources/flashplayer_not_exist.html`
- `resources/insuffient_sdk_version.html`

## Important limitation
The DEX files mostly contain AppsGeyser/Android wrapper/library code. They are not expected to contain the original Lovable site's frontend source because the site was loaded remotely.

# Professional – Home Assistant theme

A clean light/dark theme with a blue/teal palette, rounded cards, soft shadows and extra spacing for sections dashboards.

## Install via HACS
1. HACS > three-dot menu > Custom repositories
2. Add this repository URL, category **Theme**
3. Download "Professional", then make sure `configuration.yaml` has:
   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
   ```
4. Developer Tools > YAML > Reload themes, then select **Professional** in your profile.

## Manual install
Copy `themes/professional.yaml` to `/config/themes/`.

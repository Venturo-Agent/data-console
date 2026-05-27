# VENTURO 景點審核站 (Review Station)

獨立部署的爬蟲景點候選審核站。CORNER workspace 同事登入、審核/潤稿/通過後同步進 ERP attractions。
- 靜態 SPA（單一 index.html）+ Supabase client-side（登入 + RLS 撈 scrape_candidates）
- 部署：nginx static（Dockerfile）via Coolify

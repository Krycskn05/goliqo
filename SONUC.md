# Yayın sonucu

- Calisma: 40097231015 / commit a4f0df1006374c50ee2b638baf28435928c104cc
- Tarih (UTC): 2026-10-24 13:15

```
1-pnpm=basarili
2-kurulum=basarili
mod=YAYIN (worker: goligo, d1: lernkoko-db)
3-hesap=basarili
4-d1=basarili
5-sesler=basarili
5-derleme=basarili
6-sema=basarili
6-uyelik=basarili
7-yayin=basarili
8-kontrol=basarili
9-eski-adres=basarili
```
## 01-pnpm.log
```
v24.21.0
Preparing pnpm@11.25.0 for immediate activation...
11.25.0
```
## 02-install.log
```
? Verifying lockfile against supply-chain policies (842 entries)...
Lockfile is up to date, resolution step is skipped
Progress: resolved 1, reused 0, downloaded 0, added 0
Packages: +640
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Progress: resolved 640, reused 0, downloaded 15, added 0
Progress: resolved 640, reused 0, downloaded 57, added 0
Packages are hard linked from the content-addressable store to the virtual store.
  Content-addressable store is at: /home/runner/work/goligo/goligo/.sites-runtime/pnpm-store/v11
  Virtual store is at:             node_modules/.pnpm
Progress: resolved 640, reused 0, downloaded 139, added 8
Progress: resolved 640, reused 0, downloaded 214, added 16
Progress: resolved 640, reused 0, downloaded 328, added 24
Progress: resolved 640, reused 0, downloaded 511, added 43
Progress: resolved 640, reused 0, downloaded 639, added 99
Progress: resolved 640, reused 0, downloaded 640, added 345
Progress: resolved 640, reused 0, downloaded 640, added 640, done
✓ Lockfile passes supply-chain policies (842 entries in 9.5s)
.../esbuild@0.27.3/node_modules/esbuild postinstall$ node install.js
.../node_modules/workerd postinstall$ node install.js
.../esbuild@0.18.20/node_modules/esbuild postinstall$ node install.js
.../esbuild@0.25.12/node_modules/esbuild postinstall$ node install.js
.../esbuild@0.28.0/node_modules/esbuild postinstall$ node install.js
.../esbuild@0.27.3/node_modules/esbuild postinstall: Done
.../esbuild@0.18.20/node_modules/esbuild postinstall: Done
.../node_modules/workerd postinstall: Done
.../esbuild@0.25.12/node_modules/esbuild postinstall: Done
.../node_modules/unrs-resolver postinstall$ napi-postinstall unrs-resolver 1.11.1 check
.../esbuild@0.28.0/node_modules/esbuild postinstall: Done
.../node_modules/unrs-resolver postinstall: Done

dependencies:
+ @base-ui/react 1.7.0
+ @hookform/resolvers 5.7.1
+ @shadcn/react 0.3.0
+ class-variance-authority 0.7.1
+ clsx 2.1.1
+ cmdk 1.1.1
+ date-fns 4.4.0
+ drizzle-orm 0.45.2
+ embla-carousel-react 8.6.0
+ input-otp 1.4.2
+ lucide-react 1.31.0
+ next 16.3.4
+ next-themes 0.4.6
+ radix-ui 1.6.7
+ react 19.2.6
+ react-day-picker 10.0.1
+ react-dom 19.2.6
+ react-hook-form 7.85.0
+ react-resizable-panels 4.12.2
+ recharts 3.8.0
+ sonner 2.0.8
+ tailwind-merge 3.6.0
+ vaul 1.1.2
+ zod 3.25.76

devDependencies:
+ @cloudflare/vite-plugin 1.37.1
+ @cloudflare/workers-types 4.20260515.1
+ @tailwindcss/postcss 4.2.1
+ @types/node 22.19.19
+ @types/react 19.2.14
+ @types/react-dom 19.2.3
+ @vitejs/plugin-react 6.0.2
+ @vitejs/plugin-rsc 0.5.26
+ drizzle-kit 0.31.10
+ eslint 9.39.4
+ eslint-config-next 16.3.4
+ json-rpc-2.0 1.7.1
+ raw-body 3.0.2
+ react-server-dom-webpack 19.2.6
+ tailwindcss 4.2.1
+ tw-animate-css 1.4.0
+ typescript 5.9.3
+ vinext 1.0.0-beta.5
+ vite 8.0.13
+ wrangler 4.92.0

Done in 11.1s using pnpm v11.25.0
```
## 03-account.log
```
Anahtar özeti: 53 karakter, biçim: uygun, not: boşluklar temizlendi

 ⛅️ wrangler 4.92.0
───────────────────
Getting User settings...
👋 You are logged in with an User API Token, associated with the email kooraycoskun@gmail.com.
ℹ️  The API Token is read from the CLOUDFLARE_API_TOKEN environment variable.
┌──────────────────────────────────┬──────────────────────────────────┐
│ Account Name                     │ Account ID                       │
├──────────────────────────────────┼──────────────────────────────────┤
│ Kooraycoskun@gmail.com's Account │ 0a6c54cf57b27b54097f9fe4b6f59923 │
└──────────────────────────────────┴──────────────────────────────────┘
🔓 To see token permissions visit https://dash.cloudflare.com/profile/api-tokens.
```
## 04-d1.log
```
D1 veritabanı: lernkoko-db (bc8bdd18-7628-4727-9fd2-a7d6e96ac054)
```
## 05-build.log
```
[34m[1/5] analyze client references...[39m
[2Ktransforming...✓ 482 modules transformed.
rendering chunks...
[32m✓ built in 2.49s[39m
[34m[2/5] analyze server references...[39m
[2Ktransforming...✓ 333 modules transformed.
rendering chunks...
[32m✓ built in 1.02s[39m
[34m[3/5] build rsc environment...[39m
[2Ktransforming...✓ 479 modules transformed.
rendering chunks...
computing gzip size...
[32m✓ built in 2.15s[39m
[34m[4/5] build client environment...[39m
[2Ktransforming...✓ 2104 modules transformed.
rendering chunks...
computing gzip size...
[33m[33m[PLUGIN_TIMINGS] [0mYour build spent significant time in plugins. Here is a breakdown:
  - vinext:middleware-server-only (34%)
  - vinext:css-data-url (11%)
  - alias (11%)
  - rsc:virtual-client-package (10%)
  - vinext:jsx-in-js (10%)
See https://rolldown.rs/options/checks#plugintimings for more details.
[39m
[32m✓ built in 6.66s[39m
[34m[5/5] build ssr environment...[39m
[2Ktransforming...✓ 339 modules transformed.
rendering chunks...
computing gzip size...
[32m✓ built in 1.73s[39m
[0m
  Route (app)
  ┌ ƒ /                      
  ├ ƒ /a1-2/ausbildung       
  ├ ƒ /a1-2/ausbildung/hoeren
  ├ ƒ /a1-2/ev-ve-yasam      
  ├ λ /api/auth              
  ├ λ /api/study             
  ├ ƒ /ev-esyalar            
  ├ ƒ /fiiller               
  ├ ƒ /giris                 
  ├ ƒ /gizlilik              
  ├ ƒ /hesabim               
  ├ ƒ /impressum             
  ├ ƒ /konular               
  ├ ƒ /kullanim-kosullari    
  ├ ƒ /oyunlar               
  ├ ƒ /sifre-yenile          
  ├ ƒ /uye-ol                
  ├ ƒ /yanlislarim           
  └ ƒ /yonetim               

  λ API  ƒ Dynamic

  Build complete. Run `vinext start` to start the production server.

--- dist/server/wrangler.json (özet) ---
{
 "name": "goligo",
 "main": "index.js",
 "compatibility_date": "2026-05-15",
 "compatibility_flags": [
  "nodejs_compat"
 ],
 "d1_databases": [
  {
   "binding": "DB",
   "database_name": "lernkoko-db",
   "database_id": "bc8bdd18-7628-4727-9fd2-a7d6e96ac054"
  }
 ],
 "vars": {
  "TEAM_DOMAIN": "https://throbbing-bread-1016.cloudflareaccess.com",
  "POLICY_AUD": "3cd3e8e441c3a316e36262af3a1bb856b8e59cfe09100720ad8804701ffde8b0"
 },
 "assets": {
  "directory": "../client"
 }
}
```
## 05-voices.log
```
Site sesleri: 31450 dosya
```
## 06-members.log
```
      "rows_written": 0,
      "total_attempts": 1
    }
  },
  {
    "results": [],
    "success": true,
    "meta": {
      "served_by": "v3-prod",
      "served_by_region": "ENAM",
      "served_by_colo": "ORD",
      "served_by_primary": true,
      "timings": {
        "sql_duration_ms": 0.1972
      },
      "duration": 0.1972,
      "changes": 0,
      "last_row_id": 0,
      "changed_db": false,
      "size_after": 1060864,
      "rows_read": 0,
      "rows_written": 0,
      "total_attempts": 1
    }
  },
  {
    "results": [],
    "success": true,
    "meta": {
      "served_by": "v3-prod",
      "served_by_region": "ENAM",
      "served_by_colo": "ORD",
      "served_by_primary": true,
      "timings": {
        "sql_duration_ms": 0.1549
      },
      "duration": 0.1549,
      "changes": 0,
      "last_row_id": 0,
      "changed_db": false,
      "size_after": 1060864,
      "rows_read": 0,
      "rows_written": 0,
      "total_attempts": 1
    }
  }
]
[
  {
    "results": [
      {
        "name": "auth_attempts"
      },
      {
        "name": "member_sessions"
      },
      {
        "name": "members"
      }
    ],
    "success": true,
    "meta": {
      "served_by": "v3-prod",
      "served_by_region": "ENAM",
      "served_by_colo": "ORD",
      "served_by_primary": true,
      "timings": {
        "sql_duration_ms": 0.2476
      },
      "duration": 0.2476,
      "changes": 0,
      "last_row_id": 0,
      "changed_db": false,
      "size_after": 1060864,
      "rows_read": 29,
      "rows_written": 0,
      "total_attempts": 1
    }
  }
]
```
## 06-schema.log
```
Şema zaten var, dokunulmadı.
```
## 07-deploy.log
```
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼──────────────┤
│ ssr/_next/static/verb-examples.sq-CKz3Akxc.js                                                                                 │ esm  │ 40.48 KiB    │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼──────────────┤
│ ssr/_next/static/verb-examples.ti-C7CCSu8Z.js                                                                                 │ esm  │ 70.20 KiB    │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼──────────────┤
│ ssr/_next/static/verb-examples.tr-DzXsunR6.js                                                                                 │ esm  │ 40.92 KiB    │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼──────────────┤
│ ssr/_next/static/verb-examples.uk-DdzIIitt.js                                                                                 │ esm  │ 63.90 KiB    │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼──────────────┤
│ ssr/_next/static/verb-examples.ur-BjWJA89m.js                                                                                 │ esm  │ 67.29 KiB    │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼──────────────┤
│ ssr/_next/static/verb-examples.vi-Byc88wPX.js                                                                                 │ esm  │ 55.89 KiB    │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼──────────────┤
│ ssr/_next/static/verb-examples.zh-Cjz9sjBR.js                                                                                 │ esm  │ 40.09 KiB    │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼──────────────┤
│ ssr/_next/static/verb-study-bCM4FNhJ.js                                                                                       │ esm  │ 131.85 KiB   │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼──────────────┤
│ ssr/_next/static/vi-DQHPYT_T.js                                                                                               │ esm  │ 130.33 KiB   │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼──────────────┤
│ ssr/_next/static/zh-BJq6Pze3.js                                                                                               │ esm  │ 41.55 KiB    │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼──────────────┤
│ ssr/_next/static/zh-ByOaPezp.js                                                                                               │ esm  │ 111.87 KiB   │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼──────────────┤
│ ssr/index.js                                                                                                                  │ esm  │ 273.64 KiB   │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼──────────────┤
│ ssr/vinext-client-assets.js                                                                                                   │ esm  │ 22.10 KiB    │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼──────────────┤
│ vinext-client-assets.js                                                                                                       │ esm  │ 22.10 KiB    │
├───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┼──────┼──────────────┤
│ Total (223 modules)                                                                                                           │      │ 10922.22 KiB │
└───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────┴──────┴──────────────┘
🌀 Building list of assets...
✨ Read 32336 files from the assets directory /home/runner/work/goligo/goligo/dist/client
🌀 Starting asset upload...
🌀 Found 27 new or modified static assets to upload. Proceeding with upload...
+ /vinext-client-entry-manifest.json
+ /_next/static/chunks/public-language-BCry-Oot.js
+ /_next/static/chunks/site-logo-CuK3T9bX.js
+ /_next/static/chunks/housing-illustrations-jerPbvay.js
+ /_next/static/chunks/ausbildung-hoeren-BkUHf2Nu.js
+ /_next/static/chunks/object-study-D7NDXggH.js
+ /_next/static/chunks/start-wait-C7IfMDRP.js
+ /_next/static/chunks/learning-effects-Cm-_-ydM.js
+ /_next/static/chunks/index-CBth1SSj.js
+ /_next/static/chunks/layout-segment-context-DvYAPeF9.js
+ /_next/static/chunks/app-route-prefetch-policy-eiPULtce.js
+ /_next/static/chunks/ausbildung-progress-pRjEmaB9.js
+ /_next/static/chunks/site-languages-DPEFZdBu.js
+ /_next/static/chunks/housing-copy-qUXYrssA.js
+ /_next/static/chunks/ausbildung-study-kzkN85Vz.js
+ /_next/static/chunks/game-names-BSy_HSuW.js
+ /_next/static/chunks/verb-study-B4mIJTLW.js
+ /_next/static/chunks/progress-ui-DM-oALwf.js
+ /_next/static/chunks/vault-language-preference-_d31c4w_.js
+ /_next/static/chunks/device-language-DqL192Ke.js
+ /_next/static/chunks/course-selector-BDKa3a6z.js
+ /_next/static/chunks/account-panel-Bc4GAx_y.js
+ /_next/static/chunks/category-study-Dhf5kOtz.js
+ /_next/static/chunks/ausbildung-listen-y7iq6QVl.js
+ /_next/static/chunks/housing-study-BD87IFl2.js
+ /_next/static/chunks/toon-art-Dvz4m5Y6.js
+ /_next/static/css/index.EH0Hs9lV.css
Uploaded 9 of 27 assets
Uploaded 18 of 27 assets
Uploaded 27 of 27 assets
✨ Success! Uploaded 27 files (32268 already uploaded) (1.70 sec)

Total Upload: 12143.39 KiB / gzip: 4033.05 KiB
Worker Startup Time: 16 ms
Your Worker has access to the following bindings:
Binding                                                           Resource                  
env.EMAIL (unrestricted)                                          Send Email                
env.DB (lernkoko-db)                                              D1 Database               
env.TEAM_DOMAIN ("https://throbbing-bread-1016.cloudfla...")      Environment Variable      
env.POLICY_AUD ("3cd3e8e441c3a316e36262af3a1bb856b8e59...")       Environment Variable      

Uploaded goligo (13.83 sec)
Deployed goligo triggers (0.68 sec)
  https://goligo.kooraycoskun.workers.dev
Current Version ID: fc2cbe34-a743-4ef6-a52a-5279e6b28d5c
```
## 08-check.log
```
Adres: https://goligo.kooraycoskun.workers.dev
/ -> HTTP 308 https://goliqo.com/
/giris -> HTTP 308 https://goliqo.com/giris
/api/study -> HTTP 308 https://goliqo.com/api/study
/ev-esyalar -> HTTP 308 https://goliqo.com/ev-esyalar
Site adresi: https://goliqo.com
https://goliqo.com/ -> HTTP 200 
https://goliqo.com/giris -> HTTP 200 
https://goliqo.com/ev-esyalar -> HTTP 200 
https://www.goliqo.com/ -> HTTP 301 https://goliqo.com/
```
## 09-old-address.log
```
Eski adres: lernkoko -> https://goliqo.com

 ⛅️ wrangler 4.92.0 (update available 4.152.0)
──────────────────────────────────────────────
Total Upload: 3.44 KiB / gzip: 1.65 KiB
Worker Startup Time: 1 ms
Your Worker has access to the following bindings:
Binding                          Resource                  
env.NEW_ORIGIN ("(hidden)")      Environment Variable      

Uploaded lernkoko (2.19 sec)
Deployed lernkoko triggers (1.23 sec)
  https://lernkoko.kooraycoskun.workers.dev
Current Version ID: 47547539-95aa-40ee-ac42-9a5e8942a0b0
```

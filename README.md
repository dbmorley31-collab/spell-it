# spell-it
A fun spelling game for kids

<!doctype html>
<html lang="en"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="theme-color" content="#FFF1C2">
<title>Spell it!</title>
<link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@500;700&display=swap" rel="stylesheet">
<style>
:root{box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);
--bg:#FFF1C2;--ink:#1B2A49;--panel:#fff;--c1:#E8482B;--c2:#2B7DE9;--c3:#1F9D5B;--c4:#D99A00}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#121C36;--ink:#FFF1C2;--panel:#1F2E52}}
*,*::before,*::after{box-sizing:inherit}
body{margin:0;background:var(--bg);color:var(--ink);font-family:"Fredoka","Trebuchet MS",system-ui,sans-serif;font-weight:500}
main{max-width:480px;margin:0 auto;padding:16px 14px 28px}
h1{font-size:1.9rem;margin:0 0 4px;font-weight:700}
.sub{margin:0 0 14px}
.view{position:relative;aspect-ratio:4/3;border-radius:26px;overflow:hidden;background:linear-gradient(160deg,#3B5FC0,#6C3FB5);border:4px solid var(--ink)}
video{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;display:none}
.emoji{position:absolute;inset:0;display:grid;place-items:center;font-size:6.5rem;text-shadow:0 6px 18px rgba(0,0,0,.35)}
.emoji.pop{animation:pop .4s}
button,select{font:inherit;color:var(--ink)}
button:focus-visible,select:focus-visible{outline:4px solid var(--c2);outline-offset:2px}
.cam{position:absolute;left:10px;bottom:10px;background:var(--panel);border:3px solid var(--ink);border-radius:14px;padding:8px 14px;cursor:pointer}
.snap{display:block;width:100%;margin-top:1
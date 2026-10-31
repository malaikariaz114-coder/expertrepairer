# Repair / maintenance landing pages (Riyadh)
Arabic (RTL, wording "صيانة"):
  /automatic-washing-machine-repair   (automatic-washing-machine-repair.html)
  /fridge-repair                      (fridge-repair.html)
English (LTR, Poppins, wording "repair"):
  /en/washing-machine-repair          (en/washing-machine-repair.html)
  /en/refrigerator-repair             (en/refrigerator-repair.html)
Shared: style.css, en.css (English overrides), images/, vercel.json (clean URLs + redirects).
Phone: edit PHONE_INTL / PHONE_SHOW in the <script> at the bottom of each of the 4 HTML files
(and replace 0500000000 once in each file for the no-JS fallback).
Deploy: push everything to GitHub (keep the folder structure), import in Vercel (Framework: Other).

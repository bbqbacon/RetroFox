# Firefox Era's 2010-2026
a "huge" firefox userchrome guide if you want to theme your firefox like these era's of firefox that we know in love.

For firefox 3 you need https://github.com/OmegaAOL/Firefox-3-Theme-NEW by OmegaAOL <img width="1986" height="1102" alt="Screenshot 2026-10-22 171059" src="https://github.com/user-attachments/assets/19e5a2c0-946f-445b-a553-3ae8ce664314" />
# Firefox-era-s-
if you want the firefox 4-9 you need https://github.com/DiegoSainzPardoLaso/Firefox-Classic-Theme-155-158 by Diego Sainz-Pardo Laso 

<img width="1811" height="1122" alt="Screenshot 2026-10-22 173557" src="https://github.com/user-attachments/assets/ffb7cccc-1a6f-49d3-aeaf-3882373d8a58" />
 

there is currently no Firefox theme for firefox 10-28 echelon dosen't work on modern firefox versions

For the Firefox 29-56 you need https://github.com/QNetITQ/WaveFox by QNetITQ
<img width="1938" height="1161" alt="image" src="https://github.com/user-attachments/assets/fdade261-9eba-431a-9801-fad5758544ee" />

For the Firefox 57-88 you need https://github.com/zapSNH/zapsCoolPhotonTheme by zapSNH <img width="1847" height="1187" alt="image" src="https://github.com/user-attachments/assets/df0531bc-7fce-4b23-a0b5-6397a400768f" />

Firefox 89-157 you need https://github.com/black7375/Firefox-UI-Fix/releases/download/v8.7.6/Lepton.zip by zapSNH
<img width="2001" height="1168" alt="image" src="https://github.com/user-attachments/assets/9016865f-8a47-4c67-a126-7c5779fe7cc4" />
for the New Nova theme (2026) you need to go to "about:config" and and apply browser.nova.enabled
<img width="1891" height="1205" alt="image" src="https://github.com/user-attachments/assets/3293e1c5-bc9a-46a0-97dc-4c5781737649" />

These UserChrome themes aren't my work respect to the developers who put hours into these themes

if you want to replace the new firefox icon do this (zap's Cool Photon Theme does it already) type this into your "UserContent" this


@-moz-document url(about:newtab), url(about:home) { 
/* Changes the logo on the about:home screen */
  .logo {background-image: url("FILENAME.png") !important;
}


if you want the old firefox ring buttons you need to paste this into userchrome

/* --- LIGHT MODE --- */
@media (prefers-color-scheme: light) {
  #back-button .toolbarbutton-icon {
    border: 1px solid #707070 !important;
    background-color: transparent !important;
  }

  #back-button:hover .toolbarbutton-icon {
    border-color: #333333 !important;
    background-color: rgba(0, 0, 0, 0.05) !important;
  }
}

/* --- DARK MODE --- */
@media (prefers-color-scheme: dark) {
  #back-button .toolbarbutton-icon {
    border: 1px solid rgba(255, 255, 255, 0.1) !important;
    background-color: #525252 !important; /* Filled gray circle for dark mode */
  }

  #back-button:hover .toolbarbutton-icon {
    background-color: #636363 !important;
  }
}






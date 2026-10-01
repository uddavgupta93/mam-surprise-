# Mam Birthday Surprise ❤️

A mobile-first cinematic birthday surprise site for GitHub Pages.

## Folder structure
```text
mam-birthday-surprise/
├── index.html
├── README.md
├── photo1.jpg
├── photo2.jpg
├── photo3.jpg
├── photo4.jpg
├── photo5.jpg
├── photo6.jpg
└── love_moments.mp4
```

All assets are in the same folder as `index.html` — no separate images folder.

## Login
Accepted User IDs (case-insensitive): Tuktuk, Uddav, Babu, Sir, Uddav Gupta
Password: `29/02/2024`

## Music
The site uses the official T-Series YouTube video for **Bol Do Na Zara** and requests playback from **00:15** after successful login. Browser autoplay rules can still block playback; if that happens, use the small **Start** control. The YouTube player itself is kept out of the visual design so the page only shows the music status.

## Memory flow
The five memory photos are shown one-by-one. The photo is not clickable. A romantic English + Bangla message types in below each photo, and the user presses **Open the next memory →** to move forward.

## Animated love video
`love_moments.mp4` is a short 15-second silent romantic animation made of three 5-second moments. It plays automatically after the memory sequence while the main song continues.

## Easy future edits
Open `index.html` and edit the `CONFIG` object near the bottom. To add more memories, put the new image beside `index.html` and add its filename to `MEMORY_PHOTOS`. Add matching English/Bangla text in `MEMORY_MESSAGES` if desired.

For GitHub Pages, upload all files to the repository root and enable Pages from the repository's main branch/root folder.

Note: the login is a cute client-side entry lock, not real security. The password is visible in the site's JavaScript.

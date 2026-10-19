# My Live Location Website

## Features
- Browser geolocation permission ke saath apni current location dikhata hai.
- Map marker, accuracy radius, latitude/longitude, speed aur last update.
- Google Maps link aur coordinates copy.
- Location ko kisi backend/server par upload nahi karta.

## Online deploy: GitHub Pages (Android Chrome)
1. GitHub account mein sign in karein: https://github.com
2. `New repository` banayein, naam `my-live-location` rakh sakte hain. Public select karein.
3. Repository mein `Add file` > `Upload files` select karein.
4. `index.html` upload karein aur `Commit changes` dabayein.
5. Repository ke `Settings` > `Pages` mein jaayein.
6. `Build and deployment` mein `Deploy from a branch` select karein.
7. Branch `main` aur folder `/(root)` select karke `Save` karein.
8. Kuch minute baad Pages section mein URL aayega, aam taur par:
   `https://YOUR-GITHUB-USERNAME.github.io/my-live-location/`
   `YOUR-GITHUB-USERNAME` ko apne GitHub username se replace karein. Yeh example hai, live URL tabhi banega jab aap deploy karenge.
9. URL ko Android Chrome mein kholein. Browser site settings mein Location allow karein; phone ki Location/GPS bhi on rakhein.
10. `Live Location Start` dabayein aur permission prompt mein `Allow` chunein.

## Important
- Geolocation ke liye HTTPS (ya localhost) aur user ki explicit browser permission zaroori hai.
- Yeh website sirf us device ki location dikhati hai jismein yeh page khula hai aur permission di gayi hai.
- Yeh incoming caller ki location ya phone number se location nahi nikal sakti.
- Background tracking ke liye page ko khula rakhein; browser/OS background mein updates rok sakte hain.
- Map dikhane ke liye internet connection chahiye.

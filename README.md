# Saryu Sankul Website

This folder is configured and ready for GitHub Pages:

- `index.html` is the public website.
- `user.html` is a second copy of the public website.
- `admin.html` is the admin panel.
- `firebase.rules.json` contains Realtime Database rules.
- `database.seed.json` contains the starter admin login.

Firebase status:

- Project: `saryu-sankul`
- Realtime Database: `https://saryu-sankul-default-rtdb.asia-southeast1.firebasedatabase.app`
- Web Firebase config has been added to `index.html`, `user.html`, and `admin.html`.
- Starter admin login has been added at `/adminCredentials`.
- `firebase.rules.json` contains the suggested public per-node rules if you want to replace Firebase test mode rules.

Admin login:

- Admin ID: `admin`
- Password: `123456`

After login, use `admin.html` to add settings, rooms, banners, gallery, blogs, testimonials, attractions, and manage bookings.

Local preview:

```bash
npm run dev
```

Then open `http://localhost:3006/` for the public site or `http://localhost:3006/admin.html` for the admin panel.

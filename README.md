# Spotify Clone with Next.js, React, Tailwind, Supabase, PostgreSQL, Stripe

![spotify_clone_screenshot](https://github.com/kt946/spotify-clone-nextjs-yt-cwa/assets/103476893/f002144a-bc66-417d-ab3b-3824f3b28560)

## Description

This project was built using a youtube tutorial by [Code With Antonio](https://www.youtube.com/watch?v=2aeMRB8LL4o).

Welcome to the Full Stack Spotify Clone! Developed with Next.js 13.4, React, Tailwind CSS, Supabase, PostgreSQL, and Stripe, this project offers a dynamic Spotify-like experience. Users can register, upload songs to Supabase, and access premium plans via Stripe. With secure authentication, responsive design, and an integrated audio player for seamless music streaming, this application encapsulates the core elements of a modern music platform.

❗❗❗ I do not own the rights to the music used in this project. The music is for demonstration purposes only. In addition, this project is not intended for commercial use.

⭐ Note: The database may become inactive if the app is not used for a while. If this happens, please contact me and I will reactivate the database.

## Table of Contents

- [Installation](#installation)
- [Features](#features)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [Links](#links)
- [License](#license)

## Installation

1. To get started, clone the repository or download the zip file.
2. Install the dependencies by running the following command in the terminal:

```
npm install
```

3. Create a .env file in the root directory and add the following environment variables:

```
NEXT_PUBLIC_SUPABASE_URL
NEXT_PUBLIC_SUPABASE_ANON_KEY
SUPABASE_SERVICE_ROLE_KEY
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY
STRIPE_SECRET_KEY
STRIPE_WEBHOOK_SECRET
```

4. Run the development server by running the following command in the terminal:

```
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

⭐ Note: The project may require some additional configuration to run properly. Please refer to the youtube tutorial for more information.

## Features

This project includes the following features:

- Sleek and responsive user interface using Tailwind CSS
- User login and signup authentication
- GitHub login integration
- Uploading audio files, artist name, song title, and album art.
- Audio player with play, pause, skip, and volume control functionality
- Liked songs and playlists system
- Search functionality
- Supabase storage and authentication
- Stripe integration for subscriptions

⭐ Note: For the Stripe integration, refer to [Stripe's documentation](https://stripe.com/docs/testing) for testing cards.

## Screenshots

![login_screenshot](https://github.com/kt946/spotify-clone-nextjs-yt-cwa/assets/103476893/5a029a45-68b7-40ee-94cc-6ac263bce6c9)

![add_song_screenshot](https://github.com/kt946/spotify-clone-nextjs-yt-cwa/assets/103476893/658cef1e-47f6-44bc-8fbc-47f7d0179350)

![linked_songs_screenshot](https://github.com/kt946/spotify-clone-nextjs-yt-cwa/assets/103476893/82b41117-ca16-44a1-86f2-5cb56b3c6f1a)

![search_screenshot](https://github.com/kt946/spotify-clone-nextjs-yt-cwa/assets/103476893/242f801b-0192-4187-9b07-f3bb24d4b75f)

![account_settings_screenshot](https://github.com/kt946/spotify-clone-nextjs-yt-cwa/assets/103476893/e87e4965-5e7e-4975-8720-1bdfc66f5947)

## Technologies Used

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Supabase](https://supabase.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [Stripe](https://stripe.com/)
- [Vercel](https://vercel.com/)

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request.

## Links

- [Link to deployed application](https://spotify-clone-nextjs-yt-cwa.vercel.app)

- [Link to GitHub repository](https://github.com/kt946/spotify-clone-nextjs-yt-cwa)

- [Link to original GitHub repository by Code With Antonio](https://github.com/antonioerdeljac/next13-spotify)

- [Link to youtube tutorial by Code With Antonio](https://www.youtube.com/watch?v=2aeMRB8LL4o)

## License

This project is licensed under the MIT License.

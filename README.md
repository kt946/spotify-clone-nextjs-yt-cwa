# Spotify Clone with Next.js, React, Tailwind, Supabase, PostgreSQL, Stripe

## Description

This project was built using a youtube tutorial by [Code With Antonio](https://www.youtube.com/watch?v=2aeMRB8LL4o).

This project is a Spotify clone that uses Next.js 13.4, React, Tailwind CSS, Supabase, PostgreSQL, and Stripe. Users can sign up and upload songs to the music platform and subscribe to a premium plan using Stripe. This app also includes user authentication and a responsive user interface.

⭐ I do not own the rights to the music used in this project. The music is for demonstration purposes only. In addition, this project is not intended for commercial use.

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

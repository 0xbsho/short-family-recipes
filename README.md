# Our Recipes — Britt & Brendan

A simple recipe reference site for meal planning and sharing with friends.

## Quick Deploy to Vercel (easiest)

1. Push this folder to a new GitHub repo
2. Go to [vercel.com](https://vercel.com) and sign in with GitHub
3. Click "Add New Project" → Import your repo
4. Vercel auto-detects Vite — just click **Deploy**
5. Done! Share the URL with friends.

## Run Locally

```bash
npm install
npm run dev
```

Opens at `http://localhost:5173`

## Adding New Recipes

Edit `src/RecipeBook.jsx` and add a new object to the `recipes` array:

```js
{
  id: 10,
  name: "Recipe Name",
  source: "Blog Name",
  time: "30 min",
  tags: ["Tag1", "Tag2"],
  url: "https://full-recipe-url.com",
  color: "#E8D5B7",       // warm background fallback color
  accent: "#C4956A",      // text color for initials fallback
  initials: "RN",         // 2-3 letter abbreviation
  image: "https://blog.com/wp-content/uploads/photo.jpg",
},
```

Push to GitHub and Vercel auto-deploys.

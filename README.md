# ParcelApp Dashboard

This is the standalone repository for the ParcelApp Dashboard.

## Setup

1.  **Install Dependencies**
    ```bash
    npm install
    ```

2.  **Environment Variables**
    - Copy `.env.example` to `.env`:
      ```bash
      cp .env.example .env
      ```
    - Fill in your Supabase credentials:
      - `VITE_SUPABASE_URL`
      - `VITE_SUPABASE_ANON_KEY`

3.  **Run Locally**
    ```bash
    npm run dev
    ```

## Deployment (Netlify)

1.  Create a new site on Netlify.
2.  Connect to this repository.
3.  **Build Settings:**
    - **Build Command:** `npm run build`
    - **Publish Directory:** `dist`
4.  **Environment Variables:**
    - Add `VITE_SUPABASE_URL` and `VITE_SUPABASE_ANON_KEY` in Netlify's "Site configuration > Environment variables".
# xamleydiplaintesdashboard

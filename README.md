<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

## Deployment

### Cloudflare Pages

This project is configured for deployment to Cloudflare Pages.

1.  **Build the project**:
    ```bash
    npm run build
    ```

2.  **Deploy using Wrangler**:
    ```bash
    npm run deploy
    ```

3.  **Environment Variables**:
    Ensure you set the following environment variables in the Cloudflare Pages Dashboard (Settings > Functions > Variables):
    - `VITE_SUPABASE_URL`
    - `VITE_SUPABASE_ANON_KEY`
    - `VITE_API_KEY` (Gemini API Key)

The `public/_redirects` file ensures that client-side routing works correctly after deployment.

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/drive/1Zlh5q4Voudh5SA8NAyMW7gjyZO18dYyi

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`

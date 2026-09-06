# FrameMine Mobile — GitHub Pages Edition

## Deploy from iPhone
1. Upload `index.html` and `.nojekyll` to the **root** of your GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select your branch (usually `main`) and folder **/(root)**, then Save.
5. Open the Pages URL GitHub gives you. Do **not** open the HTML from the repository file viewer or the `raw.githubusercontent.com` URL.

The homepage file must remain named `index.html`.

## API note
GitHub Pages is static hosting. It cannot securely store an OpenAI API secret. This mobile build's temporary direct-key mode is intended only for personal testing. For a permanent no-reentry setup, use the companion serverless proxy architecture (for example, a Cloudflare Worker) and store the OpenAI key there as a secret.

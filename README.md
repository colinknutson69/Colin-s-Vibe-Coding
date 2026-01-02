# Metal America - Site-Specific Drawings Calculator

A simple calculator tool for sales reps to calculate the site-specific engineered drawings price (10% of building subtotal).

## Local Testing

To test locally, simply open `index.html` in your web browser.

## Deploy to Railway

### Step 1: Create a Railway Account
1. Go to [railway.app](https://railway.app)
2. Sign up with GitHub (it's free)

### Step 2: Deploy Your App
1. Install Railway CLI (optional, but recommended):
   ```bash
   npm i -g @railway/cli
   ```

2. Login to Railway:
   ```bash
   railway login
   ```

3. Navigate to your project folder:
   ```bash
   cd metal-calculator
   ```

4. Initialize and deploy:
   ```bash
   railway init
   railway up
   ```

5. Get your public URL:
   ```bash
   railway domain
   ```

### Alternative: Deploy via GitHub
1. Push this folder to a GitHub repository
2. Go to [railway.app](https://railway.app)
3. Click "New Project"
4. Select "Deploy from GitHub repo"
5. Choose your repository
6. Railway will automatically detect the Node.js app and deploy it
7. Click "Generate Domain" to get your public URL

### Alternative: Deploy via Railway Dashboard (Simplest)
1. Go to [railway.app](https://railway.app) and log in
2. Click "New Project"
3. Click "Deploy from local"
4. Select the `metal-calculator` folder
5. Railway will deploy automatically
6. Click "Generate Domain" under Settings to get your public URL

That's it! Your calculator will be live at the provided Railway URL.

## How to Use the Calculator
1. Enter the building subtotal (pre-tax price)
2. Select the state from the dropdown
3. Enter a 5-digit zip code
4. Click "Calculate Drawings Price"
5. The tool will show 10% of the subtotal as the site-specific drawings price
6. Add this price as a custom expense in Idearoom or Sensei

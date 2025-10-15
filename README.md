# FLIPino Backend

Flask backend for the FLIPino mobile app - Dance pose analysis using MediaPipe and OpenCV.

## Deployment

This app is configured for deployment on Render.

### Environment Variables Required:
- `SUPABASE_URL`: Your Supabase project URL
- `SUPABASE_KEY`: Your Supabase anon key
- `DATABASE_URL`: PostgreSQL database connection string

### Local Development:
1. Create a virtual environment: `python -m venv venv`
2. Activate: `venv\Scripts\activate` (Windows) or `source venv/bin/activate` (Mac/Linux)
3. Install dependencies: `pip install -r requirements.txt`
4. Create `.env` file with environment variables
5. Run: `python app.py`

### Deployment Steps:
1. Push code to GitHub
2. Create new Web Service on Render
3. Connect GitHub repository
4. Add environment variables
5. Deploy!

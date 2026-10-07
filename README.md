# Multi-Purpose Calculator

A Streamlit app with basic, scientific, financial, plotting, circle and image viewer tools.

## How to run

1. Install dependencies (your `requirements.txt` should list `streamlit`, `numpy`, `matplotlib` and `pillow`):

   ```bash
   pip install -r requirements.txt
   ```

2. Start the app:

   ```bash
   streamlit run app.py
   ```

3. Streamlit will open it in your browser (usually `http://localhost:8501`).

## Running via localtunnel (e.g. from Colab)

If you're running this somewhere without direct browser access (like Colab)
and want a public link, use `requirements_localtunnel.txt` alongside a tunnel:

```bash
pip install -r requirements.txt
pip install -r requirements_localtunnel.txt

streamlit run app.py &
npx localtunnel --port 8501
```

localtunnel will print a public URL you can open in your browser.

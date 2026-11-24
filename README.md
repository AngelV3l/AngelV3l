# Ángel Velázquez Bolívar

Data Scientist and Computer Vision Engineer based in Almería, Spain. Mathematician (BSc, University of Almería, 3rd in my year) with an MSc in Applied Statistics (University of Granada).

At work I build computer vision and time-series models for precision agriculture (YOLO, PyTorch, OpenCV), from raw data to production. That code is private, so what you see here are side projects.

### Currently building
- **Kian** (private repo): an AI assistant that handles email and calendar from Telegram. Python, multi-tenant, Google Calendar sync, voice notes with Whisper and a private knowledge base with RAG. Being tested by a couple of users.

### Open source
- [Merged PR in NVlabs/Eagle](https://github.com/NVlabs/Eagle/pull/52), NVIDIA's vision-language model repo: fallback to SDPA when recent `transformers` versions initialise eager attention, which made the LocateAnything Qwen2 backbone raise `NotImplementedError`. The PR also documents a processor output type mismatch for downstream users.

### Projects
- [World Cup 2026 predictor](https://github.com/AngelV3l/Prediccion-Mundial-2026): Dixon-Coles goal model fitted by maximum likelihood, 10,000 Monte Carlo runs of the 48-team bracket, back-tested against the real 2026 results (Brier ≈ 0.12).
- [IMDb sentiment classifier](https://github.com/AngelV3l/Clasificador_reviews_IMDb): TF-IDF and logistic regression pipeline served with FastAPI and Gradio, with tests and Docker.

### Stack
Python · PyTorch · YOLO · OpenCV · scikit-learn · XGBoost · statsmodels · MLflow · Docker · FastAPI · SQL · R

[LinkedIn](https://www.linkedin.com/in/angelvelazquezbolivar)

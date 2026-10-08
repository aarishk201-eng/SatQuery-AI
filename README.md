# 🌍 SatQuery-AI

**SatQuery-AI** is an advanced Geospatial Intelligence Engine and Satellite Image Query system built using Multi-Agent Reasoning. It enables users to interact with, query, and analyze satellite imagery (like GeoTIFFs) using natural language.

---

## 🚀 Key Features

- **Multi-Agent Reasoning:** Specialized agents for planning, routing, and executing complex geospatial queries.
- **Bi-temporal Change Detection:** Compare satellite images from different time periods to highlight changes.
- **Visual Question Answering (VQA):** Ask natural language questions about land-cover and objects in satellite images.
- **Cross-Modal Fusion:** Combine optical and SAR (Synthetic Aperture Radar) data for comprehensive analysis.
- **FastAPI Backend:** A robust, high-performance API supporting image uploads and validation.

## 🛠️ Technology Stack
- **Backend:** FastAPI, Python, PyTorch (for AI models)
- **Geospatial Processing:** Rasterio
- **Frontend:** Next.js (React)

## 📦 Getting Started

### Prerequisites
- Python 3.10+
- Node.js (for the frontend)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/aarishk201-eng/SatQuery-AI.git
   cd SatQuery-AI
   ```

2. **Backend Setup:**
   ```bash
   cd satquery/backend
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. **Frontend Setup:**
   ```bash
   cd satquery/frontend
   npm install
   ```

### Running the Application

- **Start Backend:**
  ```bash
  cd satquery/backend
  uvicorn main:app --reload
  ```
- **Start Frontend:**
  ```bash
  cd satquery/frontend
  npm run dev
  ```

---
*Developed for Smart India Hackathon (SIH)*

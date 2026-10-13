<p align="center">
  <img src="./assets/banner.png" alt="InsightAI Banner" width="100%" />
</p>

# InsightAI — Intelligent Data Analytics & Preprocessing Studio

> **Transform raw datasets into actionable insights. Clean data with interactive controls and generate rich statistical visualizations with AI guidance.**

---

### 🌐 Live Demo

<p align="center">
  <a href="https://insightai-nine.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/🚀%20Live%20Project-Click%20Here%20to%20Open-5281ee?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo" />
  </a>
</p>

---

## 📌 Overview

**InsightAI** is a full-stack, AI-augmented data analytics workspace built for analysts, researchers, and engineers. It replaces tedious notebook scripts with an intuitive interface where you can:

- 📁 **Upload any CSV** and instantly inspect statistical health signals.
- ⚙️ **Preprocess datasets** through an 11-step pipeline with live preview & rollback.
- 📊 **Generate 7 chart types** via manual controls or natural language prompts.
- 💬 **Ask questions** to an integrated LLM copilot and run queries in a live Pandas console.

---

## 🏗 Architecture & Tech Stack

```mermaid
graph LR
    A["Frontend Client (React 19 + Vite)"] -->|REST API Requests| B["Backend Server (FastAPI + Uvicorn)"]
    B --> C["Data Processing (Pandas + NumPy)"]
    B --> D["LLM Service (OpenRouter / AI Models)"]
    A --> E["Data Visualizations (Recharts + SVG)"]
```


## ✨ Key Features & Modules

## ✨ Features & Capabilities
>>>>>>> 9734792 (docs: streamline and improve README readability)

### 1. 📊 Automated Profiling & Data Stories
- **Instant Health Check:** Automatic row/column counts, missing value heatmaps, duplicates, outlier detection, and data type inference.
- **AI Business Story:** Generates context on what rows represent and likely domain goals without exposing raw data.
- **Column Explorer:** Deep dive into distributions, frequencies, unique values, and single-click column explanations.
- **Correlation Matrix:** Highlights top positive and negative numeric correlations at a glance.

---

### 2. 🛠 11-Step Preprocessing Pipeline
Clean data safely with an isolated working copy, live previews, undo/redo history, and CSV export.

| Category | Operations Supported |
| :--- | :--- |
| **Cleaning** | • **Missing Values:** Impute (mean, median, mode, custom) or drop rows/columns<br>• **Duplicates:** Remove all, keep first, or keep last |
| **Structure** | • **Columns:** Rename, drop, reorder, or duplicate<br>• **Data Types:** Safe cast to String, Int64, Float, DateTime, Boolean, Category |
| **Transforms** | • **Text:** Case conversion, trim whitespace, find & replace<br>• **Numeric:** Min-max normalization, outlier clipping, rounding, binning<br>• **Dates:** Extract Year/Month/Day, custom formatting, day shifting |
| **ML Prep** | • **Encoding:** One-Hot, Label, and Ordinal encoding<br>• **Scaling:** Standard (Z-score), Min-Max, and Robust (IQR) scaling |
| **Controls** | • **Filter & Sort:** Multi-column sorting and conditional filtering<br>• **Audit Trail:** Undo last action, redo, reset to original, and export cleaned CSV |

---

### 3. 📈 Visualization Studio
Create interactive charts with zoom, pan, fullscreen inspection, and multi-format exports (PNG, SVG, PDF, CSV).

- **7 Chart Types:**
  - 📊 **Bar Chart:** Category comparisons with aggregations (`sum`, `mean`, `count`, `min`, `max`)
  - 📈 **Line Chart:** Trends and chronological time-series
  - 🥧 **Pie Chart:** Proportions and composition
  - 🔵 **Scatter Plot:** Bi-variate relationships and clustering
  - 📉 **Histogram:** Bin intervals and distributions
  - 📦 **Box Plot:** Five-number statistical summary (Min, Q1, Median, Q3, Max, IQR)
  - 🌡 **Correlation Heatmap:** Multi-variable correlation grid
- **Dual Creation Modes:**
  - **Builder Mode:** Fine-grained manual control over axes, aggregations, and filters.
  - **Assistant Mode:** Prompt-to-chart AI engine converting plain English requests into charts.
- **Session Persistence:** Built visualizations remain saved as you navigate between tabs.

---

### 4. 🤖 AI Copilot & Pandas Console
- **Analyst Copilot:** LLM assistant grounded in your dataset’s summary to answer queries about trends, anomalies, and insights.
- **Live Pandas Console:** Run arbitrary Pandas expressions (`df.describe()`, `df.groupby()`, etc.) directly on the DataFrame with instantaneous feedback.

---

* **Frontend:**
  * **React 19** & **Vite**
  * **Recharts** (Interactive charting engine)
  * **Axios** (REST API client with environment-aware baseURL)
  * **Neumorphic Glass Design System** (Full-page box components and responsive cards)
* **Backend:**
  * **FastAPI** & **Uvicorn**
  * **Pandas** & **NumPy** (Vectorized data processing and statistical analysis)
  * **Pydantic** (Request and schema validation)
  * **OpenRouter / LLM APIs** (Context-aware natural language processing with deterministic NLP fallbacks)

## 🏗 Architecture & Tech Stack

```mermaid
graph LR
    A["Frontend (React 19 + Vite)"] -->|REST API| B["Backend (FastAPI + Uvicorn)"]
    B --> C["Data Processing (Pandas + NumPy)"]
    B --> D["AI Service (OpenRouter / LLM APIs)"]
    A --> E["Visualizations (Recharts + SVG)"]
```

### 💻 Technologies

- **Frontend:** React 19, Vite, Recharts, Axios, Neumorphic Glass UI
- **Backend:** FastAPI, Uvicorn, Pandas, NumPy, Pydantic
- **AI / LLM:** OpenRouter API with context-aware prompts & NLP fallbacks
>>>>>>> 9734792 (docs: streamline and improve README readability)

---

## 👨‍💻 Project Team

| Student | Roll No | Batch | University | Subject |
| :--- | :--- | :--- | :--- | :--- |
| **Devansh Gupta** | 1240258159 | BCADS-33 | Babu Banarasi Das University | Predictive Analytics |
| **Krishna Verma** | 1240258236 | BCADS-33 | Babu Banarasi Das University | Predictive Analytics |

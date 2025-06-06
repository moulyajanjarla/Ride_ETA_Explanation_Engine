# 🚗 Ride ETA Explanation Engine (LLM + Maps API)

## 📌 Project Overview
This project simulates a system where given an ETA for a ride, the backend generates a natural language explanation like:
- "Traffic on Outer Ring Road due to a festival event in Koramangala."
- "ETA increased because of heavy rainfall in the pickup area."

It enhances user trust by providing transparency into delays and ETA changes using LLMs and event/context data.

---

## 🧠 Key Features

- 🤖 **Contextual Explanation via LLM**: Uses OpenAI/Gemini to explain ETA shifts.
- 🌐 **Maps + Events Integration**: Simulated Google Maps traffic and event data influence the output.
- 🚀 **FastAPI Backend**: API to serve ETA explanations.
- 🧩 **Data Fusion**: Combines weather, events, and traffic metadata for more meaningful insights.

---

## 🛠️ Tech Stack

| Component       | Technology               |
|-----------------|--------------------------|
| Backend         | Python, FastAPI          |
| LLM             | OpenAI GPT / Gemini Pro  |
| Traffic/Events  | Simulated Google Maps API |
| API Layer       | FastAPI                  |
| Context Parser  | Custom logic             |

---

## 🗂️ Project Structure


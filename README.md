# <h1 align="center">🚀 Algo Graph Idi</h1>
<p align="center">
  <strong>AI-Powered Algorithm Visualizer via Telegram Bot</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/n8n-FF6C37?style=for-the-badge&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/Telegram_Bot-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" />
  <img src="https://img.shields.io/badge/GPT--5-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white" />
</p>

---

## 📌 Project Description
Understanding complex algorithms often requires breaking them down into smaller, logical steps. **Algo Graph Idi** is a professional Telegram bot interface that automates this entire process. By simply sending an algorithm's name to the bot, the workflow performs a deep semantic analysis, partitions the logic into **"atomic"** steps, and delivers a high-quality visual flowchart directly to your chat.

---

## 🚀 Key Features

1. **🧠 Advanced Semantic Analysis (GPT-5)**: Algoritmanın sadece adını alarak derinlemesine bir analiz yapar; zaman karmaşıklığını ($O(n)$, $O(\log n)$) ve temel çalışma mantığını (Core Logic) belirler.

2. **🧩 Logical Decomposition & Partitioning**: Karmaşık yapıları (örneğin Dijkstra, QuickSort veya Red-Black Trees) yönetilebilir, "atomik" mantıksal parçalara böler.

3. **🔄 Structured JSON-Driven Pipeline**: AI tarafından üretilen metinsel mantığı, backend sistemlerine entegre edilebilir **Standardized JSON Schema** formatına dönüştürür.

4. **🎨 High-Fidelity Instant Visualization**: Yapılandırılmış veriyi kullanarak algoritmanın adım adım execution flow'unu temsil eden yüksek çözünürlüklü grafikler üretir.

5. **📈 Model-Agnostic Scalability**: Sistem sadece GPT-5'e bağlı değildir; **Claude 3.5 Sonnet** veya **Gemini 1.5 Pro** gibi diğer üst seviye LLM'ler ile entegre olmaya tamamen hazırdır.

---

## ⚙️ How It Works (The Pipeline)

1. **The Telegram Trigger**: Kullanıcı Telegram botuna bir algoritma ismi gönderir (Örn: "Merge Sort").
2. **AI Reasoning & Partitioning**: GPT-5 algoritmayı analiz eder ve onu mantıksal durumlara (states) ayırır.
3. **Data Transformation**: Bir ara node, bu mantıksal parçaları makine tarafından okunabilir bir JSON objesine dönüştürür.
4. **Graph Generation**: Hazırlanan JSON verisi, REST API üzerinden görselleştirme motoruna gönderilir.
5. **Bot Delivery**: Oluşturulan profesyonel grafik, Telegram üzerinden kullanıcıya saniyeler içinde anlık mesaj olarak iletilir.

---

## 🛠 Tech Stack

| Component | Technology |
| :--- | :--- |
| **Interface** | **Telegram Bot API** |
| **Orchestration** | [n8n](https://n8n.io/) |
| **Intelligence Engine** | OpenAI GPT-5 (Current) / **Multi-LLM Ready** |
| **Data Format** | JSON (JavaScript Object Notation) |
| **Communication** | RESTful API Architecture |

---

## 📂 Installation & Usage

1.  **Clone** this repository.
2.  **Import** the `algo-graph-idi.json` file into your **n8n** instance.
3.  **Configure** your Telegram Bot Token and AI Credentials (OpenAI/Claude/Gemini).
4.  **Start the Bot** and send any algorithm name to witness the automation.

---


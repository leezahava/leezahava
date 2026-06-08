# Hi there, I'm a Software Developer! 👋

I am a passionate developer focused on Computer Science, Systems Engineering, and Artificial Intelligence Systems. Currently, I am expanding my horizons by transitioning from high-level application development to low-level systems programming, with a primary focus on mastering Rust. 

My goal is to leverage Rust's memory safety, concurrency model, and performance guarantees to build robust, efficient, and secure software solutions.
🛠️ Tech Stack & Tools

- Languages:
  ![C](https://img.shields.io/badge/c-%2300599C.svg?style=flat&logo=c&logoColor=white)
  ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54)
  ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=flat&logo=openjdk&logoColor=white)
- Currently Mastering:
  ![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=flat&logo=rust&logoColor=white)
- Databases & Tools:
  ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=flat&logo=sqlite&logoColor=white)
  ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white)
  ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=flat&logo=github&logoColor=white)


🚀 Featured Project

🤖 [AI-Powered Smart Calorie Tracker Bot](https://github.com/YOUR_USERNAME/ai-calorie-tracker-bot)
An advanced, asynchronous Telegram bot designed to automate nutrition tracking using computer vision and LLMs. Instead of manually looking up food metrics, users can simply upload a photo of their meal.

*   **Core Technical Highlights:**
    *   **Asynchronous Architecture:** Built using `aiogram v3` and `asyncio` for handling concurrent user requests efficiently.
    *   **AI Integration & Computer Vision:** Integrated Google Gemini Vision API (`gemini-2.5-flash`) with custom structured prompts enforcing JSON-only outputs for multi-dish identification.
    *   **External API Integration:** Embedded barcode scanning functionality by querying the OpenFoodFacts API via `aiohttp` for global product lookup.
    *   **Data Safety & Consistency:** Implemented thread-safe SQLite database interactions utilizing explicit context managers to prevent connection leaks.
    *   **Data Visualization:** Utilized `matplotlib` with non-GUI backends (`Agg`) to dynamically generate and stream weight progress charts into binary memory buffers (`io.BytesIO`).
    *   **Resilience & Rate Limiting:** Applied exponential backoff retry mechanisms (`tenacity`) for external AI API calls and engineered a custom time-based throttling middleware for security.

### 📚 Current Rust Learning Roadmap
*Projects I am currently building to master Rust core concepts:*

- 📥 **Rust CLI Task Manager** — A command-line utility implementing custom argument parsing, strict error handling (`Result`/`Option`), and robust JSON file persistence.
- 🧠 **Rust Algorithms & Core Concepts** — A dedicated playground repository exploring ownership, borrowing, lifetimes, and smart pointers through the implementation of classic data structures, backed by native unit testing.


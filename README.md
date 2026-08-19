<div align="center">

# `>_ Ali Hasnain`
### **AI Engineer | Full-Stack Developer**

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=google-chrome&logoColor=c0f430)](#)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=c0f430)](#)

</div>

---

### `ali-hasnain@portfolio:~$ cat whoami.log`

> Computer Science graduate specializing in Agentic AI, LLM automation, and full-stack systems. Building intelligent workflows that solve real-world problems.

---

### `$ ./stack --list`

| 🧠 **AI & Intelligent Systems** | ⚡ **Full-Stack Development** | 🛠️ **Tools & Ops** |
| :--- | :--- | :--- |
| `>` LLMs & Fine-tuning | `>` React / Next.js | `>` Git Version Control |
| `>` RAG Architectures | `>` Node.js & Express | `>` Docker Containerization |
| `>` Prompt Engineering | `>` Python (FastAPI/Flask) | `>` CI/CD Pipelines |
| `>` Autonomous Agents | `>` MongoDB & PostgreSQL | `>` Jupyter Environments |

---

### `> execute ./run_featured_project.sh`

#### 🏆 **ProctorAI** *(1st Position)*
AI-powered proctoring system for online exam monitoring. Ensures integrity through continuous facial recognition and behavioral analysis.

```python
import cv2
import mediapipe as mp

def analyze_behavior(frame):
    # Initialize pose estimation
    results = pose.process(frame)
    if detect_anomaly(results):
        return "FLAG: SUSPICIOUS_MOVEMENT"
    return "STATUS: NORMAL"

# Meat-Brain-Mentor

## Overview
Meat-Brain-Mentor is an open-source, AI-augmented spaced repetition and skill acquisition platform designed to replace Anki and cybernetically link humans and AI for accelerated learning. It overcomes the flaws of traditional flashcard-based SRS (Spaced Repetition Systems) by integrating sensory-motor predictive models (**saṅkhāra**) into a graph-based knowledge structure.

## Core Goals & Philosophy
- **Eliminate UI Complexity** → Defaults should work for 99% of users, with customization in config files.
- **Remove Plugin Chaos & Versioning Nightmares** → Core features should be built-in, avoiding reliance on third-party plugins that break.
- **Decentralized Learning** → No vendor lock-in, sync across devices without a centralized server.
- **Break Free from the Flashcard Paradigm** → Moves beyond traditional flashcards to **graph-based sensory-motor learning**.
- **AI-Enhanced Learning** → AI dynamically generates questions & adapts difficulty in real-time.

## Core Technology Stack
### **Database Backend (Graph-Based & Open-Source Friendly)**
- **Neo4j / ArangoDB** → Suited for graph-based knowledge storage and sensory-motor modeling.
- **PostgreSQL** → If structured relational data is needed alongside graph-based storage.

### **Backend API (Web-Based & AI-Ready)**
- **FastAPI (Python)** → Minimal, high-performance API for AI integrations.
- **Docker** → For modular, portable deployments.
- **WebSockets** → Enables real-time updates between clients.

### **Frontend (Minimalist, Web-Based, & Device-Agnostic)**
- **TypeScript + React / Next.js** → Intuitive UI with a web-first approach.
- **Tailwind CSS** → Clean, fast styling with minimal complexity.
- **Tauri / Flutter (Optional)** → Native desktop or mobile clients (if needed).

## Planned Features & Roadmap
📌 **Phase 1: MVP (Minimum Viable Product)**
✅ Basic graph-based SRS (flashcard alternative).  
✅ Web-based UI with API backend.  
✅ AI-generated questions & answers.  
✅ Docker-based self-hosting.  

📌 **Phase 2: Advanced Learning Features**
✅ Multi-modal learning (lists, diagrams, images, videos, etc.).  
✅ AI-powered difficulty adjustment.  
✅ Seamless sync across devices.  

📌 **Phase 3: Cybernetic AI-Human Learning**
✅ AI mentors users in real-time via adaptive questioning.  
✅ Users can collaboratively build & refine **Knowledge Graphs**.  
✅ Multi-AI integration (LLMs, speech synthesis, real-time feedback).  

## Installation
Clone the repository and install dependencies:
```bash
git clone git@github.com:alexryan/MeatMentor-AI.git
cd MeatMentor-AI
python -m venv venv
source venv/bin/activate  # On Windows: venv\\Scripts\\activate
pip install -r requirements.txt
```

## Usage
Run the application:
```bash
python main.py
```

## Contributing
We welcome contributions! Follow these steps:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-branch`).
3. Commit changes (`git commit -m "Add new feature"`).
4. Push to your branch (`git push origin feature-branch`).
5. Submit a pull request.

## License
This project is licensed under the **MIT License**. See the `LICENSE` file for details.

## Contact
For questions, suggestions, or collaborations, visit the [MeatMentor AI GitHub Repo](https://github.com/alexryan/MeatMentor-AI) or open an issue.

## Tagline Options
- *"MeatMentor AI: Slow. Forgetful. Still Smarter Than You."*
- *"MeatMentor AI: Because flashcards are for losers."*
- *"MeatMentor AI: Mentoring Meat-Brains Since 2024."*

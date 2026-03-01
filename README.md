# AI Video Call

Just a small experiment I built — a website where you can talk to an AI through your webcam
It sends frames from your camera to a local AI model (Ollama + LLaVA) and it describes what it sees

Kinda like if your computer had eyes


#What it does

- You open the page
- Click "Start Camera"
- Every 5 seconds it sends a frame to the AI
- The AI replies with what it sees


# Why I built this

I've been learning Python and wanted to try something with real time video + AI
Also I just think it's cool to have your own Jarvis that actually sees stuff


# How to run it yourself

1. Install [Ollama](https://ollama.com) if you don't have it
2. Pull the vision model:
   ollama pull llava:7b
 
4. Install dependencies: pip install fastapi uvicorn ollama pillow

   
5. And run the server: uvicorn main:app --reload --host 0.0.0.0

---

Built by [blghhhy](https://github.com/blghhhy)

# License

MIT

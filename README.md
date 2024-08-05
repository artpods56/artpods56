```shell
artpods56@pc:~$ git clone https://github.com/artpods56/artpods56

Cloning into 'artpods56'...
remote: Enumerating objects: 21, done.
remote: Counting objects: 100% (21/21), done.
remote: Compressing objects: 100% (16/16), done.
remote: Total 21 (delta 4), reused 6 (delta 0), pack-reused 0
Receiving objects: 100% (21/21), 8.87 KiB | 2.22 MiB/s, done.
Resolving deltas: 100% (4/4), done.

artpods56@pc:~$ python3
```
```python
Python 3.12.3 (main, Jul 31 2024, 17:43:48) [GCC 13.2.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import json
>>> data = json.loads(open('/artpods56/about.json').read())
>>> print(json.dumps(data, indent=4))
```

```json
{
    "full_name": "Artur Podsiad\u0142y",
    "country": "Poland",
    "contact": {
        "email": "artpods56@gmail.com",
        "linkedin": "https://www.linkedin.com/in/artpods56/"
    },
    "summary": "I'm really fascinated by the world of artificial intelligence, especially the ability of machines to understand and process human language. That's why LLMs and intelligent systems are my main area of interest and something that I strive to explore. Here, you'll find some of the projects I built along the way.",
    "education": [
        {
            "institution": "The John Paul II Catholic University of Lublin",
            "bachelor": "Artificial Intelligence",
            "years": "2022-2025"
        },
        {
            "institution": "Power Engineering School Complex named after Prof. Kazimierz Drewnowski in Lublin",
            "specialization": "IT Technician",
            "years": "2017-2021",
            "certifications": [
                {
                    "name": "Technical certificate EE.09",
                    "covers": "Programming, development and administration of websites and databases."
                },
                {
                    "name": "Technical certificate EE.08",
                    "covers": "Installation and operation of computer systems, equipment peripherals and networks."
                },
                {
                    "name": "Cisco Networking Academy - IT Essentials",
                    "covers": "Certificate for theoretical and practical professional skills."
                }
            ]
        }
    ],
    "experience": [
        {
            "position": "IT Lead / Web Design and Development",
            "company": "TEDxLublin",
            "location": "Lublin",
            "duration": "March 2024 - Present",
            "responsibilities": [
                "Designed and developed a fully functional and responsive website using Docker, Django, and Bootstrap and Umami for analytics.",
                "Managed the website production launch and ensured compliance with TED guidelines.",
                "Ensured the website met user needs and business objectives through continuous feedback and iteration."
            ]
        },
        {
            "position": "AI R&D / Software Development",
            "company": "The John Paul II Catholic University of Lublin",
            "location": "Lublin",
            "duration": "Sep 2022 - Feb 2023",
            "responsibilities": [
                "Experimented with various methods to develop an AI assistant/chatbot.",
                "Conducted research and development on natural language processing (NLP) techniques and RAG architecture.",
                "Analyzed and evaluated the effectiveness of different AI models and approaches."
            ]
        }
    ],
    "skills": {
        "programming_languages": [
            "Python",
            "JavaScript",
            "R (basics)"
        ],
        "ai": {
            "general": [
                "Numpy", "Pandas", "Matplotlib", "SciPy", "scikit-learn"
            ],
            "deep_learning": [
                "Keras", "PyTorch (basics)", "TensorFlow (basics)"
            ],
            "computer_vision": [
                "Pillow", "OpenCV"
            ],
            "llm | nlp": [
                "Transformers", "Spacy", "OpenAI API", "Anthropic API", "Groq API"
            ],
            "visualization": [
                "Matplotlib", "Gradio"
            ]
        },
        "web_development": [
            "Django", "FastAPI", "HTML", "CSS", "JavaScript", "Bootstrap"
        ],
        "databases": [
            "PostgreSQL", "Neo4j"
        ],
        "tools": [
            "Git", "OpenAI", "Groq", "HuggingFace", "RegEx", "Copilot", "LM Studio", "Roboflow", "Protégé", "LaTeX", "Docker", "Deepnote", "Postman", "Bootstrap Studio"
        ]
    },
    "projects": [
        {
            "name": "TEDxLublin Website",
            "description": "A website I created from scratch for the TEDxLublin event that took place in 2024",
            "technologies": [
                "Docker", "Django", "Bootstrap5", "NGINX", "Umami"
            ]
        },
        {
            "name": "AttireKeeper",
            "description": "An inventory management web app I created for myself, specifically to be more productive and to utilize some AI tools I found useful and interesting. The app features all necessary CRUD operations and tools like item templates, background removal and image augmentation.",
            "technologies": [
                "Docker", "Django", "HTML", "JavaScript", "Ajax", "Bootstrap5", "PostgreSQL", "FastAPI", "Pytorch", "CUDA Toolkit"
            ]
        }
    ],
    "languages": [
        {
            "language": "Polish",
            "proficiency": "Native"
        },
        {
            "language": "English",
            "proficiency": "B2+"
        }
    ]
}
```

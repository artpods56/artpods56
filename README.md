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
>>> print(json.dumps(data, indent=2))
```

```json
{
  "personal_info": {
    "name": "Artur Podsiad\u0142y",
    "email": "artpods56@gmail.com",
    "linkedin": "linkedin.com/in/artpods56",
    "github": "github.com/artpods56",
    "last_updated": "20th September 2025"
  },
  "objective": [
    "Passionate about artificial intelligence with a strong focus on MLOps/LLMOps and RAG systems.",
    "Specialized in designing and implementing end-to-end ML pipelines, automating deployment processes, and integrating LLM solutions in production environments.",
    "Experienced in building intelligent systems that bridge the gap between research and real-world applications."
  ],
  "education": [
    {
      "institution": "THE JOHN PAUL II CATHOLIC UNIVERSITY OF LUBLIN",
      "degree": "BACHELOR OF ARTIFICIAL INTELLIGENCE",
      "thesis": "EVOLUTION OF RAG (RETRIEVAL-AUGMENTED GENERATION) SYSTEMS",
      "dates": "Oct 2022 | June 2025 | Graduated"
    },
    {
      "institution": "POWER ENGINEERING SCHOOL COMPLEX NAMED AFTER PROF. KAZIMIERZ DREWNOWSKI IN LUBLIN",
      "specialization": "IT TECHNICIAN SPECIALIZATION",
      "certifications": [
        "Technical certificate EE.09",
        "Technical certificate EE.08",
        "Cisco Networking Academy - IT Essentials"
      ],
      "dates": "2017 | 2021"
    }
  ],
  "certifications": [
    "Technical certificate EE.09",
    "Technical certificate EE.08",
    "Cisco Networking Academy - IT Essentials"
  ],
  "coursework": [
    "Fundamentals of Machine Learning",
    "Deep Neural Networks in Data Processing",
    "Natural Language Processing",
    "Deep Neural Networks in Computer Vision"
  ],
  "skills": {
    "development": [
      "Python (SOLID, Clean Code, TDD)",
      "FastAPI",
      "Django",
      "Docker",
      "Git",
      "PostgreSQL"
    ],
    "data_ai": [
      "HuggingFace Transformers | Models | Datasets",
      "PyTorch",
      "MCP",
      "Semantic Kernel",
      "LangGraph",
      "RAG",
      "Vision LLMs",
      "DSPy"
    ],
    "ops_deployment": [
      "llama.cpp",
      "Dagster",
      "Label Studio",
      "MinIO",
      "Weights & Biases",
      "OpenRouter",
      "Hydra"
    ]
  },
  "projects": [
    {
      "name": "ML PLAYGROUND",
      "description": "INTERACTIVE MACHINE LEARNING PLATFORM THAT ALLOWS USERS TO EXPERIMENT WITH VARIOUS ALGORITHMS THROUGH A WEB INTERFACE."
    },
    {
      "name": "ALPHABETALOGIC",
      "description": "A PYTHON LIBRARY FOR PARSING AND ANALYZING FIRST-ORDER LOGIC EXPRESSIONS USING THE PLY (PYTHON LEX-YACC) LIBRARY."
    }
  ],
  "experience": [
    {
      "position": "SOLUTION ARCHITECT | MLOPS/LLMOPS ENGINEER",
      "company": "",
      "location": "Lublin",
      "dates": "March 2025 - August 2025",
      "achievements": [
        "Designed and built end-to-end ML pipelines for automated information extraction from historical schematisms using LayoutLMv3 and vision LLMs.",
        "The system achieved over 90% accuracy in extracting structured data from complex document layouts and is being prepared for production deployment.",
        "Configured production-ready annotation platform with Docker, Label Studio, and MinIO, applying MLOps best practices including model versioning and experiment tracking."
      ]
    },
    {
      "position": "IT / WEB DESIGN AND DEVELOPMENT",
      "company": "TEDXLUBLIN",
      "location": "Lublin",
      "dates": "March 2024 - Present",
      "achievements": [
        "Designed and developed the official TEDxLublin website that enabled seamless event management and allowed the organization focus on delivering a great experience for attendees.",
        "Integrated forms for volunteers, speakers, and partners with real-time Airtable synchronization and newsletter subscription.",
        "Integrated Umami for privacy-focused web analytics, ensuring GDPR compliance and data security."
      ]
    },
    {
      "position": "AI R&D / SOFTWARE DEVELOPMENT",
      "company": "THE JOHN PAUL II CATHOLIC UNIVERSITY OF LUBLIN",
      "location": "Lublin",
      "dates": "September 2022 - February 2023",
      "achievements": [
        "Conducted research and development on natural language processing techniques and RAG architecture for AI assistant/chatbot development in academic environment.",
        "Analyzed and evaluated the effectiveness of different AI models and approaches."
      ]
    }
  ]
}
>>> 
```

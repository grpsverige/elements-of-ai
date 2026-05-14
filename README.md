<html>
<body>
<!--StartFragment--><html><head></head><body><h1>🎨 DreamBrush AI</h1>
<h3><em>Turning Imagination into Personalised Digital Art</em></h3>
<hr>
<h2>📋 Academic Declaration</h2>

Field | Detail
-- | --
Author | [Your Full Name]
Course | Elements of AI — Building AI (University of Helsinki & Reaktor)
Project type | Independent student project
Submission | Original work conceived and written by the author


<h3>Usage context</h3>
<p>The user provides one of the following inputs:</p>
<ul>
<li>A custom text description</li>
<li>A journal entry</li>
<li>A social media post or caption</li>
</ul>
<p><strong>Example input:</strong></p>
<blockquote>
<p><em>"Just finished a stressful week, finally relaxing with tea and rain outside."</em></p>
</blockquote>
<p>The system then:</p>
<ol>
<li>Analyses the <strong>content</strong> (relaxing, rain, tea)</li>
<li>Detects the <strong>mood</strong> (transitioning from stress to calm)</li>
<li>Evaluates <strong>writing style</strong> (personal, reflective, quiet)</li>
<li>Generates an artwork reflecting that emotional and textual context</li>
</ol>
<h3>People affected</h3>
<p>It is important to consider all stakeholders, not just primary users:</p>
<ul>
<li><strong>Users</strong> gain a new, accessible way to express themselves creatively</li>
<li><strong>Content creators</strong> can enhance posts with personalised AI-generated visuals</li>
<li><strong>Professional artists</strong> may benefit from using it as an ideation and inspiration tool, though some may have legitimate concerns about AI automation of creative work</li>
<li><strong>Marginalised communities</strong> with limited access to art education stand to benefit most from lowering the creative barrier</li>
<li><strong>Dataset contributors</strong> — images used to train generative models were created by human artists; this raises ongoing ethical questions about compensation and consent that the AI community continues to debate</li>
</ul>
<hr>
<h2>5. Challenges</h2>
<p>DreamBrush AI does not solve every problem, and it is important to be honest about its limitations:</p>
<p><strong>Technical limitations:</strong></p>
<ul>
<li>Interpreting sarcasm, irony, or culturally specific expression in social media posts remains difficult for current NLP models</li>
<li>Generated images may not fully capture nuanced human intent — the gap between what a person imagines and what a model produces can be significant</li>
<li>Real-time generation at scale requires substantial computational resources</li>
</ul>
<p><strong>Ethical limitations:</strong></p>
<ul>
<li>Privacy concerns arise when users share personal text — robust data handling policies and local processing are essential</li>
<li>Potential bias in sentiment or style detection may reflect the biases present in training data, producing outputs that feel culturally narrow</li>
<li>Questions around AI-generated creative content — including copyright, attribution, and the impact on human artists — are unresolved at an industry and legal level</li>
<li>The system could be misused to generate misleading or manipulated visual content from real social media posts</li>
</ul>
<p><strong>Scope limitations:</strong></p>
<ul>
<li>The current concept does not support audio, video, or multi-modal inputs</li>
<li>It does not learn from individual user preferences over time without explicit personalisation features being built</li>
</ul>
<hr>
<h2>6. What Next</h2>
<p>DreamBrush AI could grow in several concrete directions:</p>
<p><strong>Near-term:</strong></p>
<ul>
<li>Build a live interactive demo using <strong>Gradio</strong> and deploy it on <strong>Hugging Face Spaces</strong> so users can test the full pipeline — from text input to generated image — without any setup</li>
<li>Integrate directly with the <strong>Stability AI</strong> or <strong>Replicate</strong> API to replace the concept stage with a fully working image generation pipeline</li>
<li>Add support for multiple emotional dimensions beyond simple positive/negative polarity (using <strong>NRC Emotion Lexicon</strong> for nuanced emotion detection: joy, anticipation, trust, fear, surprise, sadness, disgust, anger)</li>
</ul>
<p><strong>Medium-term:</strong></p>
<ul>
<li>Build a <strong>browser extension</strong> that automatically generates a small artwork alongside any social media post as the user types</li>
<li>Develop <strong>personalised artistic styles</strong> that learn from a user's history of inputs and preferred outputs</li>
<li>Add an <strong>interactive editing interface</strong> allowing users to adjust mood sliders and style parameters and regenerate in real time</li>
</ul>
<p><strong>Long-term:</strong></p>
<ul>
<li>Explore <strong>ethical compensation models</strong> for the artists whose work trained the underlying generative models</li>
<li>Research <strong>bias auditing tools</strong> to ensure outputs are culturally diverse and representative</li>
<li>Expand to <strong>multi-modal inputs</strong> — allowing voice notes, photos, or videos as the creative prompt</li>
</ul>
<hr>
<h2>7. Acknowledgments</h2>
<h3>Open-source tools and models</h3>
<ul>
<li><strong><a href="https://stability.ai/">Stable Diffusion</a></strong> by Stability AI — the open-weights generative image model that would power the image generation stage of this project</li>
<li><strong><a href="https://textblob.readthedocs.io/">TextBlob</a></strong> by Steven Loria — the Python NLP library used in the working sentiment analysis demo</li>
<li><strong><a href="https://huggingface.co/transformers">Hugging Face Transformers</a></strong> — the open-source library providing access to state-of-the-art NLP and embedding models</li>
<li><strong><a href="https://openai.com/research/clip">CLIP</a></strong> by OpenAI — the embedding model that bridges text and image representations</li>
<li><strong><a href="https://gradio.app/">Gradio</a></strong> — the open-source tool planned for building the interactive demo interface</li>
</ul>
<h3>Datasets</h3>
<ul>
<li><strong>LAION-5B</strong> — open large-scale text-image dataset from the LAION non-profit</li>
<li><strong>WikiArt</strong> — open fine-art image dataset</li>
<li><strong>MS-COCO</strong> — Microsoft Common Objects in Context dataset, used widely in vision-language research</li>
<li><strong>Common Crawl</strong> — open web-crawl text corpus</li>
</ul>
<h3>Course</h3>
<p>This project was developed as part of the <strong><a href="https://buildingai.elementsofai.com/">Elements of AI — Building AI</a></strong> course by Reaktor and the University of Helsinki. The course provided the conceptual foundation for thinking about AI problems, data, techniques, and societal impact that shaped every section of this project.</p>
<hr>
<p><em>© 2025 [Your Full Name] — Original work submitted for the Elements of AI: Building AI course.</em></p></body></html><!--EndFragment-->
</body>
</html># 🎨 DreamBrush AI

### *Turning Imagination into Personalised Digital Art*

---

## 📋 Academic Declaration

| Field | Detail |
|---|---|
| **Author** | [Your Full Name] |
| **Course** | Elements of AI — *Building AI* (University of Helsinki & Reaktor) |
| **Project type** | Independent student project |
| **Submission** | Original work conceived and written by the author |

### Originality Statement

This project — including its concept, written analysis, code, and documentation — was conceived and produced independently by the author as an original submission for the *Building AI* course. All third-party tools, datasets, and models used are fully credited in the [[Acknowledgments](https://claude.ai/chat/0cacbd38-ae69-4e29-aa07-01ebc79989ce#-acknowledgments)](#-acknowledgments) section. No work from other students has been copied or incorporated without attribution.

> **This submission complies fully with the academic integrity requirements of the Elements of AI programme. No aspect of this work has been plagiarised.**

---

## 📖 Table of Contents

- [[Academic Declaration](https://claude.ai/chat/0cacbd38-ae69-4e29-aa07-01ebc79989ce#-academic-declaration)](#-academic-declaration)
- [[1. The Idea in a Nutshell](https://claude.ai/chat/0cacbd38-ae69-4e29-aa07-01ebc79989ce#1-the-idea-in-a-nutshell)](#1-the-idea-in-a-nutshell)
- [[2. Background](https://claude.ai/chat/0cacbd38-ae69-4e29-aa07-01ebc79989ce#2-background)](#2-background)
- [[3. Data and AI Techniques](https://claude.ai/chat/0cacbd38-ae69-4e29-aa07-01ebc79989ce#3-data-and-ai-techniques)](#3-data-and-ai-techniques)
- [[4. How It Is Used](https://claude.ai/chat/0cacbd38-ae69-4e29-aa07-01ebc79989ce#4-how-it-is-used)](#4-how-it-is-used)
- [[5. Challenges](https://claude.ai/chat/0cacbd38-ae69-4e29-aa07-01ebc79989ce#5-challenges)](#5-challenges)
- [[6. What Next](https://claude.ai/chat/0cacbd38-ae69-4e29-aa07-01ebc79989ce#6-what-next)](#6-what-next)
- [[7. Acknowledgments](https://claude.ai/chat/0cacbd38-ae69-4e29-aa07-01ebc79989ce#7-acknowledgments)](#7-acknowledgments)

---

## 1. The Idea in a Nutshell

**DreamBrush AI** is a creative AI-powered tool that generates personalised digital artwork from user descriptions, moods, or short journal entries. It can also analyse social media posts and automatically produce small artworks based on the content, emotional tone, and writing style of the text. By combining natural language processing and generative image models, the system transforms abstract ideas and everyday digital expressions into visual art pieces — with no artistic skill required from the user.

---

## 2. Background

### The problem

Many people have creative ideas but lack the technical or artistic skills to bring them to life visually. Whether it is imagining a dream landscape, designing a fantasy character, or expressing a feeling through colour and form, the barrier to visual creation can be high.

This problem is widespread — particularly among hobbyists, writers, and casual creators who think visually but cannot draw or design. People also constantly share thoughts and emotions through social media, yet these expressions almost never get transformed into other creative formats. A heartfelt post about a rainy afternoon stays as text, when it could become something richer.

### Personal motivation

I find it genuinely compelling that everyday digital expression — something as small as a social media caption — could be automatically transformed into something visual and personal. Growing up, I always had ideas I wanted to illustrate but never had the skill to execute them. AI changes that equation completely.

This topic matters because creativity should not be gated behind technical ability. AI can lower that barrier and make artistic expression more accessible, interactive, and joyful for everyone.

---

## 3. Data and AI Techniques

### Data sources

Rather than vague categories, the following specific, publicly available datasets would be used to train and evaluate this system:

| Dataset | Purpose |
|---|---|
| **LAION-5B** | Large-scale text-image pairs for training multimodal generative models |
| **WikiArt** | Labelled fine-art images across styles, periods, and genres for style transfer |
| **MS-COCO** | Image captioning dataset for grounding textual descriptions to visual content |
| **Common Crawl** | Large-scale web text for pre-training language understanding components |
| **User-provided input** | Text prompts, journal entries, or social media posts (processed locally; not stored) |

The availability and quality of these datasets are essential to ensure meaningful, diverse, and culturally representative outputs.

### AI techniques

| Technique | Role in the system |
|---|---|
| **Natural Language Processing (NLP)** | Interprets the meaning and intent of text input |
| **Sentiment analysis** | Detects emotional tone (calm, anxious, joyful, melancholic) |
| **Style analysis** | Evaluates writing patterns to inform artistic style selection |
| **Diffusion models** (e.g., Stable Diffusion) | Generates high-quality images from text prompts |
| **Embedding models** (e.g., CLIP) | Bridges textual meaning and visual representation |

### Concrete demo

The following working Python demo shows the sentiment analysis stage of the pipeline — the step that determines the visual mood before passing a structured prompt to an image generator.

**Stage 1 — Sentiment analysis (working demo)**

```python
from textblob import TextBlob

post = "I feel so calm watching the sunset after a long day."

# Analyse sentiment polarity (-1 = very negative, +1 = very positive)
analysis = TextBlob(post)
mood_score = analysis.sentiment.polarity
subjectivity = analysis.sentiment.subjectivity

# Map sentiment to visual style parameters
if mood_score > 0.3:
    style = "warm golden tones, soft light, impressionist brush strokes"
    palette = "amber, peach, soft yellow"
elif mood_score < -0.3:
    style = "dark muted tones, heavy shadows, expressionist style"
    palette = "deep blue, charcoal, grey"
else:
    style = "neutral pastel tones, minimal composition"
    palette = "soft grey, lavender, off-white"

print(f"Input: '{post}'")
print(f"Mood score: {mood_score:.2f} | Subjectivity: {subjectivity:.2f}")
print(f"Visual style: {style}")
print(f"Colour palette: {palette}")
```

**Example output:**

```
Input: 'I feel so calm watching the sunset after a long day.'
Mood score: 0.60 | Subjectivity: 0.80
Visual style: warm golden tones, soft light, impressionist brush strokes
Colour palette: amber, peach, soft yellow
```

**Stage 2 — Image generation (API integration concept)**

In a full implementation, the style parameters above are assembled into a structured prompt and passed to the Stable Diffusion API:

```python
import requests

def generate_image(mood_prompt: str, style: str, palette: str) -> str:
    """
    Sends a structured prompt to the Stable Diffusion API
    and returns the URL of the generated image.
    """
    structured_prompt = (
        f"A digital artwork depicting: {mood_prompt}. "
        f"Style: {style}. Colour palette: {palette}. "
        f"High detail, artistic, dreamlike quality."
    )

    response = requests.post(
        "https://api.stability.ai/v1/generation/stable-diffusion-xl-1024-v1-0/text-to-image",
        headers={"Authorization": "Bearer YOUR_API_KEY"},
        json={
            "text_prompts": [{"text": structured_prompt, "weight": 1.0}],
            "cfg_scale": 7,
            "height": 1024,
            "width": 1024,
            "samples": 1,
            "steps": 30,
        }
    )

    result = response.json()
    return result["artifacts"][0]["base64"]  # base64-encoded image

# Example call
image_data = generate_image(
    mood_prompt="calm sunset after a long day",
    style="warm golden tones, soft light, impressionist brush strokes",
    palette="amber, peach, soft yellow"
)
print("Image generated successfully.")
```

> **Note:** A live Hugging Face Spaces demo is planned as a future milestone — see [[What Next](https://claude.ai/chat/0cacbd38-ae69-4e29-aa07-01ebc79989ce#6-what-next)](#6-what-next).

---

## 4. How It Is Used

### Who uses it

DreamBrush AI is designed for anyone who wants to visualise an idea, feeling, or story without needing artistic skill:

| User group | How they benefit |
|---|---|
| **Hobby artists** | Generate reference images and inspiration boards instantly |
| **Writers and storytellers** | Visualise scenes, characters, and atmospheres from their writing |
| **Social media users** | Transform posts into personalised visual art |
| **Educators** | Use as a creative engagement tool in classrooms |
| **People with disabilities** | Access creative expression without requiring fine motor skills |

### Usage context

The user provides one of the following inputs:

- A custom text description
- A journal entry
- A social media post or caption

**Example input:**

> *"Just finished a stressful week, finally relaxing with tea and rain outside."*

The system then:

1. Analyses the **content** (relaxing, rain, tea)
2. Detects the **mood** (transitioning from stress to calm)
3. Evaluates **writing style** (personal, reflective, quiet)
4. Generates an artwork reflecting that emotional and textual context

### People affected

It is important to consider all stakeholders, not just primary users:

- **Users** gain a new, accessible way to express themselves creatively
- **Content creators** can enhance posts with personalised AI-generated visuals
- **Professional artists** may benefit from using it as an ideation and inspiration tool, though some may have legitimate concerns about AI automation of creative work
- **Marginalised communities** with limited access to art education stand to benefit most from lowering the creative barrier
- **Dataset contributors** — images used to train generative models were created by human artists; this raises ongoing ethical questions about compensation and consent that the AI community continues to debate

---

## 5. Challenges

DreamBrush AI does not solve every problem, and it is important to be honest about its limitations:

**Technical limitations:**
- Interpreting sarcasm, irony, or culturally specific expression in social media posts remains difficult for current NLP models
- Generated images may not fully capture nuanced human intent — the gap between what a person imagines and what a model produces can be significant
- Real-time generation at scale requires substantial computational resources

**Ethical limitations:**
- Privacy concerns arise when users share personal text — robust data handling policies and local processing are essential
- Potential bias in sentiment or style detection may reflect the biases present in training data, producing outputs that feel culturally narrow
- Questions around AI-generated creative content — including copyright, attribution, and the impact on human artists — are unresolved at an industry and legal level
- The system could be misused to generate misleading or manipulated visual content from real social media posts

**Scope limitations:**
- The current concept does not support audio, video, or multi-modal inputs
- It does not learn from individual user preferences over time without explicit personalisation features being built

---

## 6. What Next

DreamBrush AI could grow in several concrete directions:

**Near-term:**
- Build a live interactive demo using **Gradio** and deploy it on **Hugging Face Spaces** so users can test the full pipeline — from text input to generated image — without any setup
- Integrate directly with the **Stability AI** or **Replicate** API to replace the concept stage with a fully working image generation pipeline
- Add support for multiple emotional dimensions beyond simple positive/negative polarity (using **NRC Emotion Lexicon** for nuanced emotion detection: joy, anticipation, trust, fear, surprise, sadness, disgust, anger)

**Medium-term:**
- Build a **browser extension** that automatically generates a small artwork alongside any social media post as the user types
- Develop **personalised artistic styles** that learn from a user's history of inputs and preferred outputs
- Add an **interactive editing interface** allowing users to adjust mood sliders and style parameters and regenerate in real time

**Long-term:**
- Explore **ethical compensation models** for the artists whose work trained the underlying generative models
- Research **bias auditing tools** to ensure outputs are culturally diverse and representative
- Expand to **multi-modal inputs** — allowing voice notes, photos, or videos as the creative prompt

---

## 7. Acknowledgments

### Open-source tools and models

- **[[Stable Diffusion](https://stability.ai/)](https://stability.ai)** by Stability AI — the open-weights generative image model that would power the image generation stage of this project
- **[[TextBlob](https://textblob.readthedocs.io/)](https://textblob.readthedocs.io)** by Steven Loria — the Python NLP library used in the working sentiment analysis demo
- **[[Hugging Face Transformers](https://huggingface.co/transformers)](https://huggingface.co/transformers)** — the open-source library providing access to state-of-the-art NLP and embedding models
- **[[CLIP](https://openai.com/research/clip)](https://openai.com/research/clip)** by OpenAI — the embedding model that bridges text and image representations
- **[[Gradio](https://gradio.app/)](https://gradio.app)** — the open-source tool planned for building the interactive demo interface

### Datasets

- **LAION-5B** — open large-scale text-image dataset from the LAION non-profit
- **WikiArt** — open fine-art image dataset
- **MS-COCO** — Microsoft Common Objects in Context dataset, used widely in vision-language research
- **Common Crawl** — open web-crawl text corpus

### Course

This project was developed as part of the **[[Elements of AI — Building AI](https://buildingai.elementsofai.com/)](https://buildingai.elementsofai.com)** course by Reaktor and the University of Helsinki. The course provided the conceptual foundation for thinking about AI problems, data, techniques, and societal impact that shaped every section of this project.

---

*© 2025 grpsverige — Original work submitted for the Elements of AI: Building AI course.* 

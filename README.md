<a name="top"></a>

<div align="center">

# LogicForge

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

</div>

---

Everyone starts somewhere. This is where Python started making sense.

LogicForge is a terminal program built while learning the basics — `for`, `while`, `if/elif/else`, string manipulation, list operations. Nothing fancy. But at some point during the build, a question came up: *what would it take to connect this to an actual AI?* The chatbot is the answer to that question. Three lines of Groq API, a loop, and suddenly a terminal program was having conversations.

The tools are small. The logic is simple. But every function here was written to understand something — not to copy it.

---

## What's inside

Type `/` after running to see the full list. Here's what you'll find:

**`chatbot`** — a conversational AI backed by Llama 3 via Groq. Responds in under 500 characters. Type `quit` to exit.

**`impares e pares`** — give it a number, it splits everything from 0 to that number into even and odd lists.

**`consoantes`** — type a word or phrase, it finds and counts every unique consonant.

**`sum`** — separates a list of numbers into positives and negatives, then sums each group.

**`max e min`** — finds the highest and lowest values from a list you provide.

---

## Running locally

```bash
git clone https://github.com/ScatmanVit/LogicForge.git
```
```bash
cd LogicForge
```
```bash
pip install -r requirements.txt
```

The chatbot requires a Groq API key. Create a `.env` in the root:

```
GROQ_API_KEY=your_key_here
```

```bash
python main.py
```

> All other tools work without the API key. Only the chatbot needs it.

<br>

<div align="center">

<a href="#top">↑ back to top</a>

</div>

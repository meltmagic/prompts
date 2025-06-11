# 🧠 prompts

<div align="center">

![MeltMagic Logo](https://img.shields.io/badge/MeltMagic-Prompts-%23ff69b4?style=for-the-badge)

A centralized repository for storing, organizing, and evolving prompt templates used across MeltMagic Agency's LLM-powered tools and services.

[![GitHub: MeltMagic](https://img.shields.io/github/followers/MeltMagic?label=follow&style=social)](https://github.com/MeltMagic)

</div>

## 🌟 Features

- 📄 Store prompts in clean, version-controlled Markdown format
- 🧱 Modular organization for reuse across different projects
- 🔍 Optimized for clarity, editability, and prompt chaining
- 📚 Supports categorization by use-case, model, and context
- ✅ Easy integration with LLM pipelines (OpenAI, Claude, etc.)

## 📂 Repository Structure

```bash
prompts/
├── README.md
├── _template.md                # Prompt authoring guide
├── general/                    # Universal utility prompts
│   ├── summarizer.md
│   └── rewriter.md
├── product/                    # Product-specific flows
│   ├── onboarding.md
│   └── feature_request.md
├── technical/                  # Developer/engineering use-cases
│   ├── api_doc_generator.md
│   └── bug_report_classifier.md
└── marketing/                  # Copywriting, branding, SEO
    ├── tagline_creator.md
    └── persona_refiner.md
```

## 🛠️ How to Use

Each Markdown file follows a consistent prompt schema for easy reading and integration. Here's a sample structure:

```markdown
# 📌 Prompt: Tagline Creator

## 🧠 Purpose
Craft punchy taglines for a product or campaign based on brand values and tone.

## 🧾 Prompt
> "Create a catchy tagline for a product that [description]. The tone should be [tone]."

## 🧪 Example Inputs
- Product: “AI-powered meeting notes”
- Tone: “Friendly and helpful”

## ✅ Output Example
> “Never Miss a Beat – Your Meetings, Summarized”

## 🔧 Notes
Use with GPT-4 or Claude 3 Opus for best results.
```

## ✍️ Contributing Guidelines

- Follow the `_template.md` format
- Use clear, declarative prompt language
- Include example inputs and outputs
- Commit with descriptive messages (`feat:`, `fix:`, `chore:`)

## 🧩 Integration Ideas

These prompts can be used in:

- MeltMagic’s internal tooling
- Marketing automation pipelines
- Customer onboarding bots
- Developer support assistants

## 📄 License

MIT

---

<div align="center">
  <p>Maintained by the team at <strong>MeltMagic Agency</strong> 🚀</p>
</div>

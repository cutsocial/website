---
title: About
date: 2018-09-25 08:37:54 +0000
layout: test
---
# What is Cut?

Cut was created to take advantage of the increasing online presence of people, and the use of web-based technologies in behavioral and social science research. Broadly, I aimed for two things:

* **Usability**: Facilitate the use of engaging and sophisticated research instruments in studies, by going beyond simple multiple choice questions and scales. Some available tools developed by psychologists and others are too specific in their use-cases, and narrow in their application. In contrast, others have developed platforms that are too generalized and require extensive effort and learning. A balance between these two poles was needed.

* **Adaptability**: A second issue was running these instruments on different platforms and mobile devices. People today use their phones more than their computers for the majority of non-work stuff. Also, these devices offer access to a much larger population, in arguably more ecologically valid settings, at significantly lower costs. No one studying modern humans can ignore mobile devices.

---

## Lens: The Evolution of Cut

**Lens** is the evolution of Cut, a platform that revolutionizes how researchers create and deploy interactive research instruments. Built with React and Material UI, Lens simplifies study design for experimenters while providing a seamless, device-adaptive experience for participants.

### Why Lens?

- **🚀 Rapid Development**: Create complex experiments using simple JSON configuration files
- **🌍 Multilingual Support**: Built-in i18n support for English, Farsi, Arabic, and more
- **📱 Device Adaptive**: Works seamlessly on desktop, tablet, and mobile devices
- **🎯 Research-Ready**: Includes validated cognitive tasks and economic games
- **📊 Integrated Surveys**: Combine interactive tasks with traditional survey elements
- **🔬 Published Research**: Used in peer-reviewed publications

---

## Available Experiments

Lens supports a comprehensive suite of research instruments:

### Cognitive Tasks

| Task | Description | Demo |
|------|-------------|------|
| **BART** | Balloon Analogue Risk Task - Measures risk-taking behavior | [Try it](https://lens.cut.social/#/bart/en) |
| **Stroop** | Cognitive interference task measuring selective attention | [Try it](https://lens.cut.social/#/stroop/en) |
| **Go/NoGo** | Response inhibition task with go and no-go stimuli | [Try it](https://lens.cut.social/#/gonogo/en) |
| **Task Switch** | Measures cognitive flexibility by switching between tasks | [Try it](https://lens.cut.social/#/taskswitch/en) |
| **N-back** | Working memory task requiring recall of previous stimuli | [Try it](https://lens.cut.social/#/nback/en) |

### Economic Games

| Game | Description | Demo |
|------|-------------|------|
| **Ultimatum Game** | Measures fairness and negotiation behavior | [Try it](https://lens.cut.social/#/ultimatum/en) |
| **Dictator Game** | Measures altruism and fairness preferences | [Try it](https://lens.cut.social/#/dictator/en) |

### Survey Elements

- **Text Input**: Instruction pages, text questions, autocomplete fields
- **Matrix Questions**: Multiple choice with sliders, vertical/horizontal layouts
- **Prolific Integration**: Specialized participant management

### Comprehensive Demo

See all experiment types in action: [Demo Comprehensive](https://lens.cut.social/#/demo-comprehensive/en)

---

## Key Features

### Flexible Experiment Design

- **JSON-Based Configuration**: Define entire studies with simple JSON files
- **Sequential Views**: Chain multiple tasks and questions in any order
- **Conditional Logic**: Support for different experimental conditions
- **Custom Styling**: Markdown support for rich text formatting

### Internationalization

- **Multi-language Support**: Currently supports English, Farsi, and Arabic
- **Easy Translation**: Add new languages by adding translation JSON files
- **RTL Support**: Full right-to-left language support

### Responsive Design

- **Mobile-First**: Optimized for all screen sizes
- **Touch-Friendly**: Works with mouse, keyboard, and touch inputs
- **Adaptive UI**: Material UI components adapt to device capabilities

### Research Features

- **Data Collection**: Automatic response collection in structured format
- **Progress Tracking**: Built-in progress indicators
- **Validation**: Required field validation and attention checks
- **Randomization**: Support for trial and choice randomization

---

## Architecture

Lens uses a JSON-driven architecture where experimenters define studies using configuration files. The platform:

1. **Loads** experiment configuration from JSON
2. **Renders** views sequentially based on the configuration
3. **Collects** responses in a structured format
4. **Submits** data to your backend API

This approach provides:

- **Separation of Concerns**: Logic separated from presentation
- **Version Control**: Experiments as code
- **Rapid Iteration**: Update experiments without code changes
- **Reproducibility**: Share exact experiment configurations

For detailed demo seen the Demo page [Demo](https://cut.social/demo.html).

---

## Research & Publications

Lens has been used in published research and is supported by:

- **The New School for Social Research**
- **Association for Psychological Science (APS)**

### Published Research

**Rad, M. S., Ansarinia, M., & Shafir, E. (2023).**
*Temporary self-deprivation can impair cognitive control: evidence from the Ramadan fast.*
Personality and Social Psychology Bulletin, 49(3), 415-428.
[View Publication](https://journals.sagepub.com/doi/full/10.1177/01461672211070385)

---

## Getting Started

This is work in progress. Please check the [demos page](demo.html) for details and examples of how experiments are configured.

### Creating Your First Experiment

Experiments are defined using JSON configuration files. A simple example:

```json
{
  "studyId": "my-study",
  "condition": "a",
  "redirectTo": "https://example.com",
  "submissionNote": "submission.note",
  "metadata": {
    "maintainer": "your.email@example.com"
  },
  "views": [
    {
      "id": "intro",
      "type": "text",
      "instruction": true,
      "text": "intro"
    },
    {
      "id": "bart-task",
      "type": "bart",
      "reward": 10,
      "maxPumps": 20,
      "safePumps": 1,
      "trials": 25
    }
  ]
}
```

Experiments are accessed via: `https://lens.cut.social/#/{studyId}/{language}`

---

## Links

- **Live Platform**: [lens.cut.social](https://lens.cut.social)
- **Documentation**: [Cut Documentation](https://sites.google.com/view/msrad/cut?authuser=0)
- **Demo Page**: [Demo](demo.html)

---

I would love to hear your feedback. Let me know!

\
[MS Rad](https://sites.google.com/view/msrad/home)
\
[Arman Rad](https://armanradmanesh.com)

New School for Social Research


# AZ-900 Prep Buddy (Unofficial)

> Built for the 1M Devs "Building Smarter Exam Prep Tools from Our Own Learning Journey" hackathon.

**Live demo:** https://github.com/tweety-KM/az900-prep-buddy/

**Disclaimer:** This is an unofficial study aid. It is not affiliated with or endorsed by Microsoft. All questions are original and written from the public AZ-900 skills outline on Microsoft Learn. No real exam questions or Microsoft logos are used.

## The problem

Many AZ-900 learners practise with questions but never understand *why* an answer is right or wrong, forget Azure terms quickly, and have no idea whether they are ready to sit the exam.

## The solution

One lightweight web app that covers three hackathon challenges:

| Challenge | Feature |
|---|---|
| Smart Quiz Builder | 15 original questions grouped by AZ-900 skill area, with instant feedback and an explanation for every answer |
| Flashcard Coach | Glossary cards plus an automatic card for every question you miss; "Again" cards return sooner |
| Readiness Tracker | Score per topic and overall, with a plain-language next step |

Questions you got wrong are shown more often in the quiz, so practice focuses on weak spots.

## Topics covered

1. Cloud concepts (CapEx/OpEx, shared responsibility, IaaS/PaaS/SaaS, elasticity, cloud models)
2. Azure architecture and services (regions, Availability Zones, resource groups, storage, Functions, ExpressRoute)
3. Azure management and governance (Policy, locks, MFA, Advisor, pricing and cost tools)

## How it works

- Plain HTML, CSS and JavaScript in a single `index.html`, with no build step and no backend
- Progress is saved in the browser with `localStorage`, so there is no sign-up
- Responsive layout with light and dark mode

## Run it locally

```bash
git clone https://github.com/YOUR-USERNAME/az900-prep-buddy.git
cd az900-prep-buddy
# open index.html in your browser
```

## AI tools and prompt engineering

Built with Claude.ai for generating and refining the app and the question set.

Example prompt used:

```
Act as an AZ-900 tutor. Using only the public skills outline on Microsoft Learn,
write 5 original multiple-choice questions for [topic]. For each: 4 options,
one correct answer, and a 2-sentence explanation of why it is right and why
the common wrong choice is wrong. Do not reproduce real exam questions.
```

<!-- Add your own prompts, what you changed after reviewing the output, and how you verified accuracy against Microsoft Learn. -->

## Roadmap

- Personal Study Planner (exam date, hours per week, weak areas)
- AI Study Buddy explaining concepts with African examples and local languages
- Bigger question bank and spaced-repetition scheduling
- Support for other entry-level certifications

## Author

**Koketso Matobako**, 1M Devs learner. [LinkedIn](www.linkedin.com/in/koketso-matobako-2b15061a3) · [GitHub](https://github.com/tweety-KM/)

## Licence

MIT. Educational use encouraged.

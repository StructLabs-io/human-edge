# What AI already matches, and where it still falls short

Use this file whenever someone says "AI can't do X". Many "human-only" claims are already false for written work. The edge that survives is mostly about who stands behind the work, not about outputs AI can't produce.

## What AI matches or beats

| Capability | Where AI stands | Evidence | Source |
|---|---|---|---|
| **Empathic wording, source unknown** | Matched or beat people | GPT-4 rated more compassionate than trained crisis-line volunteers (4.08 vs 3.47); the advantage held even when the source was disclosed (N = 556) | [Ovsyannikova, de Mello & Inzlicht, *Communications Psychology*, 2025](https://www.nature.com/articles/s44271-024-00182-6) |
| **Empathy in medicine (text)** | Beat clinicians | Meta-analysis of 13 pooled studies: standardized mean difference 0.87 in AI's favour. Text only, GPT-3.5/4, proxy raters | [Howcroft et al., *British Medical Bulletin*, 2025](https://doi.org/10.1093/bmb/ldaf017) |
| Physician vs chatbot answers | Chatbot rated higher on quality and empathy | Online patient questions | [Ayers et al., *JAMA Internal Medicine*, 2023](https://jamanetwork.com/journals/jamainternalmedicine/fullarticle/2804309) |
| **Empathy, source known** | **Label penalty** | Same AI text rated less empathic when labelled AI; people would wait for a human reply (see `edges.md`, Edge 1) | [Rubin et al., *Nature Human Behaviour*, 2025](https://www.nature.com/articles/s41562-025-02247-w) |
| **Therapy symptom relief** | Partly | Therabot users' depression symptoms fell 51% and anxiety 31% on average, significantly more than a waitlist group (N = 210). The authors say no generative agent is ready to run on its own | [Heinz et al., *NEJM AI*, 2025](https://doi.org/10.1056/aioa2400802) (coverage) |
| **Coaching outcomes** | **Not yet** | Human coaching beat control on goals and stress; a scripted AI chatbot group showed no significant gain | [de Haan, Terblanche & Nowack, *HRDI*, 2026](https://doi.org/10.1080/13678868.2026.2633990) |
| **Persuasion** | Beat people | Personalized GPT-4 more persuasive than humans in 64.4% of non-tied debates; without personal data, no significant difference (N = 900) | [Salvi et al., *Nature Human Behaviour*, 2025](https://www.nature.com/articles/s41562-025-02194-6) |
| **Persuasion at scale** | Beat people, with a cost | Post-training raised persuasiveness up to 51%, but more persuasive models were less accurate (N = 76,977) | [Hackenburg, Tappin et al., *Science*, 2025](https://arxiv.org/abs/2507.13919) |
| Persuasion in elections | Moved voter preferences | Experiments across several countries | [Lin et al., *Nature*, 2025](https://doi.org/10.1038/s41586-025-09771-9) |
| **Changing entrenched beliefs** | Beat people | Conspiracy belief down about 20%, lasting two months (N = 2,190). An expression of concern was issued in June 2026 over data errors; a reanalysis and an independent replication support the result | [Costello, Pennycook & Rand, *Science*, 2024](https://doi.org/10.1126/science.adq1814); [expression of concern](https://retractionwatch.com/2026/06/11/science-ai-chatbots-debunk-conspiracy-theories-expression-of-concern/) |
| **Divergent creativity** | Beat the average, not the best | GPT-4 beat the mean of 100,000 humans, but "even the best-performing models do not exceed the mean of the top 50%"; humans keep an edge in creative writing | [Bellemare-Pepin et al., *Scientific Reports*, 2026](https://www.nature.com/articles/s41598-025-25157-3) |
| **Collective idea diversity** | AI makes it worse | ChatGPT narrowed idea diversity in 37 of 45 comparisons (a short published comment on another study, [Lee & Chung, 2024](https://doi.org/10.1038/s41562-024-01953-1)) | [Meincke, Nave & Terwiesch, *Nature Human Behaviour*, 2025](https://doi.org/10.1038/s41562-025-02173-x) |
| **Moral advice, as perceived** | Matched, small effects | GPT-4o rated more moral, trustworthy and thoughtful than the *NYT* Ethicist (N = 900); no difference on nuance | [Dillion et al., *Scientific Reports*, 2025](https://doi.org/10.1038/s41598-025-86510-0) |
| Moral evaluations ("moral Turing test") | Rated higher, possibly for style | People rated AI's moral evaluations above humans'. A published comment found the AI texts were more complex (grade 11.2 vs 8.4) and argues style drives the perceived superiority | [Aharoni et al., *Scientific Reports*, 2024](https://doi.org/10.1038/s41598-024-58087-7); [Warren et al., 2025](https://doi.org/10.1038/s41598-025-25046-9) |
| **Forecasting** | Likely parity (disputed) | "AI models have likely reached parity with superforecasters" on ForecastBench. The superforecaster data is from 2024 and the comparison is extrapolated. Good Judgment disputes it: on market questions, superforecasters scored a Brier of about 0.039 vs 0.059 for the best AI | [Forecasting Research Institute, 2026](https://forecastingresearch.substack.com/p/ai-models-have-likely-reached-parity); [Good Judgment](https://goodjudgment.com/what-forecastbench-doesnt-measure/) |
| **Expert prediction** | Beat experts | LLMs 81.4% vs neuroscientists 63.4% at predicting study results | [Luo et al., *Nature Human Behaviour*, 2024](https://doi.org/10.1038/s41562-024-02046-9) |
| **Passing as human** | Beat people | GPT-4.5 with a persona prompt was judged human 73% of the time in 5-minute tests (36% without the persona) | [Jones & Bergen, *PNAS*, 2026](https://doi.org/10.1073/pnas.2524472123); [UC San Diego release](https://today.ucsd.edu/story/ai-can-seem-more-human-than-real-humans-in-a-classic-turing-test-study-finds) |
| **Theory of mind** | Partly | At or above human on standard tests, with a "steep drop" when tasks are perturbed | [Strachan et al., *Nature Human Behaviour*, 2024](https://doi.org/10.1038/s41562-024-01882-z); [Nickel et al., 2026](https://arxiv.org/abs/2602.22072) |
| **Taste** | Unresolved | Lay readers spotted AI poems below chance (46.6%) and rated them higher; no AI-vs-expert-critic study found | [Porter & Machery, *Scientific Reports*, 2024](https://www.nature.com/articles/s41598-024-76900-1) |

**Don't claim as human-only:**
- empathic wording
- persuasion
- average creativity
- moral advice that sounds wise
- forecasting
- sounding human in short chats
- reading intentions on standard tests
- synthesising expert knowledge
- short-term relief from loneliness

## Where AI still falls short

| Capability | Where AI stands | Evidence | Source |
|---|---|---|---|
| **Honest disagreement** | Not by default | Models affirmed users 49% more often than humans, including on deception or harm; users preferred the flattering models | [Cheng et al., *Science*, 2026](https://doi.org/10.1126/science.aec8352) |
| **Turning knowledge into outcomes with real people** | Not yet | LLMs alone identified the medical condition in 94.9% of cases; people using them did so in under 34.5% of cases, no better than controls (N = 1,298) | [Bean et al., *Nature Medicine*, 2026](https://doi.org/10.1038/s41591-025-04074-y) |
| **Running things on its own for long periods** | Not yet | An agent-run shop lost money in phase 1 ("we would not hire Claudius"); it was profitable in phase 2, but staff manipulated it and it "still needed a great deal of human support" | [Anthropic, Project Vend, 2025](https://www.anthropic.com/research/project-vend-1); [phase 2](https://www.anthropic.com/research/project-vend-2) (*vendor*) |
| **Reliability when stakes are high** | Not yet | 2,184 court cases in which AI-invented content was filed, as of 10 October 2026 (a count of incidents, not a failure rate) | [Charlotin, AI Hallucination Cases database](https://www.damiencharlotin.com/hallucinations/) |
| **Accountability** | Not, structurally | A tribunal rejected Air Canada's claim that its chatbot was a separate entity; only 18% of consumers would trust AI alone for financial recommendations | [Moffatt v. Air Canada, 2024](https://decisions.civilresolutionbc.ca/crt/crtd/en/item/525448/index.do); [TD Bank, 2026](https://stories.td.com/us/en/article/nearly-80-of-americans-use-ai-tools-but-most-still-want-humans-making-financial-decisions-td-survey-finds) |

## The label effect: where the surviving edge lives

- **Same words, different value.** AI-written text made people feel more heard, and the AI label cost about as much as the AI quality gained ([Yin et al., 2024](https://doi.org/10.1073/pnas.2319112121)). Rubin et al. replicated the penalty across lengths, delays and models, strongest for emotional sharing and care ([2025](https://www.nature.com/articles/s41562-025-02247-w)).
- **It spreads beyond empathy.** Medical advice labelled "human + AI" was penalized even with a doctor supervising ([Reis et al., 2024](https://doi.org/10.1038/s41591-024-03180-7)). Disclosing AI use cuts professional trust; being exposed by someone else cuts it more ([Schilke & Reimann, 2025](https://doi.org/10.1016/j.obhdp.2025.104405)).
- **So:** much of the human edge in support work sits outside the output, in knowing that a person spent scarce time and chose to show up. Hiding AI use is the worst option. Practise open authorship: "I used AI for X; the call and the care are mine."
- **It's conditional.** The preference for humans drops once people learn about an algorithm, and further after good experiences with one ([Kaiser, Sunstein & Reisch, 2025](https://doi.org/10.1007/s11166-025-09466-6)). People often prefer algorithmic advice for estimates and forecasts ([Logg, Minson & Moore, 2019](https://doi.org/10.1016/j.obhdp.2018.12.005)).

## A warning about "human plus AI"

- **Teams can be worse than either alone.** Across 106 experiments and 370 effect sizes, human–AI teams on average did *worse* than the better of the two alone ([Vaccaro, Almaatouq & Malone, *Nature Human Behaviour*, 2024](https://doi.org/10.1038/s41562-024-02024-1); preregistered meta-analysis).
- **It depends on the task.** Teams lost ground on decision tasks. Creative tasks did significantly better than decision tasks, but their gain over the best single performer wasn't statistically significant.
- **It depends on who is stronger.** Teams gained when the human was better than the AI at the task, and lost when the AI was better.
- **The jagged frontier.** Inside AI's abilities, consultants got better and faster. Just outside them, they were markedly less likely to be correct ([Dell'Acqua et al., 2026; working paper 2023](https://doi.org/10.1287/orsc.2025.21838)).
- **So:** "human plus AI" isn't automatically better. Know who's stronger at what, and where the frontier is.

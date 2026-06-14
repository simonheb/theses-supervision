# Master & Bachelor Thesis: Guidelines

**Development Economics / Applied Micro-Econometrics**

Simon Heß
*Vienna University of Economics and Business*

Writing a thesis can be a chance to dig into a question you care about and apply what you've learned. 
These guidelines provide an overview of the structure and content of a thesis in the field of Development Economics / Applied Econometrics.

 

## 1. Supervision

Start with submitting an exposé (2–3 pages) which outlines your:

1. Research question
2. Related literature
3. Empirical framework (potential data and methods)

A working title must be included. In case I can supervise your project, we will then schedule a meeting to discuss the way forward for the thesis.

You then work independently. I am available via email or for meetings in case there are any difficulties, but I expect you to study the relevant literature and do your empirical implementations on your own (this is when you learn the most and gain experience). I am happy to discuss results and code with you, during our meetings, but I will not review or edit code via email.

### Seeking Advice

Meet your advisors (i.e., maybe me). Especially if you feel there's no progress despite effort. That's when you need help -- not when all is going well.

Advising is our job. That being said: you can make our job easy by preparing the meetings well, by sending *concise* bullet points prior to meetings, and by collecting questions instead of making each question one email.

### AI

Of course you will use AI tools (Grammarly, Claude, etc.) for both text writing and coding. It's a useful skill that you should practice! Conversely, this means that errors that could have been avoided by using AI tools (e.g., very basic grammar or coding mistakes) as well as errors that indicate AI-generated content was adopted uncritically (e.g., hallucinated results) will be taken particularly seriously and *at least* lead to point deductions.

 

## 2. Finding a Topic

- Consider starting from a topic you *really* care about, even if it doesn't strike you as "econ". Most economically/socially/politically relevant topics can be studied from an econ perspective, and you'll enjoy the thesis more if you actually care.
- Be realistic about scope. Find a topic that allows you to show the skills you acquired using a relevant research question. Conclusively closing a literature gap is an unrealistic expectation.
- Finding a research question is hard. It's a major part of doing research. How hard the rest is depends on how good a research question you have.
- For empirical theses, it helps to start from existing papers and expand their analyses with different data, alternative estimators, etc.
- There are thousands of public data sets. E.g., [DHS micro survey data](https://dhsprogram.com/), ["Data is Plural" archive](https://docs.google.com/spreadsheets/d/1wZhPLMCHKJvwOkP4juclhjFgqIY8fQFMemwKL2c64vk/edit#gid=0), [the World Bank microdata catalog (e.g., arabbarometer)](https://microdata.worldbank.org/index.php/catalog/?page=1&ps=15).
- Manage and diversify *your* risk: if working on an ambitious project, make sure to have a fallback. E.g.:
  - If you work with your own data, have a public dataset that you can use to at least do something if your data collection fails.
  - If you work on a reanalysis of other people's data, replicate their paper before you start so you are sure it's complete.
  - If you work on a complicated project, start with a systematic literature survey that you can expand into its own paper in case your project fails.
- I am happy to help you brainstorm and find a topic. But I will not be able to advise you on your thesis writing process if your topic does not fall within my research area (development [micro-]economics, applied econometrics). To get an idea of my research area, you can check my website [hesss.org](https://hesss.org).
  - If your research question is about a micro-level mechanism, development economics (e.g., urban development, migration), political economy (e.g., political candidacy, voting behavior) and seeks to answer a clear causal question, it is likely to be in my research area.
  - If your research question is about applied econometrics (experimental design, causal inference, econometrics of networks, etc.) and seeks to answer a clear methodological question, it is likely to be in my research area.
  - Conversely, if your research question is an empirical one, where the unit of observation is a country, or the data is a time-series it is very unlikely to be in my research area, I recommend looking for another supervisor, and I can help you with that.
- Examples of theses I advised in the past or currently advise:
  - MSc: *From Mines to Minds: The Impact of Artisanal Gold Mining on Human Capital Formation* (G. Pirich), on the effect of Gold mines on education in Ghana.
  - MSc: *Aftershocks in the Household: The Short- and Long-Run Causal Impact of the 2015 Gorkha Earthquake on Intimate Partner Violence.* (G. Ponti), on the effect of the 2015 earthquake in Nepal on intimate partner violence.
  - MSc: *Natural disasters and marriage markets: Evidence from the 2015 earthquake in Nepal* (L. Esch), on the effect of natural disasters on marriage markets.
  - BSc: *Economic Impacts of Expansions of Public Transport Networks: Evidence from Mexico City's Golden Line* (H. Lautner), on the effect of a new metro line on local economic activity in Mexico City.

 

## 3. Related Literature

- Start by reading. A decent way to start is [Google Scholar](https://scholar.google.de/). Start with recent papers with a high citation count in [famous journals](https://ideas.repec.org/top/top.journals.all.html)… they are not always better, but identifying good papers is hard at first.
- Once you like 1–3 good papers, find related papers: [connectedpapers.com](https://connectedpapers.com/), [econpapers.eduard-bruell.de](https://econpapers.eduard-bruell.de/) and check the websites of the authors for newer papers.
- Only expand your search to working papers ([arXiv](https://arxiv.org/archive/econ), [CEPR](https://cepr.org/publications/discussion-papers), [NBER](https://www.nber.org/papers?page=1&perPage=50&sortBy=public_date)) and lesser-known journals once familiar with the literature (e.g., know what makes a good paper, know authors).

 

## 4. Structure of the Thesis

I expect the thesis to be structured roughly like a research paper. In addition to the officially required parts, include a title page and a short abstract of no more than 100–150 words. The following structure is a suggestion (as a baseline) and could/should be tailored to your needs:

### (1a) Introduction

This section motivates your research question and explains how your work relates/contributes to the existing literature.

### (1b) Literature Review *(optional, can also be included in the introduction)*

This section provides an in-depth overview of the existing literature.

### (2) Theoretical Framework

This section can either be a micro-theoretical model that motivates your empirical analysis, or a detailed description of the empirical framework (e.g., discussion of the econometric model, identification strategy, etc.). 
This section also describes the econometric/statistical methods you are using.

### (3) Data and Descriptive Statistics *(can also be merged with the econometric framework)*

This section includes a description of the data sources, and perhaps some visualizations or tables with summary statistics of important variables.

### (4) Results and Discussion

This section includes your empirical findings and a thorough discussion of them. Importantly, this section should not just be a presentation of results, but also include a critical discussion of them (e.g., how do they relate to the literature, what are potential limitations, etc.). 

### (5) Conclusion

This section should be rather brief and summarizes the main ideas of the thesis and empirical results concisely.

### References

Lists all references cited in the text.

### Appendix *(optional)*

This section can include additional tables, figures, or results that are not essential for the main text but might be of interest nonetheless (e.g., robustness checks). 


## 5. Code and Replicability

Submit all code with your thesis (e.g., to an online repository, for which you include the link in your thesis). Your analysis must be fully replicable from raw data to final output. Use a single master script, relative file paths, and include a README. Do not edit data manually.

## 6. Timeline

I strongly recommend working on the thesis full-time.
Part-time thesis writing alongside a full-time job is very difficult to sustain and often leads to frustration on the side of the students---if that's your situation and you have the option: defer to a time when you can focus. If you have no choice, discuss that with me so that we can find a solution that works for you. Good theses can be written in 2–5 months of dedicated work.

Milestones: 

1. Topic selected
2. Data acquired
3. Time plan laid out and discussed with supervisor
4. Title fixed and registered
5. ToC and first tables discussed with supervisor
6. Document set up and sample page shared with supervisor
7. Thesis seminar
8. Thesis submitted

Around milestones 3-4, send me a time plan, draft title, and outline. Present in the thesis seminar ~1.5–2 months after you have your data.

All administrative handling (aside from the sign up) is your responsibility. I am happy to help you with any questions regarding the process.

## 7. Expectations and Grading

- You will be graded on how successfully you employ the toolset of an economist. This includes picking an answerable research question, choosing appropriate data and methods, clearly motivating and explaining your analyses, and openly discussing limitations. For example, in a causal study using DiD or RDD, I expect a clear discussion of identifying assumptions, possible violations, and corroborating tests where feasible. If you're unsure whether something is expected or how deep to go---just ask!
- Good news: you will *not* be graded on the (statistical) significance of your results, the length of your paper, or the publishability of your findings. Focus on doing solid work, not on chasing (significance) stars.
- Form matters. Presenting results clearly in written form is part of the toolset. Figures, tables, etc. must be clearly labelled, referenced, and self-contained.
- Statements that are not common knowledge (e.g., "Paris is in France" is; "Paris has high rates of cancer" is not) must be backed up with data, references, or clearly labelled as speculation. Ideas originating from other sources must be attributed, even if not quoted word-for-word---e.g., if your research question builds on existing literature, cite it. 

## Additional Recommendations

- I only supervise theses written in **English** (all relevant literature is in English).
- The thesis should **not exceed 35 pages** (excluding title pages, references, tables, figures). 35 is not a target. You will be graded based on the quality of your work, not the quantity (adding fluff that does not add value will deduct points). Conversely, if you can write a good thesis in 20 pages, that is perfectly fine -- in the past, good theses were often on the shorter side.
- I recommend using LaTeX, or (R)Markdown for writing the thesis. If you are not familiar with it, I can provide you with a template — [Overleaf](https://www.overleaf.com) is a useful website for managing such documents. 


# Rubric

*Five dimensions, equally weighted (20% each). Anchors: **Below expectation (4–5)**, **Meets expectation (3)**, **Exceeds expectation (1–2)**.*

| Dimension | Exceeds Expectation (1–2) | Meets Expectation (3) | Below Expectation (4–5) |
|---|---|---|---|
| **1. Research Question + Literature** | The research question is motivated by an economic model, empirical puzzle, or a well described gap in our knowledge. The literature review directly shapes the empirical approach. | Research question is clearly stated and connected to existing literature. Literature review covers the relevant work. | Research question is vague or not connected to the empirical work. Literature review is superficial or does not inform the empirical approach. |
| **2. Identification + Specification** | Threats to identification are discussed in reasonable depth. Robustness checks are tied to specific named concerns. Assumptions and limitations are handled explicitly. | Identifying assumptions are named and described. Main threats to identification are acknowledged. Limitations are stated. | Identifying assumptions are absent or unclear. Threats to identification are not discussed. Robustness checks, if present, are not connected to specific concerns. |
| **3. Estimation + Replicability** | All empirical choices are well-motivated and described. Code is well-structured and commented throughout. | Empirical specification is fully described. Standard errors are explicitly justified. Replication package is complete and code is self-contained. | Specification is not or only partially described. Standard errors are not explained. Replication package is missing, incomplete, or code cannot be followed. |
| **4. Interpretation of Results** | Results are connected back to the broader literature and critically evaluated. | Coefficients are interpreted in terms of economic magnitudes. Results are connected to the research question. | Results are reported without interpretation. Economic magnitudes are not discussed. Findings are not connected to the research question. |
| **5. Writing + Form** | Writing, exhibits, and structure actively aid the reader's understanding of the empirical argument. | All tables and figures are self-contained with complete notes. Writing is clear. | Tables or figures require the reader to search in the text to be understood. Writing is unclear or imprecise. |
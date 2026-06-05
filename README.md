# The Impact of AI on Software Development Jobs

A 10-week summer research project for high school students.

Title: The Impact of Generative AI on Software Development Jobs: A Survey and Job Market Analysis.

Research question: How is Generative AI changing software development jobs, required skills, and developer productivity?

Sub-questions:

- **RQ1:** How have software development job requirements changed since the rise of Generative AI?
- **RQ2:** What AI-related skills are increasingly requested in software jobs?
- **RQ3:** How do developers perceive AI's impact on their careers?

## How to start

1. Open `ai_jobs_analysis.ipynb` -- or launch it directly in Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VietNguyen705/ai-impact-software-jobs-highschool/blob/main/ai_jobs_analysis.ipynb)
2. No GPU needed -- a standard CPU runtime is fine.
3. Fill in every TODO cell from top to bottom.

Ask your instructor if stuck.

## 4 Big Steps

1. **Background + Data Collection** -- Learn AI-assisted programming (GitHub Copilot, ChatGPT) and software careers. Do the literature review (10-15 papers). Collect 500-1000 software job postings.
2. **Cleaning + Skill Analysis** -- Clean the job-posting text with NLP (tokenization, stopword removal, word frequency). Build a top-skills table and measure AI-related skill demand vs traditional skills.
3. **Survey + Integration** -- Design and run a developer survey (Likert 1-5, 25-50 responses). Compute statistics. Combine job-posting findings with survey findings and build the figures.
4. **Write Report** -- Draft the IEEE paper, polish figures, optionally add the ML prediction stretch goal, and prepare the poster and presentation.

## 10-Week Plan

<table>
  <thead>
    <tr><th>Step</th><th>Week</th><th>Tasks</th></tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2"><b>Background + Data Collection</b></td>
      <td>1</td>
      <td>Understand the problem. Learn AI-assisted programming, GitHub Copilot, ChatGPT for coding, and software engineering careers. Define the three research questions</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Literature review: find 10-15 papers on Google Scholar, Semantic Scholar, and arXiv. Build a literature review table (Paper / Dataset / Findings / Limitations)</td>
    </tr>
    <tr>
      <td rowspan="2"><b>Cleaning + Skill Analysis</b></td>
      <td>3</td>
      <td>Collect 500-1000 software job postings from Kaggle, O*NET, and BLS. Build a dataset with job title, skills, description, and date</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Data cleaning and NLP: tokenization, stopword removal, word frequency with NLTK and scikit-learn. Produce a top-skills frequency table</td>
    </tr>
    <tr>
      <td rowspan="2"><b>Cleaning + Skill Analysis</b></td>
      <td>5</td>
      <td>AI skill trend analysis. Track AI, Machine Learning, LLM, Generative AI, Prompt Engineering, LangChain, GitHub Copilot. Compare traditional vs AI skills with bar charts, trend charts, word clouds</td>
    </tr>
    <tr>
      <td>6</td>
      <td>Developer survey design in Google Forms. Likert 1-5 questions (productivity, job threat, changing skills, AI assistant use). Target 25-50 responses</td>
    </tr>
    <tr>
      <td rowspan="2"><b>Survey + Integration</b></td>
      <td>7</td>
      <td>Survey collection and analysis. Compute mean, median, standard deviation (optional t-tests) with Google Sheets or pandas. Build the survey results table</td>
    </tr>
    <tr>
      <td>8</td>
      <td>Integrate findings. Combine job-posting and survey data. Do postings show increased AI demand? Do developers think AI skills matter? Do the findings agree? Create Figures 1-3</td>
    </tr>
    <tr>
      <td rowspan="2"><b>Write Report</b></td>
      <td>9</td>
      <td>Write the IEEE paper (Abstract, Introduction, Background, Literature Review, Problem Definition, Methodology, Experimental Design, Results, Discussion, Limitations, Conclusion)</td>
    </tr>
    <tr>
      <td>10</td>
      <td>Final 4-6 page IEEE paper, 10-12 slide presentation, and poster. Discuss limitations and real-world use</td>
    </tr>
  </tbody>
</table>

## Methods

- **Literature review:** 10-15 papers from Google Scholar, Semantic Scholar, arXiv.
- **Job market analysis:** NLP on 500-1000 postings (tokenization, stopword removal, word frequency, skill keyword tracking) with NLTK and scikit-learn.
- **Developer survey:** Google Forms, Likert 1-5, 25-50 responses; descriptive statistics (mean, median, std) with pandas, optional t-tests.
- **Stretch goal (ML prediction):** classify a job posting as "AI-focused" vs "Traditional Software Engineering" using Logistic Regression, Random Forest, or XGBoost on skills, keywords, and experience features.

## Data Sources

- **Job postings:** [Kaggle](https://www.kaggle.com) (software engineer / tech / IT job datasets), [O*NET](https://www.onetonline.org), [U.S. Bureau of Labor Statistics](https://www.bls.gov).
- **Developer surveys:** [Stack Overflow Developer Survey](https://survey.stackoverflow.co/), [GitHub Octoverse](https://octoverse.github.com/).
- **Background reading:** [GitHub Copilot productivity research](https://github.blog/news-insights/research/research-quantifying-github-copilots-impact-on-developer-productivity-and-happiness/), [World Economic Forum Future of Jobs](https://www.weforum.org/reports/future-of-jobs-report/).

## Deliverables

- A complete IEEE-style workshop paper (4-6 pages)
- Data analysis results and visualizations (bar charts, trend charts, word clouds)
- A presentation/poster (10-12 slides)
- Potential submission to: IEEE Student Conference, Science Fair, Junior Science & Humanities Symposium (JSHS), Regeneron STS, or a local university research symposium.

## IEEE Paper Template

https://www.ieee.org/conferences/publishing/templates.html

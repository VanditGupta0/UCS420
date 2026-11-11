# UCS420 – Lab Assignments

Lab assignments for **UCS420**, written in Python as Jupyter notebooks.

**Student:** Vandit Gupta · **Roll No:** 1024170307

---

## 📚 Assignments

| # | Topic | Notebook | Files |
|:-:|-------|----------|-------|
| 1 | Python basics: printing, variables, arithmetic, string concatenation | [Assignment_1.ipynb](Assignment_1.ipynb) | – |
| 2 | Lists, tuples, sets and the `random` module | [Assignment2.ipynb](Assignment2.ipynb) | – |
| 3 | Pandas DataFrames: creating, indexing and working with CSV data | [UCS420_Assignment_3.ipynb](assignment-3/UCS420_Assignment_3.ipynb) | [Iris.csv](assignment-3/Iris.csv) · [employees.csv](assignment-3/employees.csv) · [employee_new.csv](assignment-3/employee_new.csv) |
| 4 | FAQ dataset with Pandas: keyword scoring, filtering and updating CSVs | [Assignment_4.ipynb](assignment-4/Assignment_4.ipynb) | [faq_data.csv](assignment-4/1024170307_faq_data.csv) |
| 5 | NumPy fundamentals: array operations, flipping, element comparisons | [assignment-5.ipynb](assignment-5/assignment-5.ipynb) | – |
| 6 | NumPy applied: vectorised maths, aggregation, slicing and views | [assignment6.ipynb](assignment-6/assignment6.ipynb) | – |
| 7 | NLP text preprocessing with NLTK | [Assignment7.ipynb](assignment-7/Assignment7.ipynb) | [generated_dataset.csv](assignment-7/1024170307_generated_dataset.csv) |
| 8 | NLP: tokenisation, frequency analysis, sentiment (TextBlob, VADER) and word clouds | [assignment8.ipynb](assignment-8/assignment8.ipynb) · [Q6](assignment-8/assignment8%286th_question%29.ipynb) | [positive_wordcloud.png](assignment-8/positive_wordcloud.png) |
| 9 | Computer vision with LandingAI predictions, Pillow and gTTS | [assignment9.ipynb](assignment-9/assignment9.ipynb) | – |

> Click a notebook to open it on GitHub, or open it in [Google Colab](https://colab.research.google.com/) / Jupyter to run it.

---

## 🛠️ Tech Stack

`Python` · `Jupyter / Colab` · `NumPy` · `Pandas` · `Matplotlib` · `NLTK` · `TextBlob` · `VADER` · `scikit-learn` · `WordCloud` · `Pillow` · `LandingAI` · `gTTS`

---

## 📁 Repository Structure

```
UCS420/
├── Assignment_1.ipynb
├── Assignment2.ipynb
├── assignment-3/   # Pandas + CSV datasets
├── assignment-4/   # FAQ data handling
├── assignment-5/   # NumPy basics
├── assignment-6/   # NumPy applied
├── assignment-7/   # NLP preprocessing
├── assignment-8/   # NLP + sentiment analysis
├── assignment-9/   # Computer vision (LandingAI)
└── readme.md
```

---

## 🌳 Commit History

```mermaid
%%{init: {'theme': 'base', 'gitGraph': {'mainBranchName': 'main', 'showCommitLabel': true}}}%%
gitGraph TB:
    commit id: "705aa85 · 05 Aug · 1st assignment" tag: "A1"
    commit id: "37f6c70 · 05 Aug · Fixed 1st assignment"
    branch assignment-2
    checkout assignment-2
    commit id: "7eed2ee · 06 Aug · Assignment_2 created"
    checkout main
    commit id: "ef8a4c0 · 11 Aug · Added 2nd assignment"
    merge assignment-2 id: "05ae42f · 11 Aug · Added 2nd assignment" tag: "A2"
    commit id: "b4c45e5 · 11 Aug · Added 2nd assignment"
    commit id: "eeb0503 · 11 Aug · Added the output of the file"
    commit id: "30abb17 · 19 Aug · Added 3rd assignment" tag: "A3"
    commit id: "869d098 · 25 Aug · Added Assignment 4" tag: "A4"
    commit id: "e1482db · 05 Sep · Added assignment 5" tag: "A5"
    commit id: "d2dc0d4 · 10 Oct · Add assignment 6" tag: "A6"
    commit id: "5a526ad · 15 Oct · Add assignment 6 (adds assignment-7)" tag: "A7"
    commit id: "d44d85e · 31 Oct · Add assignment 8" tag: "A8"
    commit id: "923e2fe · 31 Oct · Add assignment 9" tag: "A9"
    commit id: "d687185 · 11 Nov · Update README"
```

### Contribution Graph

[![Vandit Gupta's GitHub contribution graph](https://ghchart.rshah.org/40c463/VanditGupta0)](https://github.com/VanditGupta0)

See the full [commit history](https://github.com/VanditGupta0/UCS420/commits/main) on GitHub.

---

## 👤 Contributors

| Contributor | Role | Contributions |
|:-----------:|------|---------------|
| <a href="https://github.com/VanditGupta0"><img src="https://github.com/VanditGupta0.png" width="80" alt="VanditGupta0"/><br/><b>Vandit Gupta</b></a> | Author | All assignments (1–9), datasets and documentation |

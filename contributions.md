# Contributions

- **Group:** DSHBeauties
- **Group Members:** [Wendy/Chloe/Lin/Weizhu/Sherry]
- **Project:** The Relationship Between Communication Apprehension and Public Transportation Usage
- **Repository:** [Link to Repo](https://github.com/liangyinglee/DSHBeauties.git)

---

## Student 1: [Sherry Tao] (`argenttt`)

- **The component I "owned" and summarize here is best described as** data cleaning, variable construction, and manuscript integration.
- **You can find this contribution in** `index.qmd` **at lines** 19–100, where the data cleaning and variable construction are implemented.[Permalink to `index.qmd`](https://github.com/liangyinglee/DSHBeauties/blob/c97970ba9d2662c205a5b19c28b0236ba3a40abd/index.qmd#L19-L100)
- **Owning this component means** I cleaned the raw survey data, converted Likert-scale responses into numeric values, reverse-coded the appropriate communication apprehension items, created the communication apprehension score, and constructed the public transit variables used in the analyses. I also integrated the team’s work into the final index.qmd file.
- **The portion(s) of the data science process that this effort contributes to** is Stage 4, **Wrangle**. My work focused on cleaning, transforming, and organizing the data into an analysis-ready dataset.

---

## Student 2: [Weizhu Pan] (`WeizhuPan`)

- **The component I “owned” and that I summarize here is best described as** I used the first approach “OLS regression model” to test the relationship between communication apprehension and public transportation use.
- **You can find this contribution in a file called** `index.qmd` **at lines** 102-155. [Permalink to `index.qmd`](https://github.com/liangyinglee/DSHBeauties/blob/3d0f0de3fba23d29f4782de8b1cbb5d63d99c656/index.qmd#L102-L155)
- **Owning this component means** I selected OLS regression as our foundational parametric model to establish a direct baseline for hypothesis testing before evaluating more complex approaches.
- **The portion(s) of the [data science process](https://adamrossnelson.github.io/integsci375-public/readings/data_science_processes.html) that this effort contributes to is** stage 5, **Select + Apply** — evaluating potential analysis methods, choosing OLS regression as the baseline, and executing the statistical test to examine the relationship between communication apprehension and public transit usage. It also connects to stage 6, **Check + Recheck**: analyzing regression diagnostics, inspecting coefficients and p-values for statistical significance, and verifying that the model assumptions hold for our survey dataset.

---

## Student 3: [Chloe Oh] (`nakyungoh0314`)

- **The component I "owned" and that I summarize here is best described as** the logistic regression predicting whether a respondent was a transit user or non-user.
- **You can find this contribution in a file called** `index.qmd` **at lines** 157 – 227. [Permalink to `index.qmd`](https://github.com/liangyinglee/DSHBeauties/blob/c97970ba9d2662c205a5b19c28b0236ba3a40abd/index.qmd#L157-L227)
- **Owning this component means** I created the binary transit-user variable, fitted the logistic model, calculated odds ratios and predicted probabilities, and generated the probability plot.
- **The portion of the data science process that this effort contributes to** is stage 5, **Select + Apply**, because I used logistic regression for the binary outcome. It also contributes to stage 6, **Check + Recheck**, by providing an alternative to the two continuous models.

---

## Student 4: [Wendy Lee] (`liangyinglee`)

- **The component I "owned" and that I summarize here is best described as** I conducted the OLS regression with composite score of transit, to test the relationship between communication apprehension total score and transit composite intensity.
- **You can find this contribution in a file called** `index.qmd` **at lines** 228 - 260. [Permalink to `index.qmd`](https://github.com/liangyinglee/DSHBeauties/blob/c97970ba9d2662c205a5b19c28b0236ba3a40abd/index.qmd#L228-L260)
- **Owning this component means** I chose to construct an Estimated Total Monthly Trips metric by multiplying the category midpoints of monthly usage frequency (Q26) and daily trip intensity (Q27), rather than relying solely on a single ordinal proxy to better capture people's actual total transit usage.
- **The portions of the data science process** included Stage 5 **(Select + Apply)**—operationalized the dependent variable and applied an OLS regression model—and Stage 6 **(Check + Recheck)**—evaluated regression diagnostics, confirmed statistical significance, verified model fit, and interpreted the negative trend.

---

## Student 5: [Lin Li] (`linli97`)

- **The component I "owned" and that I summarize here is best described as** the statistical interpretation and discussion narrative.
- **You can find this contribution in a file called** `index.qmd` **at lines** 262-280.[Permalink to `index.qmd`](https://github.com/liangyinglee/DSHBeauties/blob/c97970ba9d2662c205a5b19c28b0236ba3a40abd/index.qmd#L262-L280)
- **Owning this component involved** writing APA-style statistical interpretations for all three models (OLS, Logistic, and Composite), evaluating model robustness across DV operationalizations, and contextualizing the findings—building directly on the data cleaning and visualization code authored by my teammates.
- **The portion of the data science process that this effort contributes to** is **Interpret**. It mattered because it transformed raw statistical coefficients into rigorous behavioral insights, establishing model robustness while clearly communicating the practical meaning of our effect sizes.

---

## Group sign-off

By adding your name below, each member affirms that the account of their own contribution is accurate, and that they have read the other four sections and believe them to be accurate as well.

- [ ] [Sherry Tao] (`argenttt`) — [07/30/2026]
- [ ] [Weizhu Pan] (`WeizhuPan`) — [07/30/2026]
- [ ] [Chloe Oh] (`nakyungoh0314`) — [07/30/2026]
- [ ] [Wendy Lee] (`liangyinglee`) — [07/30/2026]
- [ ] [Lin Li] (`linli97`) — [07/30/2026]

### **UNIT–III: Mathematical Foundations**  
Mathematics forms the backbone of data science and machine learning. This unit focuses on foundational concepts in linear algebra, statistics, and probability, which are essential for understanding and developing advanced algorithms.

---

### **1. Linear Algebra**  
Linear algebra is a mathematical framework used extensively in machine learning, computer graphics, and data science. It deals with vectors, matrices, and operations on them.

#### **Key Topics in Linear Algebra**:

| **Topic**    | **Definition**                                                                                      | **Applications**                                                                                   |
|--------------|----------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| **Vectors**  | A vector is a quantity with both magnitude and direction, represented as a list of numbers (e.g., \( \mathbf{v} = [v_1, v_2, v_3] \)). | Representing data points, weights in models, and directions in space.                           |
| **Matrices** | A matrix is a rectangular array of numbers, symbols, or expressions arranged in rows and columns.  | Representing datasets, transformations, and computations in machine learning algorithms.          |

---

### **2. Statistics**  
Statistics is the study of data: how to collect, summarize, and interpret it. It plays a key role in understanding datasets and drawing inferences.

#### **Key Topics in Statistics**:  

1. **Describing a Single Set of Data**:  
   Involves summarizing data using:  
   - **Mean**: Average value.  
   - **Median**: Middle value in sorted data.  
   - **Mode**: Most frequently occurring value.  
   - **Variance**: Measure of data spread.  
   - **Standard Deviation**: Square root of variance, indicating data dispersion.

2. **Correlation**:  
   - Measures the strength and direction of the relationship between two variables.  
   - Values range from \(-1\) (strong negative correlation) to \(1\) (strong positive correlation).  

3. **Simpson’s Paradox**:  
   - A trend that appears in different groups of data can reverse when these groups are combined.  
   - **Example**: In a study, a treatment might seem effective in individual groups but appear ineffective overall.  

4. **Correlation and Causation**:  
   - **Correlation**: Two variables move together.  
   - **Causation**: One variable causes the other to change.  
   - **Key Note**: Correlation does not imply causation.

---

### **3. Probability**  
Probability quantifies the likelihood of an event occurring and forms the basis for many machine learning algorithms.

#### **Key Topics in Probability**:  

| **Topic**                  | **Definition**                                                                                      | **Example**                                                                                      |
|----------------------------|----------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| **Dependence and Independence** | Two events are dependent if the outcome of one affects the other; independent otherwise.            | Flipping two coins is independent, while drawing cards without replacement is dependent.       |
| **Conditional Probability** | Probability of event \(A\) occurring given that \(B\) has occurred: \(P(A|B) = \frac{P(A \cap B)}{P(B)}\). | Calculating the probability of rain given cloudy weather.                                      |
| **Bayes’s Theorem**         | A method to update probabilities based on new evidence.                                            | Diagnosing diseases based on test results.                                                    |

#### **Random Variables and Distributions**:  

| **Term**                    | **Definition**                                                                                      | **Example**                                                                                      |
|-----------------------------|----------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| **Random Variables**         | A variable representing outcomes of a random process (e.g., rolling a die).                       | \(X = \text{outcome of a dice roll}\).                                                          |
| **Continuous Distributions** | Probability distributions for continuous data (e.g., heights).                                    | Normal distribution of human heights.                                                          |
| **The Normal Distribution**  | A symmetric bell-shaped distribution defined by mean (\(\mu\)) and standard deviation (\(\sigma\)). | Heights of adults in a population.                                                             |

#### **The Central Limit Theorem**:  
- States that the sampling distribution of the sample mean approaches a normal distribution as the sample size increases, regardless of the population's distribution.  
- **Applications**: Hypothesis testing and confidence intervals.

---

### **4. Hypothesis and Inference**  

Statistical inference allows us to make conclusions about a population based on sample data.

#### **Key Topics in Hypothesis and Inference**:  

| **Topic**                  | **Definition**                                                                                      | **Example**                                                                                      |
|----------------------------|----------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| **Statistical Hypothesis Testing** | A method to determine if there is enough evidence to reject a null hypothesis (\(H_0\)).         | Testing if a new drug is more effective than the current one.                                   |
| **Confidence Intervals**    | A range of values that likely contains the population parameter with a given confidence level.      | \(95\%\) confidence interval for average height.                                                |
| **P-Hacking**               | Manipulating data or analysis to obtain statistically significant results.                         | Selecting only favorable data to support a hypothesis.                                         |
| **Bayesian Inference**      | Uses Bayes’s theorem to update the probability of a hypothesis as more evidence is obtained.       | Estimating the probability of a disease based on prior data and new test results.              |

---

### **Detailed Examples and Applications**

#### **Example of Conditional Probability**:  
If 30% of emails are spam (\(P(\text{Spam}) = 0.3\)) and 70% of spam emails contain the word "win" (\(P(\text{Win}|\text{Spam}) = 0.7\)), the probability that an email is spam given it contains "win" (\(P(\text{Spam}|\text{Win})\)) can be calculated using Bayes’s Theorem.  

#### **Real-Life Applications**:
1. **Linear Algebra**:  
   - Image processing (converting images to pixel matrices).  
   - Principal Component Analysis (PCA) for dimensionality reduction.  

2. **Statistics**:  
   - Summarizing customer feedback using descriptive statistics.  
   - Correlation analysis in financial markets.  

3. **Probability**:  
   - Risk assessment in insurance.  
   - Predictive text suggestions in messaging apps.  

4. **Hypothesis Testing**:  
   - Evaluating the effectiveness of a marketing campaign.  
   - A/B testing in web design.  

---

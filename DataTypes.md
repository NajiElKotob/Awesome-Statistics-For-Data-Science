# Data Types

{Awesome Works in Progress}

Data types are essential for categorizing information in statistics. They fall into two primary categories: **numerical (quantitative)** and **categorical (qualitative)**. Each has distinct characteristics and subtypes that are crucial for data analysis.

## Numerical (Quantitative) Data

Numerical data represents measurable quantities. It's subdivided into:

### Discrete Data

Discrete data is countable, often represented by integers. For example:

- Number of students in a classroom: `30`
- Total countries in a dataset: `195`

### Continuous Data

Continuous data can take any value within a range and includes:

#### Interval Data

Data with ordered numbers where differences are meaningful but there is no true zero. For example:

- Temperature in Celsius: `20°C, 21°C, 22°C, ...`
- Dates in a year: `January 1, January 2, January 3, ...`

#### Ratio Data

Interval data with a true zero, allowing for a full range of operations. Examples include:

- Weight: `70 kg, 80 kg, 90 kg, ...`
- Distance traveled: `0 km, 5 km, 10 km, ...`

## Categorical (Qualitative) Data

Categorical data reflects characteristics and can be sorted into categories.

### Nominal Data

Nominal data is for labeling without a quantitative value. Examples:

- Blood types: `A, B, AB, O`
- Types of cuisine: `Italian, Chinese, Mexican, Indian`

### Ordinal Data

Ordinal data has an order but not a uniform difference between categories. For instance:

- Survey responses: `Strongly Agree, Agree, Neutral, Disagree, Strongly Disagree`
- Class levels: `Freshman, Sophomore, Junior, Senior`

## Specialized Forms of Data

These are additional data types with specific attributes.

### Binary Data

Binary data has two possible values. Examples:

- Questionnaire with yes or no answers: `Yes (1), No (0)`
- Light switch status: `On (1), Off (0)`

> **binary data** is also referred to as dichotomous, Boolean, yes/no, and sometimes even true/false data. In essence, binary data represents a scenario where there are only two possible outcomes. In programming and logic, Boolean data type is often explicitly used to represent binary values, typically with true or false. In the context of a questionnaire or simple data recording, "Yes" or "No" is a common representation, and in data analysis, such binary outcomes might be coded as 1 or 0 for ease of mathematical computation and logical comparison.

### Interval Data

Interval data with meaningful order and consistent differences, but no true zero. For instance:

- Temperature scale in Fahrenheit: `32°F, 33°F, 34°F, ...`

### Ratio Data

Like interval data but with a true zero, making more operations possible. Examples:

- Money in a bank account: `$0, $100, $200, ...`
- Time taken to complete a task: `0 hours, 2 hours, 4 hours, ...`

-----
  

```
+------------------------+
|   Data Types in        |
|   Statistics           |
+------------------------+
|                        |
+-- Numerical (Quantitative)
|     |
|     +-- Discrete
|     |     |
|     |     +-- (Example) Number of books: 0, 1, 2, ...
|     |
|     +-- Continuous
|           |
|           +-- Interval
|           |     |
|           |     +-- (Example) Temperature: 32°F, 33°F, ...
|           |
|           +-- Ratio
|                 |
|                 +-- (Example) Distance: 0 km, 5 km, 10 km, ...
|
+-- Categorical (Qualitative)
      |
      +-- Nominal
      |     |
      |     +-- (Example) Colors of shirts: Red, Blue, Green, ...
      |
      +-- Ordinal
            |
            +-- (Example) Class levels: Freshman, Sophomore, Junior, Senior, ...
```

-----
## Challenges
* What type of numerical variable best represents shoe sizes such as 40.5, 41, 41.5, etc.?

-----

## Terms
* **Individuals** are the people or things described by a data set.
* **Variables** are characteristics of the individuals that we measure or observe.

-----

## References
* [Individuals, variables, and categorical & quantitative data](https://www.khanacademy.org/math/ap-statistics/analyzing-categorical-ap/xfb5d8e68:language-variation-variables/e/individuals-variables-categorical-quantitative-data) - khanacademy.org
* [What is data?](https://www.ibm.com/think/topics/data) - ibm.com

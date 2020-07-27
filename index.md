---
title: On the Relation between Complexity, Explicitness, Effectiveness of Refactorings and Non-Functional Concerns
---

## NEW: Rebuttal-related files

### Statistical Analysis:

The statistical analysis can be found at: https://github.com/sbes2020refactoring/sbes2020refactoring.github.io/tree/master/statistical%20analysis

### Quantitative Results:

The quantitative results of this work can be found at: https://github.com/sbes2020refactoring/sbes2020refactoring.github.io/tree/master/results

They are split between RQ1, RQ2 and RQ3. The folder "summarized results" contains the full result set (and not only the frequency values)

### Analysis of Refactoring Types:

As mentioned in the Rebuttal, we attempted to analyze the difference between SAR/non-SAR commits for the top 3 refactoring types. These are: Extract Method, Extract Variable and Rename Variable. Out of these, Rename Variable did not have enough data for the analysis. Thus, we settled on analyzing Extract Method and Extract Variable.

The results of this analysis can be found at: https://github.com/sbes2020refactoring/sbes2020refactoring.github.io/tree/master/results-reftypes

### New Keywords Validation:

The results of the validation for the new keyword set proposed by the reviewers of this work, displaying the split between TP/FP/TN/FN, as well as accuracy and recall, can be found at: https://github.com/sbes2020refactoring/sbes2020refactoring.github.io/tree/master/new%20validation

## Used Internal Quality Attribute Metrics

| Metric Name | Internal Quality Attribute | Metric Description |
|-------------|----------------------------|--------------------|
| Cyclomatic Complexity | Complexity | The amount of decision points (e.g., for, while) in a method. |
| Average Cyclomatic Complexity | Complexity | The average of the Cyclomatic Complexity of all methods in a class. |
| Sum Cyclomatic Complexity | Complexity | The sum of the Cyclomatic Complexity of all methods in a class. |
| Max. Cyclomatic Complexity | Complexity | The maximum value for Cyclomatic Complexity in all methods in a class. |
| Max. Nesting | Complexity | The highest amount of nested decision points in a class or method. |
| Lack of Cohesion in Methods | Cohesion | 1 minus the average percentage of usage of instance variables in instance methods in a class. |
| Average FANOUT | Cohesion | The average FANOUT of all methods in a class. |
| Average Coupling | Cohesion | The average amount of external classes accessed by methods in a class. |
| Coupling Between Objects (CBO) | Coupling | The amount of classes coupled to the current class. |
| FANOUT | Coupling | The number of external variables and functions used by a method. |
| FANIN | Coupling | The number of paramters read by a method, plus the amount of unique methods calling the current method. |
| Lines of Code (LOC) | Size | The number of lines of code in a given class or method. |
| Number of Statements | Size | The amount of statements, regardless of lines, in a given class or method. |
| Instance Variables | Size | The amount of instance variables in a class. |
| Instance Methods | Size | The amount of instance methods in a class. |

## List of Refactorings used in this work:

| | | | |
|---------|---------|---------|---------|
| Extract Method | Inline Method | Rename Method | Move Method |
| Move Attribute | Pull Up Method | Pull Up Attribute | Push Down Method |
| Push Down Attribute | Extract Superclass | Extract Interface | Move Class |
| Rename Class | Extract and Move Method | Change Package (Move, Rename, Split, Merge) | Move and Rename Class |  
| Extract Class | Extract Subclass | Extract Variable | Inline Variable |
| Parameterize Variable | Rename Variable | Rename Parameter | Rename Attribute |
| Move and Rename Attribute | Replace Variable with Attribute | Replace Attribute (with Attribute) | Merge Variable |
| Merge Parameter | Merge Attribute | Split Variable | Split Parameter |
| Split Attribute | Change Variable Type | Change Parameter Type | Change Return Type |
| Change Attribute Type | Extract Attribute | Move and Rename Method | Move and Inline Method |
| Add Method Annotation | Remove Method Annotation | Modify Method Annotation | Add Attribute Annotation |
| Remove Attribute Annotation | Modify Attribute Annotation | Add Class Annotation | Remove Class Annotation | 
| Modify Class Annotation | Add Parameter | Remove Parameter | Reorder Parameter |

## List of SAR Keywords and Phrases
### (\*) indicates that any character can follow (e.g., refactor*: refactoring, refactored)

| | | | |
|---------|---------|---------|---------|
| "refactor*" | "renam*" | "cleanup*" | "reorganiz*" |
| "simplif*" | "restructur*" | "encapsulat*" | "rewrit*" |
| "inlin*" | "reformat*" | "decompos*" | "change design" |
| "code optimization" |  "optimize the code" |  "polishing code" |  "replace it with" |
| "coupling" | "cohesion" | "reduce complexity" | |

## List of NFR Keywords

### Maintainability

| | | | |
|---------|---------|---------|---------|
| "maintainability" | "maintenance" | "reliability" | "serviceability" |
| "accordance" | "measures" | "requirements" | "index" |
| "update" | "release" | "production" | "addition" |
| "budget" | "integration" | "operation" | |

### Performance

| | | | |
|---------|---------|---------|---------|
| "performance" | "rate" | "bandwidth" | "cpu" |
| "time" | "latency" | "throughput" | "channel" |
| "instruction" | "response" | "process" | "communication" |
| "space" | "memory" | "storage" | "peak" |
| "compress" | "uncompress" | "runtime" | "perform" |
| "execute" | "dynamic" | "offset" | "reduce" |
| "response" | "longer" | "fast" | "slow" |
| "maximum" | | |

### Robustness

| | | | |
|---------|---------|---------|---------|
| "robust" | "robustness" | "inputs" | "error" |
| "failure" | "network" | "error" | "reliability" |
| "serviceability" | "fault" | "tolerance" | "exception" |

### Security

| | | | |
|---------|---------|---------|---------|
| "access" | "author" | "ensure" | "data" |
| "authentication" | "security" | "secure" | "malicious" |
| "prevent" | "incorrect" | "harmful" | "state" |
| "exception" | | |

## Results of the Manual Validations

The results of the manual validations can be found in the following folder, divided into SAR and NFR validations, in CSV files. This folder is in the following link: [GitHub](https://github.com/sbes2020refactoring/sbes2020refactoring.github.io/tree/master/validations)

## Data Set

The data set used for this work is available in the following folder, divided into two zip files. One contains the extracted metrics for the projects, through Understand, while the other contains the extracted developer discussions through the GitHub API. This folder is in the following link: [OneDrive](https://1drv.ms/u/s!Akv4ikLFTtOtbxloCKdb1ejtCOw?e=eDc2vR)

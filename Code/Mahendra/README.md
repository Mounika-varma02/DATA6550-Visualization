# DATA6550-Visualization
## Objective

- Analyse survival patterns in the Titanic dataset 891 passengers through accurate and deliberately misleading line chart visualisations, demonstrating how design choices shape audience interpretation of the same underlying data.
## Methods

**Data Source:** Titanic dataset (titanic.csv)

**Tools:** Python, Pandas, Matplotlib, Seaborn

**Process:**

** Survival rates were calculated by taking the mean of the binary Survived column, then broken down by group using Pandas groupby() operations.
** Accurate charts were built with full 0–100% axes, all groups included, sample sizes labelled on each point, and a shaded band to reflect uncertainty.
** Misleading charts used the same data but applied truncated axes, removed inconvenient groups, swapped rates for raw counts, and added titles that implied causation where none was proven.
## Key Findings

** First-class passengers survived at significantly higher rates than second and third class, and this held true across all three embarkation ports.
** Children aged 0–12 had the highest survival rate of any age group at around 59%, a finding that disappears entirely when that group is quietly left out of the chart.
** Higher fare deciles showed better survival odds, but fare was mostly a reflection of passenger class and cabin location rather than a cause of survival in its own right.

## Ethical Considerations

** Starting a y-axis at 15% instead of 0% makes gradual differences look dramatic — a small design choice with a big impact on perception.
** Dropping the Child age group or filtering out Southampton passengers removes inconvenient context without technically lying about the data.
** Titles that claim causation rather than correlation push viewers toward conclusions the data does not actually support.
** Every chart carries a responsibility to the audience — honest scaling, complete categories, and careful wording are not optional extras, they are the baseline.

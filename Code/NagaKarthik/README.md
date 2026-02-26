# DATA6550-Visualization
## Objective

- The objective of this project is to analyze survival patterns in the Titanic dataset using gender and port of embarkation, and to compare accurate visualizations with an intentionally misleading chart to highlight the importance of ethical and transparent data presentation.
## Methods

**Data Processing:** Utilized pandas for cleaning and segmenting the Titanic training dataset ($n=891$).

**Visualization:** Employed matplotlib to design and refine pie charts, focusing on two specific dimensions: Gender-Based Survival and Port of Embarkation.

**Comparative Analysis:** Developed a "Best Practices" vs. "Deceptive Design" methodology to contrast transparent visualizations with those that use manipulative visual effects and selective data inclusion.
## Key Findings

**Gender Survival:** An honest breakdown shows significant survival disparities, with females having a 74.2% survival rate compared to 18.9% for males.

**Port Distribution:** Southampton was the primary embarkation point (644 passengers), yet it recorded the lowest survival rate (33.7%) compared to Cherbourg (55.4%) and Queenstown (39.0%).

**Impact of Omission:** Removing the largest data group (Southampton) completely shifts the narrative from one of mass tragedy to one of relative survival success, demonstrating how easily a "majority story" can be erased.

## Ethical Considerations

In this project, ethical visualization practices were a key focus. All relevant categories were included in each chart to ensure no data was hidden or misrepresented. Axes and scales were carefully maintained to avoid exaggerating differences or misleading viewers. Clear titles, labels, and percentages were provided so that anyone reviewing the charts could accurately interpret the data. Misleading visualizations were intentionally created and clearly marked to demonstrate common pitfalls, highlighting the importance of transparency and honesty in data presentation.

## Conclusion

The project concludes that data visualization is a powerful communication tool that carries a heavy moral responsibility. It reinforces that a data scientist’s foremost duty is to prioritize integrity, completeness, and transparency. Insights must always reflect the true story of the data rather than a manipulated narrative designed to fit a specific agenda.

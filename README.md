# A Review and Collation of Graphical Perception Knowledge for Visualization Recommendation (CHI 2023)

### **paper-list.csv**

All candidate papers in our literature review, including papers that are included / excluded for our analysis.

### **data (JSON files)**

It stores our data from the literature survey. The results of each paper are stored in a single json file, labeled with the last name of the first author, the paper published year and the first word of the paper.

### **improved-color-scheme**

The Vega-Lite specification for the color scheme suggested by Demiralp et al.

### **JSON-to-Draco**

- **to_Draco.py**: the script to translate our datasets into the training dataset for Draco-Learn
- **Draco-Learn-Input**: Results of to_Draco.py. Ranked Visualization pairs as training dataset for Draco-Learn.

# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    Microsoft Excel (Bar Graph) and Python/Matplotlib (Line Graph)

    > Who is your intended audience? 
    Regular Public who is interested to see the Gaseoline tax price changes over years

    (participation/A3_GasTaxRates_Excel_v2.jpg)

    (participation/GaseolineTaxOverYears_withPython.png)
    
    > What information or message are you trying to convey with your visualization? 
    Unleaded and Leaded regular fuel type tax trend over years.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    Decluttered unnecessary columns by dropping them. Descriptive labels and Title was used. Contrast colours were used for accessibility.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Historical data is SORTED to keep the tax year in ascending order for the reproducibility. The code is created using open source software (with Python code) and commented. The excel graph is reproducible as the data used is included in screenshot.
    
    > How did you ensure that your data visualization is accessible?  
    The url of the datasource is included in the source code and pandas read_csv directly fetches the data from Open data source.
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    Creates public awareness and encourages people to buy non-leaded fuel for reduced taxes and environment.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    This is a simple dataset with few features. The intention is to create awareness and benefit of purchasing non-leaded fuel. So the Aircraft fuel taxes, Premium fuel taxes and propane taxes have been discarded as majority of public buys regular fuel.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    Data inspection and Feature selection. Open source libraries are used and their contributors are also contributed to this effort.

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 02/23/2026`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * Two distinct data visualizations (for example, PNGs, PDFs, or screenshots)
        * Two Markdown files answering all questions for each visualization (including a link to your dataset in both files)
        * One Python file contains the complete code and visualization, and another file (with or without code) contains the visualization.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.

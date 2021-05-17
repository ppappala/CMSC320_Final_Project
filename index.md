## Analyzing Maryland Crashes from 2015 to 2020 by Pranav Pappala

The start of this data analysis starts with a personal observation.

Maryland is notorious for bad drivers and bad driving. Personal story, my parents' car insurance used to be 300 dollars with me, and that was a really good deal due to their safe driving habits and good credit. The moment we moved to Maryland, that number close to tripled and reached roughly 1000 dollars. I learned that the main reason why that figure shot up was because Maryland drivers got into a lot of crashes, so to compensate, the premiums from the insurance companies went up quite a bit.

So, I was motivated to understand what factors can predict a crash with Maryland vehicles, so I looked at the official Maryland open data websites funded by the state government.

Here are the libraries that were used as well as references to them for future data science use

Numpy -> used for certain mathematical functions that make predictions easier

Pandas -> used to place data from files and place them in dataframes

Matplotlib -> used to help plot data in a 2D figure for simple analysis

Scikit-learn -> used to help create predictive model for crash severity

Seaborn -> used to help plot and highlight correlations in data

Folium -> used to help map Maryland as well as the crashes that occurred

The first dataset is a CSV file of Maryland statewide vehicle crashes garnered from official crash reports which was retrieved from this website: https://opendata.maryland.gov/Public-Safety/Maryland-Statewide-Vehicle-Crashes/65du-s3qu

The second dataset is a CSV file of vehicle details garnered from the exact same set of official crash reports which was retrieved from this website: https://opendata.maryland.gov/Public-Safety/Maryland-Statewide-Vehicle-Crashes-Vehicle-Details/mhft-5t5y

With that personal story in mind, I wanted to focus on some of the aspects behind the severity of a crash in Maryland. Do some crashes happen more in certain areas of Maryland than others? Do some features (like road conditions or daylight conditions) suggest a crash is more likely to happen?

I would also like to determine correlations between damage and movement descriptions to see if there is a certain type of movement that causes worse crashes than others. I want to create a correlation matrix for the vehicle type in the crash to find out if correlations exist between items such as the model and severity using seaborn, or vehicle year and damage.

To end this all, could one predict the damage done to a vehicle in a crash using only a select few features with decent correlation?

You can use the [editor on GitHub](https://github.com/ppappala/CMSC320_Final_Project/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
import pandas as pd

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ppappala/CMSC320_Final_Project/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

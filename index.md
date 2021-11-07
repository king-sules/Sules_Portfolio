# Welcome To My Portfolio! I have listed projects I have done in the past. 
### Categories are organized by: Machine Learning, Data Analysis, and Mechanical Engineering


## Machine Learning
### [Project 1: Housing Prices vs. Nuclear Power Plants](https://github.com/king-sules/Nuclear_Matrix_Data)
The following is my python and R codes I used for my undergraduate thesis paper. The basis of my paper was to capture house price variation with distance from a nearby nuclear power plant. I used the town of Plymouth, Massachussets for my house data. 

I continued to clean, and later find correlations in my data. Prices were originally listed in my dataset, but distance was obtained using geopy and geopandas library. By using these libraries, I obtained distance from each individual house listed to the power plant.

My paper essentially looked at how the Fukushima Daiichi event effected house prices. I created a new column in my dataset, a Fukushima dummy, where a value of 1 was assigned if the indivial house sold after 2011 and 0 before 2011. I also categorically grouped my distance column, in incriments of 4 miles, to control price variation in rural areas.

Lastly I used R to run multiple regressions.


<img width="300" img height="300" alt="plymouth" src="https://user-images.githubusercontent.com/54907087/140659135-7cc55f6b-087c-4d19-9b3c-298bfdbbee41.png">




All of my codes are listed in this repository and I also included an original sample of data I recieved for the year 2007, which can be ran through each file.

[Here is the full thesis paper](https://github.com/king-sules/Nuclear_Matrix_Data/blob/master/Final%20Thesis.pdf)

### Project 4: Airplane Wing Vibration Analysis
In this project I analysized a sample airplane wing to determine the effects of vibration towards the whole airplane. 

The wing was experimentally divided into many degrees of freedom, and furthermore vibration modes were determined with the help of a Matlab code I created. 

Results were also visualized with ANSYS software.

Full report was created with latex and can be found here
You can use the [editor on GitHub](https://github.com/king-sules/Sules_Portfolio/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/king-sules/Sules_Portfolio/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

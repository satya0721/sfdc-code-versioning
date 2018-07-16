## Welcome to Salesforce Code Versioning Guide

When we got a deadline of 1 week for implementation of a code versioning for our project's Salesforce org, we headed over to Google assuming it would take just 2 days for this implementation. But we were wrong. There were very few resources which provided steps for achieving this. ***Challenge Accepted***

Based on a colleague's suggestion, we decided to use Bitbucket + Bamboo for a quick proof of concept. After the proof of concept was successful, we tried to understand the basic concepts behind the different alternatives. So, we tried the below combinations after our proof of concept : 
1. Bitbucket + Jenkins
2. Github + Bamboo
3. Github + Jenkins
4. Bitbucket + Pipelines (our ultimate choice)

So here it goes. 

First : 
We need to setup a repository for our Salesforce metadata. In our case, we wanted to have a repository only for Apex Classes, Triggers & Visualforce pages. 

Headover to bitbucket.org. Open a new 


Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block
MY FIRST PAGE
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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/satyajeetmaharana/sfdc-code-versioning/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

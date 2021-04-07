# Process Simulation of Methanol Production from Syngas

**Author:** [Rajdeep Dev](https://rajdeepdev10.github.io)  
**UBC ID:** 71666887

<img src="./assets/images/cover-image.jpg" alt="chemical plant" width="400"><br>
*image_caption*

## Process Description

This project will focus on the production process of methanol from syngas. Syngas is a fuel mixture produced from natural gas that consists primarily of hydrogen, carbon monoxide, and carbon dioxide with small amounts of water, nitrogen, and methanol. On an industrial scale, methanol is predominantly produced from the reaction of hydrogen with carbon monoxide and carbon dioxide. The resulting gas mixture is then distilled to create pure methanol [1]. This process is comprised of the following reactions is carried out at varying conditions [2]:

<div align="center">
  CO + 2H<sub>2</sub> ⇌ CH<sub>3</sub>OH (1)
  CO<sub>2</sub> + 3H<sub>2</sub> ⇌ CO + H<sub>2</sub>O (2)
  CO + H<sub>2</sub>O ⇌ CO<sub>2</sub> + H<sub>2</sub> (3)
</div>

Reaction 1 and 2 is carbon dioxide and carbon monoxide hydrogenation reaction to methanol. These reactions produce high amounts of crude methanol which is needed to purify by distillation. The operating condition is between 50-100atm and 250°C [3]. Reaction 3 is known as “water-gas shift reaction” where carbon monoxide and steam are reacted using a catalyst to produce carbon dioxide and more hydrogen. The products from this reaction are recycled back to the hydrogenation reaction so it can work as reagents. Reaction 1 and 2 is endothermic reaction so low temperature and high pressure is favorable whereas water gas shift reaction is exothermic reaction. Catalysis will be ignored in this process simulation for each of the reactions.

### Sample Chemical Reaction

H<sub>2</sub>SO<sub>4</sub> + 2NaOH &rarr; 2H<sub>2</sub>O + Na<sup>+</sup> + SO<sub>4</sub><sup>2-</sup>

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

markdown
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


For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/rajdeepdev44/jekyll-test-2/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

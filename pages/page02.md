### This is page 2

![AI tiers]({{ site.baseurl }}/Resources/AI_tiers.png){: width="600px" }

#### Here is some fenced code
````markdown
### This is a markdown header, level 3
<!-- 
Note in the following, I use the ../ to go up one directory level
to access the Resources folder.
-->
#### This is an image from Resources:
![green_folder]({{ site.baseurl }}/Resources/green_folder.png)

#### Two images from Resources on same line:
![green _folder]({{ site.baseurl }}/Resources/green_folder.png) ![blue_folder](/Resources/blue_folder.png)
#### Using image to link back to home page:
````
#### This demonstrates how to access the variables defined in the _config.yml file:
The site title is: {{ site.title }}

The site theme is: {{ site.theme }}

The site description is: {{ site.description }}

The site baseurl is: {{ site.baseurl }}

The site url is: {{ site.url }}



#### Return to opening page (home):
[home]({{ site.baseurl }}/index.html)
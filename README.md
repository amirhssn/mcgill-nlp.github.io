# Group Website

## Installation & Setup

1. Install Ruby
2. Clone `git clone https://github.com/McGill-NLP/group-website.git && cd group-website`
1. Install dependencies `bundle install`
5. Serve the site: `bundle exec jekyll serve`

## Update contents
### Home page
Just open `index.html`, and start modifying it.

### Add news
Create a `.md` file under the `_news` directory. Here is the format
```markdown
---
date: 2020-11-07T10:00:00+3:30
---
The news content is placed here, and it supports markdown formatting.
```

### People page
Open `_data/people.yml`. This file should follow the this format:
```yml
faculty:
  - name: John Smith
    affiliation: Computer Science & Linguistics
    avatar: img/people/john.jpg
    url: https://john-smith.com (optional)
    research_areas: Area #1, Area #2, and Area #3 (optional)
    desc: some desc (optional)
  
  - name
    ...

postdoc:
  - name: John Smith
    affiliation: Computer Science & Linguistics
    avatar: img/people/john.jpg
    url: https://john-smith.com (optional)
    research_areas: Area #1, Area #2, and Area #3 (optional)
    co_supervisor: John Smith 2 (optional)
    desc: some desc (optional)
  
  - name
    ...

phd:
  - name: John Smith
    affiliation: Computer Science & Linguistics
    avatar: img/people/john.jpg
    url: https://john-smith.com (optional)
    research_areas: Area #1, Area #2, and Area #3 (optional)
    co_supervisor: John Smith 2 (optional)
    desc: some desc (optional)
  
  - name
    ...

msc:
  - name: John Smith
    affiliation: Computer Science & Linguistics
    avatar: img/people/john.jpg
    url: https://john-smith.com (optional)
    research_areas: Area #1, Area #2, and Area #3 (optional)
    co_supervisor: John Smith 2 (optional)
    desc: some desc (optional)
  
  - name
    ...


undergrad:
  - name: John Smith
    affiliation: Computer Science & Linguistics
    avatar: img/people/john.jpg
    url: https://john-smith.com (optional)
    research_areas: Area #1, Area #2, and Area #3 (optional)
    co_supervisor: John Smith 2 (optional)
    desc: some desc (optional)
  
  - name:
    ...

alumni:
  - name: John Smith
    last_position: MSc
    leave_year: 2020
    current_position: Ph.D. at Mila (optional)
    url: https://john-smith.com (optional)

  - name:
    ...
```
You should put the images in `img/people/`

### Publications page
To add a new publication, create a `.md` file under the `_publications` directory. Follow the below format:
```markdown
---
title: The paper title should be here
authors: Author 1, Author 2, Author 3, Author 4, and Author 5     
year: 2020
venue: EMNLP 2020
sitemap: false
date: 2020-11-07

// Optional
other_desc: Other Descripion 
red_note: "*Won the Best Paper Award" (optional)

// Optional
// If you want to link this paper to a project, just add the following line. 
// If the project filename is my_project.md, then the id is as follows:
project_id: /projects/my_project

// (Optional)
links: 
    - url: https://path.to.pdf.com
      name: PDF
    - url: https://path.to.code.com
      name: Source Code
    - url: https://google.com
      name: Project Page
    - url: https://path.to.dataset.com
      name: Dataset
    - url: https://path.to.demo.com
      name: Demo
    - url: https://path.to.bibliography.com
      name: BIB
    - url: https://other.com
      name: some other link
---
```

### Projects page
Add a new `.md` file like this in the `_projects` directory:
```markdown
---
title: Project Title
img: /img/projects/project.img

// Optional
key_people: Person 1, Person 2, Person 3, and Person 4
---
The project description should be provided here. It supports **markdown**
Lorem ipsum dolor sit amet, consectetur adipiscing elit. In vehicula sodales felis vel tincidunt. Praesent sagittis imperdiet nibh, nec varius metus malesuada sed. Quisque finibus venenatis justo a blandit. Sed placerat, dui sit amet aliquet iaculis, nisi mi interdum ex, non elementum eros tellus non libero. Maecenas at accumsan ligula. 

Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Vestibulum vitae nulla nisi. Etiam imperdiet justo a facilisis molestie. In sit amet ipsum semper, tincidunt neque vitae, vulputate turpis. Nam vulputate interdum laoreet. Integer convallis efficitur nibh, vitae pellentesque felis.
```

### Resources page
Update `resources.md`. It doesn't have any specific format.

## About

Start Bootstrap is an open source library of free Bootstrap templates and themes. All of the free templates and themes on Start Bootstrap are released under the MIT license, which means you can use them for any purpose, even for commercial projects.

* <https://startbootstrap.com>
* <https://twitter.com/SBootstrap>

Start Bootstrap was created by and is maintained by **[David Miller](http://davidmiller.io/)**.

* <http://davidmiller.io>
* <https://twitter.com/davidmillerskt>
* <https://github.com/davidtmiller>

Start Bootstrap is based on the [Bootstrap](https://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2013-2020 Start Bootstrap LLC. Code released under the [MIT](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll/blob/gh-pages/LICENSE) license.

## Welcome to Newdle site

**Newdle** is the new, shiny tool brought to you by the [Indico Team](https://getindico.io/about/) @ [CERN](https://home.cern/). Here at CERN we **hold a lot of meetings**. While [Indico](https://getindico.io/) makes it super easy to manage those meetings, we still **lose a lot of time** trying to schedule them, which usually involves numerous emails and private messages. That is what newdle has been created for: to streamline the process of choosing **the perfect date and time** for your next meeting/event.

Newdle is part of the [MALT project](https://malt.web.cern.ch/malt/).

### Why another tool?

It's true that there are already several commercial and Open Source solutions available that provide ad-hoc "polls". However, we have noticed that none of those tools seem to offer, at the same time, a user-friendly and modern interface and the additional freedom and flexibility that come with being part of an Open Source ecosystem. Additionally, none of them seem to seamlessly integrate with other enterprise systems.

#### Integration

Newdle can currently fetch free-busy information from **Exchange servers**. This information can be used while deciding on candidate slots ("when is everyone free?") as well as when answering to a "poll" ("when am I free?"). We are currently working on integrating with other providers.

Newdle is also developed by the same people who are behind [Indico](https://getindico.io/), and that's not by pure chance. newdle naturally complements Indico, as it targets what comes immediately before the actual creation of a meeting. This is why we would like to have the possibility to **create meetings on Indico** once a final date is decided (still work in progress!).


### Development

We chose Python 3.8 as the backend language, so make sure you have it installed. To prepare the development environment it is enough to run ```markdown make ``` which takes care of installing all required dependencies inside a new virtualenv. Typically that will be the ```markdown .venv ``` directory unless you override the environment variable ```markdown VENV``` e.g. ```markdown VENV=.virtualenv make```. Activate your virtualenv using ```markdown source .venv/bin/activate``` since this is required to run the various flask comments that come later.

Make sure you have the ```markdown python3.8``` binary in your PATH. You can also use the ```PYTHON``` environment variable to override the location of the ```markdown python``` binary. e.g.:

```markdown $ PYTHON=/usr/bin/python3.8 make ```


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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Caetan95/newdle.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

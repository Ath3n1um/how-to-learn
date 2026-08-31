# Structure 
The project is organized like this:

```
|-- assets/                    (global)
|-- docs/
|   |-- EN/
|   |   |-- Assets/ (language dependant)
|   |   |-- Sections.md
|   |-- ES/
|   |   |-- Assets/ 
|   |   |-- Sections.md
|-- README.md
|-- README.es.md
|-- LICENSE
|-- CONTRIBUTING.md
|-- .gitignore
|-- zensical.toml
```

every Section.md is a single Markdown file where there is only one H1 heading 
It's done with [zensical](https://zensical.org/) based on Markdown, the configuration is in zensical.toml 

# Issues 
Before creating an issue, verify that it has not been closed or opened already
- Specify: Title of the section, Source (if needed)

# Modify or Add/Delete Content 

- Make sure that changes in case of techniques or factors are supported by a reliable source
- When consulting sources, have the following priority: meta-analysis > systematic reviews > individual studies
- Translate the changes to the other languages or specify that translation is pending


## Copyright 
As the project has the CC-BY-SA 4.0 license, avoid violating copyright when adding/removing or modifying content.

# Building 
```
git clone https://github.com/Ath3n1um/how-to-learn.git
cd how-to-learn
```

Follow the zensical install instructions based on your device on https://zensical.org/docs/get-started/

## Preview
run the command:
```
zensical serve
```

## Build
```
zensical build
```

# PlantUML

How can you add plantUML diagrams to your repositories. We would be using [PUML for Markdown](https://github.com/danielyaa5/puml-for-markdown)

### Steps
1. Install puml-for-markdown : `npm i -g puml-for-markdown`
2. Write all the PlantUML file in a file with the extension `.puml` (use vs code extension for previewing PlantUML diagram while creating it).
3. Embed the PlantUML diagram in the readme.md file this way : `<!--[Example With Only Link](./example.puml)-->`
4. Run ```puml-for-markdown``` in the root directory. 
[Example With Only Link](https://tinyurl.com/225p775n)<!--[Example With Only Link](./PlantUmlDiagrams/example.puml)-->
5. Now, you would be having a link. If you just add `!` in the beginning in the beginning of `[Example With Only Link](https://tinyurl.com/225p775n)`. You would be able to embed the plantUML.

![Example With Only Link](https://tinyurl.com/225p775n)

### Pro Tip
1. When you click on the link, you will be taken to a plantUML website : https://www.plantuml.com/plantuml/svg/SoWkIImgAStDuNBCoKnELT2rKt3AJx9IA4ajBk7ooi_80uauvkKbAbWfPAJcvEGJhSutCIyzNq4N95nGa9FAvP2QbmAq9mK0%7D

  replace `/svg` or `/png` with `/uml` to get back the PlantUML code online.

### More Resources
1. https://github.com/danielyaa5/puml-for-markdown
2. https://github.com/plantuml-stdlib/C4-PlantUML
3. Another Option : Mermaid : https://mermaid.js.org/intro/
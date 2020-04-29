# plantuml-ifstyle
innFactory PlantUML Styling for awesome uml diagrams.

# Usage
Install [plantuml](https://plantuml.com/) and the vscode plugin. 

Add this to the top of your .puml file after @startuml:

```plantuml
!define DARK
!define COLOREDTYPES
!define WATERMARK
!includeurl https://raw.githubusercontent.com/innFactory/plantuml-ifstyle/master/innfactorystyle.puml
```

You can switch to light theme by define LIGHT instead of DARK. If you don't need the colored typed like in the database diagram just remove COLOREDTYPES definition. If you want to remove the watermark just remove the WATERMARK definition. The default font is "Roboto". You have to install it first. Sometimes the style tag does not work. You can remove it when you define NOSTYLE.

# Examples
Example Code under /examples.

## Grouped Components
<img src="examples/groupedcomponent.svg" width="450px" alt="Grouped Components" />

## Datebase
<img src="examples/database.svg" width="450px" alt="database" />

## Activity
### Simple
<img src="examples/activity.svg" width="450px" alt="activity" />

### Compley parallel
<img src="examples/activity-par.svg" width="450px" alt="activity2" />

## Mindmap
<img src="examples/mindmap.svg" width="450px" alt="mindmap" />

## Deployment Items
<img src="examples/deployment-items.svg" width="450px" alt="deployment" />

## WBS
<img src="examples/wbs.svg" width="450px" alt="wbs" />

# Credits
[innFactory.de](https://innfactory.de)
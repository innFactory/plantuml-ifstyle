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

You can switch to light theme by define LIGHT instead of DARK. If you don't need the colored typed like in the database diagram just remove COLOREDTYPES definition. If you want to remove the watermark just remove the WATERMARK definition. The default font is "Roboto". You have to install it first.

# Examples
Examples are in the example folder.

## Grouped Components
<img src="examples/groupedcomponent.svg" width="400px" alt="Grouped Components" />

## Datebase
<img src="examples/database.svg" width="400px" alt="database" />

## Activity
<img src="examples/activity.svg" width="300px" alt="activity" />


# Credits
[innFactory.de](https://innfactory.de)
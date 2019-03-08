# Command Line Parameters

| Command    | Description           | 
| ------------- |:------------- 
| `@filename`     | Specifies a response file that contains LSACreator.exe commands. Commands in the response file can appear one per line or on the same line, separated by one or more spaces. | 
| `/build`    | Build project.      |   
| `/buildwithexport` | Build project (if `/build`) and export output to libraries locations.     |  
| `/buildtodir:dirname` | Build project and export output to specified diretory (dirname).      |  
| `/close` | Close program after process command line.     |  
| `/create` | Create a new project (`/project`:filename) and overriding the file if exists.      |  
| `/exportxml:filename` | Export project to xml file (filename).     |  
| `/ignoreempty` | Ignores assemblies without resources.     |  
| `/library:filename` | Add assembly (filename) to project.    |  
| `/librariesdir:dirname` | Add assemblies from specified directory (dirname) to project.      |  
| `/project:filename` | Project file location.      |  
| `/save` | Save project.      |  
| `/showgui` | Force to show GUI in auto close mode (`/close`).      |  
| `/xmlsource:filename` | Import project from xml file (filename) in merge mode using project (`/project`:filename) as primary source.  |  
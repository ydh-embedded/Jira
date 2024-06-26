_________________________________________________________________________


_________________________________________________________________________

# Jira
_________________________________________________________________________

### CSV Import:

```csv
software, Project Name, Sample Project, Issue Type, Summary, Assignee, Reporter, Description, Priority, Fix Version, Component, Labels, Project Key, Project Name
, bug, "First issue", bob@example.com, bob@example.com, "This is a bug", High, v1, Component1, Label1, SAMP, Sample Project
, bug, "Second issue", bob@example.com, bob@example.com, "This is another bug", Medium, v2, Component1, Component2, SAMP, Sample Project
, task, "Third issue", alice@example.com, alice@example.com, "This is a task", Low, v1, v2, v3, Component1, EXAM, Example Project
```

.

```csv
software,Summary,Description,Assignee,Reporter,Priority,Labels,Component,Project Key,Project Name
```


### CSV file
Then, you'll need to map the columns in your CSV file to the corresponding Jira fields. For example:

- `Card Name` -> `Summary`
- `Description` -> `Description`
- `Members` -> `Assignee`
- `Labels` -> `Labels`
- `Board Name` -> `Project Name`
- `List Name` -> `Component`

You may need to create custom fields in Jira to match the columns in your CSV file. Once you've modified the header row and mapped the columns, you should be able to import the CSV file into Jira successfully.

### IFTTT-Format
#### Erstellen Ihrer ersten Regel

- Regeln sind Automatisierungen, die Sie im IFTTT-Format (If This, Then That – wenn, dann) definieren. Damit können Sie repetitive Aufgaben automatisieren.

Jede Regel wird durch die Kombination verschiedener Komponenten erstellt:

	- Wann: Trigger hinzufügen
	- Wenn: Bedingung hinzufügen
	- Für   jedes Element: Branch hinzufügen
	- Dann: Aktion hinzufügen

### config

![[Jira - config.png]]
!(bild)[./screen/Jira%-%config.png]
# Object Naming Criteria for SMML Schema Files and Folders
You can name SMML schema files and folders by following the object-specific naming criteria for maximum character length, spaces, unsupported characters, and unique naming rules.

|Object Type &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|Unique Naming Rules|Maximum Length (characters)|Leading/Trailing Blank Spaces Allowed|Unsupported Characters &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
|---|---|---|---|---|
|Business Model| None|128|No|Asterisk (*)</br> Question mark (?)</br> Single quote (')|
|Catalog Schema|None|128|Yes|Asterisk (*)</br> Question mark (?)</br> Single quote (') |
|Connection Pool|None|128|Yes|Asterisk (*)</br> Question mark (?)|
|Database|None|128|Yes|Asterisk (*)</br> Question mark (?) |
|Initialization Blocks|None|128|Yes| Asterisk (*)</br> Question mark (?)|
|Logical Table|None|128|No|Asterisk (*)</br> Question mark (?)</br> Single quote (') |
|Logical Column</br> Logical Level</br> Logical Table Source|None|128|No|Asterisk (*)</br> Question mark (?)</br> Single quote (')|
|Physical Table</br> Physical Table Alias|Use unique physical table and unique physical table alias names. You can't use the same names when the object shares a parent.|128|Yes|Asterisk (*)</br> Question mark (?)|
|Presentation Table|Use unique presentation table names. You can't share the same name as the parent subject area.|128|No|Asterisk (*)</br> Question mark (?)</br> Single quote (')|
|Presentation Column</br> Presentation Hierarchy</br> Presentation Level|None|128|No|Asterisk (*)</br> Question mark (?)</br> Single quote (')|
|Subject Area|Use unique subject area names. You can't use the same name for any child tables.|128|No|Asterisk (*)</br> Question mark (?)</br> Single quote (')|
|Variable|Use unique variable names. You can't use the same name as any other variable associated with any initialization block in the semantic model.|128|Yes|Asterisk (*)</br> Question mark (?)| 

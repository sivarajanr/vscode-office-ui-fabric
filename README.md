# Office UI Fabric Snippets
A set of Office UI Fabric Snippets for Visual Studio Code. Create a new HTML document and type 'fabric' to see all available snippets.

[Office UI Fabric Documentation](http://dev.office.com/fabric/components)
#### Supported Version: Office UI Fabric 3.0.0 Beta 2
####Please submit issues or suggestion to [Office UI Fabric Snippets](https://github.com/sivarajanr/vs-snippets-office-ui-fabric/issues)
![alt text](http://sivarajan.me/output.gif "Code Snippet")
## Available Snippets

### Breadcrumb
Snippet | Description
--- | ---
fabric-breadcrumb-script | To instantiate all Breadcrumbs on the page. Insert this snippet in the header tag.
fabric-breadcrumb | Breadcrumb
fabric-breadcrumb-item | Breadcrumb Item

### Button
Snippet | Description
--- | ---
fabric-button | Default Button 
fabric-button-primary | Primary Button
fabric-button-command | Command Button. [For more icons](http://dev.office.com/fabric/styles)
fabric-button-compound | Compound Button
fabric-button-hero | Hero Button

### Callout
Snippet | Description
--- | ---
fabric-callout | Callout
fabric-callout-action | Includes buttons to take action
fabric-callout-close | Callout with close icon
fabric-callout-oobe | Draws attention to one aspect of the application during a product tour
fabric-callout-peek | A smaller callout with an action

### Choice Field / Checkbox / Choice Field Group
Snippet | Description | Dependency Snippet
--- | --- | ---
fabric-choicefield | Radio option |
fabric-checkbox | Checkbox option |
fabric-choicefield-group | Multiple options | fabric-choicefield, fabric-checkbox

### Command Bar
Snippet | Description | Dependency Snippet
--- | --- | ---
fabric-commandbar-script | To instantiate all Command Bar components on the page. Insert this snippet in the header tag. |
fabric-commandbar | Command Bar | fabric-commandbar-search-item, fabric-commandbar-item 
fabric-commandbar-search-item |  |
fabric-commandbar-item |  |

### Contextual Menu
Snippet | Description | Dependency Snippet
--- | --- | ---
fabric-contextual-menu-script | To instantiate all Contextual Menu components on the page. Insert this snippet in the header tag. |
fabric-contextual-menu | Default Contextual Menu | fabric-contextual-menu-{header-item, item, divider-item, submenu-item}
fabric-contextual-menu-multi-select | Default Contextual Menu | fabric-contextual-menu-{header-item, item, divider-item, submenu-item}
fabric-contextual-menu-item | |
fabric-contextual-menu-divider-item | |
fabric-contextual-menu-header-item | |
fabric-contextual-menu-submenu-item | |

###Date Picker
Snippet | Description | Dependency Snippet
--- | --- | ---
fabric-datepicker-script | To instantiate all Date Picker components on the page. Insert this snippet in the header tag. |
fabric-datepicker | Default Date Picker |

###Dialog
Snippet | Description | Dependency Snippet
--- | --- | ---
fabric-dialog-script | To instantiate all Dialog components on the page. Insert this snippet in the header tag. |
fabric-dialog | Default Dialog |
fabric-dialog:blocking | Blocking Dialog |

###Dropdown
Snippet | Description | Dependency Snippet
--- | --- | ---
fabric-dropdown-script | To instantiate all Dropdown components on the page. Insert this snippet in the header tag. |
fabric-dropdown | Default Dropdown |

###Label
Snippet | Description | Dependency Snippet
--- | --- | ---
fabric-label | Default Label |

###Link
Snippet | Description | Dependency Snippet
--- | --- | ---
fabric-link | Default Link |

### List 
Snippet | Description | Dependency Snippet
--- | --- | ---
fabric-list | Presents a number of related items as a list | fabric-list-item, :document, :image, :selectable, :selected, :unread, :unseen 
fabric-list-grid | Presents a number of related items as a grid | fabric-list-item, :document, :image, :selectable, :selected, :unread, :unseen

### ListItem
Snippet | Description | Dependency Snippet
--- | --- | ---
fabric-list-item | List item | 
fabric-list-item:document | |
fabric-list-item:image | |
fabric-list-item:selectable | |
fabric-list-item:selected | |
fabric-list-item:unread | |
fabric-list-item:unseen | |

### Message Banner
Snippet | Description | Dependency Snippet
--- | --- | ---
fabric-message-banner | Presents a message to the user | 
fabric-message-banner-script | To instantiate all Message Banner components on the page. Insert this snippet in the header tag. | 

### Message Bar
Snippet | Description | Dependency Snippet
--- | --- | ---
fabric-message-banner | Default Message Bar |
fabric-message-banner:error | Message Bar (error) |
fabric-message-banner:severe-warning | Message Bar (Severe Warning) |
fabric-message-banner:success | Message Bar (Success) |
fabric-message-banner:warning | Message Bar (Warning) |

### Nav Bar
Snippet | Description | Dependency Snippet
--- | --- | ---
fabric-navbar-script | To instantiate all Nav Bar components on the page. Insert this snippet in the header tag. |
fabric-navbar | Default Nav Bar | fabric-navbar-item, fabric-navbar-right-item, fabric-navbar-menu-item 
fabric-navbar-item | Nav Item | 
fabric-navbar-right-item | Nav Item with right align |
fabric-navbar-menu-item | Nav Item with dropdown menu |

### Org Chart
Snippet | Description | Dependency Snippet
--- | --- | ---
fabric-orgchart | Displays multiple Persona components in groups with headers in order to show the hierarchy of an organization or team | 
fabric-orgchart-group | To group the members in the OrgChart | fabric-orgchart-list-item
fabric-orgchart-list-item | Each item in the OrgChart group.  | fabric-persona

###Overlay
Snippet | Description | Dependency Snippet
--- | --- | ---
fabric-overlay | Default Overlay | 
fabric-overlay:dark | Overlay (Dark) | 
fabric-overlay:none | Overlay (None) | 

### People Picker
Snippet | Description | Dependency Snippet
--- | --- | ---
fabric-peoplepicker-script |  To instantiate all People Picker components on the page. Insert this snippet in the header tag. | 
fabric-peoplepicker | Default PeoplePicker. | fabric-peoplepicker:result-group
fabric-peoplepicker:result-group | To group the members in the PeoplePicker dropdown list. | fabric-peoplepicker:result
fabric-peoplepicker:result | PeoplePicker Item | fabric-persona  

### Persona
Snippet | Description
--- | ---
fabric-persona | Profile image with presence indicator.
fabric-persona:available | Persona (Available)
fabric-persona:away | Persona (Away)
fabric-persona:busy | Persona (Blocked)
fabric-persona:dnd | Persona (Do not distrub)
fabric-persona:offline | Persona (Offline)
fabric-persona:large | Persona (Large)
fabric-persona:extra-large | Persona (Extra Large)
fabric-persona:small | Persona (Small)
fabric-persona:extra-small | Persona (Extra Small)
fabric-persona:tiny | Persona (tiny)
fabric-persona:initials | Persona (Initials)

### Persona Card
Snippet | Description | Dependency Snippet
--- | --- | ---
fabric-persona-card-script |  To instantiate all PersonaCard components on the page. Insert this snippet in the header tag. |  
fabric-personacard | Default PersonaCard | fabric-persona

### Pivot
Snippet | Description
--- | ---
fabric-pivot-script |  To instantiate all Pivot components on the page. Insert this snippet in the header tag.
fabric-pivot | Default Pivot
fabric-pivot:large | Large Pivot
fabric-pivot:tabs | Pivot (Tabs style)
fabric-pivot:large-tabs | Large Pivot (Tabs style) 

### Progress Indicator 
Snippet | Description
--- | ---
progress-indicator | Default Progress Indicator 

### Search Box
Snippet | Description
--- | ---
fabric-searchbox-script | To instantiate all SearchBox components on the page. Insert this snippet in the header tag. 
fabric-searchbox | Input field that allows for the input of search text.

### Spinner
Snippet | Description
--- | ---
fabric-spinner | Default Spinner.
fabric-spinner:large | Large Spinner.
fabric-spinner:message | Spinner with message.
fabric-spinner:large-message | Large Spinner with message.

### Table
Snippet | Description
--- | ---
fabric-table | Default Table.
fabric-table:fixed | Table with fixed columns. 
fabric-table:row-selectable | Table with selectable rows.


### Text Field
Snippet | Description
--- | ---
fabric-textfield | Single line input of text.
fabric-textfield:multiline | Multiple line input of text.
fabric-textfield:placeholder | Single line input of text with placeholder.
fabric-textfield:underlined | Single line input of text with underlined.

### Toggle
Snippet | Description
--- | --- 
fabric-toggle | Toggle with label on above (default).
fabric-toggle:text-left | Toggle with label on left


In the current release, Code snippets are not available for both Facepile and Panel components.

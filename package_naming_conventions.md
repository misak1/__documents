# Package Naming Conventions

![Pickles2 package Map](http://g.gravizo.com/g?
digraph pickles2_Map {
aize ="4,4";
pickles2, YoungCorn, "Pickles2 DesktopTool";
pickles2 -> "Pickles Framework Core";
"Pickles Framework Core" -> "px2-plugin";
"Pickles Framework Core" -> "px2-theme";
YoungCorn -> "px2agent";
YoungCorn -> "broccoli HTML Editor Core";
YoungCorn -> "Other npm packages";
"Pickles2 DesktopTool" -> "px2agent";
"Pickles2 DesktopTool" -> "broccoli HTML Editor Core";
"Pickles2 DesktopTool" -> "Other npm packages";
"broccoli HTML Editor Core" -> "broccoli field";
"broccoli HTML Editor Core" -> "broccoli module";
"px2agent" -> "Pickles Framework Core";
"Pickles Framework Core" -> "px2agent";
}
)

## Applications examples

- composer package: pickles2/pickles2
- repository: youngcorn
- repository: pickles2desktoptool

## Pickles Framework Core

- composer package: pickles2/px-fw-2.x

### Pickles2 plugin packages

- repository: px2-{$plugin\_name}
- composer package: pickles2/px2-{$plugin\_name}

### Pickles2 theme packages

- repository: px2-theme-{$theme\_name}
- composer package: pickles2/px2-theme-{$theme\_name}


## broccoli HTML Editor Core

- npm package: broccoli-html-editor

### broccoli-html-editor module packages

- repository: broccoli-module-{$module\_name}
- composer package: pickles2/broccoli-module-{$module\_name}
- npm package: broccoli-module-{$module\_name}

### broccoli-html-editor field packages

- repository: broccoli-field-{$field\_name}
- composer package: pickles2/broccoli-field-{$field\_name}
- npm package: broccoli-field-{$field\_name}

## Other libraries examples

### npm package

- repository: node-px2agent
- npm package: px2agent

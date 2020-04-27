Fork of [Liquid language support for VS Code](https://github.com/panoply/vscode-liquid)

### New
* shortcut property

### How to install
TBA

### Shortcuts
* img:section
```
 {% if section.settings.id != blank %}
   <img class='class' src='{{ section.settings.id | img_url: '1920x' }}' alt='{{ section.settings.body.alt | escape }}>
 {% endif %}
```
* img:block
```
 {% if block.settings.id != blank %}
   <img class='class' src='{{ block.settings.id | img_url: '1920x' }}' alt='{{ block.settings.id.alt | escape }}>
 {% endif %}
```
* ss
```
{{ section.settings.id }}
```
* bs
```
{{ block.settings.id }}
```

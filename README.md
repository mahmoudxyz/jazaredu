## Introduction 
Jazaredu is an open-source educational website to make you learn any field for free. 

## How to write? 

We use markdown and Latex to write lessons. You can learn both from anywhere online or even use any editor to convert between them and vice versa.


For markdown, we noticed that the most commonly used styles are h2 and bold so it is worth nothing to demonstrate it here.
In markdown to make a header from a specific size, you use #. For example, if you want to create h1, you should use # You header, and for h2, use ##.

If you wrote the following
```
## Heading 
```
it gives:

## Heading

If you wrote the following
```
### Heading 
```
it gives:

### Heading

Also please notice that this is a pitfall and don't do it:
```
###Heading

```
It yields:
###Heading
So keep in mind that space is important.

For bold use ```**Text**``` it will gives you **Text**`

-----

We also use special markdown to create custom components to make the topics more readable and pretty.
Here's a list of all custom components till now:

### Note
```
:::lesson-note
We are going to use the two terms ‘magnitude’ and ‘length’ interchangeably.
:::
```
![lesson-note](https://i.imgur.com/9oqaByX.png)


please keep :::lesson-note and ::: on separate lines to avoid any errors.

### Definition
```
:::lesson-def
You text here or maybe your LateX.
:::
```
![lesson-Definition](https://i.imgur.com/XB3Eq7d.png)


### Enriching information
```
:::lesson-enrich
The term "salt factor" refers to the amount of the active ingredient present in a salt form compared to its non-salt form.
:::
```
![lesson-Definition](https://i.imgur.com/YiPu9ZM.png)

Only use this if you want to give more details but are not required so it will be hidden by default unless the user clicks on it.


### Diagrams

To create diagrams from a plain text language we use [PlantUML](https://plantuml.com/guide). Learn more from their official docs, how to draw UML and entity relationships and much more.

To apply the text in our markdown please use the following: 

  c```plantuml Your title

  c```

The title will be alt in the picture in HTML.

For example the following:

c```plantuml Your title

class Class01 {
string name
void method()
}

class Class02 {
string name
void method()
}

Class01 <|-- Class02

c```

Will be :

![Imgur](https://i.imgur.com/HWVsrGv.png)

> please note that "c" is just for styling purpose and don't use it when writing.

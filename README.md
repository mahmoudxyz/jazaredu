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

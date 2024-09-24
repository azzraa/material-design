# Part 2: Using Icon Buttons

In this section, we will explore how to implement icon buttons using Material Design's [Icon Buttons](https://m3.material.io/components/icon-buttons/overview). We will use the Material Symbols font for our icons. 

You can find the necessary codes that we will use in the next steps here: https://github.com/material-components/material-web/blob/main/docs/components/icon-button.md

## Step 1: Add External Resources

Before we start coding, let's add the necessary external resources in JSFiddle. After logging in or signing up, navigate to the left panel to add the following links:

1. [Material Symbols Outlined](https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL@20..48,100..700,0..1)
2. [Material Symbols Rounded](https://fonts.googleapis.com/css2?family=Material+Symbols+Rounded:opsz,wght,FILL@20..48,100..700,0..1)
3. [Material Symbols Sharp](https://fonts.googleapis.com/css2?family=Material+Symbols+Sharp:opsz,wght,FILL@20..48,100..700,0..1)


## Step 2: Add HTML Code

Now, let's add the following HTML code for the icons:

```html
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL@20..48,100..700,0..1" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Rounded:opsz,wght,FILL@20..48,100..700,0..1" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Sharp:opsz,wght,FILL@20..48,100..700,0..1" rel="stylesheet">

<h3>Outlined</h3>
<span>
  <span class="material-symbols-outlined">settings</span>
  <span class="material-symbols-outlined">check_box</span>
  <span class="material-symbols-outlined">house</span>
  <span class="material-symbols-outlined filled">settings</span>
  <span class="material-symbols-outlined filled">check_box</span>
  <span class="material-symbols-outlined filled">house</span>
</span>

<h3>Rounded</h3>
<span>
  <span class="material-symbols-rounded">settings</span>
  <span class="material-symbols-rounded">check_box</span>
  <span class="material-symbols-rounded">house</span>
  <span class="material-symbols-rounded filled">settings</span>
  <span class="material-symbols-rounded filled">check_box</span>
  <span class="material-symbols-rounded filled">house</span>
</span>

<h3>Sharp</h3>
<span>
  <span class="material-symbols-sharp">settings</span>
  <span class="material-symbols-sharp">check_box</span>
  <span class="material-symbols-sharp">house</span>
  <span class="material-symbols-sharp filled">settings</span>
  <span class="material-symbols-sharp filled">check_box</span>
  <span class="material-symbols-sharp filled">house</span>
</span>
```

## Step 3: Add CSS Code
```css
span {
  color: #006A6A;
  --md-icon-size: 48px;
  font-size: var(--md-icon-size);
  vertical-align: middle; /* Align icons with text if any */
}
.rounded {
  font-family: 'Material Symbols Rounded';
}
.sharp {
  font-family: 'Material Symbols Sharp';
}
.filled {
  font-variation-settings: 'FILL' 1; /* Apply fill effect */
}
```

## Step 4: Run Your Code

After clicking on Run, you should be able to see your icons displayed. Your result should look similar to this:

![Result Icon Buttons](result.icons.jpg)

# Part 3: Use Buttons with Front-End Framework Based on Material Design

## Step 1: Download CSS File
Download the CSS file from [Materialize CSS Getting Started](https://materializecss.com/getting-started.html).

## Step 2: Add Link in HTML
Add the following link to your HTML file:

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">
```

## Step 3: Go to Components and Then Buttons

Visit the Materialize [CSS Buttons page](https://materializecss.com/buttons.html).

## Step 4: Copy and Paste This Code to Your HTML

Your current HTML should look like this:

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">

<a class="waves-effect waves-light btn">button</a>
<a class="waves-effect waves-light btn"><i class="material-icons left">cloud</i>button</a>
<a class="waves-effect waves-light btn"><i class="material-icons right">cloud</i>b
```

# Part 2: Using Icon Buttons

In this section, we will explore how to implement icon buttons using Material Design's Icon buttons. We will use the Material Symbols font for our icons.

## Step 1: Add External Resources

Before we start coding, let's add the necessary external resources in JSFiddle. After logging in or signing up, navigate to the left panel to add the following links:

1. (https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL@20..48,100..700,0..1)
2. (https://fonts.googleapis.com/css2?family=Material+Symbols+Rounded:opsz,wght,FILL@20..48,100..700,0..1)
3. (https://fonts.googleapis.com/css2?family=Material+Symbols+Sharp:opsz,wght,FILL@20..48,100..700,0..1)

## Step 2: Add HTML Code

Now, let's add the following HTML code for rounded icons:

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
![Result Icon Buttons](path/to/your/image.png)



# SASS starterpack
1. Think of your grid
2. Define your HTML tags based on the grid
```
<aside></aside>
<header></header>
<section></section>
<footer></footer>
```
3. Change the grid of the body to your needs
4. Define all the variable and functions in `_utils.scss` for the project

## Grid tricks
* To make a responsive gallery like grid use this:
```
main {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(19rem, 1fr));
    grid-gap: 1rem;
    cursor: pointer;
    
    img {
        width: 100%;
    }
}
```

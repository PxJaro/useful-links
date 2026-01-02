# Useful Links

A collection of handy links, organized by category. This project is built with HTML and CSS, so you can easily add or modify links.

## Structure

- **index.html**: main page containing all links.
- **images/**: (optional) folder for logos or icons.
- **styles**: CSS is embedded in the `<style>` section of the HTML (you can also move it to a separate file).

## How to edit links

1. Open `index.html`.
2. Find the section `<div id="links-container">`.
3. Add new categories using a small header:
```
   <div class="center header-card small">
       <h2>Category Name</h2>
   </div>
```

4. Add links with this structure:

```
    <a class="center link" href="https://example.com" target="_blank">
    <img src="example_logo.png" alt="Logo Description" style="padding:4px;width:28px;height:28px;">
    Link Name
    </a>
```

5. Repeat for as many links and categories as you like.

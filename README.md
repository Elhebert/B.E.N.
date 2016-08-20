# B.E.N.

This is B.E.N., a light **ES6 javascript** module to create a modal.

> There was a big door, opening and closing, opening and closing.

![B.E.N.](https://media.giphy.com/media/HYofV1aotMk5G/giphy.gif)

## Usage

Add the **ben.js** file to your index.(html|php).
```
<script src="/path/to/ben.js"></script>
```

Initialize B.E.N.
```
<script>
    let modal = new ben('my content');
</script>
```

- Use the `add()` method to add the modal to the DOM (but not display it).
- Use the `show()` method to display the modal (and add it to the DOM if necessary).
- Use the `remove()` method to remove the modal from the DOM.
- Use the `hide()` method to hide the modal (but keep it in the DOM).
- Use the `setContent('new content')` method to change the content without reloading the modal.

## Styling

- The overlay can be stylize by modifying the `.modal__overlay` class.
- The modal can be stylize by modifying the `.modal__box` class.
- The content can be stylize by modifying the `.modal__content` class.

## License
This script is published under the [MIT license](./LICENSE)

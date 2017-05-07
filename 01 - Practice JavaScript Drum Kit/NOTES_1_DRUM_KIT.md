Usefull tool or finding keycodes
[http://keycode.info/](http://keycode.info/)

```
window.addEventListener('keydown', function(e) {
  console.log(e); // returns info of key clicked
  console.log(e.keyCode); // output key number code
});
```

ES6 template strings
`audio[data-key="${e.keyCode}"]`

## Lookup

`document.querySelector`

```
`.key[data-key="${e.keyCode}"]`
```

`this.classList.remove('playing');`

`document.querySelectorAll('.key');`

`key.addEventListener('transitionend', removeTransition));`

## Lessons learned

- data attributes `data-*`
- `audio` api
- set audio time `audio.currentTime = 0;`
- play audio `audio.play();`
- add classes `key.classList.add('playing');`
- if / return `if(e.propertyName !== 'transform') return;`
- forEach `keys.forEach(key => key.addEventListener('transitionend', removeTransition));`

## emoji-editor
Forked from https://github.com/DIYgod/OwO

### JS

```js
var OwO_demo = new OwO({
    logo: '表情 :)',
    container: document.getElementsByClassName('OwO')[0],
    target: document.getElementsByClassName('OwO-textarea')[0],
    api: './OwO.json',
    position: 'down',
    width: '100%',
    maxHeight: '250px'
});
```

#### Options

```js
{
    logo: '表情 :)',                                               // OwO button text, default: `表情 :)`
    container: document.getElementsByClassName('OwO')[0],         // OwO container, default: `document.getElementsByClassName('OwO')[0]`
    target: document.getElementsByClassName('OwO-textarea')[0],   // OwO target input or textarea, default: `document.getElementsByTagName('textarea')[0]`
    api: './OwO.json',                                            // OwO Emoticon data api, default: `http://localhost/emoji-editor/demo/OwO.json`
    position: 'down',                                             // OwO body position, default: `down`
    width: '100%',                                                // OwO body width, default: `100%`
    maxHeight: '250px'                                            // OwO body max-height, default: `250px`
}
```

#### Work with module bundler

```js
var OwO = require('owo');
var OwO_demo = new OwO({
    // ...
});
```

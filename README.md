# subtleBar
This javascript library allows you to make cross-platform customized scrollbars. The main focus of the scrollbar is to be as low profile as possible. To achieve this, it will automatically hide away when not in use. This behaviour can be disabled however.

Basic example:
```javascript
$("selector").scrollbar();
```

An object with properties can be passed into the command, to alter behaviour:
```javascript
$("selector").scrollbar({autoHide:false});
```

To see a demo and all the customisation options click here:
[tarvk.github.io/subtleBar](https://tarvk.github.io/subtleBar)

Dependencies
- [jQuery](https://jquery.com/)
- [resize-sensor](https://github.com/marcj/css-element-queries) *optional*

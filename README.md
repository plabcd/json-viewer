# [Json Viewer](http://overtrue.github.io/json-viewer/)
A tool for make JSON view in browser.

# Usage

```html

<link rel="stylesheet" href="json-viewer/json-viewer.css">
<script src="https://code.jquery.com/jquery-2.2.4.min.js"></script>
<script src="json-viewer/json-viewer.js"></script>

<div id="json-container"></div>

<script>
    var json = {
        name: "JsonViewer",
        author: {
          name: "overtrue",
          email: "i@overtrue.me",
          contact: [
            {
              location: "office",
              number: 123456
            },
            {
              location: "home",
              number: 987654
            }
          ]
        }
    };

    $('#json-container').jsonview(json); // Support json string/object
</script>
```

[Demo](http://overtrue.github.io/json-viewer/)

# License

MIT

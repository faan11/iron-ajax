


## paper-download

The `paper-download` element exposes network request functionality.

```html
<paper-download
    buttontext="Button value"
    url="https://www.googleapis.com/youtube/v3/search"
    params='{"part":"snippet", "q":"polymer", "key": "YOUTUBE_API_KEY", "type": "video"}'
    handle-as="json"
    on-response="handleResponse"
    debounce-duration="300"></paper-download>
```


You can trigger a request explicitly by calling `generateRequest` on the
element.

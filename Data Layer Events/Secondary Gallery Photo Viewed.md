# Secondary Gallery Photo Viewed

### 

It has been requested that this event also fires when the user clicks on photo captions

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "secondary_gallery_view",
  "detailed_event": "Secondary Gallery Photo Viewed",
    "page_data": {
        "page_path": "<page_path>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|page_data.page_path|string|Captures the path portion of the page URL.||||||||





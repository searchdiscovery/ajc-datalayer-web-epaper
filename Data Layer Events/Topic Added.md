# Topic Added

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "TopicAdded",
  "event_data": {
    "itemName": "<itemName>",
    "location": "<location>"
  }
});
```


## Variable Definitions

|Path|Type|Description|
| --- | --- | --- |
|event_data.itemName|string|Captures the topic name.|
|event_data.location|string|Captures the location.|

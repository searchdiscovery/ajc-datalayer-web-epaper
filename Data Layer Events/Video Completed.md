# Video Completed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "video_complete",
  "detailed_event": "Video Completed",
    "event_data": {
        "identifier": "<identifier>",
        "ncd_content": "<ncd_content>",
        "type": "<type>",
        "video_title": "<video_title>",
        "video_topic": "<video_topic>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.identifier|string|Captures the ID of video content viewed by visitor.|YT456789, BC4567890, 876546789|||||||
|event_data.ncd_content|string|The NCD content topic of the video.||||||||
|event_data.type|string|Captures the type of video viewed.||||||||
|event_data.video_title|string|Captures the Name of video content viewed by visitor.|Twitch\_FPS, Age of Empires, Halo|||||||
|event_data.video_topic|string|The topic of the video.||||||||





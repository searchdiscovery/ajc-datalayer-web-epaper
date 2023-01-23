# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "page_load_started",
  "detailed_event": "Page Load Started",
    "page_data": {
        "byline": "<byline>",
        "category": "<category>",
        "clicktale_pageview_id": "<clicktale_pageview_id>",
        "content_id": "<content_id>",
        "content_type": "<content_type>",
        "country": "<country>",
        "experimentID": "<experimentID>",
        "language": "<language>",
        "page_location": "<page_location>",
        "page_path": "<page_path>",
        "page_title": "<page_title>",
        "paywall_status": "<paywall_status>",
        "previous_page": "<previous_page>",
        "publication_name": "<publication_name>",
        "publish_date": "<publish_date>",
        "site_metro": "<site_metro>",
        "site_name": "<site_name>",
        "site_section": "<site_section>",
        "subcategory": "<subcategory>",
        "topics": "<topics>",
        "user_group_id": "<user_group_id>"
    },
    "user_data": {
        "user_registration_status": "<user_registration_status>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|page_data.byline|string|The byline of the page.||||||||
|page_data.category|string|The Page category||||||||
|page_data.clicktale_pageview_id|string|The clicktale pageview ID of the pageview.||||||||
|page_data.content_id|string|The content ID of the page.|T3FAWCMCENGILOUBIU2LY2XB7Y|||||||
|page_data.content_type|string|The content type of the page.||||||||
|page_data.country|string|The country the site is associated with.||||||||
|page_data.experimentID|string|The experiment ID of the page||||||||
|page_data.language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.||||||||
|page_data.page_location|string|The url of the page currently being viewed.||||||||
|page_data.page_path|string|Captures the path portion of the page URL.||||||||
|page_data.page_title|string|The title of the page currently being viewed, generally available in &lt;title&gt;.||||||||
|page_data.paywall_status|string|The paywall status of the page.|subscriberonly|||||||
|page_data.previous_page|string|The name of the previous page.||||||||
|page_data.publication_name|string|The name of the publication associated with the page.|Atlanta Journal-Constitution|||||||
|page_data.publish_date|string|The publish date of the page||||||||
|page_data.site_metro|string|The site metro of the page.||||||||
|page_data.site_name|string|Common language used within the business to refer to the website. May be specific County Sites.|Prospecting-EU, Prospecting-US, Member Portal, Shop-CA, Shop-US, Shop-EU|||||||
|page_data.site_section|string|The section of the site that the current page resides in. site\_section2 through site\_section5can also be used if the site has many sections.||||||||
|page_data.subcategory|string|The page sub-category.||||||||
|page_data.topics|string|The content topics for the page.||||||||
|page_data.user_group_id|string|The user group id of the page,||||||||
|user_data.user_registration_status|string|Captures the current registration status of the user.|registered|||||||





#### `https://acciotables.herokuapp.com`
## <ins>API to scrape dynamically generated contents in a webapge.</ins>

Let's see how the API works
URL : `http://acciotables.herokuapp.com/?page_url=some_content&content_selector_id=some_content`

| a | a |
| - | - |
| API Format | `https://acciotables.herokuapp.com/?page_url=some_content&content_selector_id=some_content` |
| Attributes |  **page_url** : The URL of the webpage on which the content to be scrapped is available (in html encoded format)  |
|  | **content_selector_id** : CSS Selector ID of a particular table or any html element (in html encoded format)|
| Request Method | **GET** : GET methods means the API returns you something you ask |
| Response Type | **text/html** : Outer HTML content of the scrapped table (or any html element) |

## <ins> Sample usage:</ins>




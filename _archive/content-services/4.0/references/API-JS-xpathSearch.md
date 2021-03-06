---
author: [Alfresco Documentation, Alfresco Documentation]
source: JavaScript API
audience: 
category: JS API
option: xpathSearch
---

# ``xpathSearch(xpath)``

`xpathSearch(xpath)` performs an XPath search.

## Parameters

-   **xpath**

    The XPath search string


## Returns

Returns an array of `ScriptNode` objects that were found by the Alfresco repository XPath search.

## Example

```

var query = "//";
var nodes = search.xpathSearch(query);
```

**Parent topic:**[Search API](../references/API-JS-Search.md)

## `xpathSearch(store, xpath)`

`xpathSearch(store, xpath)`

This method performs an XPath search in a given store.

### Parameters

-   **store**

    The given store

-   **xpath**

    The XPath string


### Returns

Returns an array of `ScriptNode` objects that were found by the Alfresco repository XPath search in the given store.

### Example

```

var query = "//";
var store = "archive://SpacesStore"; 
var nodes = search.xpathSearch(store, query);

```


# Register a new piece of media

Register a new piece of media. Optionally provide a decrypt key

**URL** : `/stream/:token/:mediaId`

**Method** : `POST`

**Parameters:**

```json
{
  "token": {
    "description": "The JSON web token granted by the auth API to access the media given by the mediaId. Must be current and generated by this node.",
    "type": "string",
    "required": true
  },
  "mediaId": {
    "description": "RAIR unique identifier for a piece of media.",
    "type": "string",
    "required": true
  }
}
```

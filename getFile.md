# getFile

## 1. Step

`POST https://api.telegram.org/bot<token>/getFile`

### Body

```json
{
  "file_id": "file_id"
}
```

### Response

```json
{
  "ok": true,
  "result": {
    "file_id": "file_id",
    "file_size": 6383,
    "file_path": "voice/file_0.oga"
  }
}
```

## 2. Step

`GET https://api.telegram.org/file/bot<token>/<file_path>`

### Response

> The response body will contain a voice file.

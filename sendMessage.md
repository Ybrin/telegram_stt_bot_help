# sendMessage

## 1. Step

`POST https://api.telegram.org/bot<token>/sendMessage`

### Body

```json
{
  "chat_id": 83441420,
  "text": "The text to send",
  "reply_to_message_id": 4
}
```

### Response

```json
{
  "ok": true,
  "result": {
    "message_id": 5,
    "from": {
      "id": 354289097,
      "first_name": "Speech to Text",
      "username": "SpeechieBot"
    },
    "chat": {
      "id": 83441420,
      "first_name": "Koray",
      "username": "Ybrin",
      "type": "private"
    },
    "date": 1492107301,
    "reply_to_message": {
      "message_id": 4,
      "from": {
        "id": 83441420,
        "first_name": "Koray",
        "username": "Ybrin"
      },
      "chat": {
        "id": 83441420,
        "first_name": "Koray",
        "username": "Ybrin",
        "type": "private"
      },
      "date": 1492106508,
      "text": "/convertspeech",
      "entities": [{
        "type": "bot_command",
        "offset": 0,
        "length": 14
      }]
    },
    "text": "Hallo? Hallooo!"
  }
}
```

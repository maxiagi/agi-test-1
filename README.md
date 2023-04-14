# agi-test-1
{
  "text": "how many people between Tuesday and Friday",
  "intents": [
    {
      "id": "1701608719981716",
      "name": "inquiry",
      "confidence": 0.8849
    }
  ],
  "entities": {
    "metric:metric": [
      {
        "id": "3701487719281796",
        "name": "metric",
        "role": "metric",
        "start": 9,
        "end": 15,
        "body": "people",
        "value": "metric_visitor",
        "confidence": 0.9231,
        "entities": {}
      }
    ],
    "wit$datetime:datetime": [
      {
      "id": "1701608719981711",
      "name": "wit$datetime",
      "role": "datetime",
      "start": 16,
      "end": 42,
      "body": "between Tuesday and Friday",
      "confidence": 0.9541,
      "entities": {},
      "type": "interval",
      "from": {
        "grain": "day",
        "value": "2020-05-05T00:00:00.000-07:00"
      },
      "to": {
        "grain": "day",
        "value": "2020-05-09T00:00:00.000-07:00"
      },
      "values": [
        {
          "type": "interval",
          "from": {
            "grain": "day",
            "value": "2020-05-05T00:00:00.000-07:00"
          },
          "to": {
            "grain": "day",
            "value": "2020-05-09T00:00:00.000-07:00"
          }
        },
        {
          "type": "interval",
          "from": {
            "grain": "day",
            "value": "2020-05-12T00:00:00.000-07:00"
          },
          "to": {
            "grain": "day",
            "value": "2020-05-16T00:00:00.000-07:00"
          }
        },
        {
          "type": "interval",
          "from": {
            "grain": "day",
            "value": "2020-05-19T00:00:00.000-07:00"
          },
          "to": {
            "grain": "day",
            "value": "2020-05-23T00:00:00.000-07:00"
          }
        }
      ]
    ]
  }
}

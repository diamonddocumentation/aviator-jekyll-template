---
title: /break
position: 1
type: get
description: Controls the global break functionality.
parameters:
  - name: type
    content: 'http-all, http-request or http-response'
  - name: state
    content: >-
      true (for turning break on for the specified type) or false (for turning
      break off)
  - name: scope
    content: not currently used
content_markdown:
left_code_blocks:
  - code_block: >-
      $.get("http://api.myapp.com/books/", { "token": "YOUR_APP_KEY"},
      function(data) {
        alert(data);
      });
    title: jQuery
    language: python
  - code_block: |-
      r = requests.get("http://api.myapp.com/books/", token="YOUR_APP_KEY")
      print r.text
    title: Python
    language: python
  - code_block: >-
      var request = require("request");

      request("http://api.myapp.com/books?token=YOUR_APP_KEY", function (error,
      response, body) {

      if (!error && response.statusCode == 200) {
        console.log(body);
      }
    title: Node.js
    language: javascript
  - code_block: 'curl http://sampleapi.readme.com/orders?key=YOUR_APP_KEY'
    title: Curl
    language: bash
right_code_blocks:
  - code_block: |-
      [
        {
          "id": 1,
          "title": "The Hunger Games",
          "score": 4.5,
          "dateAdded": "12/12/2013"
        },
        {
          "id": 1,
          "title": "The Hunger Games",
          "score": 4.7,
          "dateAdded": "15/12/2013"
        },
      ]
    title: Response
    language: json
  - code_block: |-
      {
        "error": true,
        "message": "Invalid offset"
      }
    title: Error
    language: json
---
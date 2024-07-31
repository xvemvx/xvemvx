
[
  {
    "tags": [
      {
        "type": "param",
        "string": "{String} html",
        "name": "html",
        "description": "",
        "types": [
          "String"
        ],
        "typesDescription": "<code>String</code>",
        "optional": false,
        "nullable": false,
        "nonNullable": false,
        "variable": false,
        "html": "<p>{String} html</p>"
      },
      {
        "type": "return",
        "string": "{String}",
        "types": [
          "String"
        ],
        "typesDescription": "<code>String</code>",
        "optional": false,
        "nullable": false,
        "nonNullable": false,
        "variable": false,
        "description": "",
        "html": "<p>{String}</p>"
      },
      {
        "type": "api",
        "string": "private",
        "visibility": "private",
        "html": "<p>private</p>"
      }
    ],
    "description": {
      "full": "<p>Escape the given <code>html</code>.</p>",
      "summary": "<p>Escape the given <code>html</code>.</p>",
      "body": ""
    },
    "isPrivate": true,
    "isConstructor": false,
    "isClass": false,
    "isEvent": false,
    "ignore": false,
    "line": 2,
    "codeStart": 10,
    "code": "exports.escape = function(html){\n  return String(html)\n    .replace(/&(?!\\w+;)/g, '&amp;')\n    .replace(/</g, '&lt;')\n    .replace(/>/g, '&gt;');\n};",
    "ctx": {
      "type": "method",
      "receiver": "exports",
      "name": "escape",
      "string": "exports.escape()"
    }
  }
]
<!---
xvemvx/xvemvx is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

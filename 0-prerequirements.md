# Prerequirements

You need to have node.js installed. I am using version 10.

You also need make a new folder and navigate into it.

In this folder we need a file `ctype.json` with following content:
```json
{
  "schema": {
    "$id": "SBHACK_KILT_WORKSHOP_ATTENDED",
    "$schema": "http://kilt-protocol.org/draft-01/ctype#",
    "properties": {
      "name": {
        "type": "string"
      },
      "age": {
        "type": "integer"
      }
    },
    "type": "object"
  },
  "metadata": {
    "title": {
      "default": "SBHACK KILT Workshop Attended"
    },
    "description": {
      "default": ""
    },
    "properties": {
      "name": {
        "title": {
          "default": "name"
        }
      },
      "age": {
        "title": {
          "default": "age"
        }
      }
    }
  },
  "owner": "5HXfLqrqbKoKyi61YErwUrWEa1PWxikEojV7PCnLJgxrWd6W",
  "hash": "0x981955a2b7990554f6193a9e770ea625c68d2bfc5a1ff996e6e28d2a620fae16"
}

```
# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 315`

```javascript
Program {
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 18
      index: 44
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  comments: Array [
    CommentBlock {
      id: '0'
      value: ' Multiline\nComment '
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 10
          index: 36
          line: 2
        }
        start: Object {
          column: 13
          index: 13
          line: 1
        }
      }
    }
  ]
  body: Array [
    BlockStatement {
      directives: Array []
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 18
          index: 44
          line: 2
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: Array [
        ThrowStatement {
          trailingComments: Array ['0']
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 13
              index: 13
              line: 1
            }
            start: Object {
              column: 2
              index: 2
              line: 1
            }
          }
          argument: ReferenceIdentifier {
            name: 'error'
            trailingComments: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 13
                index: 13
                line: 1
              }
              start: Object {
                column: 8
                index: 8
                line: 1
              }
            }
          }
        }
        ExpressionStatement {
          leadingComments: Array ['0']
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 16
              index: 42
              line: 2
            }
            start: Object {
              column: 10
              index: 36
              line: 2
            }
          }
          expression: ReferenceIdentifier {
            name: 'error'
            leadingComments: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 15
                index: 41
                line: 2
              }
              start: Object {
                column: 10
                index: 36
                line: 2
              }
            }
          }
        }
      ]
    }
  ]
}
```
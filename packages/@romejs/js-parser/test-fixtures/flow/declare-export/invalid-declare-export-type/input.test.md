# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > declare-export > invalid-declare-export-type`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 34
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: '`declare export type` is not supported. Use `export type` instead'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 14
          index: 14
          line: 1
        }
        start: Object {
          column: 15
          index: 15
          line: 1
        }
      }
    }
  ]
  body: Array [
    FlowDeclareExportNamed {
      exportKind: 'type'
      specifiers: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 33
          index: 33
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: TypeAliasTypeAnnotation {
        id: BindingIdentifier {
          name: 'foo'
          loc: Object {
            filename: 'input.js'
            identifierName: 'foo'
            end: Object {
              column: 23
              index: 23
              line: 1
            }
            start: Object {
              column: 20
              index: 20
              line: 1
            }
          }
        }
        typeParameters: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 33
            index: 33
            line: 1
          }
          start: Object {
            column: 15
            index: 15
            line: 1
          }
        }
        right: NumberKeywordTypeAnnotation {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 32
              index: 32
              line: 1
            }
            start: Object {
              column: 26
              index: 26
              line: 1
            }
          }
        }
      }
    }
  ]
}
```

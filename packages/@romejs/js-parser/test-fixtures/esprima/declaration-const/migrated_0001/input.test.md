# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > declaration-const > migrated_0001`

```javascript
Program {
  comments: Array []
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
      column: 0
      index: 17
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    BlockStatement {
      directives: Array []
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 16
          index: 16
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: Array [
        VariableDeclarationStatement {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 14
              index: 14
              line: 1
            }
            start: Object {
              column: 2
              index: 2
              line: 1
            }
          }
          declaration: VariableDeclaration {
            kind: 'const'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 14
                index: 14
                line: 1
              }
              start: Object {
                column: 2
                index: 2
                line: 1
              }
            }
            declarations: Array [
              VariableDeclarator {
                id: BindingIdentifier {
                  name: 'x'
                  loc: Object {
                    filename: 'input.js'
                    identifierName: 'x'
                    end: Object {
                      column: 9
                      index: 9
                      line: 1
                    }
                    start: Object {
                      column: 8
                      index: 8
                      line: 1
                    }
                  }
                }
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 14
                    index: 14
                    line: 1
                  }
                  start: Object {
                    column: 8
                    index: 8
                    line: 1
                  }
                }
                init: NumericLiteral {
                  value: 42
                  format: undefined
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 14
                      index: 14
                      line: 1
                    }
                    start: Object {
                      column: 12
                      index: 12
                      line: 1
                    }
                  }
                }
              }
            ]
          }
        }
      ]
    }
  ]
}
```

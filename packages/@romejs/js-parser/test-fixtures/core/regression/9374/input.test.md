# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `core > regression > 9374`

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
      index: 40
      line: 4
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    FunctionDeclaration {
      id: BindingIdentifier {
        name: 'test'
        loc: Object {
          filename: 'input.js'
          identifierName: 'test'
          end: Object {
            column: 14
            index: 14
            line: 1
          }
          start: Object {
            column: 10
            index: 10
            line: 1
          }
        }
      }
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 1
          index: 39
          line: 3
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      head: FunctionHead {
        async: false
        generator: true
        hasHoistedVars: false
        params: Array []
        predicate: undefined
        rest: undefined
        returnType: undefined
        thisType: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 17
            index: 17
            line: 1
          }
          start: Object {
            column: 14
            index: 14
            line: 1
          }
        }
      }
      body: BlockStatement {
        directives: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 1
            index: 39
            line: 3
          }
          start: Object {
            column: 17
            index: 17
            line: 1
          }
        }
        body: Array [
          ExpressionStatement {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 18
                index: 37
                line: 2
              }
              start: Object {
                column: 2
                index: 21
                line: 2
              }
            }
            expression: YieldExpression {
              delegate: false
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 17
                  index: 36
                  line: 2
                }
                start: Object {
                  column: 2
                  index: 21
                  line: 2
                }
              }
              argument: NewExpression {
                arguments: Array []
                optional: undefined
                typeArguments: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 17
                    index: 36
                    line: 2
                  }
                  start: Object {
                    column: 8
                    index: 27
                    line: 2
                  }
                }
                callee: ReferenceIdentifier {
                  name: 'Foo'
                  loc: Object {
                    filename: 'input.js'
                    identifierName: 'Foo'
                    end: Object {
                      column: 15
                      index: 34
                      line: 2
                    }
                    start: Object {
                      column: 12
                      index: 31
                      line: 2
                    }
                  }
                }
              }
            }
          }
        ]
      }
    }
  ]
}
```

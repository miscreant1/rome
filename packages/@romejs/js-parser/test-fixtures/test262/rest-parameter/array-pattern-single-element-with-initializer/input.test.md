# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `test262 > rest-parameter > array-pattern-single-element-with-initializer`

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
      index: 53
      line: 2
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
        name: 'singleElementWithInitializer'
        loc: Object {
          filename: 'input.js'
          identifierName: 'singleElementWithInitializer'
          end: Object {
            column: 37
            index: 37
            line: 1
          }
          start: Object {
            column: 9
            index: 9
            line: 1
          }
        }
      }
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 52
          index: 52
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: BlockStatement {
        body: Array []
        directives: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 52
            index: 52
            line: 1
          }
          start: Object {
            column: 50
            index: 50
            line: 1
          }
        }
      }
      head: FunctionHead {
        async: false
        generator: false
        hasHoistedVars: false
        params: Array []
        predicate: undefined
        returnType: undefined
        thisType: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 50
            index: 50
            line: 1
          }
          start: Object {
            column: 37
            index: 37
            line: 1
          }
        }
        rest: BindingArrayPattern {
          rest: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 48
              index: 48
              line: 1
            }
            start: Object {
              column: 41
              index: 41
              line: 1
            }
          }
          meta: PatternMeta {
            optional: undefined
            typeAnnotation: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 48
                index: 48
                line: 1
              }
              start: Object {
                column: 41
                index: 41
                line: 1
              }
            }
          }
          elements: Array [
            BindingAssignmentPattern {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 47
                  index: 47
                  line: 1
                }
                start: Object {
                  column: 42
                  index: 42
                  line: 1
                }
              }
              right: NumericLiteral {
                value: 0
                format: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 47
                    index: 47
                    line: 1
                  }
                  start: Object {
                    column: 46
                    index: 46
                    line: 1
                  }
                }
              }
              left: BindingIdentifier {
                name: 'a'
                loc: Object {
                  filename: 'input.js'
                  identifierName: 'a'
                  end: Object {
                    column: 43
                    index: 43
                    line: 1
                  }
                  start: Object {
                    column: 42
                    index: 42
                    line: 1
                  }
                }
                meta: PatternMeta {
                  optional: undefined
                  typeAnnotation: undefined
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 43
                      index: 43
                      line: 1
                    }
                    start: Object {
                      column: 42
                      index: 42
                      line: 1
                    }
                  }
                }
              }
            }
          ]
        }
      }
    }
  ]
}
```

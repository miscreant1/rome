# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > type-annotations > 133`

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
      index: 54
      line: 4
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
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Cannot overwrite primitive type string'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 17
          index: 17
          line: 1
        }
        start: Object {
          column: 11
          index: 11
          line: 1
        }
      }
    }
  ]
  body: Array [
    FunctionDeclaration {
      id: BindingIdentifier {
        name: 'a'
        loc: Object {
          filename: 'input.js'
          identifierName: 'a'
          end: Object {
            column: 10
            index: 10
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
          column: 1
          index: 53
          line: 3
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: BlockStatement {
        directives: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 1
            index: 53
            line: 3
          }
          start: Object {
            column: 38
            index: 38
            line: 1
          }
        }
        body: Array [
          ReturnStatement {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 11
                index: 51
                line: 2
              }
              start: Object {
                column: 2
                index: 42
                line: 2
              }
            }
            argument: ReferenceIdentifier {
              name: 'x'
              loc: Object {
                filename: 'input.js'
                identifierName: 'x'
                end: Object {
                  column: 10
                  index: 50
                  line: 2
                }
                start: Object {
                  column: 9
                  index: 49
                  line: 2
                }
              }
            }
          }
        ]
      }
      head: FunctionHead {
        async: false
        generator: false
        hasHoistedVars: false
        predicate: undefined
        rest: undefined
        thisType: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 38
            index: 38
            line: 1
          }
          start: Object {
            column: 10
            index: 10
            line: 1
          }
        }
        returnType: StringKeywordTypeAnnotation {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 37
              index: 37
              line: 1
            }
            start: Object {
              column: 31
              index: 31
              line: 1
            }
          }
        }
        typeParameters: FlowTypeParameterDeclaration {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 18
              index: 18
              line: 1
            }
            start: Object {
              column: 10
              index: 10
              line: 1
            }
          }
          params: Array [
            FlowTypeParameter {
              name: 'string'
              bound: undefined
              default: undefined
              variance: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 17
                  index: 17
                  line: 1
                }
                start: Object {
                  column: 11
                  index: 11
                  line: 1
                }
              }
            }
          ]
        }
        params: Array [
          BindingIdentifier {
            name: 'x'
            loc: Object {
              filename: 'input.js'
              identifierName: 'x'
              end: Object {
                column: 20
                index: 20
                line: 1
              }
              start: Object {
                column: 19
                index: 19
                line: 1
              }
            }
            meta: PatternMeta {
              optional: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 28
                  index: 28
                  line: 1
                }
                start: Object {
                  column: 19
                  index: 19
                  line: 1
                }
              }
              typeAnnotation: StringKeywordTypeAnnotation {
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 28
                    index: 28
                    line: 1
                  }
                  start: Object {
                    column: 22
                    index: 22
                    line: 1
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

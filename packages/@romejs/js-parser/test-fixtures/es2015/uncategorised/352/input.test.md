# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 352`

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
      column: 48
      index: 48
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 48
          index: 48
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: ObjectExpression {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 47
            index: 47
            line: 1
          }
          start: Object {
            column: 1
            index: 1
            line: 1
          }
        }
        properties: Array [
          ObjectMethod {
            kind: 'get'
            key: StaticPropertyKey {
              value: Identifier {
                name: '__proto__'
                loc: Object {
                  filename: 'input.js'
                  identifierName: '__proto__'
                  end: Object {
                    column: 16
                    index: 16
                    line: 1
                  }
                  start: Object {
                    column: 7
                    index: 7
                    line: 1
                  }
                }
              }
              variance: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 16
                  index: 16
                  line: 1
                }
                start: Object {
                  column: 7
                  index: 7
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 31
                index: 31
                line: 1
              }
              start: Object {
                column: 3
                index: 3
                line: 1
              }
            }
            head: FunctionHead {
              async: false
              generator: false
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
                  column: 19
                  index: 19
                  line: 1
                }
                start: Object {
                  column: 16
                  index: 16
                  line: 1
                }
              }
            }
            body: BlockStatement {
              directives: Array []
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 31
                  index: 31
                  line: 1
                }
                start: Object {
                  column: 19
                  index: 19
                  line: 1
                }
              }
              body: Array [
                ReturnStatement {
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 29
                      index: 29
                      line: 1
                    }
                    start: Object {
                      column: 21
                      index: 21
                      line: 1
                    }
                  }
                  argument: NumericLiteral {
                    value: 1
                    format: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 29
                        index: 29
                        line: 1
                      }
                      start: Object {
                        column: 28
                        index: 28
                        line: 1
                      }
                    }
                  }
                }
              ]
            }
          }
          ObjectProperty {
            key: StaticPropertyKey {
              value: Identifier {
                name: '__proto__'
                loc: Object {
                  filename: 'input.js'
                  identifierName: '__proto__'
                  end: Object {
                    column: 42
                    index: 42
                    line: 1
                  }
                  start: Object {
                    column: 33
                    index: 33
                    line: 1
                  }
                }
              }
              variance: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 42
                  index: 42
                  line: 1
                }
                start: Object {
                  column: 33
                  index: 33
                  line: 1
                }
              }
            }
            value: NumericLiteral {
              value: 2
              format: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 45
                  index: 45
                  line: 1
                }
                start: Object {
                  column: 44
                  index: 44
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 45
                index: 45
                line: 1
              }
              start: Object {
                column: 33
                index: 33
                line: 1
              }
            }
          }
        ]
      }
    }
  ]
}
```

# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0207`

```javascript
Program {
  comments: Array []
  corrupt: false
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
      index: 64
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
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'eval is a reserved word'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 51
          index: 51
          line: 1
        }
        start: Object {
          column: 47
          index: 47
          line: 1
        }
      }
    }
  ]
  body: Array [
    FunctionDeclaration {
      id: BindingIdentifier {
        name: 'hello'
        loc: Object {
          filename: 'input.js'
          identifierName: 'hello'
          end: Object {
            column: 14
            index: 14
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
          column: 63
          index: 63
          line: 1
        }
        start: Object {
          column: 0
          index: 0
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
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 63
            index: 63
            line: 1
          }
          start: Object {
            column: 17
            index: 17
            line: 1
          }
        }
        directives: Array [
          Directive {
            value: 'use strict'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 31
                index: 31
                line: 1
              }
              start: Object {
                column: 18
                index: 18
                line: 1
              }
            }
          }
        ]
        body: Array [
          ExpressionStatement {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 61
                index: 61
                line: 1
              }
              start: Object {
                column: 32
                index: 32
                line: 1
              }
            }
            expression: ObjectExpression {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 59
                  index: 59
                  line: 1
                }
                start: Object {
                  column: 33
                  index: 33
                  line: 1
                }
              }
              properties: Array [
                ObjectProperty {
                  key: StaticPropertyKey {
                    value: Identifier {
                      name: 's'
                      loc: Object {
                        filename: 'input.js'
                        identifierName: 's'
                        end: Object {
                          column: 36
                          index: 36
                          line: 1
                        }
                        start: Object {
                          column: 35
                          index: 35
                          line: 1
                        }
                      }
                    }
                    variance: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 36
                        index: 36
                        line: 1
                      }
                      start: Object {
                        column: 35
                        index: 35
                        line: 1
                      }
                    }
                  }
                  value: FunctionExpression {
                    id: BindingIdentifier {
                      name: 'eval'
                      loc: Object {
                        filename: 'input.js'
                        identifierName: 'eval'
                        end: Object {
                          column: 51
                          index: 51
                          line: 1
                        }
                        start: Object {
                          column: 47
                          index: 47
                          line: 1
                        }
                      }
                    }
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 57
                        index: 57
                        line: 1
                      }
                      start: Object {
                        column: 38
                        index: 38
                        line: 1
                      }
                    }
                    body: BlockStatement {
                      body: Array []
                      directives: Array []
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 57
                          index: 57
                          line: 1
                        }
                        start: Object {
                          column: 54
                          index: 54
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
                      rest: undefined
                      returnType: undefined
                      thisType: undefined
                      typeParameters: undefined
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 54
                          index: 54
                          line: 1
                        }
                        start: Object {
                          column: 51
                          index: 51
                          line: 1
                        }
                      }
                    }
                  }
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 57
                      index: 57
                      line: 1
                    }
                    start: Object {
                      column: 35
                      index: 35
                      line: 1
                    }
                  }
                }
              ]
            }
          }
        ]
      }
    }
  ]
}
```

# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 522`

```javascript
Program {
  comments: Array []
  corrupt: false
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 69
      index: 69
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  directives: Array [
    Directive {
      value: 'use strict'
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 13
          index: 13
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
    }
  ]
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Legacy octal literals are not allowed in strict mode'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 68
          index: 68
          line: 1
        }
        start: Object {
          column: 68
          index: 68
          line: 1
        }
      }
    }
  ]
  body: Array [
    FunctionDeclaration {
      id: BindingIdentifier {
        name: 'foo'
        loc: Object {
          filename: 'input.js'
          identifierName: 'foo'
          end: Object {
            column: 25
            index: 25
            line: 1
          }
          start: Object {
            column: 22
            index: 22
            line: 1
          }
        }
      }
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 42
          index: 42
          line: 1
        }
        start: Object {
          column: 13
          index: 13
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
            column: 27
            index: 27
            line: 1
          }
          start: Object {
            column: 25
            index: 25
            line: 1
          }
        }
      }
      body: BlockStatement {
        body: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 42
            index: 42
            line: 1
          }
          start: Object {
            column: 27
            index: 27
            line: 1
          }
        }
        directives: Array [
          Directive {
            value: 'use strict'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 41
                index: 41
                line: 1
              }
              start: Object {
                column: 28
                index: 28
                line: 1
              }
            }
          }
        ]
      }
    }
    FunctionDeclaration {
      id: BindingIdentifier {
        name: 'bar'
        loc: Object {
          filename: 'input.js'
          identifierName: 'bar'
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
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 69
          index: 69
          line: 1
        }
        start: Object {
          column: 42
          index: 42
          line: 1
        }
      }
      head: FunctionHead {
        async: false
        generator: false
        hasHoistedVars: true
        params: Array []
        predicate: undefined
        rest: undefined
        returnType: undefined
        thisType: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 56
            index: 56
            line: 1
          }
          start: Object {
            column: 54
            index: 54
            line: 1
          }
        }
      }
      body: BlockStatement {
        directives: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 69
            index: 69
            line: 1
          }
          start: Object {
            column: 56
            index: 56
            line: 1
          }
        }
        body: Array [
          VariableDeclarationStatement {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 68
                index: 68
                line: 1
              }
              start: Object {
                column: 57
                index: 57
                line: 1
              }
            }
            declaration: VariableDeclaration {
              kind: 'var'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 68
                  index: 68
                  line: 1
                }
                start: Object {
                  column: 57
                  index: 57
                  line: 1
                }
              }
              declarations: Array [
                VariableDeclarator {
                  id: BindingIdentifier {
                    name: 'v'
                    loc: Object {
                      filename: 'input.js'
                      identifierName: 'v'
                      end: Object {
                        column: 62
                        index: 62
                        line: 1
                      }
                      start: Object {
                        column: 61
                        index: 61
                        line: 1
                      }
                    }
                  }
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 68
                      index: 68
                      line: 1
                    }
                    start: Object {
                      column: 61
                      index: 61
                      line: 1
                    }
                  }
                  init: NumericLiteral {
                    value: 13
                    format: 'octal'
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 68
                        index: 68
                        line: 1
                      }
                      start: Object {
                        column: 65
                        index: 65
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
    }
  ]
}
```

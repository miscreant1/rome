# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-yield > yield-generator-function-parameter`

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
      index: 45
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
        name: 'g'
        loc: Object {
          filename: 'input.js'
          identifierName: 'g'
          end: Object {
            column: 11
            index: 11
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
          column: 44
          index: 44
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
        generator: true
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
            column: 14
            index: 14
            line: 1
          }
          start: Object {
            column: 11
            index: 11
            line: 1
          }
        }
      }
      body: BlockStatement {
        directives: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 44
            index: 44
            line: 1
          }
          start: Object {
            column: 14
            index: 14
            line: 1
          }
        }
        body: Array [
          VariableDeclarationStatement {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 42
                index: 42
                line: 1
              }
              start: Object {
                column: 16
                index: 16
                line: 1
              }
            }
            declaration: VariableDeclaration {
              kind: 'var'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 42
                  index: 42
                  line: 1
                }
                start: Object {
                  column: 16
                  index: 16
                  line: 1
                }
              }
              declarations: Array [
                VariableDeclarator {
                  id: BindingIdentifier {
                    name: 'z'
                    loc: Object {
                      filename: 'input.js'
                      identifierName: 'z'
                      end: Object {
                        column: 21
                        index: 21
                        line: 1
                      }
                      start: Object {
                        column: 20
                        index: 20
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
                      column: 20
                      index: 20
                      line: 1
                    }
                  }
                  init: FunctionExpression {
                    id: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 42
                        index: 42
                        line: 1
                      }
                      start: Object {
                        column: 24
                        index: 24
                        line: 1
                      }
                    }
                    body: BlockStatement {
                      body: Array []
                      directives: Array []
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 42
                          index: 42
                          line: 1
                        }
                        start: Object {
                          column: 40
                          index: 40
                          line: 1
                        }
                      }
                    }
                    head: FunctionHead {
                      async: false
                      generator: false
                      hasHoistedVars: false
                      predicate: undefined
                      rest: undefined
                      returnType: undefined
                      thisType: undefined
                      typeParameters: undefined
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 40
                          index: 40
                          line: 1
                        }
                        start: Object {
                          column: 32
                          index: 32
                          line: 1
                        }
                      }
                      params: Array [
                        BindingIdentifier {
                          name: 'yield'
                          loc: Object {
                            filename: 'input.js'
                            identifierName: 'yield'
                            end: Object {
                              column: 38
                              index: 38
                              line: 1
                            }
                            start: Object {
                              column: 33
                              index: 33
                              line: 1
                            }
                          }
                          meta: PatternMeta {
                            optional: undefined
                            typeAnnotation: undefined
                            loc: Object {
                              filename: 'input.js'
                              end: Object {
                                column: 38
                                index: 38
                                line: 1
                              }
                              start: Object {
                                column: 33
                                index: 33
                                line: 1
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
          }
        ]
      }
    }
  ]
}
```

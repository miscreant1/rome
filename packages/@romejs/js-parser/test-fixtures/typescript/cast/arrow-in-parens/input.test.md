# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > cast > arrow-in-parens`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.ts'
  hasHoistedVars: true
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array ['ts']
  loc: Object {
    filename: 'input.ts'
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
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.ts'
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
      declaration: VariableDeclaration {
        kind: 'var'
        loc: Object {
          filename: 'input.ts'
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
        declarations: Array [
          VariableDeclarator {
            id: BindingIdentifier {
              name: 'asserted1'
              loc: Object {
                filename: 'input.ts'
                identifierName: 'asserted1'
                end: Object {
                  column: 13
                  index: 13
                  line: 1
                }
                start: Object {
                  column: 4
                  index: 4
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.ts'
              end: Object {
                column: 43
                index: 43
                line: 1
              }
              start: Object {
                column: 4
                index: 4
                line: 1
              }
            }
            init: ArrowFunctionExpression {
              loc: Object {
                filename: 'input.ts'
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
              typeParameters: TSTypeParameterDeclaration {
                loc: Object {
                  filename: 'input.ts'
                  end: Object {
                    column: 21
                    index: 21
                    line: 1
                  }
                  start: Object {
                    column: 16
                    index: 16
                    line: 1
                  }
                }
                params: Array [
                  TSTypeParameter {
                    name: 'any'
                    constraint: undefined
                    default: undefined
                    loc: Object {
                      filename: 'input.ts'
                      end: Object {
                        column: 20
                        index: 20
                        line: 1
                      }
                      start: Object {
                        column: 17
                        index: 17
                        line: 1
                      }
                    }
                  }
                ]
              }
              head: FunctionHead {
                async: false
                hasHoistedVars: false
                predicate: undefined
                rest: undefined
                returnType: undefined
                thisType: undefined
                loc: Object {
                  filename: 'input.ts'
                  end: Object {
                    column: 29
                    index: 29
                    line: 1
                  }
                  start: Object {
                    column: 22
                    index: 22
                    line: 1
                  }
                }
                params: Array [
                  BindingIdentifier {
                    name: 'n'
                    loc: Object {
                      filename: 'input.ts'
                      identifierName: 'n'
                      end: Object {
                        column: 24
                        index: 24
                        line: 1
                      }
                      start: Object {
                        column: 23
                        index: 23
                        line: 1
                      }
                    }
                  }
                ]
              }
              body: BlockStatement {
                directives: Array []
                loc: Object {
                  filename: 'input.ts'
                  end: Object {
                    column: 42
                    index: 42
                    line: 1
                  }
                  start: Object {
                    column: 29
                    index: 29
                    line: 1
                  }
                }
                body: Array [
                  ReturnStatement {
                    loc: Object {
                      filename: 'input.ts'
                      end: Object {
                        column: 40
                        index: 40
                        line: 1
                      }
                      start: Object {
                        column: 31
                        index: 31
                        line: 1
                      }
                    }
                    argument: ReferenceIdentifier {
                      name: 'n'
                      loc: Object {
                        filename: 'input.ts'
                        identifierName: 'n'
                        end: Object {
                          column: 39
                          index: 39
                          line: 1
                        }
                        start: Object {
                          column: 38
                          index: 38
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
```

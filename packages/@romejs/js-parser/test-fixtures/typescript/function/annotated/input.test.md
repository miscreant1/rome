# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > function > annotated`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.ts'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array ['ts']
  loc: Object {
    filename: 'input.ts'
    end: Object {
      column: 0
      index: 27
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
        name: 'f'
        loc: Object {
          filename: 'input.ts'
          identifierName: 'f'
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
        filename: 'input.ts'
        end: Object {
          column: 26
          index: 26
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
          filename: 'input.ts'
          end: Object {
            column: 26
            index: 26
            line: 1
          }
          start: Object {
            column: 24
            index: 24
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
        thisType: undefined
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 24
            index: 24
            line: 1
          }
          start: Object {
            column: 10
            index: 10
            line: 1
          }
        }
        returnType: TSTypeReference {
          typeParameters: undefined
          loc: Object {
            filename: 'input.ts'
            end: Object {
              column: 23
              index: 23
              line: 1
            }
            start: Object {
              column: 22
              index: 22
              line: 1
            }
          }
          typeName: ReferenceIdentifier {
            name: 'T'
            loc: Object {
              filename: 'input.ts'
              identifierName: 'T'
              end: Object {
                column: 23
                index: 23
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
        typeParameters: TSTypeParameterDeclaration {
          loc: Object {
            filename: 'input.ts'
            end: Object {
              column: 13
              index: 13
              line: 1
            }
            start: Object {
              column: 10
              index: 10
              line: 1
            }
          }
          params: Array [
            TSTypeParameter {
              name: 'T'
              constraint: undefined
              default: undefined
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 12
                  index: 12
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
              filename: 'input.ts'
              identifierName: 'x'
              end: Object {
                column: 15
                index: 15
                line: 1
              }
              start: Object {
                column: 14
                index: 14
                line: 1
              }
            }
            meta: PatternMeta {
              optional: true
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 19
                  index: 19
                  line: 1
                }
                start: Object {
                  column: 14
                  index: 14
                  line: 1
                }
              }
              typeAnnotation: TSTypeReference {
                typeParameters: undefined
                loc: Object {
                  filename: 'input.ts'
                  end: Object {
                    column: 19
                    index: 19
                    line: 1
                  }
                  start: Object {
                    column: 18
                    index: 18
                    line: 1
                  }
                }
                typeName: ReferenceIdentifier {
                  name: 'T'
                  loc: Object {
                    filename: 'input.ts'
                    identifierName: 'T'
                    end: Object {
                      column: 19
                      index: 19
                      line: 1
                    }
                    start: Object {
                      column: 18
                      index: 18
                      line: 1
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

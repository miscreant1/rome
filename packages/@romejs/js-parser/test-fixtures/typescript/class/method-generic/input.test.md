# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > class > method-generic`

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
      index: 84
      line: 5
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ClassDeclaration {
      id: BindingIdentifier {
        name: 'C'
        loc: Object {
          filename: 'input.ts'
          identifierName: 'C'
          end: Object {
            column: 7
            index: 7
            line: 1
          }
          start: Object {
            column: 6
            index: 6
            line: 1
          }
        }
      }
      loc: Object {
        filename: 'input.ts'
        end: Object {
          column: 1
          index: 83
          line: 4
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      meta: ClassHead {
        implements: undefined
        superClass: undefined
        superTypeParameters: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 1
            index: 83
            line: 4
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        body: Array [
          ClassMethod {
            kind: 'method'
            key: StaticPropertyKey {
              value: Identifier {
                name: 'f'
                loc: Object {
                  filename: 'input.ts'
                  identifierName: 'f'
                  end: Object {
                    column: 5
                    index: 15
                    line: 2
                  }
                  start: Object {
                    column: 4
                    index: 14
                    line: 2
                  }
                }
              }
              variance: undefined
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 5
                  index: 15
                  line: 2
                }
                start: Object {
                  column: 4
                  index: 14
                  line: 2
                }
              }
            }
            loc: Object {
              filename: 'input.ts'
              end: Object {
                column: 38
                index: 48
                line: 2
              }
              start: Object {
                column: 4
                index: 14
                line: 2
              }
            }
            body: BlockStatement {
              body: Array []
              directives: Array []
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 38
                  index: 48
                  line: 2
                }
                start: Object {
                  column: 36
                  index: 46
                  line: 2
                }
              }
            }
            meta: ClassPropertyMeta {
              abstract: false
              accessibility: undefined
              optional: false
              readonly: false
              static: false
              typeAnnotation: undefined
              start: Object {
                column: 4
                index: 14
                line: 2
              }
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 5
                  index: 15
                  line: 2
                }
                start: Object {
                  column: 4
                  index: 14
                  line: 2
                }
              }
            }
            head: FunctionHead {
              async: false
              generator: false
              hasHoistedVars: false
              predicate: undefined
              thisType: undefined
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 36
                  index: 46
                  line: 2
                }
                start: Object {
                  column: 8
                  index: 18
                  line: 2
                }
              }
              returnType: TSTypeReference {
                typeParameters: undefined
                loc: Object {
                  filename: 'input.ts'
                  end: Object {
                    column: 35
                    index: 45
                    line: 2
                  }
                  start: Object {
                    column: 34
                    index: 44
                    line: 2
                  }
                }
                typeName: ReferenceIdentifier {
                  name: 'T'
                  loc: Object {
                    filename: 'input.ts'
                    identifierName: 'T'
                    end: Object {
                      column: 35
                      index: 45
                      line: 2
                    }
                    start: Object {
                      column: 34
                      index: 44
                      line: 2
                    }
                  }
                }
              }
              typeParameters: TSTypeParameterDeclaration {
                loc: Object {
                  filename: 'input.ts'
                  end: Object {
                    column: 8
                    index: 18
                    line: 2
                  }
                  start: Object {
                    column: 5
                    index: 15
                    line: 2
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
                        column: 7
                        index: 17
                        line: 2
                      }
                      start: Object {
                        column: 6
                        index: 16
                        line: 2
                      }
                    }
                  }
                ]
              }
              rest: BindingIdentifier {
                name: 'c'
                loc: Object {
                  filename: 'input.ts'
                  identifierName: 'c'
                  end: Object {
                    column: 26
                    index: 36
                    line: 2
                  }
                  start: Object {
                    column: 25
                    index: 35
                    line: 2
                  }
                }
                meta: PatternMeta {
                  optional: undefined
                  loc: Object {
                    filename: 'input.ts'
                    end: Object {
                      column: 31
                      index: 41
                      line: 2
                    }
                    start: Object {
                      column: 25
                      index: 35
                      line: 2
                    }
                  }
                  typeAnnotation: TSArrayType {
                    loc: Object {
                      filename: 'input.ts'
                      end: Object {
                        column: 31
                        index: 41
                        line: 2
                      }
                      start: Object {
                        column: 28
                        index: 38
                        line: 2
                      }
                    }
                    elementType: TSTypeReference {
                      typeParameters: undefined
                      loc: Object {
                        filename: 'input.ts'
                        end: Object {
                          column: 29
                          index: 39
                          line: 2
                        }
                        start: Object {
                          column: 28
                          index: 38
                          line: 2
                        }
                      }
                      typeName: ReferenceIdentifier {
                        name: 'T'
                        loc: Object {
                          filename: 'input.ts'
                          identifierName: 'T'
                          end: Object {
                            column: 29
                            index: 39
                            line: 2
                          }
                          start: Object {
                            column: 28
                            index: 38
                            line: 2
                          }
                        }
                      }
                    }
                  }
                }
              }
              params: Array [
                BindingIdentifier {
                  name: 'a'
                  loc: Object {
                    filename: 'input.ts'
                    identifierName: 'a'
                    end: Object {
                      column: 10
                      index: 20
                      line: 2
                    }
                    start: Object {
                      column: 9
                      index: 19
                      line: 2
                    }
                  }
                  meta: PatternMeta {
                    optional: undefined
                    loc: Object {
                      filename: 'input.ts'
                      end: Object {
                        column: 13
                        index: 23
                        line: 2
                      }
                      start: Object {
                        column: 9
                        index: 19
                        line: 2
                      }
                    }
                    typeAnnotation: TSTypeReference {
                      typeParameters: undefined
                      loc: Object {
                        filename: 'input.ts'
                        end: Object {
                          column: 13
                          index: 23
                          line: 2
                        }
                        start: Object {
                          column: 12
                          index: 22
                          line: 2
                        }
                      }
                      typeName: ReferenceIdentifier {
                        name: 'T'
                        loc: Object {
                          filename: 'input.ts'
                          identifierName: 'T'
                          end: Object {
                            column: 13
                            index: 23
                            line: 2
                          }
                          start: Object {
                            column: 12
                            index: 22
                            line: 2
                          }
                        }
                      }
                    }
                  }
                }
                BindingIdentifier {
                  name: 'b'
                  loc: Object {
                    filename: 'input.ts'
                    identifierName: 'b'
                    end: Object {
                      column: 16
                      index: 26
                      line: 2
                    }
                    start: Object {
                      column: 15
                      index: 25
                      line: 2
                    }
                  }
                  meta: PatternMeta {
                    optional: true
                    loc: Object {
                      filename: 'input.ts'
                      end: Object {
                        column: 20
                        index: 30
                        line: 2
                      }
                      start: Object {
                        column: 15
                        index: 25
                        line: 2
                      }
                    }
                    typeAnnotation: TSTypeReference {
                      typeParameters: undefined
                      loc: Object {
                        filename: 'input.ts'
                        end: Object {
                          column: 20
                          index: 30
                          line: 2
                        }
                        start: Object {
                          column: 19
                          index: 29
                          line: 2
                        }
                      }
                      typeName: ReferenceIdentifier {
                        name: 'T'
                        loc: Object {
                          filename: 'input.ts'
                          identifierName: 'T'
                          end: Object {
                            column: 20
                            index: 30
                            line: 2
                          }
                          start: Object {
                            column: 19
                            index: 29
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
          ClassMethod {
            kind: 'method'
            key: ComputedPropertyKey {
              value: MemberExpression {
                loc: Object {
                  filename: 'input.ts'
                  end: Object {
                    column: 20
                    index: 69
                    line: 3
                  }
                  start: Object {
                    column: 5
                    index: 54
                    line: 3
                  }
                }
                object: ReferenceIdentifier {
                  name: 'Symbol'
                  loc: Object {
                    filename: 'input.ts'
                    identifierName: 'Symbol'
                    end: Object {
                      column: 11
                      index: 60
                      line: 3
                    }
                    start: Object {
                      column: 5
                      index: 54
                      line: 3
                    }
                  }
                }
                property: StaticMemberProperty {
                  value: Identifier {
                    name: 'iterator'
                    loc: Object {
                      filename: 'input.ts'
                      identifierName: 'iterator'
                      end: Object {
                        column: 20
                        index: 69
                        line: 3
                      }
                      start: Object {
                        column: 12
                        index: 61
                        line: 3
                      }
                    }
                  }
                  loc: Object {
                    filename: 'input.ts'
                    identifierName: 'iterator'
                    end: Object {
                      column: 20
                      index: 69
                      line: 3
                    }
                    start: Object {
                      column: 12
                      index: 61
                      line: 3
                    }
                  }
                }
              }
              variance: undefined
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 21
                  index: 70
                  line: 3
                }
                start: Object {
                  column: 4
                  index: 53
                  line: 3
                }
              }
            }
            loc: Object {
              filename: 'input.ts'
              end: Object {
                column: 32
                index: 81
                line: 3
              }
              start: Object {
                column: 4
                index: 53
                line: 3
              }
            }
            body: BlockStatement {
              body: Array []
              directives: Array []
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 32
                  index: 81
                  line: 3
                }
                start: Object {
                  column: 30
                  index: 79
                  line: 3
                }
              }
            }
            meta: ClassPropertyMeta {
              abstract: false
              accessibility: undefined
              optional: false
              readonly: false
              static: false
              typeAnnotation: undefined
              start: Object {
                column: 4
                index: 53
                line: 3
              }
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 21
                  index: 70
                  line: 3
                }
                start: Object {
                  column: 4
                  index: 53
                  line: 3
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
              thisType: undefined
              loc: Object {
                filename: 'input.ts'
                end: Object {
                  column: 30
                  index: 79
                  line: 3
                }
                start: Object {
                  column: 24
                  index: 73
                  line: 3
                }
              }
              returnType: TSTypeReference {
                typeParameters: undefined
                loc: Object {
                  filename: 'input.ts'
                  end: Object {
                    column: 29
                    index: 78
                    line: 3
                  }
                  start: Object {
                    column: 28
                    index: 77
                    line: 3
                  }
                }
                typeName: ReferenceIdentifier {
                  name: 'T'
                  loc: Object {
                    filename: 'input.ts'
                    identifierName: 'T'
                    end: Object {
                      column: 29
                      index: 78
                      line: 3
                    }
                    start: Object {
                      column: 28
                      index: 77
                      line: 3
                    }
                  }
                }
              }
              typeParameters: TSTypeParameterDeclaration {
                loc: Object {
                  filename: 'input.ts'
                  end: Object {
                    column: 24
                    index: 73
                    line: 3
                  }
                  start: Object {
                    column: 21
                    index: 70
                    line: 3
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
                        column: 23
                        index: 72
                        line: 3
                      }
                      start: Object {
                        column: 22
                        index: 71
                        line: 3
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

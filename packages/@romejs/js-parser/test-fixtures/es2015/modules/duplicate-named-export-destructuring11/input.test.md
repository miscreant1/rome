# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > modules > duplicate-named-export-destructuring11`

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
  sourceType: 'module'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 97
      line: 3
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ExportLocalDeclaration {
      exportKind: 'value'
      specifiers: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 25
          index: 25
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: FunctionDeclaration {
        id: BindingIdentifier {
          name: 'foo4'
          loc: Object {
            filename: 'input.js'
            identifierName: 'foo4'
            end: Object {
              column: 20
              index: 20
              line: 1
            }
            start: Object {
              column: 16
              index: 16
              line: 1
            }
          }
        }
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 25
            index: 25
            line: 1
          }
          start: Object {
            column: 7
            index: 7
            line: 1
          }
        }
        body: BlockStatement {
          body: Array []
          directives: Array []
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 25
              index: 25
              line: 1
            }
            start: Object {
              column: 23
              index: 23
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
              column: 23
              index: 23
              line: 1
            }
            start: Object {
              column: 20
              index: 20
              line: 1
            }
          }
        }
      }
    }
    EmptyStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 26
          index: 26
          line: 1
        }
        start: Object {
          column: 25
          index: 25
          line: 1
        }
      }
    }
    ExportLocalDeclaration {
      exportKind: 'value'
      specifiers: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 69
          index: 96
          line: 2
        }
        start: Object {
          column: 0
          index: 27
          line: 2
        }
      }
      declaration: VariableDeclarationStatement {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 69
            index: 96
            line: 2
          }
          start: Object {
            column: 7
            index: 34
            line: 2
          }
        }
        declaration: VariableDeclaration {
          kind: 'const'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 69
              index: 96
              line: 2
            }
            start: Object {
              column: 7
              index: 34
              line: 2
            }
          }
          declarations: Array [
            VariableDeclarator {
              id: BindingArrayPattern {
                rest: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 62
                    index: 89
                    line: 2
                  }
                  start: Object {
                    column: 13
                    index: 40
                    line: 2
                  }
                }
                elements: Array [
                  BindingObjectPattern {
                    rest: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 61
                        index: 88
                        line: 2
                      }
                      start: Object {
                        column: 14
                        index: 41
                        line: 2
                      }
                    }
                    meta: PatternMeta {
                      optional: undefined
                      typeAnnotation: undefined
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 61
                          index: 88
                          line: 2
                        }
                        start: Object {
                          column: 14
                          index: 41
                          line: 2
                        }
                      }
                    }
                    properties: Array [
                      BindingObjectPatternProperty {
                        key: StaticPropertyKey {
                          value: Identifier {
                            name: 'a'
                            loc: Object {
                              filename: 'input.js'
                              identifierName: 'a'
                              end: Object {
                                column: 17
                                index: 44
                                line: 2
                              }
                              start: Object {
                                column: 16
                                index: 43
                                line: 2
                              }
                            }
                          }
                          variance: undefined
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 17
                              index: 44
                              line: 2
                            }
                            start: Object {
                              column: 16
                              index: 43
                              line: 2
                            }
                          }
                        }
                        value: BindingArrayPattern {
                          rest: undefined
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 28
                              index: 55
                              line: 2
                            }
                            start: Object {
                              column: 19
                              index: 46
                              line: 2
                            }
                          }
                          elements: Array [
                            BindingObjectPattern {
                              rest: undefined
                              loc: Object {
                                filename: 'input.js'
                                end: Object {
                                  column: 27
                                  index: 54
                                  line: 2
                                }
                                start: Object {
                                  column: 20
                                  index: 47
                                  line: 2
                                }
                              }
                              meta: PatternMeta {
                                optional: undefined
                                typeAnnotation: undefined
                                loc: Object {
                                  filename: 'input.js'
                                  end: Object {
                                    column: 27
                                    index: 54
                                    line: 2
                                  }
                                  start: Object {
                                    column: 20
                                    index: 47
                                    line: 2
                                  }
                                }
                              }
                              properties: Array [
                                BindingObjectPatternProperty {
                                  key: StaticPropertyKey {
                                    value: Identifier {
                                      name: 'foo'
                                      loc: Object {
                                        filename: 'input.js'
                                        identifierName: 'foo'
                                        end: Object {
                                          column: 25
                                          index: 52
                                          line: 2
                                        }
                                        start: Object {
                                          column: 22
                                          index: 49
                                          line: 2
                                        }
                                      }
                                    }
                                    variance: undefined
                                    loc: Object {
                                      filename: 'input.js'
                                      end: Object {
                                        column: 25
                                        index: 52
                                        line: 2
                                      }
                                      start: Object {
                                        column: 22
                                        index: 49
                                        line: 2
                                      }
                                    }
                                  }
                                  value: BindingIdentifier {
                                    name: 'foo'
                                    loc: Object {
                                      filename: 'input.js'
                                      identifierName: 'foo'
                                      end: Object {
                                        column: 25
                                        index: 52
                                        line: 2
                                      }
                                      start: Object {
                                        column: 22
                                        index: 49
                                        line: 2
                                      }
                                    }
                                  }
                                  loc: Object {
                                    filename: 'input.js'
                                    end: Object {
                                      column: 25
                                      index: 52
                                      line: 2
                                    }
                                    start: Object {
                                      column: 22
                                      index: 49
                                      line: 2
                                    }
                                  }
                                }
                              ]
                            }
                          ]
                        }
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 28
                            index: 55
                            line: 2
                          }
                          start: Object {
                            column: 16
                            index: 43
                            line: 2
                          }
                        }
                      }
                      BindingObjectPatternProperty {
                        key: StaticPropertyKey {
                          value: Identifier {
                            name: 'b'
                            loc: Object {
                              filename: 'input.js'
                              identifierName: 'b'
                              end: Object {
                                column: 31
                                index: 58
                                line: 2
                              }
                              start: Object {
                                column: 30
                                index: 57
                                line: 2
                              }
                            }
                          }
                          variance: undefined
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 31
                              index: 58
                              line: 2
                            }
                            start: Object {
                              column: 30
                              index: 57
                              line: 2
                            }
                          }
                        }
                        value: BindingObjectPattern {
                          rest: undefined
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 59
                              index: 86
                              line: 2
                            }
                            start: Object {
                              column: 33
                              index: 60
                              line: 2
                            }
                          }
                          properties: Array [
                            BindingObjectPatternProperty {
                              key: StaticPropertyKey {
                                value: Identifier {
                                  name: 'foo2'
                                  loc: Object {
                                    filename: 'input.js'
                                    identifierName: 'foo2'
                                    end: Object {
                                      column: 39
                                      index: 66
                                      line: 2
                                    }
                                    start: Object {
                                      column: 35
                                      index: 62
                                      line: 2
                                    }
                                  }
                                }
                                variance: undefined
                                loc: Object {
                                  filename: 'input.js'
                                  end: Object {
                                    column: 39
                                    index: 66
                                    line: 2
                                  }
                                  start: Object {
                                    column: 35
                                    index: 62
                                    line: 2
                                  }
                                }
                              }
                              value: BindingArrayPattern {
                                rest: undefined
                                loc: Object {
                                  filename: 'input.js'
                                  end: Object {
                                    column: 57
                                    index: 84
                                    line: 2
                                  }
                                  start: Object {
                                    column: 41
                                    index: 68
                                    line: 2
                                  }
                                }
                                elements: Array [
                                  BindingObjectPattern {
                                    rest: undefined
                                    loc: Object {
                                      filename: 'input.js'
                                      end: Object {
                                        column: 56
                                        index: 83
                                        line: 2
                                      }
                                      start: Object {
                                        column: 42
                                        index: 69
                                        line: 2
                                      }
                                    }
                                    meta: PatternMeta {
                                      optional: undefined
                                      typeAnnotation: undefined
                                      loc: Object {
                                        filename: 'input.js'
                                        end: Object {
                                          column: 56
                                          index: 83
                                          line: 2
                                        }
                                        start: Object {
                                          column: 42
                                          index: 69
                                          line: 2
                                        }
                                      }
                                    }
                                    properties: Array [
                                      BindingObjectPatternProperty {
                                        key: StaticPropertyKey {
                                          value: Identifier {
                                            name: 'foo3'
                                            loc: Object {
                                              filename: 'input.js'
                                              identifierName: 'foo3'
                                              end: Object {
                                                column: 48
                                                index: 75
                                                line: 2
                                              }
                                              start: Object {
                                                column: 44
                                                index: 71
                                                line: 2
                                              }
                                            }
                                          }
                                          variance: undefined
                                          loc: Object {
                                            filename: 'input.js'
                                            end: Object {
                                              column: 48
                                              index: 75
                                              line: 2
                                            }
                                            start: Object {
                                              column: 44
                                              index: 71
                                              line: 2
                                            }
                                          }
                                        }
                                        value: BindingIdentifier {
                                          name: 'foo4'
                                          loc: Object {
                                            filename: 'input.js'
                                            identifierName: 'foo4'
                                            end: Object {
                                              column: 54
                                              index: 81
                                              line: 2
                                            }
                                            start: Object {
                                              column: 50
                                              index: 77
                                              line: 2
                                            }
                                          }
                                        }
                                        loc: Object {
                                          filename: 'input.js'
                                          end: Object {
                                            column: 54
                                            index: 81
                                            line: 2
                                          }
                                          start: Object {
                                            column: 44
                                            index: 71
                                            line: 2
                                          }
                                        }
                                      }
                                    ]
                                  }
                                ]
                              }
                              loc: Object {
                                filename: 'input.js'
                                end: Object {
                                  column: 57
                                  index: 84
                                  line: 2
                                }
                                start: Object {
                                  column: 35
                                  index: 62
                                  line: 2
                                }
                              }
                            }
                          ]
                        }
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 59
                            index: 86
                            line: 2
                          }
                          start: Object {
                            column: 30
                            index: 57
                            line: 2
                          }
                        }
                      }
                    ]
                  }
                ]
              }
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 68
                  index: 95
                  line: 2
                }
                start: Object {
                  column: 13
                  index: 40
                  line: 2
                }
              }
              init: ReferenceIdentifier {
                name: 'bar'
                loc: Object {
                  filename: 'input.js'
                  identifierName: 'bar'
                  end: Object {
                    column: 68
                    index: 95
                    line: 2
                  }
                  start: Object {
                    column: 65
                    index: 92
                    line: 2
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

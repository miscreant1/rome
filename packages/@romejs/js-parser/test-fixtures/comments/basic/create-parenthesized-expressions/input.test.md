# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `comments > basic > create-parenthesized-expressions`

```javascript
Program {
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
      index: 66
      line: 13
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  comments: Array [
    CommentLine {
      id: '0'
      value: ' One'
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 6
          index: 6
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
    }
    CommentBlock {
      id: '1'
      value: ' Two '
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 9
          index: 22
          line: 4
        }
        start: Object {
          column: 0
          index: 13
          line: 4
        }
      }
    }
    CommentLine {
      id: '2'
      value: ' Three'
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 10
          index: 41
          line: 8
        }
        start: Object {
          column: 2
          index: 33
          line: 8
        }
      }
    }
    CommentBlock {
      id: '3'
      value: ' Four '
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 11
          index: 61
          line: 12
        }
        start: Object {
          column: 1
          index: 51
          line: 12
        }
      }
    }
  ]
  body: Array [
    ExpressionStatement {
      leadingComments: Array ['0']
      trailingComments: Array ['1']
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 4
          index: 11
          line: 2
        }
        start: Object {
          column: 0
          index: 7
          line: 2
        }
      }
      expression: NumericLiteral {
        value: 1
        format: undefined
        leadingComments: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 2
            index: 9
            line: 2
          }
          start: Object {
            column: 1
            index: 8
            line: 2
          }
        }
      }
    }
    ExpressionStatement {
      leadingComments: Array ['1']
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 4
          index: 27
          line: 5
        }
        start: Object {
          column: 0
          index: 23
          line: 5
        }
      }
      expression: NumericLiteral {
        value: 2
        format: undefined
        leadingComments: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 2
            index: 25
            line: 5
          }
          start: Object {
            column: 1
            index: 24
            line: 5
          }
        }
      }
    }
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 2
          index: 48
          line: 10
        }
        start: Object {
          column: 0
          index: 29
          line: 7
        }
      }
      expression: NumericLiteral {
        value: 3
        format: undefined
        leadingComments: Array ['2']
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 3
            index: 45
            line: 9
          }
          start: Object {
            column: 2
            index: 44
            line: 9
          }
        }
      }
    }
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 15
          index: 65
          line: 12
        }
        start: Object {
          column: 0
          index: 50
          line: 12
        }
      }
      expression: NumericLiteral {
        value: 4
        format: undefined
        leadingComments: Array ['3']
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 13
            index: 63
            line: 12
          }
          start: Object {
            column: 12
            index: 62
            line: 12
          }
        }
      }
    }
  ]
}
```

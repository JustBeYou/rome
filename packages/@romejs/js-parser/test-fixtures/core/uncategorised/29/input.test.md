# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 29`

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
      column: 38
      index: 38
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
          column: 38
          index: 38
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: AssignmentExpression {
        operator: '='
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 38
            index: 38
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        left: AssignmentIdentifier {
          name: 'x'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 1
              index: 1
              line: 1
            }
            start: Object {
              column: 0
              index: 0
              line: 1
            }
          }
        }
        right: ObjectExpression {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 38
              index: 38
              line: 1
            }
            start: Object {
              column: 4
              index: 4
              line: 1
            }
          }
          properties: Array [
            ObjectMethod {
              kind: 'get'
              key: StaticPropertyKey {
                value: Identifier {
                  name: 'width'
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 15
                      index: 15
                      line: 1
                    }
                    start: Object {
                      column: 10
                      index: 10
                      line: 1
                    }
                  }
                }
                variance: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 15
                    index: 15
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
                  column: 36
                  index: 36
                  line: 1
                }
                start: Object {
                  column: 6
                  index: 6
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
                    column: 18
                    index: 18
                    line: 1
                  }
                  start: Object {
                    column: 15
                    index: 15
                    line: 1
                  }
                }
              }
              body: BlockStatement {
                directives: Array []
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 36
                    index: 36
                    line: 1
                  }
                  start: Object {
                    column: 18
                    index: 18
                    line: 1
                  }
                }
                body: Array [
                  ReturnStatement {
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 34
                        index: 34
                        line: 1
                      }
                      start: Object {
                        column: 20
                        index: 20
                        line: 1
                      }
                    }
                    argument: ReferenceIdentifier {
                      name: 'm_width'
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 34
                          index: 34
                          line: 1
                        }
                        start: Object {
                          column: 27
                          index: 27
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
    }
  ]
}
```
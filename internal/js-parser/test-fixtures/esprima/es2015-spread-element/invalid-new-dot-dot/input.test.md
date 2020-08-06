# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-spread-element > invalid-new-dot-dot`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: true
	directives: Array []
	filename: "esprima/es2015-spread-element/invalid-new-dot-dot/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-spread-element/invalid-new-dot-dot/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {
					parts: Array [
						RAW_MARKUP {value: "Unknown start to an "}
						"new expression argument"
					]
				}
			}
			location: Object {
				filename: "esprima/es2015-spread-element/invalid-new-dot-dot/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 6
					line: 1
				}
				start: Object {
					column: 6
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/es2015-spread-element/invalid-new-dot-dot/input.js"
				end: Object {
					column: 11
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSNewExpression {
				optional: undefined
				typeArguments: undefined
				loc: Object {
					filename: "esprima/es2015-spread-element/invalid-new-dot-dot/input.js"
					end: Object {
						column: 10
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				callee: JSReferenceIdentifier {
					name: "f"
					loc: Object {
						filename: "esprima/es2015-spread-element/invalid-new-dot-dot/input.js"
						identifierName: "f"
						end: Object {
							column: 5
							line: 1
						}
						start: Object {
							column: 4
							line: 1
						}
					}
				}
				arguments: Array [
					JSMemberExpression {
						loc: Object {
							filename: "esprima/es2015-spread-element/invalid-new-dot-dot/input.js"
							end: Object {
								column: 9
								line: 1
							}
							start: Object {
								column: 6
								line: 1
							}
						}
						object: JSReferenceIdentifier {
							name: "INVALID_PLACEHOLDER"
							loc: Object {
								filename: "esprima/es2015-spread-element/invalid-new-dot-dot/input.js"
								end: Object {
									column: 7
									line: 1
								}
								start: Object {
									column: 6
									line: 1
								}
							}
						}
						property: JSStaticMemberProperty {
							value: JSIdentifier {
								name: "g"
								loc: Object {
									filename: "esprima/es2015-spread-element/invalid-new-dot-dot/input.js"
									identifierName: "g"
									end: Object {
										column: 9
										line: 1
									}
									start: Object {
										column: 8
										line: 1
									}
								}
							}
							loc: Object {
								filename: "esprima/es2015-spread-element/invalid-new-dot-dot/input.js"
								identifierName: "g"
								end: Object {
									column: 9
									line: 1
								}
								start: Object {
									column: 8
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
```

### `diagnostics`

```

 esprima/es2015-spread-element/invalid-new-dot-dot/input.js:1:6 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unknown start to an new expression argument

    new f(..g);
          ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
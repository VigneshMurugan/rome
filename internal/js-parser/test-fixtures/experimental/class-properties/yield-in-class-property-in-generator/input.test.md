# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > class-properties > yield-in-class-property-in-generator`

### `ast`

```javascript
JSRoot {
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "experimental/class-properties/yield-in-class-property-in-generator/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "experimental/class-properties/yield-in-class-property-in-generator/input.js"
		end: Object {
			column: 0
			line: 7
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	comments: Array [
		CommentLine {
			id: "0"
			value: " here yield is an identifier reference"
			loc: Object {
				filename: "experimental/class-properties/yield-in-class-property-in-generator/input.js"
				end: Object {
					column: 44
					line: 3
				}
				start: Object {
					column: 4
					line: 3
				}
			}
		}
	]
	body: Array [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "foo"
				loc: Object {
					filename: "experimental/class-properties/yield-in-class-property-in-generator/input.js"
					identifierName: "foo"
					end: Object {
						column: 13
						line: 1
					}
					start: Object {
						column: 10
						line: 1
					}
				}
			}
			loc: Object {
				filename: "experimental/class-properties/yield-in-class-property-in-generator/input.js"
				end: Object {
					column: 1
					line: 6
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			head: JSFunctionHead {
				async: false
				generator: true
				hasHoistedVars: false
				params: Array []
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "experimental/class-properties/yield-in-class-property-in-generator/input.js"
					end: Object {
						column: 15
						line: 1
					}
					start: Object {
						column: 13
						line: 1
					}
				}
			}
			body: JSBlockStatement {
				directives: Array []
				loc: Object {
					filename: "experimental/class-properties/yield-in-class-property-in-generator/input.js"
					end: Object {
						column: 1
						line: 6
					}
					start: Object {
						column: 16
						line: 1
					}
				}
				body: Array [
					JSClassDeclaration {
						id: JSBindingIdentifier {
							name: "C"
							loc: Object {
								filename: "experimental/class-properties/yield-in-class-property-in-generator/input.js"
								identifierName: "C"
								end: Object {
									column: 9
									line: 2
								}
								start: Object {
									column: 8
									line: 2
								}
							}
						}
						loc: Object {
							filename: "experimental/class-properties/yield-in-class-property-in-generator/input.js"
							end: Object {
								column: 3
								line: 5
							}
							start: Object {
								column: 2
								line: 2
							}
						}
						meta: JSClassHead {
							implements: undefined
							superClass: undefined
							superTypeParameters: undefined
							typeParameters: undefined
							loc: Object {
								filename: "experimental/class-properties/yield-in-class-property-in-generator/input.js"
								end: Object {
									column: 3
									line: 5
								}
								start: Object {
									column: 2
									line: 2
								}
							}
							body: Array [
								JSClassProperty {
									key: JSStaticPropertyKey {
										value: JSIdentifier {
											name: "p"
											leadingComments: undefined
											loc: Object {
												filename: "experimental/class-properties/yield-in-class-property-in-generator/input.js"
												identifierName: "p"
												end: Object {
													column: 5
													line: 4
												}
												start: Object {
													column: 4
													line: 4
												}
											}
										}
										leadingComments: undefined
										loc: Object {
											filename: "experimental/class-properties/yield-in-class-property-in-generator/input.js"
											end: Object {
												column: 5
												line: 4
											}
											start: Object {
												column: 4
												line: 4
											}
										}
									}
									value: JSYieldExpression {
										delegate: false
										loc: Object {
											filename: "experimental/class-properties/yield-in-class-property-in-generator/input.js"
											end: Object {
												column: 18
												line: 4
											}
											start: Object {
												column: 8
												line: 4
											}
										}
										argument: JSUnaryExpression {
											operator: "+"
											prefix: true
											loc: Object {
												filename: "experimental/class-properties/yield-in-class-property-in-generator/input.js"
												end: Object {
													column: 18
													line: 4
												}
												start: Object {
													column: 14
													line: 4
												}
											}
											argument: JSNumericLiteral {
												value: 42
												format: undefined
												loc: Object {
													filename: "experimental/class-properties/yield-in-class-property-in-generator/input.js"
													end: Object {
														column: 18
														line: 4
													}
													start: Object {
														column: 16
														line: 4
													}
												}
											}
										}
									}
									definite: undefined
									typeAnnotation: undefined
									leadingComments: Array ["0"]
									loc: Object {
										filename: "experimental/class-properties/yield-in-class-property-in-generator/input.js"
										end: Object {
											column: 19
											line: 4
										}
										start: Object {
											column: 4
											line: 4
										}
									}
									meta: JSClassPropertyMeta {
										abstract: false
										accessibility: undefined
										leadingComments: undefined
										optional: false
										readonly: false
										static: false
										typeAnnotation: undefined
										start: Object {
											column: 4
											line: 4
										}
										loc: Object {
											filename: "experimental/class-properties/yield-in-class-property-in-generator/input.js"
											end: Object {
												column: 5
												line: 4
											}
											start: Object {
												column: 4
												line: 4
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

### `diagnostics`

```
✔ No known problems!

```
# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-export-declaration > export-from-named-as-specifiers`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-export-declaration/export-from-named-as-specifiers/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-export-declaration/export-from-named-as-specifiers/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExportExternalDeclaration {
			defaultSpecifier: undefined
			exportKind: undefined
			namespaceSpecifier: undefined
			loc: Object {
				filename: "esprima/es2015-export-declaration/export-from-named-as-specifiers/input.js"
				end: Object {
					column: 40
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			source: JSStringLiteral {
				value: "foo"
				loc: Object {
					filename: "esprima/es2015-export-declaration/export-from-named-as-specifiers/input.js"
					end: Object {
						column: 39
						line: 1
					}
					start: Object {
						column: 34
						line: 1
					}
				}
			}
			namedSpecifiers: Array [
				JSExportExternalSpecifier {
					loc: Object {
						filename: "esprima/es2015-export-declaration/export-from-named-as-specifiers/input.js"
						end: Object {
							column: 22
							line: 1
						}
						start: Object {
							column: 8
							line: 1
						}
					}
					exported: JSIdentifier {
						name: "default"
						loc: Object {
							filename: "esprima/es2015-export-declaration/export-from-named-as-specifiers/input.js"
							identifierName: "default"
							end: Object {
								column: 22
								line: 1
							}
							start: Object {
								column: 15
								line: 1
							}
						}
					}
					local: JSIdentifier {
						name: "foo"
						loc: Object {
							filename: "esprima/es2015-export-declaration/export-from-named-as-specifiers/input.js"
							identifierName: "foo"
							end: Object {
								column: 11
								line: 1
							}
							start: Object {
								column: 8
								line: 1
							}
						}
					}
				}
				JSExportExternalSpecifier {
					loc: Object {
						filename: "esprima/es2015-export-declaration/export-from-named-as-specifiers/input.js"
						end: Object {
							column: 27
							line: 1
						}
						start: Object {
							column: 24
							line: 1
						}
					}
					exported: JSIdentifier {
						name: "bar"
						loc: Object {
							filename: "esprima/es2015-export-declaration/export-from-named-as-specifiers/input.js"
							identifierName: "bar"
							end: Object {
								column: 27
								line: 1
							}
							start: Object {
								column: 24
								line: 1
							}
						}
					}
					local: JSIdentifier {
						name: "bar"
						loc: Object {
							filename: "esprima/es2015-export-declaration/export-from-named-as-specifiers/input.js"
							identifierName: "bar"
							end: Object {
								column: 27
								line: 1
							}
							start: Object {
								column: 24
								line: 1
							}
						}
					}
				}
			]
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```

# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > class-properties > new-target`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "experimental/class-properties/new-target/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "experimental/class-properties/new-target/input.js"
		end: Object {
			column: 0
			line: 11
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "X"
				loc: Object {
					filename: "experimental/class-properties/new-target/input.js"
					identifierName: "X"
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
			loc: Object {
				filename: "experimental/class-properties/new-target/input.js"
				end: Object {
					column: 1
					line: 10
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "experimental/class-properties/new-target/input.js"
					end: Object {
						column: 1
						line: 10
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				body: Array [
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "a"
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									identifierName: "a"
									end: Object {
										column: 10
										line: 2
									}
									start: Object {
										column: 9
										line: 2
									}
								}
							}
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 10
									line: 2
								}
								start: Object {
									column: 9
									line: 2
								}
							}
						}
						value: JSMetaProperty {
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 23
									line: 2
								}
								start: Object {
									column: 13
									line: 2
								}
							}
							meta: JSIdentifier {
								name: "new"
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									identifierName: "new"
									end: Object {
										column: 16
										line: 2
									}
									start: Object {
										column: 13
										line: 2
									}
								}
							}
							property: JSIdentifier {
								name: "target"
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									identifierName: "target"
									end: Object {
										column: 23
										line: 2
									}
									start: Object {
										column: 17
										line: 2
									}
								}
							}
						}
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "experimental/class-properties/new-target/input.js"
							end: Object {
								column: 24
								line: 2
							}
							start: Object {
								column: 2
								line: 2
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 2
								line: 2
							}
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 10
									line: 2
								}
								start: Object {
									column: 2
									line: 2
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "b"
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									identifierName: "b"
									end: Object {
										column: 10
										line: 3
									}
									start: Object {
										column: 9
										line: 3
									}
								}
							}
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 10
									line: 3
								}
								start: Object {
									column: 9
									line: 3
								}
							}
						}
						value: JSAssignmentExpression {
							operator: "="
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 39
									line: 3
								}
								start: Object {
									column: 14
									line: 3
								}
							}
							left: JSAssignmentIdentifier {
								name: "foo"
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									identifierName: "foo"
									end: Object {
										column: 17
										line: 3
									}
									start: Object {
										column: 14
										line: 3
									}
								}
							}
							right: JSBinaryExpression {
								operator: "+"
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									end: Object {
										column: 39
										line: 3
									}
									start: Object {
										column: 20
										line: 3
									}
								}
								left: JSNumericLiteral {
									value: 1
									format: undefined
									loc: Object {
										filename: "experimental/class-properties/new-target/input.js"
										end: Object {
											column: 21
											line: 3
										}
										start: Object {
											column: 20
											line: 3
										}
									}
								}
								right: JSCallExpression {
									loc: Object {
										filename: "experimental/class-properties/new-target/input.js"
										end: Object {
											column: 39
											line: 3
										}
										start: Object {
											column: 24
											line: 3
										}
									}
									callee: JSReferenceIdentifier {
										name: "bar"
										loc: Object {
											filename: "experimental/class-properties/new-target/input.js"
											identifierName: "bar"
											end: Object {
												column: 27
												line: 3
											}
											start: Object {
												column: 24
												line: 3
											}
										}
									}
									arguments: Array [
										JSMetaProperty {
											loc: Object {
												filename: "experimental/class-properties/new-target/input.js"
												end: Object {
													column: 38
													line: 3
												}
												start: Object {
													column: 28
													line: 3
												}
											}
											meta: JSIdentifier {
												name: "new"
												loc: Object {
													filename: "experimental/class-properties/new-target/input.js"
													identifierName: "new"
													end: Object {
														column: 31
														line: 3
													}
													start: Object {
														column: 28
														line: 3
													}
												}
											}
											property: JSIdentifier {
												name: "target"
												loc: Object {
													filename: "experimental/class-properties/new-target/input.js"
													identifierName: "target"
													end: Object {
														column: 38
														line: 3
													}
													start: Object {
														column: 32
														line: 3
													}
												}
											}
										}
									]
								}
							}
						}
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "experimental/class-properties/new-target/input.js"
							end: Object {
								column: 41
								line: 3
							}
							start: Object {
								column: 2
								line: 3
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 2
								line: 3
							}
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 10
									line: 3
								}
								start: Object {
									column: 2
									line: 3
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "c"
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									identifierName: "c"
									end: Object {
										column: 10
										line: 4
									}
									start: Object {
										column: 9
										line: 4
									}
								}
							}
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 10
									line: 4
								}
								start: Object {
									column: 9
									line: 4
								}
							}
						}
						value: JSArrowFunctionExpression {
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 29
									line: 4
								}
								start: Object {
									column: 13
									line: 4
								}
							}
							head: JSFunctionHead {
								async: false
								hasHoistedVars: false
								params: Array []
								rest: undefined
								returnType: undefined
								thisType: undefined
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									end: Object {
										column: 18
										line: 4
									}
									start: Object {
										column: 13
										line: 4
									}
								}
							}
							body: JSMetaProperty {
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									end: Object {
										column: 29
										line: 4
									}
									start: Object {
										column: 19
										line: 4
									}
								}
								meta: JSIdentifier {
									name: "new"
									loc: Object {
										filename: "experimental/class-properties/new-target/input.js"
										identifierName: "new"
										end: Object {
											column: 22
											line: 4
										}
										start: Object {
											column: 19
											line: 4
										}
									}
								}
								property: JSIdentifier {
									name: "target"
									loc: Object {
										filename: "experimental/class-properties/new-target/input.js"
										identifierName: "target"
										end: Object {
											column: 29
											line: 4
										}
										start: Object {
											column: 23
											line: 4
										}
									}
								}
							}
						}
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "experimental/class-properties/new-target/input.js"
							end: Object {
								column: 30
								line: 4
							}
							start: Object {
								column: 2
								line: 4
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 2
								line: 4
							}
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 10
									line: 4
								}
								start: Object {
									column: 2
									line: 4
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "d"
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									identifierName: "d"
									end: Object {
										column: 10
										line: 5
									}
									start: Object {
										column: 9
										line: 5
									}
								}
							}
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 10
									line: 5
								}
								start: Object {
									column: 9
									line: 5
								}
							}
						}
						value: JSArrowFunctionExpression {
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 37
									line: 5
								}
								start: Object {
									column: 13
									line: 5
								}
							}
							body: JSBlockStatement {
								body: Array []
								directives: Array []
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									end: Object {
										column: 37
										line: 5
									}
									start: Object {
										column: 35
										line: 5
									}
								}
							}
							head: JSFunctionHead {
								async: false
								hasHoistedVars: false
								rest: undefined
								returnType: undefined
								thisType: undefined
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									end: Object {
										column: 34
										line: 5
									}
									start: Object {
										column: 13
										line: 5
									}
								}
								params: Array [
									JSBindingAssignmentPattern {
										operator: "="
										loc: Object {
											filename: "experimental/class-properties/new-target/input.js"
											end: Object {
												column: 30
												line: 5
											}
											start: Object {
												column: 14
												line: 5
											}
										}
										left: JSBindingIdentifier {
											name: "foo"
											loc: Object {
												filename: "experimental/class-properties/new-target/input.js"
												identifierName: "foo"
												end: Object {
													column: 17
													line: 5
												}
												start: Object {
													column: 14
													line: 5
												}
											}
										}
										right: JSMetaProperty {
											loc: Object {
												filename: "experimental/class-properties/new-target/input.js"
												end: Object {
													column: 30
													line: 5
												}
												start: Object {
													column: 20
													line: 5
												}
											}
											meta: JSIdentifier {
												name: "new"
												loc: Object {
													filename: "experimental/class-properties/new-target/input.js"
													identifierName: "new"
													end: Object {
														column: 23
														line: 5
													}
													start: Object {
														column: 20
														line: 5
													}
												}
											}
											property: JSIdentifier {
												name: "target"
												loc: Object {
													filename: "experimental/class-properties/new-target/input.js"
													identifierName: "target"
													end: Object {
														column: 30
														line: 5
													}
													start: Object {
														column: 24
														line: 5
													}
												}
											}
										}
									}
								]
							}
						}
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "experimental/class-properties/new-target/input.js"
							end: Object {
								column: 38
								line: 5
							}
							start: Object {
								column: 2
								line: 5
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 2
								line: 5
							}
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 10
									line: 5
								}
								start: Object {
									column: 2
									line: 5
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "e"
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									identifierName: "e"
									end: Object {
										column: 3
										line: 6
									}
									start: Object {
										column: 2
										line: 6
									}
								}
							}
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 3
									line: 6
								}
								start: Object {
									column: 2
									line: 6
								}
							}
						}
						value: JSMetaProperty {
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 16
									line: 6
								}
								start: Object {
									column: 6
									line: 6
								}
							}
							meta: JSIdentifier {
								name: "new"
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									identifierName: "new"
									end: Object {
										column: 9
										line: 6
									}
									start: Object {
										column: 6
										line: 6
									}
								}
							}
							property: JSIdentifier {
								name: "target"
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									identifierName: "target"
									end: Object {
										column: 16
										line: 6
									}
									start: Object {
										column: 10
										line: 6
									}
								}
							}
						}
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "experimental/class-properties/new-target/input.js"
							end: Object {
								column: 17
								line: 6
							}
							start: Object {
								column: 2
								line: 6
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 2
								line: 6
							}
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 3
									line: 6
								}
								start: Object {
									column: 2
									line: 6
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "f"
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									identifierName: "f"
									end: Object {
										column: 3
										line: 7
									}
									start: Object {
										column: 2
										line: 7
									}
								}
							}
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 3
									line: 7
								}
								start: Object {
									column: 2
									line: 7
								}
							}
						}
						value: JSAssignmentExpression {
							operator: "="
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 32
									line: 7
								}
								start: Object {
									column: 7
									line: 7
								}
							}
							left: JSAssignmentIdentifier {
								name: "foo"
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									identifierName: "foo"
									end: Object {
										column: 10
										line: 7
									}
									start: Object {
										column: 7
										line: 7
									}
								}
							}
							right: JSBinaryExpression {
								operator: "+"
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									end: Object {
										column: 32
										line: 7
									}
									start: Object {
										column: 13
										line: 7
									}
								}
								left: JSNumericLiteral {
									value: 1
									format: undefined
									loc: Object {
										filename: "experimental/class-properties/new-target/input.js"
										end: Object {
											column: 14
											line: 7
										}
										start: Object {
											column: 13
											line: 7
										}
									}
								}
								right: JSCallExpression {
									loc: Object {
										filename: "experimental/class-properties/new-target/input.js"
										end: Object {
											column: 32
											line: 7
										}
										start: Object {
											column: 17
											line: 7
										}
									}
									callee: JSReferenceIdentifier {
										name: "bar"
										loc: Object {
											filename: "experimental/class-properties/new-target/input.js"
											identifierName: "bar"
											end: Object {
												column: 20
												line: 7
											}
											start: Object {
												column: 17
												line: 7
											}
										}
									}
									arguments: Array [
										JSMetaProperty {
											loc: Object {
												filename: "experimental/class-properties/new-target/input.js"
												end: Object {
													column: 31
													line: 7
												}
												start: Object {
													column: 21
													line: 7
												}
											}
											meta: JSIdentifier {
												name: "new"
												loc: Object {
													filename: "experimental/class-properties/new-target/input.js"
													identifierName: "new"
													end: Object {
														column: 24
														line: 7
													}
													start: Object {
														column: 21
														line: 7
													}
												}
											}
											property: JSIdentifier {
												name: "target"
												loc: Object {
													filename: "experimental/class-properties/new-target/input.js"
													identifierName: "target"
													end: Object {
														column: 31
														line: 7
													}
													start: Object {
														column: 25
														line: 7
													}
												}
											}
										}
									]
								}
							}
						}
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "experimental/class-properties/new-target/input.js"
							end: Object {
								column: 34
								line: 7
							}
							start: Object {
								column: 2
								line: 7
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 2
								line: 7
							}
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 3
									line: 7
								}
								start: Object {
									column: 2
									line: 7
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "g"
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									identifierName: "g"
									end: Object {
										column: 3
										line: 8
									}
									start: Object {
										column: 2
										line: 8
									}
								}
							}
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 3
									line: 8
								}
								start: Object {
									column: 2
									line: 8
								}
							}
						}
						value: JSArrowFunctionExpression {
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 22
									line: 8
								}
								start: Object {
									column: 6
									line: 8
								}
							}
							head: JSFunctionHead {
								async: false
								hasHoistedVars: false
								params: Array []
								rest: undefined
								returnType: undefined
								thisType: undefined
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									end: Object {
										column: 11
										line: 8
									}
									start: Object {
										column: 6
										line: 8
									}
								}
							}
							body: JSMetaProperty {
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									end: Object {
										column: 22
										line: 8
									}
									start: Object {
										column: 12
										line: 8
									}
								}
								meta: JSIdentifier {
									name: "new"
									loc: Object {
										filename: "experimental/class-properties/new-target/input.js"
										identifierName: "new"
										end: Object {
											column: 15
											line: 8
										}
										start: Object {
											column: 12
											line: 8
										}
									}
								}
								property: JSIdentifier {
									name: "target"
									loc: Object {
										filename: "experimental/class-properties/new-target/input.js"
										identifierName: "target"
										end: Object {
											column: 22
											line: 8
										}
										start: Object {
											column: 16
											line: 8
										}
									}
								}
							}
						}
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "experimental/class-properties/new-target/input.js"
							end: Object {
								column: 23
								line: 8
							}
							start: Object {
								column: 2
								line: 8
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 2
								line: 8
							}
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 3
									line: 8
								}
								start: Object {
									column: 2
									line: 8
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "h"
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									identifierName: "h"
									end: Object {
										column: 3
										line: 9
									}
									start: Object {
										column: 2
										line: 9
									}
								}
							}
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 3
									line: 9
								}
								start: Object {
									column: 2
									line: 9
								}
							}
						}
						value: JSArrowFunctionExpression {
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 30
									line: 9
								}
								start: Object {
									column: 6
									line: 9
								}
							}
							body: JSBlockStatement {
								body: Array []
								directives: Array []
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									end: Object {
										column: 30
										line: 9
									}
									start: Object {
										column: 28
										line: 9
									}
								}
							}
							head: JSFunctionHead {
								async: false
								hasHoistedVars: false
								rest: undefined
								returnType: undefined
								thisType: undefined
								loc: Object {
									filename: "experimental/class-properties/new-target/input.js"
									end: Object {
										column: 27
										line: 9
									}
									start: Object {
										column: 6
										line: 9
									}
								}
								params: Array [
									JSBindingAssignmentPattern {
										operator: "="
										loc: Object {
											filename: "experimental/class-properties/new-target/input.js"
											end: Object {
												column: 23
												line: 9
											}
											start: Object {
												column: 7
												line: 9
											}
										}
										left: JSBindingIdentifier {
											name: "foo"
											loc: Object {
												filename: "experimental/class-properties/new-target/input.js"
												identifierName: "foo"
												end: Object {
													column: 10
													line: 9
												}
												start: Object {
													column: 7
													line: 9
												}
											}
										}
										right: JSMetaProperty {
											loc: Object {
												filename: "experimental/class-properties/new-target/input.js"
												end: Object {
													column: 23
													line: 9
												}
												start: Object {
													column: 13
													line: 9
												}
											}
											meta: JSIdentifier {
												name: "new"
												loc: Object {
													filename: "experimental/class-properties/new-target/input.js"
													identifierName: "new"
													end: Object {
														column: 16
														line: 9
													}
													start: Object {
														column: 13
														line: 9
													}
												}
											}
											property: JSIdentifier {
												name: "target"
												loc: Object {
													filename: "experimental/class-properties/new-target/input.js"
													identifierName: "target"
													end: Object {
														column: 23
														line: 9
													}
													start: Object {
														column: 17
														line: 9
													}
												}
											}
										}
									}
								]
							}
						}
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "experimental/class-properties/new-target/input.js"
							end: Object {
								column: 31
								line: 9
							}
							start: Object {
								column: 2
								line: 9
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 2
								line: 9
							}
							loc: Object {
								filename: "experimental/class-properties/new-target/input.js"
								end: Object {
									column: 3
									line: 9
								}
								start: Object {
									column: 2
									line: 9
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
✔ No known problems!

```
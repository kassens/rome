# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 323`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2015/uncategorised/323/input.js"
	hasHoistedVars: true
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/uncategorised/323/input.js"
		end: Object {
			column: 33
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSForInStatement {
			loc: Object {
				filename: "es2015/uncategorised/323/input.js"
				end: Object {
					column: 33
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			body: JSBlockStatement {
				body: Array []
				directives: Array []
				loc: Object {
					filename: "es2015/uncategorised/323/input.js"
					end: Object {
						column: 33
						line: 1
					}
					start: Object {
						column: 31
						line: 1
					}
				}
			}
			right: JSReferenceIdentifier {
				name: "obj"
				loc: Object {
					filename: "es2015/uncategorised/323/input.js"
					identifierName: "obj"
					end: Object {
						column: 29
						line: 1
					}
					start: Object {
						column: 26
						line: 1
					}
				}
			}
			left: JSVariableDeclaration {
				kind: "var"
				loc: Object {
					filename: "es2015/uncategorised/323/input.js"
					end: Object {
						column: 22
						line: 1
					}
					start: Object {
						column: 5
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingArrayPattern {
							rest: undefined
							loc: Object {
								filename: "es2015/uncategorised/323/input.js"
								end: Object {
									column: 22
									line: 1
								}
								start: Object {
									column: 9
									line: 1
								}
							}
							elements: Array [
								JSBindingIdentifier {
									name: "name"
									loc: Object {
										filename: "es2015/uncategorised/323/input.js"
										identifierName: "name"
										end: Object {
											column: 14
											line: 1
										}
										start: Object {
											column: 10
											line: 1
										}
									}
									meta: JSPatternMeta {
										optional: undefined
										typeAnnotation: undefined
										loc: Object {
											filename: "es2015/uncategorised/323/input.js"
											end: Object {
												column: 14
												line: 1
											}
											start: Object {
												column: 10
												line: 1
											}
										}
									}
								}
								JSBindingIdentifier {
									name: "value"
									loc: Object {
										filename: "es2015/uncategorised/323/input.js"
										identifierName: "value"
										end: Object {
											column: 21
											line: 1
										}
										start: Object {
											column: 16
											line: 1
										}
									}
									meta: JSPatternMeta {
										optional: undefined
										typeAnnotation: undefined
										loc: Object {
											filename: "es2015/uncategorised/323/input.js"
											end: Object {
												column: 21
												line: 1
											}
											start: Object {
												column: 16
												line: 1
											}
										}
									}
								}
							]
						}
						init: undefined
						loc: Object {
							filename: "es2015/uncategorised/323/input.js"
							end: Object {
								column: 22
								line: 1
							}
							start: Object {
								column: 9
								line: 1
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

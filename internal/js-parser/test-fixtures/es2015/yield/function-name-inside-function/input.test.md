# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > yield > function-name-inside-function`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2015/yield/function-name-inside-function/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/yield/function-name-inside-function/input.js"
		end: Object {
			column: 1
			line: 3
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "fn"
				loc: Object {
					filename: "es2015/yield/function-name-inside-function/input.js"
					identifierName: "fn"
					end: Object {
						column: 11
						line: 1
					}
					start: Object {
						column: 9
						line: 1
					}
				}
			}
			loc: Object {
				filename: "es2015/yield/function-name-inside-function/input.js"
				end: Object {
					column: 1
					line: 3
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			head: JSFunctionHead {
				async: false
				generator: false
				hasHoistedVars: false
				params: Array []
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "es2015/yield/function-name-inside-function/input.js"
					end: Object {
						column: 13
						line: 1
					}
					start: Object {
						column: 11
						line: 1
					}
				}
			}
			body: JSBlockStatement {
				directives: Array []
				loc: Object {
					filename: "es2015/yield/function-name-inside-function/input.js"
					end: Object {
						column: 1
						line: 3
					}
					start: Object {
						column: 14
						line: 1
					}
				}
				body: Array [
					JSFunctionDeclaration {
						id: JSBindingIdentifier {
							name: "yield"
							loc: Object {
								filename: "es2015/yield/function-name-inside-function/input.js"
								identifierName: "yield"
								end: Object {
									column: 16
									line: 2
								}
								start: Object {
									column: 11
									line: 2
								}
							}
						}
						loc: Object {
							filename: "es2015/yield/function-name-inside-function/input.js"
							end: Object {
								column: 21
								line: 2
							}
							start: Object {
								column: 2
								line: 2
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "es2015/yield/function-name-inside-function/input.js"
								end: Object {
									column: 21
									line: 2
								}
								start: Object {
									column: 19
									line: 2
								}
							}
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: Array []
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "es2015/yield/function-name-inside-function/input.js"
								end: Object {
									column: 18
									line: 2
								}
								start: Object {
									column: 16
									line: 2
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

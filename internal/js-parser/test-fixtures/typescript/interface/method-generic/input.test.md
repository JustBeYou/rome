# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > interface > method-generic`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/interface/method-generic/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/interface/method-generic/input.ts"
		end: Object {
			column: 0
			index: 62
			line: 4
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		TSInterfaceDeclaration {
			id: JSBindingIdentifier {
				name: "I"
				loc: Object {
					filename: "typescript/interface/method-generic/input.ts"
					identifierName: "I"
					end: Object {
						column: 11
						index: 11
						line: 1
					}
					start: Object {
						column: 10
						index: 10
						line: 1
					}
				}
			}
			extends: undefined
			typeParameters: undefined
			loc: Object {
				filename: "typescript/interface/method-generic/input.ts"
				end: Object {
					column: 1
					index: 61
					line: 3
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			body: TSInterfaceBody {
				loc: Object {
					filename: "typescript/interface/method-generic/input.ts"
					end: Object {
						column: 1
						index: 61
						line: 3
					}
					start: Object {
						column: 12
						index: 12
						line: 1
					}
				}
				body: Array [
					TSMethodSignature {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "m"
								loc: Object {
									filename: "typescript/interface/method-generic/input.ts"
									identifierName: "m"
									end: Object {
										column: 5
										index: 19
										line: 2
									}
									start: Object {
										column: 4
										index: 18
										line: 2
									}
								}
							}
							loc: Object {
								filename: "typescript/interface/method-generic/input.ts"
								end: Object {
									column: 5
									index: 19
									line: 2
								}
								start: Object {
									column: 4
									index: 18
									line: 2
								}
							}
						}
						optional: false
						loc: Object {
							filename: "typescript/interface/method-generic/input.ts"
							end: Object {
								column: 45
								index: 59
								line: 2
							}
							start: Object {
								column: 4
								index: 18
								line: 2
							}
						}
						returnType: TSTypeReference {
							typeParameters: undefined
							loc: Object {
								filename: "typescript/interface/method-generic/input.ts"
								end: Object {
									column: 44
									index: 58
									line: 2
								}
								start: Object {
									column: 43
									index: 57
									line: 2
								}
							}
							typeName: JSReferenceIdentifier {
								name: "T"
								loc: Object {
									filename: "typescript/interface/method-generic/input.ts"
									identifierName: "T"
									end: Object {
										column: 44
										index: 58
										line: 2
									}
									start: Object {
										column: 43
										index: 57
										line: 2
									}
								}
							}
						}
						meta: TSSignatureDeclarationMeta {
							parameters: Array []
							rest: undefined
							loc: Object {
								filename: "typescript/interface/method-generic/input.ts"
								end: Object {
									column: 44
									index: 58
									line: 2
								}
								start: Object {
									column: 5
									index: 19
									line: 2
								}
							}
							typeParameters: TSTypeParameterDeclaration {
								loc: Object {
									filename: "typescript/interface/method-generic/input.ts"
									end: Object {
										column: 39
										index: 53
										line: 2
									}
									start: Object {
										column: 5
										index: 19
										line: 2
									}
								}
								params: Array [
									TSTypeParameter {
										name: "T"
										loc: Object {
											filename: "typescript/interface/method-generic/input.ts"
											end: Object {
												column: 38
												index: 52
												line: 2
											}
											start: Object {
												column: 6
												index: 20
												line: 2
											}
										}
										constraint: TSObjectKeywordTypeAnnotation {
											loc: Object {
												filename: "typescript/interface/method-generic/input.ts"
												end: Object {
													column: 22
													index: 36
													line: 2
												}
												start: Object {
													column: 16
													index: 30
													line: 2
												}
											}
										}
										default: TSObjectTypeAnnotation {
											loc: Object {
												filename: "typescript/interface/method-generic/input.ts"
												end: Object {
													column: 38
													index: 52
													line: 2
												}
												start: Object {
													column: 25
													index: 39
													line: 2
												}
											}
											members: Array [
												TSPropertySignature {
													key: JSStaticPropertyKey {
														value: JSIdentifier {
															name: "x"
															loc: Object {
																filename: "typescript/interface/method-generic/input.ts"
																identifierName: "x"
																end: Object {
																	column: 28
																	index: 42
																	line: 2
																}
																start: Object {
																	column: 27
																	index: 41
																	line: 2
																}
															}
														}
														loc: Object {
															filename: "typescript/interface/method-generic/input.ts"
															end: Object {
																column: 28
																index: 42
																line: 2
															}
															start: Object {
																column: 27
																index: 41
																line: 2
															}
														}
													}
													optional: false
													readonly: false
													loc: Object {
														filename: "typescript/interface/method-generic/input.ts"
														end: Object {
															column: 36
															index: 50
															line: 2
														}
														start: Object {
															column: 27
															index: 41
															line: 2
														}
													}
													typeAnnotation: TSNumberKeywordTypeAnnotation {
														loc: Object {
															filename: "typescript/interface/method-generic/input.ts"
															end: Object {
																column: 36
																index: 50
																line: 2
															}
															start: Object {
																column: 30
																index: 44
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
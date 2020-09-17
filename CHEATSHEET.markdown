# Wallmob coding cheatsheet

## Higher order functions

**Reduce**
```swift
let #result# = #collection#.reduce(#initialValue#, { result, element in
	return result + element.#property#
})
```

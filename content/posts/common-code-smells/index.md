---
title: "Common Code Smells"
date: 2020-09-15T11:30:03+00:00
draft: true
author: "Greg Peddle"
tags: ["code", "quality"]
---

Many software developers know that some of their code smells bad, but have become used to it over time.


Here ia a code sample to review:

```Go
package leetcode

func maxArea(height []int) int {

	//var maxHeight int
	var maxVal int
	maxPos := len(height) - 1

	for pos := maxPos - 1; pos > 0; pos-- {
		hMax :=
	}

	return maxVal
}
```
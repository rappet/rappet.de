---
title: "My Fist Post"
date: 2020-05-02T13:50:00+02:00
anchor: "my-fist-post"
weight: 10
tags:
  - example
  - sandbox
  - python
  - bash
  - c++
categories: 
  - sandbox
draft: true
---
# Foo Bar

Test 

- Fizz
- Buzz

| Header 1 | Header 2 |
| -------- | -------: |
| Blah     | Blip     |


## Some Code

{{< highlight python >}}
#!/usr/bin/env python3

if __name__ == "__main__":
	# print out hello message
	print("Hello, World!")
{{< /highlight >}}

{{< highlight bash >}}
#!/bin/bash

echo "Hello, World\!"
{{< /highlight >}}

{{< highlight c >}}
#include <stdio.h>
#include <stdlib.h>

int main(int argc, char *argv[])
{
	puts("Hello, World!");
	return EXIT_SUCCESS;
}
{{< /highlight >}}

---
layout: reference
title: '`()` and `{}` (invoke) operators'
tab: documentation
unique_id: docspage
author: Tom Bentley
milestone: Milestone 1
doc_root: ../../..
---

# #{page.title}

The left-associative, unary `()` and `{}` operators are used to invoke methods
and instantiate classes

## Usage

<!-- cat: class MyClass() {} -->
<!-- cat: void m() { -->
    print("hello, world!");       // positional style
    print{                        // named-arguments style
        line="hello, world";
    };
    MyClass instance = MyClass(); // invoking a class to get an instance
<!-- cat: } -->

## Description

For detailed information see the reference documentation on 
[method invocation] _doc coming soon at_ (#{page.doc_root}/reference/expression/method-invocation) and 
[class invocation] _doc coming soon at_ (#{page.doc_root}/reference/expression/class-invocation).

### Definition

The `()` and `{}` operators are primitive.

### Polymorphism

The `()` and `{}` operators are not [polymorphic](#{page.doc_root}/reference/operator/operator-polymorphism). 

## See also

* [null-safe version](../nullsafe-invoke) of invoke.
* [spread invoke] _doc coming soon at_ (../spread-invoke) for calling a `Callable[]`
* API documentation for [`Callable`] _doc coming soon at_ (../../ceylon.language/Callable)
* [operator precedence](#{page.doc_root}/#{site.urls.spec_relative}#operatorprecedence) in the 
  language specification


# Swift: Missing Argument Label Error

This example demonstrates a common error in Swift: forgetting to include argument labels when calling a function.  While seemingly minor, omitting labels can lead to compilation errors and reduced code readability.

## The Problem

In Swift, functions often use named parameters with external labels.  When calling such functions, all labels must be included, unless explicitly marked with the `_` underscore to omit the label.

## The Solution

Ensure that all argument labels are explicitly provided when calling functions.  This enhances code clarity and prevents compilation errors.
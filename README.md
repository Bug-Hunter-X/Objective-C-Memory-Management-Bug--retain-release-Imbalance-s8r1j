# Objective-C Memory Management Bug: retain/release Imbalance

This repository demonstrates a common Objective-C bug related to memory management using `retain` and `release`.  Improper handling of these methods can lead to memory leaks or crashes due to double-releasing.

## Bug Description
The bug involves an imbalance in the `retain`/`release` calls for a property of a custom class.  This example uses `NSString`, but similar problems can occur with any object.

## Solution
The solution involves carefully managing the lifecycle of the object and properly balancing `retain`/`release` to prevent memory leaks and crashes.  Modern Objective-C using ARC (Automatic Reference Counting) avoids this issue.

## Files

* `bug.m`: Demonstrates the flawed memory management.
* `bugSolution.m`: Demonstrates the correct memory management solution.
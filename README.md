# Unexpected Type Juggling in PHP Numeric Operations

This example demonstrates a common error in PHP: unexpected type juggling in numeric operations. PHP's loose typing can lead to subtle but significant errors when working with numbers and strings.

The `calculateSum` function aims to calculate the sum of numbers in an array. However, the provided array contains a string ('4a'), resulting in unexpected behavior due to PHP's implicit type conversion.

The solution shows how to explicitly type check inputs to prevent such issues.
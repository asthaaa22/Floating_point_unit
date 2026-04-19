# Floating_point_unit
## Floating Point Unit (FPU) – Adder & Multiplier Design

This project focuses on the design and implementation of a Floating Point Unit (FPU) capable of performing arithmetic operations such as addition and multiplication on floating-point numbers. The design follows the standard structure of floating-point representation, involving sign, exponent, and mantissa processing.

For the floating-point adder, the process begins with exponent comparison and alignment of mantissas. Based on the difference in exponents, the smaller mantissa is shifted to ensure both operands are aligned. After alignment, mantissa addition or subtraction is performed depending on the sign bits. The result is then normalized and rounded, and the final exponent is adjusted accordingly to produce a valid floating-point output.

For the floating-point multiplier, the mantissas of the two operands are multiplied while the exponents are added, and the sign is determined using sign bit logic. The resulting product undergoes normalization and exponent adjustment to maintain standard floating-point format. This operation highlights the parallel nature of multiplication compared to the sequential alignment required in addition.

Throughout the project, careful attention was given to edge cases such as overflow, underflow, and normalization conditions. The design helped in understanding the complexity of arithmetic operations at the hardware level and provided insight into how processors internally handle floating-point computations.

This project strengthened concepts in digital design, arithmetic logic implementation, and hardware-level data representation, forming a strong foundation for advanced VLSI and processor design.

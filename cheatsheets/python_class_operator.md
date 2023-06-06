# Python operators for classes

Operator | Expression | Internally
:------- | :--------: | :---------
Addition | p1 + p2 | p1.__add__(p2)
Subtraction | p1 - p2 | p1.__sub__(p2)
Multiplication | p1 * p2 | p1.__mul__(p2)
Power | p1 ** p2 | p1.__pow__(p2)
Division | p1 / p2 | p1.__truediv__(p2)
Floor Division | p1 // p2 | p1.__floordiv__(p2)
Remainder (modulo) | p1 % p2 | p1.__mod__(p2)
Bitwise Left Shift | p1 << p2 | p1.__lshift__(p2)
Bitwise Right Shift | p1 >> p2 | p1.__rshift__(p2)
Bitwise AND | p1 & p2 | p1.__and__(p2)
Bitwise OR | p1 \| p2 | p1.__or__(p2)
Bitwise XOR | p1 ^ p2 | p1.__xor__(p2)
Bitwise NOT | ~p1 | p1.__invert__()
Less than | p1 < p2 | p1.__lt__(p2)
Less than or equal to | p1 <= p2 | p1.__le__(p2)
Equal to | p1 == p2 | p1.__eq__(p2)
Not equal to | p1 != p2 | p1.__ne__(p2)
Greater than | p1 > p2 | p1.__gt__(p2)
Greater than or equal to | p1 >= p2 | p1.__ge__(p2)

<br><br>

I Operator | Expression | Internally
:------- | :--------: | :---------
I Addition | p1 += p2 | p1.__iadd__(p2)
I Subtraction | p1 -= p2 | p1.__isub__(p2)
I Multiplication | p1 *= p2 | p1.__imul__(p2)
I Power | p1 **= p2 | p1.__ipow__(p2)
I Division | p1 /= p2 | p1.__itruediv__(p2)
I Floor Division | p1 //= p2 | p1.__ifloordiv__(p2)
I Remainder (modulo) | p1 %= p2 | p1.__imod__(p2)
I Bitwise Left Shift | p1 <<= p2 | p1.__ilshift__(p2)
I Bitwise Right Shift | p1 >>= p2 | p1.__irshift__(p2)
I Bitwise AND | p1 &= p2 | p1.__iand__(p2)
I Bitwise OR | p1 \|= p2 | p1.__ior__(p2)
I Bitwise XOR | p1 ^= p2 | p1.__ixor__(p2)


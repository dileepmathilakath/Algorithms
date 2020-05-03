# Generic Formulas

## For Loop

```c
for(i=0;i<n;i++) -> O(n)
for(i=0;i<n;i+2) -> n/2  O(n)
for(i=n;i>1;i--) -> n/2  O(n)
for(i=0;i<n;i=i*2) -> O(logN) base 2
for(i=0;i<n;i=i*3) -> O(logN) base 3
for(i=0;i>1;i=i*3) -> O(logN) base 2
for(i=1;p<=n;i++)  -> O(√n)
{
	p=p+1!;        
}
```
## Time functions

```
O(1) -> Constant
O(logn) -> Logarithemic
O(n)   -> Linear
O(n^2) -> Qaudratic
O(n^3) -> Cubic - Matric additions
O(2^n) -> exponential
O(3^n)
O(n^n)
```
### Example:

| logn | n | n^2 | 2^n |
|:----:|:--:|:--:|:--:|
|0|1|1|1
|1|2|4|4
|2|4|16|16|
|3|8|64|256


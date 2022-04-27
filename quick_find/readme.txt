Эта программа считывает из стандартного ввода последовательность пар не отрицательных чисел, меньших чем N(интерпретируя пару p и q как
указание "связять объект p с объектом q", и выводит пары, соответствующие ещё не связанным объектам. В ней используется массив id,
содержащий элемент для каждого объекта и характеризующийся тем, что элементы id[p] и id[q] равны тогда и только тогда, когда объекты 
p и q связанны. Для простоты N определена как константа времени компиляции. Иначе можно было бы считывать её из ввода и выделять массив id
динамически.
-------------------------------------------------------------------------------------------------------------------------------------------
This program reads from standard input a sequence of pairs of non-negative numbers less than N (interpreting the pair p and q as
an indication to "link object p to object q", and prints pairs corresponding to not yet connected objects. It uses an id array,
containing an element for each object and characterized by the fact that the elements id[p] and id[q] are equal if and only if the objects
p and q are connected. For simplicity, N is defined as a compile-time constant. 
Otherwise, it would be possible to read it from the input and allocate an array of iddynamically.
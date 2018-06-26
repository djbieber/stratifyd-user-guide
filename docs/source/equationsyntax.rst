Equation Syntax
===============

Available dimensions appear in the top left menu. Dimensions should always be encapsulated by square brackets.

Operator Notations
==================

The supported operators are listed in the bottom left menu. Hovering over an operator will show a description of what the operator does. Both Prefix and Infix notations are supported, by clicking on an operator in the menu, it will use Prefix Notation. Infix Notation can be added by typing out the equation. Additionally, both styles can be combined in one equation.

Prefix Notation
^^^^^^^^^^^^^^^

With Prefix Notation the operator precedes the operands. For example::

  abs(sub([incoming],[outgoing]))

This equation will subtract incoming from outgoing, and then take the absolute value


Infix Notation
^^^^^^^^^^^^^^

Infix Notation is what is most commonly used in written expressions.::

  [incoming] - [outgoing]


Mixed
^^^^^

The following example shows how both notations can be combined.::

  abs([incoming]-[outgoing])
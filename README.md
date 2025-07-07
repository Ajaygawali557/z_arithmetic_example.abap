# z_arithmetic_example.abap
REPORT z_arithmetic_example.

* Declare variables
DATA: lv_num1 TYPE i VALUE 10,
      lv_num2 TYPE i VALUE 5,
      lv_sum  TYPE i,
      lv_diff TYPE i,
      lv_prod TYPE i,
      lv_div  TYPE p DECIMALS 2.

* Perform operations
lv_sum  = lv_num1 + lv_num2.
lv_diff = lv_num1 - lv_num2.
lv_prod = lv_num1 * lv_num2.
lv_div  = lv_num1 / lv_num2.

* Display results
WRITE: / 'Sum:', lv_sum,
       / 'Difference:', lv_diff,
       / 'Product:', lv_prod,
       / 'Division:', lv_div.

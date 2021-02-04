# [test](subfolder/)

|   link   |       test       |             effect              |
| :------: | :--------------: | :-----------------------------: |
|    ..    |    [test](..)    | go folder above (fail for root) |
|    .     |    [test](.)     |             refresh             |
| ../../.. | [test](../../..) |      Homepage from folder       |
|    \#    |    [test](#)     |            Go to top            |
|   ...    |   [test](...)    |       fail (`...` folder)       |
|    @     |    [test](@)     |              fail               |
|    /     |    [test](/)     |              fail               |
|    $     |    [test]($)     |              fail               |
|    ^     |    [test](^)     |              fail               |
|    \*    |    [test](*)     |              fail               |
|    \+    |    [test](+)     |              fail               |
|    &     |    [test](&)     |              fail               |
|    _     |    [test](_)     |              fail               |
|    >     |    [test](>)     |              fail               |
|    <     |    [test](<)     |              fail               |
|    =     |    [test](=)     |              fail               |
|    ~     |    [test](~)     |              fail               |
|    :     |    [test](:)     |              fail               |
|  ../..   |  [test](../..)   |              fail               |
|    _     |    [test](_)     |               N_A               |

```diff
+ test +
- test -
= test =```
# [test](subfolder/)

|   link   |       test       |             effect              |
| :------: | :--------------: | :-----------------------------: |
|    ..    |    [test](..)    | go folder above (fail for root) |
|    .     |    [test](.)     |             refresh             |
|   ...    |   [test](...)    |       fail (`...` folder)       |
|    /     |    [test](/)     |              fail               |
|    \#    |    [test](#)     |            Go to top            |
|    @     |    [test](@)     |              fail               |
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
| ../../.. | [test](../../..) |               N_A               |
|    _     |    [test](_)     |               N_A               |
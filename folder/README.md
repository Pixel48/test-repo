# Link tests
### [subfolder](subfolder/)

|   link   |       test       |              effect              | rating   |
| :------: | :--------------: | :------------------------------: | -------- |
|    .     |    [test](.)     |           Refresh page           | good     |
|    \#    |    [test](#)     |            Go to top             | good     |
|    ..    |    [test](..)    | One folder above (fail for root) | ok       |
| ../../.. | [test](../../..) |    Homepage (only under root)    | bad      |
|   ...    |   [test](...)    |       fail (`...` folder)        | treeible |
|    @     |    [test](@)     |               fail               | treeible |
|    /     |    [test](/)     |               fail               | treeible |
|    $     |    [test]($)     |               fail               | terrible |
|    ^     |    [test](^)     |               fail               | treeible |
|    \*    |    [test](*)     |               fail               | treeible |
|    \+    |    [test](+)     |               fail               | treeible |
|    &     |    [test](&)     |               fail               | treeible |
|    _     |    [test](_)     |               fail               | treeible |
|    >     |    [test](>)     |               fail               | treeible |
|    <     |    [test](<)     |               fail               | invalid  |
|    =     |    [test](=)     |               fail               | treeible |
|    ~     |    [test](~)     |               fail               | treeible |
|    :     |    [test](:)     |               fail               | treeible |
|  ../..   |  [test](../..)   |               fail               | treeible |
|    _     |    [test](_)     |               N_A                |          |
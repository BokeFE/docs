1. Array-like Object, 
    - 定义：
    which are Object representations of Arrays with a length property。听了那么多次Array-like Object,今天才知道它的确切定义，好丢人啊。
    - 示例：
    
        ```
        var realArray = ['a', 'b', 'c'];
        var arrayLike = {
          0: 'a',
          1: 'b',
          2: 'c',
          length: 3
        };
        ```
    - 包含： 
    `arguments`  `HTMLCollection` `NodeList`

# RecyclerListTreeView

`The fastest android Tree View based on RecyclerView in the world!!`

I am special because:<br/>
* The data store is looking like a tree but in fact it is a list.<br/>
* Not changed any thing on RecyclerView.<br/>
* No recursion,only cycle，so no worry about stack overflow.<br/>
* User will not feel any different from using way of origin Recycler.<br/>
* Less half amount of code than other's implemetion.<br/>

---

`基于RecyclerView，自认为是当前最快的 Android tree view 的实现了！！`

存储数据的结构并不是Tree，而是一个ArrayList。与所有已知的网上的实现都不一样，大家似乎都跳不出固定思维。
可以比较一下代码量，此实现比其它的少一半都不止。

核心是一个表示Tree的类，但它的本质是一个List。对RecyclerView没有任何改动，对Adapter只有少量封装，
使用者不会产生任何陌生感。也就是说你对RecyclerView能做的，现在依然能做。

以List的形式表式树，带来很多好处：<br/>
* 没有了递归。该用递归的地方全部变成了循环（Tree不论有多少层都没有栈溢出）。<br/>
* 其次是有序，插入节点时，可以指定它是它爸爸的第几个儿子。<br/>
* 极其适合在RecyclerView中使用<br/>
* 跟List无异，无论根节点还是子节点都对应RecyclerView中的一行。<br/>
* 不需对RecyclerView做任何改动<br/>

有诗为证：<br/>
远看像棵树<br/>
近看不是树<br/>
似树而非树<br/>
是为牛逼树<br/>

---

## License

   Copyright 2017 niugao.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

---

![](https://github.com/niugao/RecyclerListTreeView/blob/master/snapshots/1.png)
![](https://github.com/niugao/RecyclerListTreeView/blob/master/snapshots/2.png)
![](https://github.com/niugao/RecyclerListTreeView/blob/master/snapshots/3.png)
![](https://github.com/niugao/RecyclerListTreeView/blob/master/snapshots/4.png)

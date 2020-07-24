# 我的说明


![img](https://hbimg.huabanimg.com/2059d661900f5c59f924614bc64f3a7128e6a19a1184b-9AxsdX_fw658/format/webp)


- path  目标文件们的路径描述，这个可以使用 wildcard（通配符）或者 regex 来描述一组文件。
  - wildcard : 通配符 ：  *代表多个或者0个位置的字符，  ？  代表一个字符
  -regex ： 比较复杂，看一看看  https://github.com/vhshiwen/unity-addressable-importer/blob/master/Documentation~/AddressableImporter.md#address-replacement
- MatchType  ： 说的是 path 中使用 wildcard  或者 regex  。
- Group Name ： 这个group 的名称 
- LabelMode ： 标签的添加方式
  - add ： 将标签，都已附加的方式，加到资源上。  已有的不会消失
  - replace ：  将已有的删除，然后在附加上去。
- LableRefs ：  将所选的 标签们（可以设置多个） 附加到每一个资源上
  - 上图中我们选择两 两个标签
- Grouptemplate :  选择一个魔板给这个组
  - 主要是 是否在发布后可以动态更换
  - 打包路径
  - 加载路径
- Grouptemlat Application：  选择是只在创建的时候应用一次魔板，还是每次生成的的时候都重新应用这个魔板
- Address Simplified  :  
  - 如果选择 那么路径每个资源的名字 就只是 资源的名字。并且没有后缀
  - 如果不选择 ，那么将会以 全路径。后缀  作为资源的名字。  下图中 可以看到我没有 选择 简单名字时候名字的效果
  
 ![img](https://hbimg.huabanimg.com/b0cc5482694686065acf3318a5b1eac4b7e0b4a321586-FqshOE_fw658/format/webp)


# Personal-library
使用python过程中自己所写的一些类（去重的List等）

RemoveDuplcateList 用于去重的List类

  rdl = RemoveDuplcateList(iterable)
  
  rdl.duplicate(key=lambda x:x)  #根据key运算后的元素执行去重
  
  rdl.remove_duplcate_list        存放去重后的列表
  
  rdl.iterable                    存放初始的元素列表
  
  rdl.duplate_element_list        存放已存在元素的集合

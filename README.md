# PicFilter
## 前言
基于Pillow的图片筛选，因为找不到合适的图片筛选工具，就自己写了XD

* 图片去重
* 宽高限制
* 根据长宽筛选出横/竖/方形图片

## 如何使用
运行start.py，选择操作，输入图片路径和图片输出目录，通过迭代会取出路径内的所有图片

## 注
* 图片去重暂不支持不同大小的相同图片的判断
* 通过宽高筛选的图片会移动到已移除的图片目录中
* 图片筛选横竖图分类完成后原路径图片文件默认不会删除

## 更新
#### V0.4
1. 更新对图片的宽高排除，支持宽高比和纯宽高数据
2. 对排除的图片另外添加移除目录，防止误删

#### V0.3
1. 更新对方形图的分类

#### V0.2
1. 支持重复图片的简单去除，适用于由同一个文件复制出的图片去除

#### V0.1
1. 根据长宽筛选，分类为横竖屏图片


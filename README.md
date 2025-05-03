# CJA-CSL
csl for Chinese Journal of Aeronautics. 

This csl is modified from https://github.com/citation-style-language/styles/blob/master/chinese-journal-of-aeronautics.csl
1. add <contributor> metadata for YZW and refresh <updated> timestamp
2. introduce zh locale with custom term lang-suffix → “[Chinese]”. create new lang-note macro; append it to bibliography layout for Chinese items
3. switch author macro to use initials (initialize="true", empty initialize-with)
4. output citation number as “N. ” (number + dot + space) in bibliography
5. revise webpage layout: remove extra period after title, inject “ [Internet].” token for correct punctuation
This csl file has been tested in Zotero 7 and works fine

此 csl 修改自 https://github.com/citation-style-language/styles/blob/master/chinese-journal-of-aeronautics.csl
1. 添加 YZW 的 <contributor> 元数据并刷新 <updated> 时间戳
2. 引入 zhlocale 并自定义术语 lang-suffix→“[Chinese]”。创建新的 lang-note 宏；将其添加到参考文献布局中，用于中文条目
3. 将作者宏切换为使用首字母缩写 (initialize="true"，空的 initialize-with)
4. 在参考文献中将引用编号输出为“N.” (数字+点+空格)
5. 修改网页布局：删除标题后的多余句点，并插入“[Internet].”标记以确保标点符号正确
这个csl文件在zotero 7中经过测试，可以正常使用
航空学报，航空学报（英文版），中国航空学报，

# httpobj WriteUp
一开始我通过查询.pcapng格式的文件顺利下载了WireShark之类的工具打开了包，但是发现并找不到我想要的数据，于是尝试了包中几个长得像的，错误，于是便暂时搁置了一会。
直到做其他题搜索时发现CTF要用到工具WireShark有可以分析数据导出并查看的功能，于是我恍然大悟，可以直接分析得出大概十段文本数据，我于是按照时间顺序拼接，然后稍微完善下就得到了flag，原来这就是这一系列数据包传输的数据呀！
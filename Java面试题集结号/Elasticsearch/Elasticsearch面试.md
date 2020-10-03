### Elasticsearch
1. 详细描述一下Elasticsearch索引文档的过程。
  创建一个IndexWriter 用来写索引文件，它有几个参数，INDEX_DIR 就是索引文件所存放的位置，Analyzer 便是用来对文档进行词法分析和语言处理的。
  创建一个Document 代表我们要索引的文档。
  将不同的Field 加入到文档中。我们知道，一篇文档有多种信息，如题目，作者，修改时间，内容等。不同类型的信息用不同的Field 来表示。
  IndexWriter 调用函数addDocument 将索引写到索引文件夹中
2. 详细描述一下Elasticsearch搜索的过程。
  IndexReader 将磁盘上的索引信息读入到内存，INDEX_DIR 就是索引文件存放的位置。
  创建IndexSearcher 准备进行搜索。
  创建Analyer 用来对查询语句进行词法分析和语言处理。
  创建QueryParser 用来对查询语句进行语法分析。
  QueryParser 调用parser 进行语法分析，形成查询语法树，放到Query 中。
  IndexSearcher 调用search 对查询语法树Query 进行搜索， 得到结果TopScoreDocCollector。
3. Elasticsearch 的倒排索引是什么。
4. Elasticsearch是如何实现master选举的。
5. lucence内部结构是什么。
6. Lucene全文搜索的原理
7. 在并发情况下，Elasticsearch 如何保证读写一致呢？
8. 详细阐述一下 Elasticsearch 搜索的过程。
9. Elasticsearch 索引数据多了怎么办呢，如何调优，部署
10. Elasticsearch 对于大数据量（上亿量级）的聚合如何实现？

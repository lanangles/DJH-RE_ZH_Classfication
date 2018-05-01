- baseline
	- feature.py 抽取特征
- corpora
	- corpus1.txt 远程监督标注语料
	- sents.txt 还原的标注句子
	- sents_with_pos.txt 标注格式变换
- dict 字典 数值化转换
	- entities.dict 实体字典
	- nes.dict 实体标记字典
	- postags.dict 词性标记字典
	- rels.dict 关系字典
- libsvm-3.22 svm算法实现工具
- result 结果
	- feature2libsvm.csv 符合libsvm格式的输入文件
	- features.pickle 抽取特征的结果
	- features.vec.csv 特征数值化后的结果
	- grid.out 参数优化结果
	- grid.png 参数优化结果
	- model.txt 模型
	- test.vec 测试语料集
	- test_vec.scale 数值缩放后测试语料集
	- train.vec 训练语料集
	- train_vec.scale 数值缩放后训练语料集
	- triples.txt 三元组
- util
	- io.py
	- log.py
- check_data.py 检查数据格式
- convert2libsvm.py 转换成libsvm输入格式
- digitalize.py 数值化
- evaluation.txt 模型评测结果
- pre_process.py 预处理（生成字典s,还原句子,修改格式）
- save2mongo.py 保存到mangodb
- save2neo4j.py 保存到neo4j
- train_predict.py 训练、预测、打分
- train_test_split.py 数据集分割
- visualization
	- triples_node node.js 环境下的演示
	- visualization_evaluation.html 模型评测可视化
	- visualization_evaluation2.html 模型评测可视化
	- visualization_triples.html 三元组可视化 运行环境 ：node.js
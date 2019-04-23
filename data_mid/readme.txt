注意我们用的是小写的druga,drugb不是大写的！！！！！
train_text and test_text：是句子+label的形式。其中每个句子已经保证有一个drugA和一个drugB
sentence：是所有存在pair的句子
train_pos_A
train_pos_B:每个单词到durgA和drugB之间的距离。长度为155，没有的地方用1000的距离补齐
used_word 存放的是所有涉及到单词且有词向量的字典
word_vector 加载时用的
先利用oversample训练，再训练imbalnced data


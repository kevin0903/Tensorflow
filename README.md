# Tensorflow
遇到的問題2017/10/28

這裡會附上兩個程式，程式1是執行結果是對的，程式2是依照程式1去改寫，使用feed_dict的方式將images labels讀入，因為之後希望能將validation和train寫在同個程式裡面，但我發現使用feed_dict後預測的TrainAccuracy會越來越低，卡住了很久。
# Test_Own_Pic
#train and test your own picture

1:clone the code in your Caffe root director

2:copy the date in your caffe/data

3:meke dir myfile in your caffe root dir

4:run CreateFilelist.sh Convert_lmdb.sh Compute_Mean.sh

5:open terminal and run: sudo build/tools/caffe train -solver examples/myfile/solver.prototxt


all:
	g++ -O3 fm_train.cpp src/Frame/pc_frame.cpp src/Utils/utils.cpp -I . -std=c++0x -o bin/fm_train_softmax -lpthread
	g++ -O3 fm_predict.cpp src/Frame/pc_frame.cpp src/Utils/utils.cpp -I . -std=c++0x -o bin/fm_predict_softmax -lpthread

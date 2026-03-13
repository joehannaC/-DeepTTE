Model training:

python main.py --task train --batch_size 64 --epochs 50 --pooling_method attention --kernel_size 3 --alpha 0.1 --data_ratio 1.0 --log_file deeptte_run

Model testing:

python main.py --task test --weight_file ./saved_weights/best_model.pt --batch_size 64 --result_file ./result/deeptte.res --pooling_method attention --kernel_size 3 --alpha 0.1 --data_ratio 1.0 --log_file deeptte_test

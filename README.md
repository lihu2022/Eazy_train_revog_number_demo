#this project is a eazy demo about cnn network and linear perception

##start

conda env create -n $proj_name -f env.yaml 

conda activate $proj_name

cd $your_proj_name


###if you have already trained this model, you can run the following command in terminal

    python first_try.py True use_cnn/use_fc

###if you have not train this model,then you want use cnn train it, you can run the following command in terminal

    python first_try.py False use_cnn

###if you have not train this model,then you want use full connnect train it, you can run the following command in terminal

    python first_try.py False use_fc

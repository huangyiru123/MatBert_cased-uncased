# MatBert_cased-uncased
Matbert cased and uncased version, some plot, such as clustering/cosine similarity plot, and smilarity ranking for target words 
model download:
export MODEL_PATH="/home/customer/hyr/matbert-base-cased-copy-version"   #your path 
mkdir $MODEL_PATH/matbert-base-cased $MODEL_PATH/matbert-base-uncased
curl -# -o $MODEL_PATH/matbert-base-cased/config.json https://cedergroup-share.s3-us-west-2.amazonaws.com/public/MatBERT/model_2Mpapers_cased_30522_wd/config.json
curl -# -o $MODEL_PATH/matbert-base-cased/vocab.txt https://cedergroup-share.s3-us-west-2.amazonaws.com/public/MatBERT/model_2Mpapers_cased_30522_wd/vocab.txt
curl -# -o $MODEL_PATH/matbert-base-cased/pytorch_model.bin https://cedergroup-share.s3-us-west-2.amazonaws.com/public/MatBERT/model_2Mpapers_cased_30522_wd/pytorch_model.bin

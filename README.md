# convert_tf2py

python convert_checkpoint.py \
  --tf_checkpoint_path  $BERT_BASE_DIR/bert_model.ckpt   \
  --bert_config_file  $BERT_BASE_DIR/bert_config.json  \
  --pytorch_dump_path  $BERT_BASE_DIR/pytorch_model.bin \
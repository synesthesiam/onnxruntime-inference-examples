call run.py to calibrate, quantize and run the quantized model, e.g.:
python run.py --input_model mobilenetv2-7.onnx --output_model mobilenetv2-7.quant.onnx --calibrate_dataset ./test_images/

This will generate quantized model mobilenetv2-7.quant.onnx

Call run_qdq_debug.py to debug quantization error, e.g
python run_qdq_debug.py --float_model mobilenetv2-7.onnx --qdq_model mobilenetv2-7.quant.onnx --calibrate_dataset ./test_images/



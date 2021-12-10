# Note
For Studying

测试网络		owner	Pytorch	Dataset	Unsupport layers	Problems
inceptionresnetv2	00001_inception_v2		https://github.com/Cadene/pretrained-models.pytorch/blob/master/pretrainedmodels/models/inceptionresnetv2.py	ImageNet (ILSVRC2012)	Constant, Shape, Gather, Unsqueeze	
inception_v3	00003_inception_v3		torchvision.models	ImageNet (ILSVRC2012)	Pad	
inception_v4	00004_inception_v4		https://github.com/Cadene/pretrained-models.pytorch/blob/master/pretrainedmodels/models/inceptionv4.py	ImageNet (ILSVRC2012)	Gather, Constant, Shape, Unsqueeze	
resnet18	00008_resnet18		torchvision.models	ImageNet (ILSVRC2012)	done	
resnet50	00009_resnet50		torchvision.models	ImageNet (ILSVRC2012)	done	
resnet101 	00010_resnet101		torchvision.models	ImageNet (ILSVRC2012)	done	
mobilenet_v1	00013_mobilenet_cus1		https://github.com/zhaoyuzhi/PyTorch-MobileNet-v123		ReduceMean	
mobilenet_v2	00014_mobilenet_v2		torchvision.models		Clip, Shape, Constant, Gather, Unsqueeze	
mobilenet_ssd	00014_mobilenetssd_cus1		https://github.com/qfgaohao/pytorch-ssd		Constant, Gather, Shape, Unsqueeze, Div, ReduceL2	
mobilenet_yolov3	00015_yolo_v3_mobilenet_lite		https://github.com/ruinmessi/ASFF			
mobilefacenet	00031_mobilefacenet		https://github.com/xuexingyu24/Pruning_MTCNN_MobileFaceNet_Using_Pytorch		Constant, Gather, Shape, Unsqueeze, Slice, Softmax, Exp, Div, Sub	
yolov2	00005_yolo_v2_960540		"https://github.com/tztztztztz/yolov2.pytorch
https://github.com/longcw/yolo2-pytorch"		Constant, Shape, Gather, Unsqueeze, Slice, Exp, Softmax	"TracerWarning: Converting a tensor to a Python integer might cause the trace to be incorrect. We can't record the data flow of Python values, so this value will be treated as a constant in the future. This means that the trace might not generalize to other inputs!
TracerWarning: Converting a tensor to a Python integer might cause the trace to be incorrect. We can't record the data flow of Python values, so this value will be treated as a constant in the future. This means that the trace might not generalize to other inputs!x = TracerWarning: Converting a tensor to a Python integer might cause the trace to be incorrect. We can't record the data flow of Python values, so this value will be treated as a constant in the future. This means that the trace might not generalize to other inputs!"
yolov3	00006_yolo_v3_960540		"https://github.com/ultralytics/yolov3/releases
https://github.com/DeNA/PyTorch_YOLOv3"		Constant	torch.onnx.export 轉換模型格式錯誤
vgg16	00012_vgg		torchvision.models		exception	
squeezenet_v1	00019_squeezenet_v1_1		torchvision.models		Warning: novaic tool can't support asymmetric pad	
segnet						
retinaface	10005_retinaface		https://github.com/bubbliiiing/retinanet-pytorch	VOC	Warning: novaic tool can't support asymmetric pad	TracerWarning
sphereface(20)	00033_sphereface20		https://github.com/clcarwin/sphereface_pytorch	CASIA-Webface	Convert error	Convert error
pfld						
![image](https://user-images.githubusercontent.com/48971355/145543828-341292bf-c91d-420a-965b-8d3f6721bfa8.png)
https://github.com/zldrobit/onnx_tflite_yolov3
![image](https://user-images.githubusercontent.com/48971355/145545963-6a6ad52c-d466-4c6b-aa2d-24c16a4f942e.png)

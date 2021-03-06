# SageMaker Migrations Workshop

### Agenda for SageMaker Migrations Workshop

* #### Training
    * Experiments management 
    * SageMaker script mode
    * Model Hyperparameter Tuning
    * RESNET Notebook
        * Debugging 
        * Spot Training [MXNet](https://github.com/awslabs/amazon-sagemaker-examples/tree/master/sagemaker-python-sdk/managed_spot_training_mxnet) [TensorFlow](https://github.com/awslabs/amazon-sagemaker-examples/tree/master/sagemaker-python-sdk/managed_spot_training_tensorflow_estimator)
    * Tensorflow Estimator Notebook
        * Distributed Training [MXNet](https://github.com/vdabravolski/detectron2-sagemaker) [Pytorch](https://github.com/awslabs/amazon-sagemaker-examples/tree/master/sagemaker-python-sdk/pytorch_horovod_mnist)
        * Bring your own container
* #### Hosting
    * Deploy model as an endpoint
        * SageMaker trained model 
        * Bring your own model 
        * Perform predictions
        * Auto-Scaling [MXNet](https://github.com/C24IO/SageMaker-CustomMXNet-Autoscaling)
        * A/B testing [MXNet](https://github.com/C24IO/SageMaker-Inference/tree/master/endpoints/load-ab-testing)
        * Multi-model endpoints
    * Deploy tensorflow model as TF Serving
    * MLOPs best practices overview
        * Deployment across regions using SageMaker 
* #### SageMaker with Kubernetes
    * SageMaker + Kubernetes Overview
    * SageMaker Operators for Kubernetes
    * KubeFlow pipelines with SageMaker [Notebooks](https://github.com/kubeflow/pipelines/tree/master/components/aws/sagemaker)
* #### Data Labeling
    * GroundTruth Lab - Images 
    * GroundTruth Lab - Videos
* #### Model Formats
    * ONNX [MXNet](https://github.com/awslabs/amazon-sagemaker-examples/tree/master/sagemaker-python-sdk/mxnet_onnx_export)    


## Sources:

* https://github.com/markproy/sagemaker-workshop
* https://github.com/aws-samples/mlops-amazon-sagemaker-devops-with-ml
* By Shreyas Subramanian - https://master.d11arstd4fhlv6.amplifyapp.com/ & https://www.shreyasdemos.ml/
* https://github.com/data-science-on-aws/workshop
* https://github.com/kubeflow/pipelines/tree/master/components/aws/sagemaker
* https://aws.amazon.com/blogs/machine-learning/introducing-amazon-sagemaker-components-for-kubeflow-pipelines/
* https://aws.amazon.com/blogs/opensource/deploy-machine-learning-models-to-amazon-sagemaker-using-the-ezsmdeploy-python-package-and-a-few-lines-of-code/


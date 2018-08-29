# use case IBM Cloud Kubernetes Service + DevOps ToolChain Demo
## �g���m�P�_�̉� mod.2�u�_�̒ʂИH�v(�N���E�h/�R���e�i�׋���)

�{���|�W�g���́AGithub open-toolchain�Ɍ��J����Ă���[Continuously deliver a secure Docker app to a Bluemix Kubernetes Cluster](https://github.com/open-toolchain/secure-kube-toolchain)����A
���e���J�X�^�}�C�Y�������|�W�g���ł��B

LT�ŏЉ��ToolChain���̃f���p���|�W�g���ƂȂ�܂��B

`������`�{���|�W�g����ToolChain�f���ɂ�IBM Cloud�̏]�ʗ���(pay-as-you-go)�A�J�E���g��IBM Cloud Container Service�̕W���N���X�^�[�ȏ�̃N���X�^�̐ݒ肪�K�{�ł�

### ToolChain�������g��IBM Cloud �A�J�E���g�Ƀf�v���C����ɂ͈ȉ���Create ToolChain�{�^�����N���b�N���Ă��������B:
[![Deploy To Bluemix](https://console.bluemix.net/devops/graphics/create_toolchain_button.png)](https://console.bluemix.net/devops/setup/deploy/?repository=https%3A//github.com/phssakaigawa/kumonokai2-lt-k8s-toolchain)


# ![Icon](./.bluemix/secure-lock-kubernetes.png) Develop a Kubernetes app


### Continuously deliver a secure Docker app to a Kubernetes Cluster
This Hello World application uses Docker with Node.js and includes a DevOps toolchain that is preconfigured for continuous delivery with Vulnerability Advisor, source control, issue tracking, and online editing, and deployment to the IBM Bluemix Containers service.

Application code is stored in source control, along with its Dockerfile and its Kubernetes deployment script.
The target cluster is configured during toolchain setup (using a Bluemix API key and cluster name). You can later change these by altering the Delivery Pipeline configuration.
Any code change to the Git repo will automatically be built, validated and deployed into the Kubernetes cluster.

![Icon](./.bluemix/toolchain.png)

### To get started, click this button:
[![Deploy To Bluemix](https://console.bluemix.net/devops/graphics/create_toolchain_button.png)](https://console.bluemix.net/devops/setup/deploy/?repository=https%3A//github.com/phssakaigawa/kumonokai2-lt-k8s-toolchain)

---
### Learn more 

* Blog [Continuously deliver your app to Kubernetes with Bluemix](https://www.ibm.com/blogs/bluemix/2017/07/continuously-deliver-your-app-to-kubernetes-with-bluemix/)
* Step by step [tutorial](https://www.ibm.com/devops/method/tutorials/tc_secure_kube)
* [Getting started with Bluemix clusters](https://console.bluemix.net/docs/containers/container_index.html?pos=2)
* [Getting started with toolchains](https://bluemix.net/devops/getting-started)
* [Documentation](https://console.bluemix.net/docs/services/ContinuousDelivery/index.html?pos=2)

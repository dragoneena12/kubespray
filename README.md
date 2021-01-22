# kubespray settings
[Setting up your first cluster with Kubespray](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/setting-up-your-first-cluster.md) を参考に構築

KUBECONFIG を kubespray で作ったクラスタのものに設定
```
scp $USERNAME@$IP_CONTROLLER_0:/etc/kubernetes/admin.conf kubeconfig/kubespray-do.conf
export KUBECONFIG=$PWD/kubeconfig/kubespray-do.conf
```

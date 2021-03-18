# demo-ingress
## What's this?
Sample k8s application for Ingress controller demo.

## How to use
At first, please do "kubectl apply", and then access the Ingress IP retrieved by "kubectl get ingress".  
Ingress controller has the capablity of L7 loadbalancer, and you can check the funcitonality as follows:  
- [http://$YOUR_INGRESS_IP/cinnamon](http://$YOUR_INGRESS_IP/cinnamon)  
The display will show "cinnamon-app".  
- [http://$YOUR_INGRESS_IP/butterscotch](http://$YOUR_INGRESS_IP/butterscotch)  
The display will show "butterscotch-app".  
  
>_*For no reason in particular..._  
>_*Which do you prefer?_  
>_*Cinnamon or Butterscotch?_

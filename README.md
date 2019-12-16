
You can also build and deploy the application on OpenShift, assuming you have a
working `oc` command line environment connected to your cluster already:

`$ oc new-app openshift/nginx~https://github.com/zhengbin78/nginxdemo.git`

You can also deploy the sample template for the application:

`$ oc new-app -f https://raw.githubusercontent.com/sclorg/nginx-ex/master/openshift/templates/nginx.json`

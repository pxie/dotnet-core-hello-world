# hello-dotnet

One sample c# app to demostrate how it work on predix.io

## deploy
```
$ git clone https://github.com/pxie/dotnet-core-hello-world
$ cd dotnet-core-hello-world
$ cf push

* ignore part of cf push CLI outputs *

requested state: started
instances: 1/1
usage: 170M x 1 instances
urls: hello-dotnet-absolutory-receptacle.run.aws-jp01-pr.ice.predix.io           <-- hello-dotnet URL
last uploaded: Thu Apr 27 02:47:34 UTC 2017
stack: cflinuxfs2
buildpack: https://github.com/cloudfoundry/dotnet-core-buildpack.git

     state     since                    cpu    memory          disk             details
#0   running   2017-04-27 10:50:57 AM   1.2%   93.7M of 170M   286.9M of 350M
```
## usage

1. open browser
2. type the URL retrieved from CLI output, `https://hello-dotnet-absolutory-receptacle.run.aws-jp01-pr.ice.predix.io`
3. you will see "hello world!"
4. enjoy
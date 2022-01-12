Resources for this tutorial code can be found here:
https://learn.hashicorp.com/collections/packer/aws-get-started

Running this will create two AWS images in parallel and then a Vagrant box during Post Processing.

Please note that I had updated code to include a personal profile which I had set in my .aws/credentials file.

If you want to get straight to it and have either updated the profile in the template, updated your credentials file to include a personal profile or added the keys into the template then you can run the usual commands:

```
packer fmt .
packer validate .
packer build .
```
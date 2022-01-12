Resources for this tutorial code can be found here:
https://learn.hashicorp.com/collections/packer/docker-get-started

Running this will create two docker images in parallel and then tag them post processing.

You need docker installed for this one and can kick things off with the below commands:

```
packer fmt .
packer validate .
packer build .
```
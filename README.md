# efficientnet_repro

Tests for reaching close to referenced (blog, papers) accuracy on efficient net B0 specifically on cifar100 and imagenet tiny, with imagenet pretrained weights.

Collected hyperparams leading to performance within couple % of reported larger model variants on each.

See code comments for ref to sources.

Up to (k=1 early stopping, epoch 0-indexed):
CIFAR100 -      e5      train acc @1: 0.8904    val acc @1 0.835    test acc @1 0.8354
ImagenetTiny -  e14     train acc @1: 0.8629    val acc @1 0.7914   test acc @1 0.797

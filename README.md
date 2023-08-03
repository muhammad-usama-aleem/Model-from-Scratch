# Model-from-Scratch

* Rule of thumb: If we divide batch size by 2 or any number then divide the learning rate with the same number.
* Use batch size which can be fit into the system's GPU. Expert's use batch size smaller then they can actually fit into the system.
* Use the following to save the gpu memory:
    gc.collect()
    torch.cuda.empty_cache()

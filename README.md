# ERA-Session-15
## Huggingface model link <a href="https://huggingface.co/SV12/yolov9_object_detection_on_custom_dataset/tree/main">Link</a>

## Training Logs
```
 Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
       0/24      13.5G      1.434      4.064     0.9123        528        640: 100% 13/13 [00:48<00:00,  3.76s/it]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:02<00:00,  1.30s/it]
                   all         38        905      0.943       0.22      0.211      0.143
/usr/lib/python3.10/multiprocessing/popen_fork.py:66: RuntimeWarning: os.fork() was called. os.fork() is incompatible with multithreaded code, and JAX is multithreaded, so this will likely lead to a deadlock.
  self.pid = os.fork()

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
       1/24      15.3G      1.251      1.167     0.8433        666        640: 100% 13/13 [00:32<00:00,  2.47s/it]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  2.47it/s]
                   all         38        905      0.958      0.219      0.243      0.167

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
       2/24      15.3G       1.28      1.258     0.8405        428        640: 100% 13/13 [00:30<00:00,  2.36s/it]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  2.72it/s]
                   all         38        905      0.567      0.289       0.28      0.141

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
       3/24      15.3G      1.326      1.075     0.8343        488        640: 100% 13/13 [00:31<00:00,  2.43s/it]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.49it/s]
                   all         38        905      0.683      0.317      0.321      0.168

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
       4/24      15.3G      1.575      1.009     0.8493        672        640: 100% 13/13 [00:28<00:00,  2.18s/it]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.62it/s]
                   all         38        905      0.655      0.351      0.337      0.105

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
       5/24      15.3G      1.707     0.9849     0.8619        435        640: 100% 13/13 [00:28<00:00,  2.19s/it]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  2.04it/s]
                   all         38        905      0.747      0.381       0.49      0.312

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
       6/24      13.5G      1.537      1.064     0.8477        366        640: 100% 13/13 [00:29<00:00,  2.29s/it]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  2.58it/s]
                   all         38        905      0.715      0.392      0.453      0.196

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
       7/24      15.5G      1.504      1.103     0.8429        480        640: 100% 13/13 [00:30<00:00,  2.37s/it]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  2.42it/s]
                   all         38        905      0.719      0.482      0.537      0.238

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
       8/24      15.5G      1.496      1.134     0.8632        381        640: 100% 13/13 [00:30<00:00,  2.38s/it]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  2.57it/s]
                   all         38        905      0.855      0.556      0.619      0.358

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
       9/24      15.5G      1.406      1.117     0.8467        543        640: 100% 13/13 [00:29<00:00,  2.29s/it]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  2.58it/s]
                   all         38        905      0.818      0.569      0.625       0.31
Closing dataloader mosaic

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
      10/24      15.5G      1.458     0.8453     0.8532        227        640: 100% 13/13 [00:11<00:00,  1.13it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.50it/s]
                   all         38        905      0.842      0.595      0.593      0.311

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
      11/24      15.5G       1.29     0.7107     0.8459        259        640: 100% 13/13 [00:11<00:00,  1.12it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.60it/s]
                   all         38        905      0.833      0.568      0.624      0.275

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
      12/24      15.5G      1.341     0.7039     0.8411        246        640: 100% 13/13 [00:11<00:00,  1.14it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.51it/s]
                   all         38        905      0.848      0.583       0.64      0.337

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
      13/24      15.5G      1.177      0.655     0.8329        247        640: 100% 13/13 [00:11<00:00,  1.14it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.58it/s]
                   all         38        905      0.852       0.59      0.641      0.353

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
      14/24      15.5G      1.198     0.6248     0.8334        243        640: 100% 13/13 [00:11<00:00,  1.17it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.53it/s]
                   all         38        905      0.652      0.605      0.653      0.385

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
      15/24      15.5G      1.105     0.5999     0.8269        235        640: 100% 13/13 [00:11<00:00,  1.13it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.49it/s]
                   all         38        905      0.746       0.64      0.685      0.411

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
      16/24      15.5G      1.115     0.5854     0.8176        214        640: 100% 13/13 [00:11<00:00,  1.15it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.50it/s]
                   all         38        905      0.689      0.632      0.669      0.409

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
      17/24      15.5G      1.009     0.5442     0.8217        258        640: 100% 13/13 [00:15<00:00,  1.16s/it]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.57it/s]
                   all         38        905       0.81      0.671      0.719      0.455

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
      18/24      15.5G      1.043     0.5354     0.8201        230        640: 100% 13/13 [00:11<00:00,  1.14it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.51it/s]
                   all         38        905      0.801      0.663      0.702      0.443

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
      19/24      15.5G     0.9581     0.5124     0.8225        235        640: 100% 13/13 [00:11<00:00,  1.14it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.48it/s]
                   all         38        905      0.771      0.615      0.686      0.465

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
      20/24      15.5G     0.9261     0.4941     0.8102        233        640: 100% 13/13 [00:11<00:00,  1.12it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.63it/s]
                   all         38        905      0.929      0.651      0.736      0.481

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
      21/24      15.5G     0.9185     0.4807     0.8096        198        640: 100% 13/13 [00:11<00:00,  1.13it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.49it/s]
                   all         38        905      0.908      0.678      0.746      0.507

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
      22/24      15.5G     0.8758     0.4645     0.8058        248        640: 100% 13/13 [00:11<00:00,  1.13it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.49it/s]
                   all         38        905      0.918      0.659      0.736      0.491

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
      23/24      15.5G     0.8802     0.4585     0.8021        263        640: 100% 13/13 [00:11<00:00,  1.12it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.46it/s]
                   all         38        905      0.911      0.685      0.759      0.501

      Epoch    GPU_mem   box_loss   cls_loss   dfl_loss  Instances       Size
      24/24      15.5G     0.8596     0.4527     0.7983        261        640: 100% 13/13 [00:11<00:00,  1.12it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.46it/s]
                   all         38        905       0.91      0.689      0.759      0.519

25 epochs completed in 0.164 hours.
Optimizer stripped from runs/train/exp/weights/last.pt, saved as runs/train/exp/weights/last_striped.pt, 51.4MB
Optimizer stripped from runs/train/exp/weights/best.pt, saved as runs/train/exp/weights/best_striped.pt, 51.4MB

Validating runs/train/exp/weights/best.pt...
Fusing layers... 
gelan-c summary: 467 layers, 25414044 parameters, 0 gradients, 102.5 GFLOPs
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.64it/s]
                   all         38        905       0.91      0.689      0.759      0.519
                  ball         38         35          1      0.155       0.32     0.0904
            goalkeeper         38         27      0.967      0.889      0.936      0.727
                player         38        754      0.948      0.941      0.981      0.746
               referee         38         89      0.725      0.769      0.797      0.511
```

## Loss Curves
![image](https://github.com/ShubhamVerma16/ERA-Session-15/assets/46774613/93463a2c-dafa-4fff-881f-a1b8b046a117)

## Confusionh matrix
![image](https://github.com/ShubhamVerma16/ERA-Session-15/assets/46774613/0173f7aa-9943-4237-9105-428bb9ad92d2)

## Custom Model Validation
```
 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:06<00:00,  3.12s/it]
                   all         38        905       0.91      0.689      0.759      0.528
                  ball         38         35          1      0.156      0.322     0.0889
            goalkeeper         38         27      0.967      0.889      0.937      0.746
                player         38        754      0.948      0.942      0.981      0.758
               referee         38         89      0.725      0.771      0.797      0.517
Speed: 0.1ms pre-process, 32.8ms inference, 29.3ms NMS per image at shape (32, 3, 640, 640)
```

## Custom Model Inference
![image](https://github.com/ShubhamVerma16/ERA-Session-15/assets/46774613/b9546779-6309-4c68-b722-6728cff192a0)


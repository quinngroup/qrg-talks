# [Cilia Segmentation Using Optical Flow](https://docs.google.com/presentation/d/1sn9J4bffzk7VbuG_TEDIRAMuaE95vjtFNd8oG_5J_jY/edit?usp=sharing)
### [Sonia Rao](https://github.com/sonyeezy) and Andrew Bennett
##### November 14th for Quinn Research Group Talks
 
Using variants of dense optical flow (specifically Horne-Schunk and Farneback) to estimate cilia cell segmentation using supervised models.

### Sonia's model
- Made separate models for each of the optical flow outputs to assess optical flow output peformance
- Best pipeline used pyflow output (Horn-Schunk variant exploiting coarse to fine pyramid structure and conjugate gradient) as processed by lightGBM (gradient boosted decision tree from microsoft framework)
- evaluated using Intersection over union accuracy (Overlap of cilia binary = 1 / Total cilia binary = 1)
- best IOU achieved : ~.44 on stiff cells
- model has gone through significant changes since this time

### Andrew's Model
- Hi andrew if u want fill this out idk

# [PowerPoint Presentation on google drive](https://docs.google.com/presentation/d/1sn9J4bffzk7VbuG_TEDIRAMuaE95vjtFNd8oG_5J_jY/edit?usp=sharing)

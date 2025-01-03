# CelsiaNet2024
### Showcase Format [Framework] [Patch Code] [Dependencies]
### This Github Page is Not Yet Completed, Until All Dependencies and Documentation has been Uploaded this Page Would Work.
A Multimodal Vision Language Model Network Framework--St. Yau 2024 Finalist Bronze Award

The technological term "Celsia" or "CELSIA" stands for "Computer-vision Enhanced Lightweight System for Integrated modAlities." The Celsia series tends to try to accomplish lightweight but high-precision and accurate information determination for a multi-modal framework. This allows smaller model-sized AGI networks to operate without lagging while maintaining high precision. 

CelsiaNet is a specific Network under the Celsia project's aim that targets improving the accuracy and precision while decreasing the model size of the Vision Language Models. 

In this project, we have taken inspiration from the papers BLIP2, LLaVa, ControlCap, DynRefer, and Unicom to forge an interconnected training process for the basis of CelsiaNet.


For this program to work, easily download all the dependencies and then edit the files in the corresponding dependencies with the files located in the "integrate" folder. 

## Formatting
Your program folder should look like this for the training and evaluation to work:
```
CelsiaNet2024
| Alignment
| | Cloned project from BLIPv2
|
| BERT_thrid_code
| | Cloned project from NVIDIA Deep Learning Examples for Tensor Cores
|
| configs from ControlCap
| controlcap from ControlCap
| scripts from ControlCap
| eval.py from ControlCap
| train.py from ControlCap
|
| vision_encoder
| | Cloned from LLaVa
```

## Building
### Attention Mechanisms
To link dependencies, you will now go to "ControlCap" -> "Models" -> Replace the ControlCap T5.py file with the "Integrate/ControlCap T5.py." We have built the self-awareness layers in this file. 

### Alignment




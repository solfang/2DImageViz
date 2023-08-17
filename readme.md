Work in progress

Setup:
1. git clone --recursive https://github.com/solfang/2DImageViz
2. If you want to use the feature vector calculation functionality:

a) Make sure the `deep-image-retrieval` repo got coned corectly under FeatureVectors\

 If that's not the case, you can either use `git submodule update --init --recursive` or download the repo from https://github.com/naver/deep-image-retrieval and place it under `FeatureVectors\`

b) Download the model you want to use (by default, the code uses Resnet101-AP-GeM-LM18) from the links provided at https://github.com/naver/deep-image-retrieval

c) Place the model under \FeatureVectors\deep-image-retrieval\dirtorch\models\[model_file] - the `models folder` needs to be created manually

3. TODO


!TODO: provide codebase(excl. lm18 model) + dummy dataset in a ZIP file

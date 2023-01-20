# Pic2ChinesePoems
## Introduction
It's a teamwork of @rederxz, @poseidonchan and @ethanyang2000. This project can covert any input images to traditional Chinese poems. We constructed a data set containing pictures and Chinesepoems then built a model based on ResNet to extract keywords from pictures and a character-wise model to generate Chinese poems via RNN.

## Codes
Detailed information can be found in the [report](https://github.com/ethanyang2000/Pic2ChinesePoems/blob/main/report.pdf)
+ pic2poem is the finalized codes. You can add the test samples(images) you want in the `test/` and run this file directly, then you will get the generated poems.
+ ImageCollector is the code of the web crawler.
+ PreProcess is used for the pre-process of the poems.
+ ResNet contains the codes for the training of the extractor.
+ poem_generator contains the codes for the poem generator.
+ all `.npy` and `.pt` files are image-poem labels(for our constructed dataset) and trained parameters of the model respectively.

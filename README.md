# TrOCR_EXPLORE
Transformer based OCR for different languages. 
Date: April 8, 2025:

a) Currently, having trOCR demo with hugging face models - and only printed models are being used.
b) TrOCR fine tuned with curved texts in images and explore how the matching accuracy is.
https://learnopencv.com/fine-tuning-trocr-training-trocr-to-recognize-curved-text/

Summary, 
a) the normal trOCR with line-line cropping and with minimal colors and uniform text
seem to be processing ok. Not extensively tried out though.
b) the fine tuned trOCR with curved images from scut_text download is run with some compromoise in the
free version of colab - reduced both the batch size and also the epocs to get over the "out of memory"
situation. The accuracy is not good. But, this has been tried out just to get understanding of how
fine tuning can be done on pretrained model of OCR. 


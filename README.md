# PEIW-Net
## A Secure Deep Image Watermarking model using Patch-Based Embedding and Conditional Mechanism

Existing watermarking methods prioritize imperceptibility, robustness, and capacity but often neglect security, allowing surrogate models to be trained through student-teacher learning using numerous input-output pairs to mimic the victim model. This risks both marked images and embedded data. Hence, evaluating watermark models from both locking and discovering perspectives is crucial where locking prevents generating training targets and discovering identifies surrogate models by watching their outputs. This paper introduces a patch-based embedding deep image watermarking model (termed PEIW-Net) to improve both imperceptibility and robustness while equipped with secure-mechanism to overcome both security angles. PEIW-Net embeds the watermark code into non-overlapping patches of the cover image, generating imperceptibility marked images and ensuring consistency and robustness of extractor. Furthermore, PEIW-Net implements an authentication network to make the generation of marked images dependent on the correct receipt of the network owner's signature, resulting attackers can only optimize a surrogate model if they possess the signature. Additionally, PEIW-Net embeds signature as a secondary security layer so that if attackers access to the signature and train surrogate models using input-output pairs from PEIW-Net, the signature will be learned by the surrogate models, which can be extracted by our extractor afterwards.

## News

  -Paper Download (coming soon)
  
  -The video of proposed work (coming soon)
  
  -Training Code (coming soon)
  
  -Pre-trained Models (coming soon)
    

# XNOR-Net-Fast-inference-from-a-CNN-using-a-Binary-CNN-
Convolutional  Neural  Networks  (CNNs)  have  become the state of the art in several object recognition and object classification tasks.  However, using CNNs onresource constrained devices in real-time is limited by the inference time due to huge computational overload such asmultiplications in 2-D conv layers.  An obvious way to re-duce the complexity is to use XNOR networks. In thesenetworks, both weights and inputs to the convolutional lay-ers are binarised.  This replaces the traditional multiplica-tions with binary operations and then using a scalar to ap-proximate a floating point multiplication resulting in significant speedup.
Reference paper: Rastegari M., Ordonez V., Redmon J., Farhadi A., XNOR-Net: ImageNet Classification Using Binary Convolutional Neural Networks  

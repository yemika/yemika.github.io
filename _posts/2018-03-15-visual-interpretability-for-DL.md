# Visual Interpretability for Deep Learning: a survey

## Six research directions
### Visualization of CNN in intermediate network layers, 显示中间的unit最大化或者invert feature map to input
  - 最大化某个unit，通过梯度的反向传导，在input中找到最大的apperance
  - up-convolution， 从feature map反向到input
  - compute actual receptive field 
### Diagnosis of CNN representation
  - analyze CNN features from a global view
  - image region that directly contribute the network output
  - similar to visual 
  - vulnearble points 易受攻击区域
  - refine network representation based on feature space
  - biased representation 【样本中的错误的相关性提取】
 ### disentangle the filter patterns in CNN
  - explanatory graphs, 每个卷积层的filter构建一个对应图层中的一个节点，边确定了相对的关系
  - disentangle cnn representation into decision tree,在全连接层中使用，那些特征决定了最后的prediction
 ### Building expainable models, learning neural networks with interpretable representations
  - Interpretable CNN， 输入的是时候加入一定的特征样本，以使得中间过程的训练满足提取一定的特征
  - interpertable R-CNN 
  - capusle net
  - infoGAN
 ### Semantic-level middle-to-end learning via human iteraction
 
 ## Evaluation Metrics for network interpretability
  - filter interpretability
  - location instability

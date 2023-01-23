# Continual-Learning

Academics and practitioners alike believe that continual learning (CL) is a fundamental step towards artificial intelligence. Continual learning is the ability of a model to learn continually from a stream of data. In practice, this means supporting the ability of a model to autonomously learn and adapt in production as new data comes in. Some may know it as auto-adaptive learning, or continual AutoML. The idea of CL is to mimic humans ability to continually acquire, fine-tune, and transfer knowledge and skills throughout their lifespan.

In this repository you can see the notebook that I have applied Continual Learning on colorectal cancer histology data. I have used simple 3 layers CNN to train the model. I have started by showing the importance of regularization against over-fitting. Then I have trained the model without continual learning for 4 tasks and compared the accuracy with the model that has been trained with Elastic Weight Consolidation (EWC). 

*References*

Michieli, U., Toldo, M., & Zanuttigh, P. (2022). Domain adaptation and continual learning in semantic segmentation. Advanced Methods and Deep Learning in Computer Vision, 275-303. https://doi.org/10.1016/B978-0-12-822109-9.00017-5

Moriarty, S. (2020) “Continual Learning with Elastic Weight Consolidation in TensorFlow 2.” Available at: https://seanmoriarity.com/2020/10/18/continual-learning-with-ewc/

Kirkpatrick, J. et. al. (2017, January 25). Overcoming catastrophic forgetting in neural networks. Retrieved from https://arxiv.org/pdf/1612.00796.pdf.

Total data volume worldwide 2010-2025. (2021, June 7). Statista. https://www.statista.com/statistics/871513/worldwide-data-created/

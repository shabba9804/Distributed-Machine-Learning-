# Distributed-Machine-Learning-
This project demonstrates distributed machine learning using linear regression. Multiple workers compute gradients on partitioned data, while a coordinator averages them to update the model. It proves distributed training matches single-machine accuracy but faces communication trade-offs, running slower on small datasets due to network overhead.

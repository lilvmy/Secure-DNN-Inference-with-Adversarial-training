# Secure-DNN-Inference-with-Adversarial-training
# We use BFV and SSE to achieve the seucre DNN inference
# Since most secure DNN inference works (based on FHE or SMC) cannot deal with the last thresholding operation used for classification. For example, MNIST datset incluing two fonts, these fonts informtion is also important and necessary to protect.
# To solve above-mentioned information leak issue, we propose a training method to prevent selected sentitive features from leaking, which adversarially optimizes the DNN against an adversary trying to identify these features.

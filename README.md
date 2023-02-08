# Humor Generation Using Images

Humour is one of the essential parts of human interaction. Humour generation as a sub-field of natural language generation (NLG) is a notoriously difficult task. A joke generator using a large pre-trained language model (GPT2) where a caption is generated from an image using Resnet50 layer followed by an LSTM model.

Performed synthesizing of two language generation tasks into a singular system - Image captioning and joke generation. The image caption system acts as context from which the joke is generated. Automated metrics and human evaluation for different parts of the pipeline were used. BLEURT and answerability scores were computed for the generated questions, and human evaluators were subsequently asked to rate the generated jokes and the captions. The model accomplishes the task of generating a joke from the given image to varying degrees of success in funniness.
 main

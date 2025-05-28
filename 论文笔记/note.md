# Personalized Text Generation with Fine-Grained Linguistic Control（具有细粒度语言控制的个性化文本生成）

引入了一个全新的基准来训练生成模型，并评估其基于多种细粒度语言属性生成个性化文本的能力

不同用户输入相同的提示往往会得到结构类似的输出。以往的个性化生成方法聚焦于粗粒度，粗粒度指positive/negative或正式/非正式

## 任务目的

给定一组概括特定作者写作风格的风格属性，以及一个输入文本提示，目标是生成符合所提供属性的文本。
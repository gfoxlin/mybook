# 2018 最新机器学习 API 推荐清单，快给 APP 加点智能

雷锋网


>百家号05-3123:12
雷锋网 AI 研习社按：本文由来自伦敦的数据科学家 Pedro Lopez 编写，文中提供了与人脸识别、图像识别、文本分析、自然语言处理、情绪分析、语言翻译、机器学习和预测有关的 50 多个应用程序接口（API），雷锋网 AI 研习社根据原文进行了编译。


## 本篇基于 2017 年的推荐清单做了一些改进——去除了一些不再进行维护的 API，并且更新了一些新的 API。主要覆盖如下方向：

人脸与图像识别
文本分析、自然语言处理、情感分析
语言翻译
机器学习和预测


该清单按照字母排序，对 API 的概述是基于对应官网所提供的信息（截止 2018 年 4 月 16 日）整合而成。要是大家发现该清单中错过了某些当前流行的 API，可以在评论中告知。

人脸与图像识别

Animetrics Face Recognition：可用于检测图像中的人脸，支持同时多人检测，并且可以将检测到的人脸与已知的人脸数据进行匹配。这个 API 还可以添加或删除可检索图库中的主题，也可添加或删除主题中的人脸。
Betaface：提供在线人脸识别和检测服务。主要有如下功能：多人脸检测、人脸裁剪、123 个人脸关键点检测（22 个基本关键点，101 个高级关键点）、人脸验证、人脸识别以及大型数据库中相似人脸的检索。
Eyedea Recognition：专注于高端计算机视觉解决方案，主要针对物体检测和物体识别软件开发。提供眼睛、面部、车辆、版权和牌照识别等服务。这一 API 的主要价值是可以即时理解画面中的对象、用户和行为。
Face++：在应用中提供人脸识别和检测服务，具有检测、识别和分析服务功能。用户可以调用训练程序、检测人脸、识别人脸、人脸聚类、操纵人脸、创建人脸数据集、创建分组和获取信息。
FaceMark：该 API 可以从一张正面的人脸图像中检测出 68 个关键点，从一张侧面的人脸图像中则可以检测出 35 个点。
FaceRect：这是一个强大且完全免费的人脸检测 API。该 API 能够从单张图像中找到单张人脸或者多张人脸（不论是正脸还是侧脸），然后将找到的每个人脸信息存储在生成的 JSON 文件中。此外，FaceRect 还能为每个检测到的人脸找到面部特征（眼睛、鼻子和嘴巴等）。
Google Cloud Vision API：由诸如 TensorFlow 这样的平台作为支撑，该 API 允许模型学习和预测图像中的内容。它能帮助你在大规模数据集中快速找到你最喜欢的图像，并获得丰富的图像信息。它将图像划分成几千个类别（例如“船”、“狮子”、“埃菲尔铁塔”等），检测人脸并分析情绪，识别图像中的多国文字。
IBM Watson Visual Recognition：该 API 可以理解图像的内容、视觉概念，然后在图像中标记出来，检测人脸、估计年龄和性别，从数据集中找到相似的图像。你还可以通过创建自定义概念来训练服务器。
Imagga：该 API 可以自动将标签分配给图像，从而使得图像检索起来更加简单。它基于图像识别平台即服务（Platform as a Service）构建。
Kairos：这个平台可以帮你快速将情绪分析和人脸识别添加到应用程序（APP）和服务中。
Microsoft Cognitive Service - Computer Vision：这个云端 API 可以根据输入数据和用户的选择，通过不同的方式分析视觉内容。比如依据图像内容给图像打标签、图像分类、检测人脸并返回人脸坐标、识别特定领域的内容、生成与图像内容有关的描述、辨识图像中的文本、标记成人内容。
ParallelDots Visual Analytics APIs：它提供特别服务来帮助进行图像自动标注，可以过滤不合适的内容，从脸部表情中识别人物情绪。
Skybiometry Face Detection and Recognition：提供人脸检测和识别服务。最新版本的 API 还可以区分墨镜与一般眼镜。

文本分析、自然语言处理与情感分析

Bitext：提供了市面上最准确的基于多语言话题的情绪分析服务。目前，有四种语义服务可用：实体和概念提取，情感分析和文本分类。该 API 支持 8 种主流语言。
Diffbot Analyze：为开发者提供了许多工具，支持从任意的网页中识别、分析和提取出主要内容和部分。
Free Natural Language Processing Service：这是一项免费服务，包括情绪分析、内容提取和语言检测。这个 API 在大型云 API 市场 mashape.com 上非常流行。
Google Cloud Natural Language API：分析文本的结构和意义，包括情绪分析、实体识别和文本注释。
Watson Natural Language Understanding：分析文本并从内容中抽取元数据，例如概念、实体、关键词、类别、关系和语义信息。
MeaningCloud Text Classification：该 API 可以执行预分类任务（Pre-classification），例如文本抽取、符号化、停止词消除和词形还原。
Microsoft Cognitive Service - Text Analytics：从所给的文本中检测情绪、关键短语、主题以及语言。还有一些 API（语言的认知服务）与该 API 类似，包括：必应拼写检查、语言理解、语言分析、网络语句模型。
nlpTools：一种简单的基于 HTTP RESTful 网络服务的自然语言处理 API，反馈结果是 JSON。它可以解码在线新闻媒体，进行情绪分析和文本分类。
Geneea：能够在用户提供的原始文本上进行分析（自然语言处理），也能执行分析从指定的 URL 中提取的文本、直接提供的文件。
ParallelDots Text Analytics APIs：支持十四种语言，提供方便且多样化的自然语言理解（NLU）算法，可以检测文档的情感，查找文档中的重要实体，删除不文明用语。利用 ParallelDots 自定义分类器，不需要任何训练数据就能构建文本分类器。
Thomson Reuters Open Calais：通过使用自然语言处理、机器学习和其它方法，Calais 可以将文档与实体（人物、地点、组织等）、事实（人物“x”供职于公司"y"）和事件（人物"z"在日期“x”被任命为公司“y”的主席）进行分类与连接。
Yactraq Speech2Topics：这是一个通过语音识别和自然语言处理将音频和视频内容转换为主题元数据的 API 。

语言翻译

Google Cloud Translation：能够在数以千计的语言对（Language pairs）中动态翻译文本，允许网站和程序以编程的方式与翻译服务进行集成。
Google Cloud SPEECH-TO-TEXT：应用强大的神经网络模型，开发人员能够利用该 API 将音频转化为文本。支持识别全球 120 种语言及其变体。
IBM Watson Language Translator：文本翻译 API ，提供了多种特定领域的模型，你甚至能够基于自己独特的术语和语言进行定制。例如，顾客们可以通过自己的语言进行交流。
MotaWord：快速人工翻译平台，提供超过 70 种语言的翻译服务。该 API 还可以为开发者们提供翻译引用、翻译项目提交、文档和样式指南功能，也可以跟踪翻译项目的进度并实时获取活动反馈。
WritePath Translation：该 API 允许开发人员访问和集成 WritePath 与其它应用程序的功能。可以使用此 API 完成的操作：检索单词数量、发布翻译文档、检索已翻译的文档和文本。
Houndify：通过一个始终在学习的独立平台，将智能语音和智能对话集成到产品中。
IBM Watson Conversation：构建理解自然语言的聊天机器人，并将它们部署在任意设备上，比如信息平台和网站。与此 API 相同的其它 API（语言的认知服务）包括：对话（Dialog）、自然语言分类（Natural Language Classifier）、个性观点（Personality Insights）、文件转换（Documen Conversion）和声调分析器（Tone Analyzer）。
IBM Watson Speech：包括语音到文本的转换和文本到语音的转换，例如在联络中心录制电话或创建语音控制的应用程序。

机器学习与预测

Amazon Machine Learning：可以进行谎话检测、天气预报、目标市场预测和点击量预测。
BigML：为云托管的机器学习和数据分析提供服务。用户可以设置数据源并创建一个模型，然后通过标准的 HTTP 协议使用基础监督和无监督机器学习任务进行预测。
Google Cloud Prediction：提供一种基于 RESTful API 来构建机器学习模型的服务。这些工具可以帮助分析数据，从而为你的应用提供多种多样的新功能，例如，客户情感分析、垃圾邮件检测、推荐系统等等。
co：为电商网站提供产品推荐引擎。Guesswork 使用在 Google Prediction API 上运行的语义规则引擎可以准确预测客户意图。
Hu:toma：提供免费访问，帮助全世界的开发人员构建并实现深度学习聊天机器人，提供创建和分享对话式 AI 的工具和渠道。
IBM Watson Retrieve and Rank：开发人员可以将他们的数据加载到这一服务中，使用已知的结果来训练机器学习模型（Rank），之后将输出相关文档和元数据的列表等。利用这一 API，可以帮助呼叫中心智能体快速找到答案，以改善客户呼叫的平均处理时间。
indico：提供文本分析（例如情感分析、Twitter 预约、情感）和图像分析（例如面部情绪、面部定位）功能。indico 的 API 可以免费使用，不需要训练数据。
Microsoft Azure Cognitive Service API：支持批处理，拥有更好的 API Explorer，更简洁的 API 接口，更一致的注册/计费体验等新功能。
Microsoft Azure Anomaly Detection API：用数值（均匀时间间隔）检测时间序列数据中的异常情况。例如，当检测到计算机内存使用量开始上升时，可能会指示内存泄露。
Microsoft Cognitive Service - QnA Maker：将信息提取成会话形式。与该 API 同一个组（知识的认知服务）的有如下 API：学术知识（Academic Knowledge）、实体链接（Entity Linking）、知识探索（Knowledge Exploration）和推荐（Recommendations）。
Microsoft Cognitive Service - Speaker Recognition：能让你的应用程序理解谁正在说话。与该 API 位于同一个组（语音的认知服务）的其它 API 有必应语音（将语音转换为文本，然后再将文本转换为语音，并且还能理解语音隐含的意图）和自定义识别。
MLJAR：为原型设计、开发和部署模式识别算法提供服务。
NuPIC：这是一个用 Python/C++ 编写的开源项目，它实现了 Numenta 皮质学习算法（Cortical Learning Algorithm），由 NuPIC 社区进行维护。该 API 允许开发人员使用原始算法，将多个区域（包括层次结构）串联起来，还支持使用其它平台的功能。
PredicSis：从大数据中洞见趋势，通过预测分析来提高营销业绩。
PredictionIO：这是在 Apache Spark 许可证下发布的基于 Apache Spark、HBase 和 Spray 的开源机器学习服务。示例 API 方法包括创建管理用户和用户记录、项目和内容检索以及基于用户的推荐创建和管理。
RxNLP - Cluster Sentences and Short Texts：提供文本挖掘和自然语言处理服务。包含句子聚类 API（Cluster Sentences API），可以将句子（比如从多篇新闻中获取的句子）或简短文本（例如来自 Twitter 或者 Facebook 的贴子）划分成多个逻辑组（Logical groups）。
Recombee：通过 RESTful API 提供数据挖掘、语言查询和机器学习算法服务。

其它 API 收藏清单：Mashape 博客和 RapidAPI 机器学习集合。

扩展

高级 API 是否会妨碍机器学习从业者对算法的理解？
50+ 最有用的机器学习与预测 API
区块链与 API

Via 50+ Useful Machine Learning & Prediction APIs, 2018 Edition，雷锋网 AI 研习社编译整理。# # 
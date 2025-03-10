<!-- TOC start (generated with https://github.com/derlin/bitdowntoc) -->

- [Learning Material ](#learning-material)
   * [Free Course Material Online:](#free-course-material-online)
   * [Course Work:](#course-work)
- [References:](#reference-material)
     

<!-- TOC end -->

# Learning Material 

## Free Course Material Online:
1. Stanford [CS 324](https://stanford-cs324.github.io/winter2022/lectures/) is a self-contained LLM Book! 🙏 Stanford University had released lecture notes of their Large Language Model course. These notes are actually an incredibly organized self-contained book covering the foundations of Large Language Models
 My favorite part is these are structured as an onion, going from an overview and slowly going a level further with every page. These also have the best notes I have read on Mixture of Experts
1. [Stanford's AI course materials](https://ai.stanford.edu/courses/)
2. Stanford CS229 lecture video on [building LLM](https://www.youtube.com/watch?v=9vM4p9NN0Ts&ab_channel=StanfordOnline) is an amazing 1+ hr video
1. [UC Berkeley](http://ai.berkeley.edu/home.html) 
1. [MIT Open Learning](https://ocw.mit.edu/search/?q=machine%20learning and https://ocw.mit.edu/search/?q=artificial%20intelligence)
1. [Cameron Wolfes substack](https://cameronrwolfe.substack.com/p/explaining-chatgpt-to-anyone-in-20) Explaining LLM is a very succint beginner description on how LLM is trained 
1. [Illustrated Transformer -  by Jay Allamar](https://jalammar.github.io/illustrated-transformer/) one of the best easy to follow visual guides I have seen. I am planning to buy the book as well

## Course Work:
Both Udemy and Coursera offers a comprehesive set of courses along with hands on work. Here is a short list. Feel free to add more

1. A 5 course series on [deep learning](https://www.coursera.org/specializations/deep-learning) by Andrew Ng
2. Google offers free [AI and ML](https://cloud.google.com/learn/training/machinelearning-ai) courses for all levels

# Reference Material

1. How [deepseek-R1](https://newsletter.languagemodels.co/p/the-illustrated-deepseek-r1) is trained. Very informative and succint
2. Andrej Karpathy’s 3.5 hour video is one of the most comprehensive material that describes LLM in detail. From pre-training, SFT, RL etc.
3. 𝗪𝗮𝘁𝗰𝗵 𝘁𝗵𝗲 [𝗳𝘂𝗹𝗹 𝘃𝗶𝗱𝗲𝗼](https://youtu.be/7xTGNNLPyMI?si=iSy9vkBEA_j739AS)
U𝘀𝗲 𝘁𝗵𝗲𝘀𝗲 𝘁𝗼𝗼𝗹𝘀 to help visualize AI’s full processing logic, from tokenization to decision-making, so you can spot where reasoning works and where it fails: 

📌 [Tokenization](https://tiktokenizer.vercel.app/)

📌 [Visualize Datasets](atlas.nomic.ai) 

📌 See [LLM Architecture Flows](https://bbycroft.net/llm)

📌 Bonus: [Understand Transformer Steps](https://lnkd.in/g7P-C4HJ)

# Notes:
1. How does large model training is accelerated? Roughly there are few techniques. This is short nice [blog](https://alessiodevoto.github.io/parallelism/)
   - **Data Parallelism**, Large training data and model fits in a single GPU.
   - **Model Parallelism**, Here Models are too big to fit into a single GPU. Dividing across GPU leads to very poor GPU utilization.
   - **Pipeline Parallelism**, It solves the GPU utilization with complex scheduling but increases overhead.
   - **ZeRO**, Need better unerstanding

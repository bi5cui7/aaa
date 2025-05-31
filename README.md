Download all files and then unzip them. Here is the code, data, and logs of the model on the Hadoop dataset. The code does not include log parsing, and since the Hadoop dataset contains no numerical metrics requiring special attention, metric feature is removed, and the raw features of the nodes only have 2 channels.

The public dataset is available for download at [link](https://github.com/logpai/loghub/). However, due to concerns regarding the protection of commercial data, user privacy, and corporate data security policies, the two proprietary datasets mentioned in this paper are not publicly released.

run 'python GrapGenerator.py' to build graph, and you need to split the training and test sets yourself.

run 'python test.py' to train and evaluate.

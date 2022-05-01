# Commands
## download  gitignore using curl

'''bash
curl https://raw.githubusercontent.com/c17hawke/general_template/main/.gitignore >.gitignore 
'''
# for linux

wget https://raw.githubusercontent.com/c17hawke/general_template/main/.gitignore >.gitignore
'''
## download  init setup.sh using curl 

'''bash
curl https://raw.githubusercontent.com/Sushanth172308/general_project_template/main/init_setup.sh >init_setup.sh
'''

## Tensorflow varification
'''bash
python -c "import tensorflow as tf ; print(tf.config.list_physical_devices('GPU'))"

## Installation of object Detection API
'''bash
mkdir Tensorflow && cd Tensorflow
'''

## Clone the Tensorflow model folder here
'''bash
git clone https://github.com/Tensorflow/models.git
'''

## showing  python bash command in github  
'''python
import os
os.getcwd()
...

 remove .git directory of models to avoid git conflict 

 add models folder to .gitignore file

 we can also run  bash commands to add files in gitignore file from root directory
 '''bash
 echo "Tensorflow/models" >> .gitignore
 '''


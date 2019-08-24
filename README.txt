Used versions to setup properly:

module load conda/4.5.13
module load cuda/8.0.0
module load cudnn/8.0_v6.0

then:
conda env create -f environment.yml
installed everything except the pip stuff
activate the env by:
source activate carnd-advdl-odlab (NOT activate alone, NOT conda activate)

this had to be installed manually by:
pip install --proxy http://... moviepy
pip install --proxy http://... tensorflow-gpu==1.4

# bbocr-env-setup
Here is steps of setting up environments for apsis.net ocr recognizer and other python environment setups for further thesis on recognizers

# specific conda env setup
conda create -n name_of_env python=3.9 <br>
conda activate name_of_env <br>

# APSIS.NET ocr dependencies installation
pip install apsisocr <br>
pip install onnxruntime
pip install fastdeploy-python -f https://www.paddlepaddle.org.cn/whl/fastdeploy.html <br>
pip install torch torchvision --index-url https://download.pytorch.org/whl/cpu <br>
pip install ultralytics <br>
pip install shapely <br>

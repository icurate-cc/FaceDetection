THe short code loads all "known faces", loads webcam feed, and does realtime facial recognition matching - i only did it for family members not sure how well it works for larger known face sets.
makes "human detected" alert for unknown faces, and "welcome home" for known faces.

pip install face_recognition
manual install dlib-master for GPU - only works with CUDA v12.9 and cudnn_v8 <-- this step is painful
pip install jupyter notebook
pip install pygames

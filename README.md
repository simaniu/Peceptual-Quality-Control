# Peceptual-Quality-Control

Requirement:
Software: Microsoft Visual Studio 2015
Library: OpenCV 2.4.9

Installation Path for OpenCV:
D:\Program Files\OpenCV\opencv\build
D:\Program Files\OpenCV\opencv\sources

Experiment:
Firstly, the path of SaliencyMapPath and InputFile in .cfg file needs to be modified, corresponding to the path in your computer.
SaliencyMapPath     :$(Your Path)/$(Sequence Name)_
InputFile           :$(Your Path)/$(Sequence Name)_

Encoding experiment example:
TAppEncoder.exe -c encoder_lowdelay_P_main_official.cfg -c 1280_704_vidyo1.cfg

Decoding experiment example:
TAppDecoder.exe -b str.bin -o nothing_have_done.yuv

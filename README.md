## model data
(500 models from ShapeNet)
unzip data.zip.001-data.zip.035
(another 500 models from ShapeNet)
unzip ShapeNet.zip.001-ShapeNet.zip.
(400 models from Thingi10K)
unzip Thingi10K.zip.001-Thingi10K.zip.039

## statistics of data
data.xlsx
ShapeNet.xlsx
Thingi10K.xlsx

## notice
the input model is named with _input_origin

in case of duplicated faces with different UV, we maintain only the one with the smallest id
so in order to valid the UV of the output, we remove the duplicated faces in _input_origin to _input_render so that we can test PSNR with texture reasonably
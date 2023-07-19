## model data
unzip data.zip.001-data.zip.035

## statistics of data
data.xlsx

## notice
the input model is named with _input_origin

in case of duplicated faces with different UV, we maintain only the one with the smallest id
so in order to valid the UV of the output, we remove the duplicated faces in _input_origin to _input_render so that we can test PSNR with texture reasonably
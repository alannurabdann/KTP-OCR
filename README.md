# KTP OCR

Extract data from file KTP using Google Cloud Vision (GCV).

![alt text](https://github.com/alannurabdann/KTP-OCR/blob/master/example.jpg?raw=true)

### Config File
Please fill in the configuration in file `kyc_config.py`
`gcv_api_key_path`: path location of the GCV API Key. To get an API, check https://cloud.google.com/vision/docs/setup
`json_loc` = path location to save the OCR output from GCV
`output_loc` = path location to save the extracted KTP data

### KTP Data Extractor
use the following command to extract KTP data directly from KTP image :
```
python main.py <image_path>
```
The extracted KTP data will be saved in csv format in the `output_loc` (check config file)

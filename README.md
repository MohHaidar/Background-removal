# Background-removal

Fask app to be hosted on a remote machine, it runs a background removal AI and can be calle with the following API calls:

-/api/train:  To run the training on saved images
-/api/trainResult: To read the trainig stats in a JSON format
-/api/removeBg: POST request with raw image, returns url to the original, mask and bg removed image
-/api/save_image: POST request with raw image, saves it in the training folder
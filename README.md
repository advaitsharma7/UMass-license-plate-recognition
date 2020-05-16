# UMass-license-plate-recognition
A project to fast process and recognize all the license plate numbers in UMass Parking services and to check their validity in the UMass database of parking permits using two pre-defined models.

## Prerequisites 
* python
* google cloud vision
* OpenALPR

## Deployment
* Image database is pulled up through continuous live streaming of parking services.
* Processing of images takes place to identify the license plate number of each car.
* Each number is then checked with the database of UMass registered parking permits.

## Build With
* [Cloud Vision API](https://cloud.google.com/vision/) - API for vision detection features(OCR). 
* [OpenALPR](https://cloud.openalpr.com/cloudapi/) - open source library to recognize license plates.

## Authors
* *Advait Sharma* 
* *Arya Chaughule*

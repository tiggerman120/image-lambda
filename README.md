# image-lambda

## description of how to use your lambda

uploading a file into the s3 console will trigger the lambda function to run by use of the trigger that was added
in the other s3 bucket you will be able to download the thumbnail

## a description of any issues encountered during deployment of this lambda

I had an issue prop up while trying to invoke the function. I was trying to invoke a function from a folder path but I was not in the correct folder so the inputFile wasnt being found

## image and thumbnails
[input](https://picture1gc.s3-us-west-2.amazonaws.com/lakeOfTheAngels.jpg)
[output](https://picture1gc-resized.s3-us-west-2.amazonaws.com/resized-lakeOfTheAngels.jpg)
# Animals Classification

This data is provided by Microsoft on 5/9/2022.

ref-https://www.microsoft.com/en-us/download/details.aspx?id=54765


## Approach :
1. After data Collection we need to segreate the data based on classification before feeding to the model.
2. Imagaes we have are of a higher resolution  hence while building a model we need to pass it through various filters and pooling to lower the resolution and keep the important features unharmed.
3. Once images get to the required resolution we can Flatten them and send them to Dense layer for Learning.
4. As there are only 2 categories we wil choose to use Sigmoid Function as a output layer.

## Goal:
Construct a CNN model that achieves a a accuracy of greater than 80% meanwhile trying to keep the epoochs low.


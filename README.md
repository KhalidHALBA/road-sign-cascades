# road-sign-cascades
Collection of HAAR and LBP cascades designed to recognize various street signs.

# What's included?
- Data folder: Contains data from each stage of training. Can be used to create lower stage cascades or to train to further stages.
- info.txt: Contains notes about the training data as well as parameters used during training. Created for my own use but maybe you will find them to be helpful.
- A few cascades. Tried to include the ones that I felt performed the best. However you can use the data folders to create cascades of different stages. Sometimes lower stage cascades work better than higher stage ones.
- Vector files: Each folder contains a vector file of positive images used during training. Use to train cascades using custom parameters or to train cascades further than I did.

# Notes:
Traffic Light cascade needs work. Low detection rate.

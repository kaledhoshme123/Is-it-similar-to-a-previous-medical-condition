# Is it similar to a previous medical condition؟
- In many cases that doctors face during the different treatment processes for many patients, so that the doctor tries every time to remember an old pathological condition that he encountered in advance in order to try to retrieve the methodology that he followed at that moment to treat the patient who has the same pathological condition.
- In this study, I tried to search for the methodology by which the doctor can retrieve similar pathological conditions for a specific new case, which makes it easier for the doctor to retrieve the way he treated the old patient in order to try to propose it in solving the problem of the new patient.
- Thus, the methodology relied mainly on focusing on the basic patterns that distinguish the images included in the dataset (dataset here, we mean a list of all previous patients treated by the doctor), and working to compare those features and patterns that characterize all medical images of the chest area of previous patients with the features that Characterized by the new medical image of the new patient.
- This is what the patient does when trying to retrieve his memory to confirm a previous medical condition that he treated.
- The methodology was mainly based on the use of a conditional autoencoder, where medical images were passed to normal people and people infected with the Corona virus, and the conditional condition was used to force the autoencoder to focus on the basic features in determining the location of infection, so that the autoencoder does not focus on redrawing the basic shape of the medical images without focusing on diseased areas.
- That is, I tried through the study to focus on the basic features in determining the locations of infection with the Corona virus, and therefore I entered the normal, uninfected state during the training of the obstetric model.
- The Euclidean distance law and the Manhattan distance were used to study the distance between features.
# Dataset Used:
https://www.kaggle.com/datasets/plameneduardo/sarscov2-ctscan-dataset
## Examples:
| The image we want to find similar to  | Distance Metric | Results |
| ------------- | ------------- | ------------- |
| ![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/8256ff12-5108-4dd8-9fd4-27d03ef6748c)  | Euclidean distance  | ![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/8ecc2bba-7ea9-406b-8168-dca2d7f43ee8) |
| ![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/e9525133-fbfd-484d-8dae-56b3ec536cd1)  | Manhattan distance  | ![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/11b76c2d-36cc-46a7-a7e0-c228b4e19eba) |
| ![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/f9f3d796-e4b7-443f-bfdf-791553d1999a)  | Euclidean distance  | ![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/76a454ef-9835-42b6-aafe-525da20b1d73) |
| ![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/340f1c34-860c-4adc-aa29-e77c4abdade1)  | Manhattan distance  | ![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/7cf43620-f530-4cd6-a689-68e39fc93be6) |
| ![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/28b693ad-8f3a-4422-9f3b-d9c4d23cf636)  | Euclidean distance  | ![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/5d8e1619-a3fa-4100-98eb-e088461c9178) |
| ![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/8be0b222-d808-43c3-a832-6986f7fb371c)  | Manhattan distance  | ![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/d1b3969b-8c75-4eec-9754-264e78a26067) |
| ![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/ecd979a6-c318-4ffc-abee-3c2a56bf26fc)  | Euclidean distance  | ![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/2021f4e0-1406-4560-8225-96a1dcb1e710)  |
| ![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/9ad15bae-3581-4241-b7f0-71ab5f970dfe)  | Euclidean distance  | ![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/20166068-d3dc-4fb7-ade7-e083635c6315)  |




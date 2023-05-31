# Is it similar to a previous medical condition؟
- In many cases that doctors face during the different treatment processes for many patients, so that the doctor tries every time to remember an old pathological condition that he encountered in advance in order to try to retrieve the methodology that he followed at that moment to treat the patient who has the same pathological condition.
- In this study, I tried to search for the methodology by which the doctor can retrieve similar pathological conditions for a specific new case, which makes it easier for the doctor to retrieve the way he treated the old patient in order to try to propose it in solving the problem of the new patient.
- Thus, the methodology relied mainly on focusing on the basic patterns that distinguish the images included in the dataset (dataset here, we mean a list of all previous patients treated by the doctor), and working to compare those features and patterns that characterize all medical images of the chest area of previous patients with the features that Characterized by the new medical image of the new patient.
- This is what the patient does when trying to retrieve his memory to confirm a previous medical condition that he treated.
- The methodology was mainly based on the use of a conditional autoencoder, where medical images were passed to normal people and people infected with the Corona virus, and the conditional condition was used to force the autoencoder to focus on the basic features in determining the location of infection, so that the autoencoder does not focus on redrawing the basic shape of the medical images without focusing on diseased areas.
- That is, I tried through the study to focus on the basic features in determining the locations of infection with the Corona virus, and therefore I entered the normal, uninfected state during the training of the obstetric model.
- The Euclidean distance law and the Manhattan distance were used to study the distance between features.

## Examples:

![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/d18601ee-5578-4e46-a3c9-53e8cb8d1868)
![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/2ebecf63-9fe6-4823-b7aa-edb6876afd79)
![image](https://github.com/kaledhoshme123/Is-it-similar-to-a-previous-medical-condition/assets/108609519/b07db99f-87f8-40eb-992c-1242bb1c55ac)



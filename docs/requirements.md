# Requirements

## Functional requirements (what the system must DO)

1. FR1: The system shall enable users to upload a facial image for skin condition classification.
   
2. FR2: The system shall analyze the uploaded facial image and classify the user's visible skin condition using a trained machine learning model.
   
3. FR3: The system shall users to upload an image of a skin care product label containing its ingredients.
   
4. FR4: The system shall extract ingredient information from the uploaded label image using Optical Character Recognition (OCR).
   
5. FR5: The system shall enable the user to give information on known allergies or ingredients to be avoided.
    
6. FR6: The system shall assess ingredient compatibility according to the classified skin condition, user-provided sensitivities and ingredient database using predefined assessment rules.
    
7. FR7: The system shall display the compatibility assessment as Compatible, Caution or Potential Concern, together with explanations of identified ingredient-related concerns.


## Non-functional requirements (how the system must PERFORM)

1. NFR1 (Performance):	The system shall display assessment results within 10 seconds for at least 90% of valid requests under the defined test environment.
   
2. NFR2	(Usability): The system shall allow at least 4 out of 5 first-time test users to complete the main assessment workflow within 5 minutes without assistance.
   
4. NFR3	(Security):	The system shall reject 100% of uploaded files with unsupported file types before processing them.
   
5. NFR4	(Reliability): The system shall display an error message whenever an uploaded image cannot be processed and shall not display an incomplete assessment as a valid result.

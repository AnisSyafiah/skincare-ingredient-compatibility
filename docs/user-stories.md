# User Stories

1. As a skincare user, I want to upload a facial image so that I can get a prediction of my skin condition category for my assessment. (FR1, FR2)

   Acceptance criteria:
   - When a valid facial image is uploaded, the system shall process it and show  the predicted category of the skin condition.
   - When an unsupported or unreadable image is uploaded, the system shall reject the image and display an error message.


2. As a skincare user, I want to upload an image of my product's ingredient label so that I can view the extracted ingredient names without typing the full list.(FR3, FR4)

   Acceptance criteria:
   - When a readable ingredient label image is uploaded, the system shall extract and display the recognized ingredient text. 
   - When the image includes unreadable or incomplete ingredient text, the system shall inform the user that the extracted information may be incomplete.


3. As a skincare user, I want to assess the ingredients in my existing skincare product based on my skin condition and known sensitivities, to ensure I understand any concerns I may have about the ingredients.(FR5, FR6 ,FR7)

   Acceptance criteria:
   - When the required skin profile, sensitivity information and ingredient list are available, the system shall assess compatibility using the ingredient database and predefined rules, then display a compatibility category. 
   - The system shall provide an explanation of the assessment and highlight relevant ingredient concerns when supported by the available information.

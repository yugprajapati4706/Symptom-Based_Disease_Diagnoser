1.Problem Statement 
 In many developing regions and remote areas, immediate access to professional healthcare is often limited due to a shortage of medical personnel and infrastructure. Patients often ignore early symptoms due to the high cost of consultation or lack of awareness, leading to the aggravation of treatable conditions. Furthermore, during health crises (like pandemics), hospitals become overcrowded, making it difficult to triage patients effectively. Therefore, there is a need for an automated, accessible, and cost-effective diagnostic tool that can act as a first line of defense. This system should allow users to input symptoms and receive a preliminary probabilistic diagnosis, enabling them to distinguish between minor viral infections and conditions requiring urgent medical attention.


2. Scope of the project

 We live in an era where people instantly resort to the internet the very moment they feel
 ill. Yet, unguided searches often fall into either of two extremes: underestimating a
 Serious condition or panicking over a mild one. Though software can never replace a
 Doctor, there is a clear and specific need for sensible, accessible tools that can support users in
 organize their symptoms and understand whether they need rest or immediate
 medical attention.


3.Target users
 Target users of this simple, rule-based diagnostic project include those individuals who are looking for non-professional, preliminary, and educational information about common symptoms and illnesses.

 a. General Public Seeking Initial Information : Users with mild symptoms, for instance, coughs, colds, or light headaches who want to do a fast and non-binding check on whether they should seek professional treatment or just need rest.
 b. Students and Beginners in Programming/Health
 Computer Science Students/Beginners: The target audience is people in the learning phase of Python programming and, more specifically:
 Health/Medical Students (For Basic Concepts): Students who need a simplified, clear example of a diagnostic decision flow as a means of illustrating the concept of rule-based clinical logic.

 c.cDevelopers and Educators
 Developers: Anyone in need of a basic, independent example of a Python-based text-based chatbot or decision tree for tutorial or demonstration purposes. Educators/Trainers: Instructors seeking a concise, ready-to-run script that will teach basic programming logic, along with user interaction, in a practical context. Key Limitation Reminder for Users It is important to underline that every target user has to be clearly aware of the tool's limitation; it is an educational one and NOT a substitute for professional medical advice. The non-professional acceptance of this project should come from the users. Would you like for me to discuss in detail the specific logic paths that are followed by the diagnostician for a given diagnosis, say "FLU" or "ALLERGIES"?

4. High-level features

 The symptom_diagnoser.py project is a simplified, rule-based chatbot designed to perform preliminary symptom matching. Its high-level features focus on ease of use, clear decision-making, and user interaction within the console environment.

 a. Rule-Based Diagnostic Engine (Decision Tree)
 Feature: It implements a hard-coded decision tree using nested if/elif/else statements.
 Benefit: Allows the program to go through a predefined flow of questions depending on user answers to reach a diagnosis. The logic is simple, transparent, and deterministic.

 b. CLI: Command-Line Interface, Interactive
 Feature The program uses built-in functions input() and print() to have a question-and-answer session with the user.
 It allows the user to interface with the diagnostic system using a simple, accessible, and platform-independent method that would not require a graphical interface or a web browser.
 c. Robust Input Validation
 Feature: The ask_question() function makes sure that the user input is only valid when a user responds with either 'Yes' or 'No' ('Y' or 'N' is also acceptable).
 Benefit: Avoids crashes and ensures the diagnostic logic gets the Boolean (True/False) input it needs, adding robustness against user error.
 d. Diagnosis and Recommendation Output
 Feature: The program outputs a potential diagnosis at the endpoint of the decision tree, lists common symptoms for that condition, and provides a general health recommendation, such as "Rest, stay hydrated".s
 Advantage: Provides immediate feedback to the user, categorized in nature, making the utility more useful. 5. Loop of Repetitive Executions Feature: The main() function contains a while loop that prompts the user if they want to diagnose again once the process is completed. Benefit: Improves usability by allowing multiple diagnostic sessions without needing to restart the script. 6. Mandatory Medical Disclaimer Feature: The output for any diagnosis includes a clear, highlighted disclaimer that it is for educational use and not a substitute for professional medical advice. Benefit: This clearly sets user expectations and limits liability by making clear that the diagnosis is not a professional on

# [Computer Vision Image Recognition Model]

## Project Description
For this project I used simple objects found in my backpack on a daily basis and incorporated them into a Teachable Machine Image Recogntion Model.
 
## Classes Identified
List of the objects or "classes" that were used to train the model to identify:
* Class 1: Pen
* Class 2: Glue Stick
* Class 3: Calculator
* Class 4: Hair Comb
* Class 5: Pencil

## Discussion & Reflection

1.  **Model Performance & Iteration:**
   
      The first Iteration was effective, especially when identifying the hair comb and the calculator. However, the model struggled to identify pen vs pencil. So to improve this I added more pictures in the pen classification that focused on identifying details, such as the pocket clip. The result was extremely efficient, there is now a much higher confidence on rather the presented object was a pen or not.
   
2.  **Challenges & Observations:**

    As I assumed when picking my object, the calculator was the most proficient classification. It is the only large object in my listing, so I believe that is why it is easily distinguished. Shockingly, the model has a little confusion between gluestick and hair comb. I see 0 similarities between the two, so I am uncertain as to how to boost the confidence. As stated in the previous section, pen was initially the heaviest struggle in confidence level. After giving better images, the pen class was much more identifiable. While testing untrained objects after the final iteration, I showed the model a yellow pen with the intention of confusing the model, and it was somewhat tricked. The confidence levels were 56% pen, 36% pencil, and 8% glue stick.

3.  **Bias in AI:**
   
      Bias directly affects how an image recognition model makes it's interpretations. For example, if I were to show my model a different brand of gluestick that has a different shape, color, and size, would it still guess correctly? Probably not, but that's because it's not trained for an gluestick that is different. Same goes for the atmosphere around the object in question. All the pictures for my model were taken in a bright environment, so if the lights were turned off, then the confidence may suffer. When I tested this very question, it did exactly as previously hypothesizied. I showed the model a gluestick with the lights off, and the confidence was 44% hair comb, 35% gluestick, 14% pencil, 4% calculator, and 3% pen.

4.  **Model Limitations & Usefulness:**

      This model's biggest limitation is the lack of variety in each classifcation. The model only trained on: orange elmer gluesticks, tiny black combs, traditional yellow pencil, a normal black pen, and a graphing calcuator. Using a different brand or style could easily confuse the model (as tested with the yellow pencil example in *Challenges & Observations*). That's why linking the model files and sharing it on GitHub like this is helpful to the models evolution. Any GitHub user can download this model and reproduce a more efficient version that has more variety and even more classifications. 

5.  **Real-World Applications & Ethics:**
    * Brainstorm 2-3 real-world applications where a similar image classification model could be useful.
    * Briefly discuss one ethical consideration that developers should keep in mind when building and deploying image recognition AI in the real world (e.g., related to fairness, privacy, misuse).
      An image recognition model similar to this one have proven extremely useful in many scenarios. Firstly, healthcare deparments use one to identify and diagnose fractures or tumors using data from previous patients. Fully autonomous cars also use image recognition so that they do not run a stop sign or hit a pedestrian. Even our phones use image recognition when we try to unlock it with face identification. However, their are certain ethical issues for a developer to consider when creating one these models. For example, an image recognition model can be weaponized to create deepfakes or misinformation. There's even been reports of facial recognition errors due to underrepresented factors such as age or skin color. It's important that when developing an image recognition AI that is intended for use that factors like the previously mentioned are considered. 

## Screenshots
* Pen: <img width="1919" height="1079" alt="Screenshot 2025-11-19 150553" src="https://github.com/user-attachments/assets/4f8fbd88-d02f-4b5d-be1b-f192b1e4a742" />
* Glue Stick: <img width="1919" height="1079" alt="Screenshot 2025-11-19 150610" src="https://github.com/user-attachments/assets/ab7710cc-601e-4068-b37f-9c31a1f9ef20" />
* Calculator: <img width="1919" height="1079" alt="Screenshot 2025-11-19 150626" src="https://github.com/user-attachments/assets/5cc1a7e3-a785-4e21-8982-41863ab40e61" />
* Hair Comb: <img width="1919" height="1079" alt="Screenshot 2025-11-19 150509" src="https://github.com/user-attachments/assets/3320f674-004e-4c8d-93f5-bc4263991302" />
* Pencil: <img width="1919" height="1079" alt="Screenshot 2025-11-19 150533" src="https://github.com/user-attachments/assets/f14fa7cd-10fe-4a25-a528-6c87db4f1a14" />

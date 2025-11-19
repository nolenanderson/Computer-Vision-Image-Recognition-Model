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
   
3.  **Challenges & Observations:**
    As I assumed when picking my object, the calculator was the most proficient classification. It is the only large object in my listing, so I believe that is why it is easily distinguished. Shockingly, the model has a little confusion between gluestick and hair comb. I see 0 similarities between the two, so I am uncertain as to how to boost the confidence. As stated in the previous section, pen was initially the heaviest struggle in confidence level. After giving better images, the pen class was much more identifiable. While testing untrained objects after the final iteration, I showed the model a yellow pen with the intention of confusing the model, and it was actually not very tricked. The confidence levels were 76% pen, 16% pencil, and 8% glue stick.

4.  **Bias in AI:**
    * If you only trained your "mug" class with images of *your specific mug* (and didn't vary color, shape, etc.), how well do you think it would recognize other students' significantly different mugs? How does this illustrate the concept of bias being introduced through training data?
    * Imagine all your training images were taken in very bright, direct lighting. What might happen if you tried to use the model in a dimly lit room or with strong shadows? How does this relate to the robustness and potential biases of AI models?


5.  **Model Limitations & Usefulness:**
    * What are some key limitations of the model you created?
    * Why is it useful to be able to download your trained model files (like `model.json`, `weights.bin`) and share them (e.g., via GitHub)? What does this enable?


6.  **Real-World Applications & Ethics:**
    * Brainstorm 2-3 real-world applications where a similar image classification model could be useful.
    * Briefly discuss one ethical consideration that developers should keep in mind when building and deploying image recognition AI in the real world (e.g., related to fairness, privacy, misuse).


## Screenshots
* Pen: <img width="1919" height="1079" alt="Screenshot 2025-11-19 150553" src="https://github.com/user-attachments/assets/4f8fbd88-d02f-4b5d-be1b-f192b1e4a742" />
* Glue Stick: <img width="1919" height="1079" alt="Screenshot 2025-11-19 150610" src="https://github.com/user-attachments/assets/ab7710cc-601e-4068-b37f-9c31a1f9ef20" />
* Calculator: <img width="1919" height="1079" alt="Screenshot 2025-11-19 150626" src="https://github.com/user-attachments/assets/5cc1a7e3-a785-4e21-8982-41863ab40e61" />
* Hair Comb: <img width="1919" height="1079" alt="Screenshot 2025-11-19 150509" src="https://github.com/user-attachments/assets/3320f674-004e-4c8d-93f5-bc4263991302" />
* Pencil: <img width="1919" height="1079" alt="Screenshot 2025-11-19 150533" src="https://github.com/user-attachments/assets/f14fa7cd-10fe-4a25-a528-6c87db4f1a14" />
